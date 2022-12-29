# Calibration

With a large organization, we must be consistent in the evaluation across various families, teams and managers. Therefore, several activities take place during the performance review cycle to help us achieve consistency across the board. The calibration step helps us to catch possible inconsistencies early in the cycle before the final performance ratings are communicated to employees. We want to encourage in-person discussion about proposed ratings and keep these calibration discussions within groups of managers managing similar groups of people.

The process is the following:

- Employees fill in their self-rating in the competency spreadsheet and submit it to their manager **ahead** of the performance review meeting. Employees are encouraged to ask their colleagues for feedback before submitting the self-review.
- Managers prepare a draft of the performance reviews for the employees based on their self-evaluation, feedback collected and performance observed over the last six months.
- Technical leaders prepare overview of responsibilities of their guild members and whether those correspond to the seniority. E.g. which senior guild members are not yet involved in code reviews as codeowners. Or, on contrary, which junior guild members already have more responsibilities. 
- Managers submit the proposed score to their superiors (e.g. Engineering Managers submit the proposed score of their ICs to Engineering Directors). The draft score is added to the global spreadsheet.
- Pre-review calibration sessions are organized within various groups:
  - For each family, its Engineering Director and all Engineering Managers meet and go through the following:
    - For all promotions to senior roles and higher (e.g. to Senior Engineer and higher for IC track), discuss justification/achievements.
    - Review the list of people not progressing at all, people going significantly faster than others - discuss reasons.
  - For small families, it makes sense to do a combined session with members of 2 families together. Similar calibration sessions should also happen on higher levels:
    - VP & Engineering Directors reviewing draft ratings of Engineering Managers
    - CTO & VPs reviewing draft ratings of Engineering Directors
- Managers might be asked/encouraged to change the proposed rating for an employee if their initial evaluation of the employee needed to be more consistent with other managers.

Please note that we are still talking only about the proposed draft rating. While often this will accurately represent the fair employee assessment, there can be situations when some new important information comes up on the actual performance review meeting with the employee later, leading to rating adjustment in either direction. That is fine, but such occurrences should be relatively rare.

## Data Sanity Check

There is no good way to do detailed calibration checks across large organizations or teams. Therefore we are doing just a sanity check on the statistical data collected:

- During this exercise, we are looking at the proposed ratings already collected (see Pre-review Calibration chapter).
- The latest proposals for performance review score is in the global tech spreadsheet. This sheet also contains historical ratings, so we can use this data source to understand the 'delta' (change in employees' progress since the previous performance review)
- It doesn't make sense to compare the career growth of employees on different tracks and people of varying seniority (e.g. IC2 against IC4). Therefore we need to split people into `Calibration Groups` - calibration group is a combination of a grade (e.g. IC3 or IC4) and a track (e.g. Engineer). So one example of a calibration group could be `Engineers who were at IC3 grade before this review cycle`.
- The steps below need to be done separately for each calibration group you want to look into:
  - See the distribution of progress deltas (of each employee) within the calibration group. Check for anomalies. Does the progress delta distribution look similar across all families? Should we check if managers in one family are too harsh or too nice?
    - Then review if the distribution is similar across families and teams with large enough statistical samples. 
    - The goal of this exercise is not to remove any anomalies but to understand why it is that way and if it is fair. It is just an indicator that starts the subsequent discussion. 
  - Do people at the beginning of their careers grow faster than experienced employees with many years of experience? 
    - It is expected that people grow very quickly in their first job, while the pace of progress growth typically slows down the higher the employee already is on their career ladder.
