# Dashboard_Challenge

Inspired by the ![alt text](<img src="https://github.com/robertoalatorre33/HR_Analytics_Dashboard_Challenge/blob/281a8ce87aae81cfcee5ce83e46d69c681f4f92a/Visuals/Organizational%20Engagement%20Dashboard.jpg"  width="400" height="350">) **Case:** You are a consultant working with a human capital division that provides people analytics services to Fortune 500 organizations. The organization has asked you to build a dashboard around their team and organizational performance and employee sentiment. This case is inspired by this Kaggle challenge.

--- 

**Data:** Introduction to the HR Dataset - Version 14 - Last Updated April, 2021. This HR Dataset is a synthetic data set created specifically to use for HR analytics cases and is updated every year or so, by the owners. Updates include additional columns, and to make slight changes to the underlying data.

---

**Inspirational Questions:** Here are some open-ended questions that you can explore and try to address through creating visualizations, or R or Python analyses.

* What is the overall diversity profile of the organization?
* What are our best recruiting sources if we want to ensure a diverse organization?
* Is there any relationship between who a person works for and their performance score?
* Are there areas of the company where pay is not equitable?
* Is there a relationship between age and performance?
* Does working on special projects affects performance?
* Can we predict who is going to terminate and who isn't? What level of accuracy can we achieve on this?

Data Dictionary:

| Feature                  | Description                                                                               | DataType |
|--------------------------|-------------------------------------------------------------------------------------------|----------|
| Employee Name            | Employee’s full name                                                                      | Text     |
| EmpID                    | Employee ID is unique to each employee                                                   | Text     |
| MarriedID                | Is the person married (1 or 0 for yes or no)                                             | Binary   |
| MaritalStatusID          | Marital status code that matches the text field MaritalDesc                              | Integer  |
| EmpStatusID              | Employment status code that matches text field EmploymentStatus                         | Integer  |
| DeptID                   | Department ID code that matches the department the employee works in                     | Integer  |
| PerfScoreID              | Performance Score code that matches the employee’s most recent performance score         | Integer  |
| FromDiversityJobFairID   | Was the employee sourced from the Diversity job fair? 1 or 0 for yes or no               | Binary   |
| Salary                   | The person’s yearly salary. $ U.S. Dollars                                                | Float    |
| Termd                    | Has this employee been terminated - 1 or 0                                               | Binary   |
| PositionID               | An integer indicating the person’s position                                               | Integer  |
| Position                 | The text name/title of the position the person has                                       | Text     |
| State                    | The state that the person lives in                                                        | Text     |
| Zip                      | The zip code for the employee                                                             | Text     |
| DOB                      | Date of Birth for the employee                                                            | Date     |
| Sex                      | Sex - M or F                                                                              | Text     |
| MaritalDesc              | The marital status of the person (divorced, single, widowed, separated, etc)              | Text     |
| CitizenDesc              | Label for whether the person is a Citizen or Eligible NonCitizen                          | Text     |
| HispanicLatino           | Yes or No field for whether the employee is Hispanic/Latino                               | Text     |
| RaceDesc                 | Description/text of the race the person identifies with                                   | Text     |
| DateofHire               | Date the person was hired                                                                 | Date     |
| DateofTermination        | Date the person was terminated, only populated if, in fact, Termd = 1                      | Date     |
| TermReason               | A text reason / description for why the person was terminated                             | Text     |
| EmploymentStatus         | A description/category of the person’s employment status. Anyone currently working full time = Active | Text |
| Department               | Name of the department that the person works in                                           | Text     |
| ManagerName              | The name of the person’s immediate manager                                               | Text     |
| ManagerID                | A unique identifier for each manager                                                     | Integer  |
| RecruitmentSource        | The name of the recruitment source where the employee was recruited from                  | Text     |
| PerformanceScore         | Performance Score text/category (Fully Meets, Partially Meets, PIP, Exceeds)               | Text     |
| EngagementSurvey         | Results from the last engagement survey, managed by our external partner                  | Float    |
| EmpSatisfaction          | A basic satisfaction score between 1 and 5, as reported on a recent employee satisfaction survey | Integer |
| SpecialProjectsCount     | The number of special projects that the employee worked on during the last 6 months       | Integer  |
| LastPerformanceReviewDate| The most recent date of the person’s last performance review                              | Date     |
| DaysLateLast30           | The number of times that the employee was late to work during the last 30 days            | Integer  |
| Absences                 | The number of times the employee was absent from work                                     | Integer  |
