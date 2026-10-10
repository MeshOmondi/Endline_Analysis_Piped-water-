# Endline_Analysis_Piped-water-
Estimating the Causal Impact of Access to Piped Water on Healthcare Expenditure Among Rural Households
## Project Overview

This project demonstrates the application of a **Randomised Controlled Trial (RCT)** design to estimate the causal impact of access to piped water on healthcare expenditure among rural households.

The central research question is:

What is the causal impact of access to piped water on healthcare expenditure among rural households?

Access to piped water may improve household health by reducing exposure to water-related illnesses, potentially lowering household expenditure on treatment and other healthcare services. However, households with access to piped water may differ from those without access in several ways, making it difficult to establish whether differences in healthcare expenditure are attributable to water access itself.

To address this challenge, the project uses a hypothetical RCT framework to demonstrate how random assignment can support causal impact estimation. The analysis focuses on household survey data collected at baseline and follow-up, with Stata used for statistical analysis and Excel provided for data exploration and independent practice.

**Important:** This is a synthetic educational project. The data do not represent actual households or findings from a real-world randomised controlled trial.

## Research Objectives

The overall objective is to demonstrate how an RCT design can be used to estimate the causal impact of access to piped water on healthcare expenditure among rural households.

The specific objectives are to:

* Illustrate how random assignment to treatment and comparison groups can support causal inference.
* Examine household healthcare expenditure in relation to access to piped water.
* Demonstrate the use of baseline and endline household survey data in an impact evaluation.
* Explore sample attrition, non-response and their implications for the final analytical sample.
* Practise data management, descriptive statistics and econometric analysis using Stata.
* Demonstrate how impact evaluation findings can be organised and interpreted in a reproducible analytical workflow.

## RCT Design and Identification Strategy

The project is structured around a **Randomised Controlled Trial (RCT)** design, in which eligible households are randomly assigned to a treatment group or a control group.

* **Treatment group:** Households assigned to receive access to the piped-water intervention.
* **Control group:** Households assigned to the comparison condition, according to the hypothetical study design.
* **Baseline survey:** Collects household information before the intervention or before its effects are assessed.
* **Endline survey:** Collects follow-up information, including household healthcare expenditure, to examine outcomes after the intervention.

Random assignment is intended to make the treatment and control groups comparable, on average, before the intervention. This helps address confounding from both observed and unobserved household characteristics and provides a basis for estimating the causal effect of assignment to the intervention.

The analysis can compare healthcare expenditure between the treatment and control groups at follow-up. Baseline outcome data may also be incorporated to improve precision, depending on the analytical specification.

The interpretation of the estimate depends on the actual assignment procedure, implementation of the intervention, outcome measurement and handling of missing follow-up observations. In a real RCT, the analysis should also consider whether the target is the **intention-to-treat effect** of assignment or the effect of actually receiving piped-water access.

## Study Design, Sample and Statistical Power

The project uses a hypothetical **Randomised Controlled Trial (RCT)** design with baseline and follow-up household surveys to demonstrate how to estimate the causal impact of access to piped water on healthcare expenditure among rural households.

The initial baseline sample comprised **1,032 households**. At the endline, 124 households were lost to follow-up, representing approximately **12% attrition**, while a further 45 households could not be interviewed due to non-response, equivalent to approximately **5% of the initial sample**. Consequently, **863 households were successfully interviewed at endline**, representing approximately 83.6% of the initial baseline sample.

| Survey measure                          | Households | Percentage of baseline sample |
| --------------------------------------- | ---------: | ----------------------------: |
| Initial baseline sample                 |      1,032 |                          100% |
| Attrition at endline                    |        124 |                         12.0% |
| Endline non-response                    |         45 |                          4.4% |
| Total households not interviewed        |        169 |                         16.4% |
| **Successfully interviewed at endline** |    **863** |                     **83.6%** |

### Sample Size and Power Calculations

The study's sample-size planning incorporated allowances for attrition and non-response to account for the possibility that some households would not be interviewed during the follow-up survey. The power calculations were designed around a **minimum detectable effect (MDE) of 2,000** for the healthcare expenditure outcome. The MDE represents the smallest effect the study was designed to detect statistically, given the assumptions and parameters used in the power calculation.

The initial sample size and the planned allowances were intended to support the evaluation's ability to detect a meaningful difference in healthcare expenditure between the treatment and control groups. The endline figures reflect the households successfully followed up and interviewed, rather than the original sample-size planning assumptions.

In an RCT, attrition and non-response are important because the loss of observations may affect statistical power and, if related to treatment assignment or household outcomes, may also introduce bias. For this reason, the analysis should examine follow-up rates by treatment assignment and consider the implications of missing observations when interpreting the estimated treatment effect.

**Note:** The MDE of 2,000 is expressed in the units of the healthcare expenditure outcome. The interpretation of the power calculation depends on the assumptions used, including the significance level, statistical power, outcome variability and treatment-control allocation.



## Data and Files

This repository includes:

### Stata analysis file

The Stata file provides the analysis workflow for practising statistical analysis and econometric methods relevant to an RCT-based impact evaluation. Users can inspect the commands, review the analytical steps and adapt the code for learning purposes.

### Excel dataset

The Excel file contains the synthetic household survey data for independent exploration, data cleaning, descriptive analysis and further practice. It can be downloaded directly from the repository.

## Learning Applications

Users can practise:

1. Exploring household survey variables and checking data quality.
2. Summarising baseline and endline outcomes.
3. Examining treatment and control group differences.
4. Accounting for attrition and non-response.
5. Running regression-based analyses in Stata.
6. Exploring intention-to-treat estimation and the assumptions underlying causal inference in an RCT.
7. Documenting analysis steps to support reproducibility.

## Data and Interpretation Disclaimer

The dataset is synthetic and intended solely for education, demonstration and practice. It does not represent actual fieldwork, a verified intervention or empirical evidence about the effect of piped-water access on healthcare expenditure.

The RCT framework illustrates how random assignment can support causal inference; the presence of synthetic data alone does not establish that a real randomisation process occurred or that any estimated effect is a real-world causal finding.
