THE CHINESE UNIVERSITY OF HONG KONG, SHENZHEN
2023 - 2024 TERM 2
ECO 3121 Introductory Econometrics
ASSIGNMENT 2
TOPIC: Multiple Linear Regression Model.
INSTRUCTIONS:
• Please label clearly each answer with the appropriate question number and letter. Securely staple all answer sheets together, and make certain that your name(s) and student number (s) are printed clearly at the top of each answer sheet.
• Please use STATA to do Question 1, and report your STATA commands and results together with your answers to the questions.
• Hand-written answers must be legible. Illegible assignments will be returned unmarked.
• Please combine your answers with supporting documents into one Adobe PDF file and submit.
DUE DATE: 5PM Friday March 22, 2024
Please submit your work on Blackboard. Late submissions will receive a 0 with no excuses.
MARKING: Marks for each question are indicated in parentheses. Total marks for the assignment equal 110. Marks are given for both content and presentation.

Question 1 (40 marks)
Data file: 3121A2.da (3121A2.cs)
You are investigating the relationship between the final exam grades of university students in an introductory economics course and those students' class attendance, as measured by the percentage of classes each student attended during the term. You also have sample data on two additional explanatory variables: each student's cumulative GPA (Grade Point Average) prior to the term in which the introductory economics course was taken; and each student's score on a standardized college entrance exam, the ACT exam. You have sample data for 680 students on the following variables:
finalpct; = final exam grade of the i-th student, measured in percentage points;
attrate; = percentage of classes attended by the i-th student during the term, measured in
percentage points;
GPA; = Cumulative Grade Point Average (GPA) of the i-th student prior to the term in which
the introductory economics course was taken, measured out of 4.0;
ACT; = ACT score of the i-th student on the ACT college entrance exam, measured in points.
Compute and present OLS estimates of the following population regression equation for the full sample of 680 students:
finalpcti = Bo + Battrate; + BrGPA; + BzGPAT + BAACT + Ui
(1)
(8 marks)
(a) Compute and report OLS estimates of regression equation (1) for the full sample of 680 students. Present the estimation results, and report the OLS estimates B and By, the estimated standard errors of B, and Bs, the t-statistics for z and 3, the standard error of the regression, and the R2
(11 marks)
(b) Write the expression implied by equation (1) for the partial (ceteris paribus) marginal effect of
GPA; on final exam grade. Use the OLS estimation results for equation (1) to test the proposition that the Grade Point Average has no effect on mean final exam grade for all values of GPA;. State the null and alternative hypotheses, and show how the sample value of the test statistic is calculated (give its formula). Report the sample value of the test statistic and its p-value. State the decision rule you use, and the inference you would draw at the 5 percent significance level. Does the sample evidence favor the proposition?
(10 marks)
(c) Use the OLS estimation results for equation (1) to test an instructor's conjecture that the partial (ceteris paribus) marginal effect of GPA; on final exam grade, is larger for students with high Grade Point Average than for students with low Grade Point Average. State the null and alternative hypotheses, and show how the sample value of the test statistic is calculated (give its formula).
Report the sample value of the test statistic and its -value. State the appropriate critical values of the null distribution of the test statistic for the 5 percent significance level. State the decision rule

you use, and the inference you would draw from the test. Does the sample evidence favor the instructor's conjecture?
(11 marks)
The average student in the course has a Grade Point Average of 2.59, that is, the sample mean value of GPA; equals 2.59. Use the OLS estimation results for equation (1) to test the proposition that the marginal effect of GPA; on students final exam grade equals zero for the average student whose Grade Point Average is 2.59. State the null and alternative hypotheses, and show how the sample value of the test statistic is calculated (give its formula. Report the sample value of the test statistic and its p-value. State the appropriate critical values of the null distribution of the test statistic for the 5 percent significance levels. State the decision rule you use, and the inference you would draw from the test.
Question 2 (40 marks)
You are conducting an econometric investigation into the effect on house prices of proximity to a power plant, which presumably generates negative externalities for homeowners and others located close to it. The sample data consist of observations for 321 houses that were sold in a single metropolitan area in the year 2012 on the following variables:
price;: selling price of house i, in dollars. hsize;: house size of house i, in square meters. agei: age of house i, in years.
dist;: distance of house i from power plant, in meters.
Using the given sample data on 321 houses, your trusty research assistant has estimated the following regression equation (1) and obtained the estimation results (with estimated standard errors given in parentheses below the coefficient estimates):
price; = Bo + Bahsize; + Bage; + Bage? + Badisti + Bsdist? + 2; (1)
Bo = 17,222
(12,689)
B3 = 3.743
(1.059)
SST = 597,850,000,000
B1 = 361.1
B2 =-915.7
(28.54
(163.5)
B4 = 8.220
Bs =-0.000695
(3.456)
(0.000254)
SSR = 271,740,000,000
N = 321
(8 marks)
(a) Use the estimation results for regression equation (1) to test the joint significance of the slope
coefficient estimates B; ( = 1, ...,5) in regression equation (1). State the null and alternative
hypotheses, and show how you calculate the required test statistic. State the inference you would draw from the test at the 5 percent significance level.

(10 marks)
(b) Compute a test of the proposition that the distance from the power plant had an increasing marginal effect on mean prices as the distance increased. State the coefficient restrictions on regression equation (1) implied by this proposition; that is, state the null hypothesis Ho and the alternative hypothesis Hi. Find the p-value of the test (you may write down the expression of the probability without computing the number). Can you reject the null hypothesis at the 10% level?
(12 marks)
(c) Compute a test of the proposition that the house size was the only factor that affects the house prices and, furthermore, if the house size increases by one square meter, then the predicted house prices increase by 350 dollars. State the coefficient restrictions on regression equation (1) implied by this proposition; that is, state the null hypothesis H and the alternative hypothesis H. Write the restricted regression equation implied by the null hypothesis Ho. OLS estimation of this
restricted regression equation yields a Residual Sum-of-Squares value of SSR = 357,850,000,000.
Use this information, together with the results from OLS estimation of equation (1), to calculate the required test statistic. State the inference you would draw from the test at the 5 percent significance level.
(10 marks)
(d) Use the estimation results for regression equation (1) to perform a two-tail test of the null
hypothesis B = -3B at the 5 percent significance level. The estimated covariance of 1 and Br
is Cov B1ß2) = 1418.9597. State the null and alternative hypotheses, show how you calculate the required test statistic, and state its null distribution. State the decision rule you use, and the inference you would draw from the test at the 5 percent significance level.
Question 3 (30 marks)
Consider the standard simple regression model y = Bo + B1x + u under the Gauss-Markov
Assumptions SLR.1 through SLR.S. The usual OLS estimators Bo and 1 are unbiased for their respective population parameters. Let Bo and By be the estimator of Bo and By obtained by
connecting the first two observations (X1, Y) and (X2, 2). [Bo = Y -
- 12-31 xg and By = 1271]
エっーン」
#2-X1
(15 marks)
(a) Prove that B and By are unbiased for Bo and By.
(15 marks)
Var (Ba(x))
(b) Find Var (&alx), and pr

# ECO3121 Introductory Econometrics ASSIGNMENT 2

# WeChat: cstutorcs

# QQ: 749389476

# Email: tutorcs@163.com

# Computer Science Tutor

# Programming Code Help
