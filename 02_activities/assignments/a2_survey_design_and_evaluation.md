# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
This survey is to collect employees' opinion about the company's working environment and workload. The collected information will be used to modify the company's policy or structure to solve the problem of high turnover rate that observed especially within the entry- and lower-level positions.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: all employees.
Sampling frame: It will be delivered through the company email to all employees.
Sampling units: Employees from the different departments.
Obeservational units: Employees at different level positions (Entry-, Lower-, Senior-)

```

Your 5-10 question survey:
```
1. What's the depertment you belong to?
2. How long since you join the company?
3. What's is your current position level?
4. Do you feel comfortable of the company working environment?
5. Do you feel satified with the current working load?
6. Do you believe your work is being paid fairly?
7. Do you think the company's promotion strategy fit your career development expectation?
8. write your question here... (optional)
9. write your question here... (optional)
10. write your question here... (optional)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: It uses a stratified multistage random sampling design
2. Sample size: 4430
3. Target population: all persons 15 years of age and older living in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions.
4. Sampling frame: This survey uses a frame that combines landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame. Records on the frame are groups of one or several telephone numbers associated with the same address (or single telephone number in the case a link between a telephone number and an address could not be established).
5. Survey mode(s): It combines landline and cellular telephone numbers
6. Timeline: Data were collected from September to December in 2018 and the result was released on January 26, 2021.
7. Response rate: The overall response rate is 41.9%.
8. Weights: A weighting factor is available on the microdata file:

WGHT_PER: This is the basic weighting factor for analysis at the person level, i.e. to calculate estimates of the number of persons (non-institutionalized and aged 15 or over) having one or several given characteristics.

In addition to the estimation weights, bootstrap weights have been created for the purpose of design-based variance estimation.

Estimates based on the survey data are also adjusted (by weighting) so that they are representative of the target population with regard to certain characteristics (each month we have independent estimates for various age-sex groups by province). To the extent that the characteristics are correlated with those independent estimates, this adjustment can improve the precision of estimates.
9. Data processing: It go through the Data Capture; Data Editing and Cleaning; Coding and Classification; Weighting; Confidentiality and Anonymization; Quality Assurance; Data Integration and Dissemination
10. Cleaning, imputation, etc: Logical Consistency Checks:
Identify contradictions (e.g., a respondent claiming to volunteer 50 hours/week but reporting unemployment).
Flag outliers or implausible values for review.
Handling Missing Data:
Use imputation for critical variables (e.g., income) if nonresponse is high, employing statistical methods to fill gaps while preserving data integrity.
Non-critical missing data may remain as-is, with documentation for analysts.
11. Sources of error: Non-sampling error; Coverage error; Other non-sampling errors.
12. Limitations, known biases, etc: Institutionalized individuals and homeless populations were excluded and only aged 15+ were included. It also introduce the non-response bias, social desirability bias,recall bias. Telephone-Based Sampling Limitations: Reliance on landline and mobile phone directories, Address-Based Sampling: While used to supplement coverage, it may miss informal housing arrangements or remote areas.
13. Link to documentation and any additional sources used:
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 18/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
