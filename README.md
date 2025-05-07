## Employibility-Analytics-Dashboard
A data-driven approach to hiring Full Stack Developers in California Region

## Introduction:

The Employability Analytics Dashboard is a decision-support application developed to assist hiring teams in making informed recruitment and workforce management decisions. Created as part of a Master’s Research Project at Saint Louis University, this dashboard specifically focuses on streamlining the hiring process for Full Stack Developer roles in the California region.

Built using Power BI, the dashboard enables a data-driven hiring approach by providing clear and actionable insights into candidate qualifications, professional experience, and technical skills. It serves as a visual tool that simplifies complex data into intuitive visuals, allowing HR teams to evaluate candidates more efficiently and effectively.

## Background of our project:

Traditional hiring processes often rely on manual resume screening, subjective judgments, and unstructured data — all of which can lead to inconsistent hiring decisions and longer time-to-hire cycles. These challenges highlight the need for an evidence-based recruitment model that can bring consistency, fairness, and speed to the process.

This project addresses those challenges by introducing a visual and analytical approach to recruitment. By integrating all relevant candidate data into a centralized dashboard, the tool empowers decision-makers with:
1. Faster access to meaningful insights  
2. Improved alignment between job requirements and candidate profiles  
3. Clear visibility into hiring trends by location, experience, and skills

Visualizing hiring data effectively allows HR professionals to make well-informed decisions at a glance, rather than sorting through volumes of unstructured information.

## Key Functionalities  
The dashboard includes several interactive and analytical capabilities:

- Compare candidate skills with job requirements  
- Rank candidates by resume match and interview scores  
- Filter applicants by location, availability, and experience  
- Identify hiring trends and skill gaps by city  
- Visualize salary expectations vs. offered ranges  


## Dataset Sources & Structure:

The dashboard uses two custom-built datasets designed to simulate real-world hiring data. These datasets include both numerical and categorical data, supporting rich visual exploration.

## 1. Numeric_Job_Postings.xlsx
Details open job roles for Full Stack Developers.
Key variables include:

| Variable                  | Type         | Description                                      |
|--------------------------|--------------|--------------------------------------------------|
| Job ID                   | Categorical  | Unique identifier for each job posting           |
| Job Title                | Text         | Position title (e.g., Full Stack Developer)      |
| Required Skills          | Categorical  | List of technical skills required                |
| Minimum Experience       | Numerical    | Minimum years of experience                      |
| Preferred Certifications | Categorical  | Desired certifications                           |
| Job Location             | Categorical  | California cities or regions                     |
| Job Type                 | Categorical  | Full-time, part-time, contract                   |
| Salary Range             | Numerical    | Minimum and maximum salary                       |
| Required Education Level | Categorical  | Bachelor’s, Master’s, etc.                       |
| Job Posting Date         | Date/Time    | Posting timestamp for temporal analysis          |


## 2. Numeric_Candidate_Profiles.xlsx
Captures applicant data tailored to full stack roles.
Key variables include:

| Variable                     | Type         | Description                                                   |
|-----------------------------|--------------|---------------------------------------------------------------|
| Candidate ID                | Categorical  | Unique identifier per applicant                               |
| Name                        | Text         | Candidate's name                                              |
| Education Level             | Categorical  | Highest education attained                                    |
| Graduation Year             | Date/Time    | Year of graduation                                            |
| Technical Skills            | Categorical  | Known programming languages and frameworks                    |
| Certifications              | Categorical  | Relevant certifications                                       |
| Total & Relevant Experience | Numerical    | Overall and role-specific experience in years                 |
| Interview Score             | Numerical    | Interview performance score                                   |
| Resume Match Score          | Numerical    | Percentage match between resume and job posting               |
| Preferred Location          | Categorical  | Cities where candidate is willing to work                     |
| Availability to Join        | Categorical  | Immediate, 2 weeks, 1 month                                   |
| Current Employment Status   | Categorical  | Employed, unemployed, student                                 |


## HR Managers & Recruiters  
- Rank candidates for faster shortlisting  
- Match candidate availability with project timelines  
- Visualize alignment between job specs and applicant profiles


## Workforce Planners  
- Identify hiring trends by region and experience  
- Assess average experience and certifications among candidates  
- Optimize future hiring strategies

## Institutional & Academic Researchers  
- Study employability patterns and gaps  
- Analyze the relationship between qualifications and job match  
- Use the dashboard as a teaching or simulation tool  


## Visualizations  
The dashboard uses intuitive visuals such as:  
- Stacked bar charts for education and employment status  
- Heatmaps for geographic insights  
- Line graphs for job posting trends  
- Donut charts for skills and certifications  
- Ranking tables with slicers for deep filtering

##  Overview

- **Total Candidates:** 500  
- **Total Job Postings:** 300  
- **Applications Received:** 32,000  
- **Time Period Covered:** 3 Years  

![WhatsApp Image 2025-05-06 at 10 45 57](https://github.com/user-attachments/assets/6ce25c27-c15f-4875-bf31-5243eeed955a)


## Key Insights

###  Candidate Insights

**Experience Level Distribution:**

- Lead: 150  
- Mid: 135  
- Senior: 109  
- Entry: 106  

**Work Preference:**

- On-site: 175 (35%)  
- Remote: 169 (33.8%)  
- Hybrid: 156 (31.2%)  

![WhatsApp Image 2025-05-06 at 10 46 20](https://github.com/user-attachments/assets/fdf2c613-cb60-45ea-af1d-bd1de79512ef)



###  Salary Insights

**Average Salary Expectation vs Present Salary:**

- Notable gap of **$50K**, indicating candidate expectations exceed current offers.

**Job Roles and Salary Range:**

- Top Roles: Web Developer, Software Engineer, Backend, Full-Stack, and Frontend Developers  
- Most common salary range: **< $110K**, with **259 job postings**

![WhatsApp Image 2025-05-06 at 10 46 47](https://github.com/user-attachments/assets/9ed877e9-73c0-4195-b668-e6f927f39329)


###  Market Trends

**Top Job Locations:**

- Concentrated in **California**, especially **Los Angeles** and **San Francisco**

**Top Candidate Skills:**

- Flask, Python, Angular, Ruby, Java

**Market Demand:**

- High: 42.33%  
- Medium: 40.33%  
- Low: 17.33%

![WhatsApp Image 2025-05-06 at 10 47 15](https://github.com/user-attachments/assets/5f8da9d2-d2a6-4e86-82c3-f8755caecbaa)


##  Filters Available

Users can interactively filter the dashboard by:

- Job Role  
- Experience Level  
- Education Level  
- Work Preference  
- Location  
- Salary Range  
- Posting Date  
- Market Demand  



## Technologies Used

- **Power BI**  
- **Microsoft Excel (for data preprocessing)**  
- **DAX & Power Query**  
- **Visual Studio Code (for documentation)**  



## Conclusion  
This project demonstrates how a data-driven approach can streamline hiring processes and reduce recruitment inefficiencies. Although the focus is on Full Stack Developers in California, the dashboard model is flexible and can be expanded to other tech roles or regions.

## Contributors

This project was developed by a team of Master's students from Saint Louis University:

- **Deepak Reddy Balannagari**
- - **Mohana Maddi**
- **Vishal Phani Parapatla**
- **Sai Kumar Chebolu**
- **Sindu Madharapu**



