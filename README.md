# DSA210_TermProject

### **What is the aim of the project?**




In this project, I am going to investigate the crutial connections between studying hour,university GPA,education level,job revenue and life satisfaction.In order to answer this question and enrich the data, I will be using two detailed datasets which are taken from Kaggle.





### **What is the first dataset?**






Firstly, I will be investigating my first dataset which directly focuses on studying hour and GPA.In paticular, aim of using the first dataset is answering the "What are the key factors of having good education and better GPA?" question.


For Dataset Link:



https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset






### **What is the second dataset?**





Secondly, I will be investigating my second dataset which mainly focuses on connections between GPA and economic and life satisfaction.In particular, aim of using the second dataset is answering the "In which ways, academic success affect individuals life?(i.e. job revenue,work-life balance etc)".


For Dataset Link:



https://www.kaggle.com/datasets/adilshamim8/education-and-career-success/data





## **Description of First Dataset**






This dataset contains comprehensive information on 2,392 high school students, detailing their demographics, study habits, parental involvement, extracurricular activities, and academic performance. The target variable, **GradeClass**, classifies students' grades into distinct categories, providing a robust dataset for educational research, predictive modeling, and statistical analysis.






### 1) Student Information




- **StudentID:** A unique identifier assigned to each student (1001 to 3392).








### 2) Demographic Details

- **Age:** The age of the students ranges from 15 to 18 years.
  
- **Gender:** Gender of the students, where 0 represents Male and 1 represents Female.
  
- **Ethnicity:** The ethnicity of the students, coded as follows:
  
0: Caucasian

1: African American

2: Asian

3: Other





### 3) Parental Education

The education level of the parents, coded as follows:

0: None

1: High School

2: Some College

3: Bachelor's

4: Higher





### 4) Study Habits

- **StudyTimeWeekly:** Weekly study time in hours, ranging from 0 to 20.
  
- **Absences:** Number of absences during the school year, ranging from 0 to 30.
  
- **Tutoring:** Tutoring status, where 0 indicates No and 1 indicates Yes.




### 5) Parental Involvement

- **ParentalSupport:** The level of parental support, coded as follows:

0: None

1: Low

2: Moderate

3: High

4: Very High

### 6) Extracurricular Activities

- **Extracurricular:** Participation in extracurricular activities, where 0 indicates No and 1 indicates Yes.
  
- **Sports:** Participation in sports, where 0 indicates No and 1 indicates Yes.
  
- **Music:** Participation in music activities, where 0 indicates No and 1 indicates Yes.
  
- **Volunteering:** Participation in volunteering, where 0 indicates No and 1 indicates Yes.

### 7) Academic Performance

- **GPA:** Grade Point Average on a scale from 2.0 to 4.0, influenced by study habits, parental involvement, and extracurricular activities.
  
- **Target Variable:** Grade Class
  
- **GradeClass:** Classification of students' grades based on GPA:

0: 'A' (GPA >= 3.5)

1: 'B' (3.0 <= GPA < 3.5)

2: 'C' (2.5 <= GPA < 3.0)

3: 'D' (2.0 <= GPA < 2.5)

4: 'F' (GPA < 2.0)



---




## **Description of Second Dataset**







This dataset explores the relationship between academic performance and career success. It includes 5000 records of students' educational backgrounds, skills, and career outcomes. The dataset can be used for various analyses, such as predicting job success based on education, identifying key factors influencing salaries, and understanding the role of networking and internships in career growth.


### **1) Student Information**
- **Student_ID:** Unique identifier for each student
  
- **Age:** Age of the student (18-30 years)
  
- **Gender:**  Gender of the student (Male, Female, or Other)  


### **2) Academic Performance**

- **High_School_GPA:** – High school GPA (2.0 - 4.0 scale)
  
- **SAT_Score:** – Standardized test score (900 - 1600)
  
- **University_Ranking:** – Ranking of the university attended (1-1000)
  
- **University_GPA:** – University GPA (2.0 - 4.0 scale)
  
- **Field_of_Study:** – Major or discipline (e.g., Computer Science, Medicine, Business)  


### **3) Skills & Extracurricular Activities**

- **Internships_Completed:**  Number of internships completed (0-4)
  
- **Projects_Completed:**  Number of personal/academic projects completed (0-9)
  
- **Certifications:**  Number of additional certifications earned (0-5)
  
- **Soft_Skills_Score:**  Soft skills rating (1-10)
  
- **Networking_Score:**  Score based on professional networking and connections (1-10)  


### **4) Career Outcomes**

- **Job_Offers:** Number of job offers received after graduation (0-5)
   
- **Starting_Salary:** First job salary in USD ($25,000 - $150,000)
  
- **Career_Satisfaction:**  Career satisfaction level (1-10)
  
- **Years_to_Promotion:**  Time taken to receive the first promotion (1-5 years)
  
- **Current_Job_Level:**  Career level (Entry, Mid, Senior, Executive)
  
- **Work_Life_Balance:**  Work-life balance rating (1-10)
  
- **Entrepreneurship:**  Whether the individual started a business (Yes/No)




  


## **The Key Idea**





Idea of the project is making connections between these two datasets and applying ML techniques.This project aim to **predict unknown individuals' future career**; therefore, we can find the **optimum career paths** by knowing random individuals' personal habits and background information.








