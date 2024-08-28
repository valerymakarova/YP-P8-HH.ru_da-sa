# YP-P8-HH.ru_da-sa
Simple analysis of vacancies published on HH.ru  
The data was obtained from the HH.ru API and is presented for the part of the year 2024.

Objective: Identify the differences in job postings for Data Analysts and Systems Analysts.
Hypothesis: There should be differences in the job descriptions and requirements for Systems Analysts and Data Analysts, likely in terms of their responsibilities and the skills required.

Used libraries: pandas, seaborn, matplotlib, numpy, collections


============================ Data Description =================================

The data was relatively clean:

- There were no implicit duplicates in the categorical data, but they were found in the skill lists. The list was cleaned, and new columns with indicators of key hard/soft skills were created based on it.
- Missing values were partially filled in for salaries, with a minimum threshold of 60k. The remaining missing values were significant enough to avoid averaging data for the minority.

Analysis period: 2024-02-13 - 2024-07-09

Total number of job postings: 3,711

Number of job postings by position:

	•	Systems Analyst: 1,915
	•	Data Analyst: 1,801

Number of active employers: 1,358


============================ Key Findings =================================

The roles of Systems Analyst and Data Analyst have many similarities but also some differences:

Similarities:

	•	Similar employment conditions and job opportunities
	•	Variety of employers and salary conditions
	•	Specific skill and software experience requirements

Differences:

	•	Primarily in salary - Systems Analysts earn significantly more than Data Analysts.
	•	Key skillsets differ - while Systems Analysts rely on SQL and specialized software, Data Analysts need to know Python and its core libraries in addition to SQL.
	•	Regional salary variations are also significant between these roles.

============================ What Does the Perfect Candidate Look Like? =================================

Profile of a Systems Analyst candidate:

	•	Junior with up to 3 years of experience or Mid-level specialist with 3 to 6 years of experience
	•	Full-time employment with the possibility of remote work
	•	Average salary range around 140-200k RUB
	•	Target employers: financial organizations or IT holdings
	•	Proficient in documentation, SQL, BPMN, Jira Confluence, and possesses an analytical mindset, good communication skills, and task-setting abilities

Profile of a Data Analyst candidate:

	•	Junior+ or Mid-level with 3 to 6 years of experience
	•	Full-time employment
	•	Average salary range around 100-160k RUB
	•	Target employers: financial or TMT sector
	•	Proficient in SQL, Python, and its libraries, and possesses an analytical mindset, good communication skills, and demonstrates a proactive approach

============================ Recommendations =================================

For Job Seekers:

	•	Assess your experience and set salary expectations accordingly
	•	If project-based work or remote work is necessary, look for corresponding job postings (especially for Systems Analysts)
	•	Highlight targeted skills in your resume for the desired role
	•	Monitor new job postings on Tuesdays

For Employers:

	•	Compare your salary ranges with competitors
	•	Specify minimum and maximum salary thresholds more clearly
	•	Expand the list of required skills in job descriptions to better define the ideal candidate
