# Project 2: World University Ranking Systems
# Introudction
University rankings are difficult to determine because different universities and ranking systems use varying factors to measure success. But why is ranking universities important? That depends on what matters to each person. So, why should you consider university rankings before enrolling? Don’t worry. This isn’t a pop quiz! Any reason that matters to you is valid.

Here, we are considering three different ranking systems: Shanghai Ranking, Times Higher Education Ranking, and Center World University Ranking, to answer the following questions:

1. Which universities are ranked in the top 10 globally?
2. Which universities are ranked in the top 10 for employment outcomes?
3. What positions do universities in Saudi Arabia hold within the global rankings?
4. Considering various factors such as employment rankings, research rankings, and others, which has the most significant impact on a university's overall ranking?
5. Is there a correlation between national and global university rankings, and based on this information, can you recommend a country that appears to have a high concentration of top-ranked universities?
6. **Bonus:** Are there any universities that have stayed in the same position in both 2022 and 2023?
7. **Bonus:** Which university experienced the most significant decline in its global ranking from 2022 to 2023?

# Dataset Overview and Source.

All the datasets are from Kaggle and they match the data on the official website.

## The Academic Ranking of World Universities (ARWU)
Datasets overfiew:
Shanghai 2022
- Ranking : it's based on the globle scope.
- University Name: the name of the university.
- National/Regional Rank: it's based on the country's scope.
- Total Score: the score of the university.
- Logo: logo of the university.
- University Detail: shows details about a university.

Shanghai 2023:
- Rank: rank of the university.
- Logo: logo of the university.
- Name: name of the university.
- Link: shows a link to university details including: its best subjects' ranks and some key statistics.
- website: shows a link to the website of the university.
- Flag: shows the flag of the country of the university.
- Country: shows the country of the university.
- Region: shows the continent of the country of the university.
- Foundation year: shows the year when the university was established.
- Adress: shows the address of the university.
- Total enrollment: shows the total number of enrolled students in the university.
- Total International Enrollment: shows the total number of enrolled international students in the university.
- UG_Entollment: shows the number of enrolled undergradute students.
- International_UG_Enrollment: shows the percentage of enrolled international undergraduate students out of the number of enrolled undergraduate students.
- PG_Enrollment: shows the number of enrolled post-graduate students in the university.
- International_PG_Enrollment: shows the percentage of enrolled international post-graduate students out of the number of enrolled post-graduate students.
- latitude: shows the north-south position in decimal degrees.
- longitude: shows the the east-west position in decimal degrees.

Times Higher Education 2022 & 2023:
- rank: The rank of the university.  
- name: The name of the university.  
- scores_overall: The overall score assigned to the university based on various metrics.  
- scores_overall_rank: The university's rank based on its overall score.  
- scores_teaching: The score reflecting the quality of teaching at the university.  
- scores_teaching_rank: The university's rank based on its teaching score.  
- scores_research: The score reflecting the quality and quantity of research output.  
- scores_research_rank: The university's rank based on its research score.  
- scores_citations: The score based on the number of citations of research papers produced by the university.  
- scores_citations_rank: The university's rank based on its citations score.  
- scores_industry_income: The score reflecting the university's ability to generate income from industry.  
- scores_industry_income_rank: The university's rank based on its industry income score.  
- scores_international_outlook: The score representing the university's international diversity and collaboration.  
- scores_international_outlook_rank: The university's rank based on its international outlook score.  
- location: The geographical location of the university.  
- stats_number_students: The total number of students enrolled at the university.  
- stats_student_staff_ratio: The ratio of students to academic staff at the university.  
- stats_pc_intl_students: The percentage of international students enrolled.  
- stats_female_male_ratio: The ratio of female to male students at the university.  
- aliases: Alternative names or abbreviations for the university.  
- subjects_offered: The academic subjects or programs available at the university.  
- closed: Indicates whether the university is closed.  
- unaccredited: Indicates whether the university is unaccredited.

  Center for World University Ranking 2022 & 2023
- World Rank: it is based on the global scope.
- Institution: shows the name of the university.
- Location: shows the location (country) of the university.
- National RanK: it is based on the country's scope.
- Educational Rank: this rank reflects the quality of education provided by the university, based on various metrics.
- Employability Rank	:The university's ranking based on the employability of its graduates, often influenced by industry connections and job placement rates.
- Faculty Rank:Ranking based on the qualifications and achievements of the university's faculty members.
- Research Rank:This rank indicates the university's research output and impact, including publications and citations.
- Score:The overall score assigned to the university, typically ranging from 0 to 100, reflecting its performance across various metrics.


# List of EDA steps that applied on data with description

1. Data Profiling: Used descriptive analysis on all datasets and cheked data quality with the 7 dimensions (Reliability, Timeliness, Consistency, Relevance, Uniquness, Completencss, Accuracy Check)
2. Data Cleaning: handling missing values in all datasets, renaming some columns, changing the data type of some columns.
3. Bivariate Analysis: was used to identify the countries with the most top-ranked universities. 
4. Multivariate Analysis: used heatmap to check the corrleation between scores and each factor in Center for World University Ranking dataset.

#Team Members
- Raghad Alharbi
- Sarah Belal
- Sultan Alqasami
- Yaqeen Alhalal
