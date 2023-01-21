# Grades

The last piece of the puzzle is grading within career tracks. Career progress is a continuous number between 0 and 5, however we need to establish a finite number of job titles, grades in company-wide career ladder etc. That is why each career track is subdivided into finite (usually 4) buckets. **Based on your career track and progress, you can look up your grade within the table below.** That will determine your job title, your minimum salary bound, next salary bound and also grade in company-wide career ladder. It contains the following columns:

- **Career Track** - Name of the [career track](career-tracks/readme.md).
- **Min Progress** - Minimum [progress](progress.md) in the [career track](career-tracks/readme.md) required for the grade. Closed lower bound.
- **Max Progress** - Maximum [progress](progress.md) in the [career track](career-tracks/readme.md) required for the grade. Open upper bound.
- **Grade** - Grade within the company-wide career ladder.
- **Job Title** - Job title corresponding to the grade and career track.
- **Min Salary** - Minimum normalized salary awarded to the grade and career track.
- **Next Salary** - Next minimum normalized salary, corresponding to max progress.

For example an engineer with progress P = 2.50 would have grade IC4, minimum normalized salary 98000 and next normalized salary 138000. Their job title would be e.g. "Senior Backend Engineer". Some job titles contain `{Discriminator}` which is a dynamic placeholder that can be replaced with various values, most common ones are "Backend", "Frontend" and "Mobile" in case of IC roles. For management roles, it can be name of family or division. More on how to interpret and work with the normalized salaries can be found in the [compensation](compensation.md) guide.

