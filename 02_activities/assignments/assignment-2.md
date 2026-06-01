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

The number of your chosen topic: `2`

Describe the purpose of your survey:
```
The purpose of the survey is to find what issues and party leadership qualities are most important to voters leading up to the election. The goal is to figure out what strategy to take moving forward to increase party and leader popularity to gain votes and better secure the election.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population for the survey is all eligible voters. Voters that are especially important are people who are undecided, or are more closely aligned politically with the current stance of the party because they are more likely to become voters following small changes to the party. The sampling unit is the individual voters (or potential voters). The survey sampling strategy will involve a random sample among stratified groups. I selected this sampling strategy because it's common among political polls and surveys. Eligible voters will be separated into groups by riding, age, and gender, and these groups will then be randomly sampled in proportion to their representation in the whole voting block.
```

Your 5-10 question survey:
```
1. How likely are you to vote in the upcoming election?: I will vote; I will likely vote; Undecided; I likely will not vote; I will not vote
2. If the election were held today, which party would you vote for?: Liberal; Conservative; NDP; Green; Bloc Quebecois; People's Party of Canada; Other; Prefer not to say
3. Which of the following issues do you feel are most important?: Housing; Affordability; Economics; Healthcare; Climate; Immigration; Energy; Other
4. What policy change would increase the chance of you voting for our party?: Increased subsidies for home purchases; Economic reform; Healthcare subsidies; Environmental sustainability; Other
5. How would you describe the party leader in the following?: Trustworthiness; Reliability; Consistency; Leadership ability; Competence; Other
6. write your question here... (optional)
7. write your question here... (optional)
8. write your question here... (optional)
9. write your question here... (optional)
10. write your question here... (optional)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type
    Stratified and weighted sampling. This was done to produce estimates that are representative of the general population while accounting for gaps in sampling and response.
2. Sample size
    Approximately 40 000 invitation letters to the electronic questionnaire were sent, and an estimated 24 000 would be responded to.
3. Target population
    Everyone 15 years old or older in Canada, excluding residents of the three territories, full-time residents of institutions, and residents of First Nations reserves
4. Sampling frame
    Stratified by province and population groups, with one response from an eligible person in each household
5. Survey mode(s)
    Two modes were used, an electronic questionnaire done online, and a computer assisted phone interview
6. Timeline
    Data were collected from Sept 4th, 2018 to Dec 28th, 2018
7. Response rate
    Response rate was likely around 60%, based on the number sent (40k) and number of expected responses (24k). I could not find information on exact response rates.
8. Weights
    Responses were weighted by the number of persons represented by a given respondent (i.e., number of people in each household represented by a single response). Survey estimates were also weighted to represent all persons in the target population, inclding those not covered by the survey frame. Also, some non-responses occured at the household level, and some occured at the individual level, so survey estimates were weighted to account for these non-responses. Weights were also adjusted so that the weighted income distribution matched the 2017 CIS distribution by province. Lastly, bootstrap weights were created for design-based variance estimation.
9. Data processing
    Performed using Statistics Canada's Social Survey Processing Environment's (SSPE) generalized processing steps
10. Cleaning, imputation, etc
    Edits for cleaning were performed automatically and manually at verious stages of processing. Family relationships were checked to ensure the integrity of the data matrix, and checks done in series to ensure consistency of survey data.
11. Sources of error
    A common issue is that different sampled houses or even people within the house could produce different results. The sample excluded the territories, institutionalized people, and First Nations people, meaning many Canadians were inherently excluded. Also, some people selected didn't respond, though there was effort to address this issue by weighting. Lastly, the sample depends on the respondants accurately reporting the information in the questionnaire. 
12. Limitations, known biases, etc
    A major limitation is that the survey excludes some demographics in Canada (people in the territories, institutions, and First Nations reserves) and the results likely don't apply to them. Also, the self-reporting of these data may result in people inflating their volunteer and donation information due to social biases looking favourably on these behaviours.
13. Link to documentation and any additional sources used
    https://www150.statcan.gc.ca/n1/en/catalogue/45250011 
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
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