| Career Track           | Min Progress | Max Progress | Grade | Job Title                                       | Min Salary | Next Salary |
| ---------------------- | ------------ | ------------ | ----- | ----------------------------------------------- | ---------- | ----------- |
| Product Division Lead  | 3.50         | 5.00         | L1    | VP Engineering, Product                         | 0          | 0           |
| Platform Division Lead | 3.50         | 5.00         | L1    | VP Engineering, Platform                        | 0          | 0           |
| Product Family Lead    | 0.00         | 3.10         | M1    | Engineering Manager, {Discriminator}            | 0          | 0           |
| Product Family Lead    | 3.10         | 4.20         | D1    | Director of Engineering, {Discriminator}        | 0          | 0           |
| Product Family Lead    | 4.20         | 5.00         | D2    | Senior Director of Engineering, {Discriminator} | 0          | 0           |
| Platform Family Lead   | 0.00         | 3.10         | M1    | Engineering Manager, {Discriminator}            | 0          | 0           |
| Platform Family Lead   | 3.10         | 4.20         | D1    | Director of Engineering, {Discriminator}        | 0          | 0           |
| Platform Family Lead   | 4.20         | 5.00         | D2    | Senior Director of Engineering, {Discriminator} | 0          | 0           |
| DevOps Family Lead     | 0.00         | 3.10         | M1    | DevOps Manager                                  | 0          | 0           |
| DevOps Family Lead     | 3.10         | 4.20         | D1    | Director of DevOps                              | 0          | 0           |
| DevOps Family Lead     | 4.20         | 5.00         | D2    | Senior Director of DevOps                       | 0          | 0           |
| Product Team Lead      | 0.00         | 1.40         | S1    | Engineering Manager                             | 0          | 0           |
| Product Team Lead      | 1.40         | 2.60         | S2    | Engineering Manager                             | 0          | 0           |
| Product Team Lead      | 2.60         | 3.80         | M1    | Engineering Manager                             | 0          | 0           |
| Product Team Lead      | 3.80         | 5.00         | M2    | Senior Engineering Manager                      | 0          | 0           |
| Platform Team Lead     | 0.00         | 1.40         | S1    | Engineering Manager                             | 0          | 0           |
| Platform Team Lead     | 1.40         | 2.60         | S2    | Engineering Manager                             | 0          | 0           |
| Platform Team Lead     | 2.60         | 3.80         | M1    | Engineering Manager                             | 0          | 0           |
| Platform Team Lead     | 3.80         | 5.00         | M2    | Senior Engineering Manager                      | 0          | 0           |
| Data Team Lead         | 0.00         | 1.40         | S1    | Team Lead, Data Science & Engineering           | 0          | 0           |
| Data Team Lead         | 1.40         | 2.60         | S2    | Team Lead, Data Science & Engineering           | 0          | 0           |
| Data Team Lead         | 2.60         | 3.80         | M1    | Team Lead, Data Science & Engineering           | 0          | 0           |
| Data Team Lead         | 3.80         | 5.00         | M2    | Senior Team Lead, Data Science & Engineering    | 0          | 0           |
| DevOps Team Lead       | 0.00         | 1.40         | S1    | DevOps Manager                                  | 0          | 0           |
| DevOps Team Lead       | 1.40         | 2.60         | S2    | DevOps Manager                                  | 0          | 0           |
| DevOps Team Lead       | 2.60         | 3.80         | M1    | DevOps Manager                                  | 0          | 0           |
| DevOps Team Lead       | 3.80         | 5.00         | M2    | Senior DevOps Manager                           | 0          | 0           |
| Technical Leader       | 0.00         | 3.10         | S2    | Staff {Discriminator} Engineer                  | 0          | 0           |
| Technical Leader       | 3.10         | 4.20         | M1    | Senior Staff {Discriminator} Engineer           | 0          | 0           |
| Technical Leader       | 4.20         | 5.00         | D1    | Principal {Discriminator} Engineer              | 0          | 0           |
| Engineer               | 0.00         | 1.20         | IC2   | {Discriminator} Engineer                        | 0          | 0           |
| Engineer               | 1.20         | 2.40         | IC3   | {Discriminator} Engineer II                     | 0          | 0           |
| Engineer               | 2.40         | 3.60         | IC4   | Senior {Discriminator} Engineer                 | 0          | 0           |
| Engineer               | 3.60         | 5.00         | IC5   | Senior {Discriminator} Engineer II              | 0          | 0           |
| Data Scientist         | 0.00         | 1.20         | IC2   | Data Scientist                                  | 0          | 0           |
| Data Scientist         | 1.20         | 2.40         | IC3   | Data Scientist II                               | 0          | 0           |
| Data Scientist         | 2.40         | 3.60         | IC4   | Senior Data Scientist                           | 0          | 0           |
| Data Scientist         | 3.60         | 5.00         | IC5   | Senior Data Scientist II                        | 0          | 0           |
| Data Engineer          | 0.00         | 1.20         | IC2   | Data Engineer                                   | 0          | 0           |
| Data Engineer          | 1.20         | 2.40         | IC3   | Data Engineer II                                | 0          | 0           |
| Data Engineer          | 2.40         | 3.60         | IC4   | Senior Data Engineer                            | 0          | 0           |
| Data Engineer          | 3.60         | 5.00         | IC5   | Senior Data Engineer II                         | 0          | 0           |
| DevOps Engineer        | 0.00         | 1.20         | IC2   | Devops Engineer                                 | 0          | 0           |
| DevOps Engineer        | 1.20         | 2.40         | IC3   | Devops Engineer II                              | 0          | 0           |
| DevOps Engineer        | 2.40         | 3.60         | IC4   | Senior Devops Engineer                          | 0          | 0           |
| DevOps Engineer        | 3.60         | 5.00         | IC5   | Senior Devops Engineer II                       | 0          | 0           |
| QA Engineer            | 0.00         | 1.20         | IC1   | QA Engineer                                     | 0          | 0           |
| QA Engineer            | 1.20         | 2.40         | IC2   | QA Engineer II                                  | 0          | 0           |
| QA Engineer            | 2.40         | 3.60         | IC3   | Senior QA Engineer                              | 0          | 0           |
| QA Engineer            | 3.60         | 5.00         | IC4   | Senior QA Engineer II                           | 0          | 0           |
