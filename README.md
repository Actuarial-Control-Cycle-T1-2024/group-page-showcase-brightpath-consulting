# BrightPath Consulting - SuperLife Health Incentive Program

_“Our bodies are our gardens, our wills are our gardeners.” – William Shakespeare_

<p align="center">
  <img src="Resources/logo_team.png" height="100" />
  <img src="Resources/logo_unsw.png" height="100" />
</p>

## Overview

In the modern age of Lumaria, health is increasingly recognized as the ultimate wealth. BrightPath Consulting, in collaboration with SuperLife Insurance, introduces a cutting-edge health incentive program designed to encourage healthy behaviours among policyholders, thereby reducing mortality rates, boosting life insurance sales, and enhancing market competitiveness.

This GitHub repository houses all project materials for the SuperLife Insurance Incentive Program, including data analyses, R coding scripts, modelling methodologies, and comprehensive documentation on pricing strategies and sensitivity testing analysis. We aim to provide a transparent, detailed overview of our approach to creating a sustainable, beneficial program for SuperLife and its customers.

## Repository Structure

```{shell}
.
├─ Distribution Channel (Online) Analysis
│  ├─ Plots and Results
│  └─ R Coding
├─ Inflation and Interest Rates Modelling
│  ├─ Plots and Results
│  └─ R Coding
├─ Lapse Rates Modelling
│  ├─ Plots and Results
│  └─ R Coding
├─ Mortality Rates Modelling
│  ├─ Plots and Results
│  └─ R Coding
├─ Pricing
│  ├─ Pricing Template
│  ├─ Pricing Design
│  └─ Product Performance (Normal Conditions)
│     ├─ Plots and Results
│     └─ R Coding
├─ Resources
├─ Risk Analysis
│  ├─ Plots and Results
│  └─ R Coding
├─ Sales Prediction Modelling
│  ├─ Plots and Results
│  └─ R Coding
└─ Sensitivity Testing Analysis
   ├─ Plots and Results
   └─ R Coding
```

## Project Report

### Executive Summary

In Lumaria, the modern age has progressively transformed societal lifestyles and perspectives, firmly establishing the belief that health is the ultimate health within the community. With this principle in consideration and leveraging available data, BrightPath Consulting has designed a health incentive program bundled with SuperLife’s longer-term life insurance offerings. The core objectives of the programs are to incentivise healthy behaviours through participation in the program, decrease anticipated mortality rates, improve life insurance sales, enhance product marketability and competitiveness, and contribute economic value to SuperLife.
 
This report highlights the design and unique features of the program aimed at enhancing health incentives among the policyholders. Additionally, it delves into appropriate modelling approaches and meticulously considers necessary assumptions to capture pivotal factors such as inflation and interest rates, mortality rates, and lapse rates, that could significantly impact the pricing of the program. By taking these considerations into account, the cost of the program is then determined using unique formulae developed by BrightPath Consulting. Following this, analysis, including sensitivity analysis and risk analysis, will be conducted to examine and evaluate the performance of the program designed. 

### Program Design

This program aims to tackle the main objectives by implementing two interventions tailored to non-smoking and smoking policyholders in Lumaria (refer to *Appendix A* for more details on the invention selection approach).

*Figure 1: Features and design of health incentive program.*
<img src="Resources/Figure 1.png">

***Incentives for Preventive Screenings***  
Late detection of potential health issues or diseases has generally increased the risk of mortality due to more severe health outcomes, limited treatment options, and higher treatment cost. One common example involves the late detection and treatment for cancer diseases. According to the British Medical Journal (2020), the risk of mortality is raised by approximately 10% for each month of delay in cancer treatment. Therefore, the implementation of incentives for preventive screenings in this program aims to encourage policyholders, regardless of smoking status, to undergo preventive health screenings by offering monetary rewards. The list of preventive health screenings are provided in *Appendix B*. Consequently, policyholders who participate in the listed preventive health screenings will receive monetary rewards annually. With the implementation of this intervention, policyholders are empowered to proactively manage their health and well-being, resulting in a higher quality of life and a reduced risk of mortality.

***Smoking Cessation Programs***  
Smoking, as one of the leading causes of mortality, should be considered to achieve the main objectives of the program. This is evident from the mortality analysis conducted, which highlights smoking as the predominant factor influencing mortality rates in Lumaria (refer to *Appendix D* for further details). Furthermore, the latest available estimate from the World Health Organization (2023), as of November 2023, suggests that tobacco claims the lives of over 7 million smokers worldwide annually. Therefore, smoking cessation programs are implemented to directly address smoking policyholders by offering resources and ample support, with the goal of reducing smoking frequency or ideally facilitating smoking cessation, and ultimately, reduce the mortality rates. The list of available resources and support for smoking policyholders is provided in *Appendix B*. By introducing this intervention, smoking policyholders are provided with access to all available resources and support aimed at assisting them in overcoming nicotine addiction, which harms their health and increases their risk of mortality.

### Pricing and Modelling

***Methodologies***  
The methodologies involved to model and forecast specific factors that can significantly impact the performance of the program are stated in *Table 1* below.

*Table 1: Methodologies applied to economic factors, mortality rates, policyholder lapsing behaviour and future sales.*
<img src="Resources/Table 1.png">  
*Note that SPWL represents single premium whole life and T20 represents 20-year level-term.*

***Assumptions***  
During the process of conducting analyses, constructing models, and carrying out calculations, assumptions are considered and implemented to steer the decision-making process as a result of data limitations and insufficient information. The central assumptions considered in the analyses, models and calculations are thoroughly discussed.

The central assumptions considered are as follows.
* After the implementation of the program, policyholders are expected to pay level premiums annually for 20-year term insurance and single-premium for whole-life insurance products.
* All policyholders enter at the start of the year where the policy issued and premiums are received at the start of each year, while all benefit payments are made at end of the corresponding year where the policyholder dies or lapses.
* Lapses can occur only for policyholders with a 20-year term insurance policy and are not possible for those with a whole-life insurance policy.

Central assumptions are also considered when implementing each intervention under the health incentive program. These central assumptions are listed in the *Table 2* below.

*Table 2: Central assumptions for the health incentive program.*
<img src="Resources/Table 2.png">

***Pricing and Modelling***  
The pricing structure for the health incentive program, bundled with SuperLife’s longer-term life insurance offerings, considers the application of actuarial equivalence as such.
<img src="Resources/Formula Report.png">
The actuarial equivalence concept is applied to establish both premiums with and without the health incentive program, along with the estimated mortality rates and potential expenses considered. The objective of this application is to observe and analyse the changes in expected value for premium, specifically T20 insurance product with level-premium rather than SPWL with single-premium, and death benefits before and after the implementation of the program (refer to *Appendix G* for more information). Note that this program sets a reserve rate of 10% of the face value for every policyholder within the program. This rate is determined by maintaining its actuarial present value at the year of issue constant. While this approach may appear daring, it remains in compliance with regulations. This assertion is supported by Regina (2021), who states that legal minimum reserve requirements for insurance typically fall within the range of 8% to 12% of anticipated claims.

As a result, the application of the following methods and calculations has produced the desired outcomes concerning profitability of bundling the program with the SPWL and T20 insurance products. The estimated profit per policy determined is approximately Č140,000 after the program is implemented. Although the estimated profit per policy is substantial, it is expected to decrease over time. The reason behind this decrease is mainly due to an increase in claim frequency, especially for SPWL policyholders, where the claim amount is considered tremendous.

*Figure 2: Average premium per face amount per year.*
<img src="Resources/Figure 2.png">

Based on *Figure 2*, the results depict the minimum premium acceptance rate for each year, with the red line representing the current premium and the blue line representing the least premium accepted. Upon observation of the results, there is a clear evidence that both SPWL and T20 insurance products become profitable after the implementation of the health incentive program, as there is a noticeable difference between the current premium and the least premium accepted. These differences can serve as potential options for SuperLife to provide additional rewards or benefits to existing policyholders to enhance customer relationships, or even to promote its unique insurance products to a wider audience of potential customers.

***Sensitivity Testing***  
The robustness of the health incentive program is examined through a sensitivity analysis, exploring two specific factors which are changes in interest rates and changes in mortality rates. These sensitivity tests are conducted with these factors set to the following extreme values using specific methods mentioned in *Table 3* below.

*Table 3: Specific methods considered for sensitivity tests.*
<img src="Resources/Table 2.png">

When conducting the sensitivity analysis, the performance of the health incentive program under extreme case scenarios is compared with the expected or baseline scenario to monitor the robustness, ensure the quality assurance, and promote long-term sustainability of the program, while also maintaining stakeholder confidence. Therefore, the application of the specific methods mentioned regarding interest rates and mortality rates has yielded the results of the sensitivity tests, which are presented in *Figure 3* and *Figure 4* below.

*Figure 3: Sensitivity test on interest rates with and without health incentive program.*
<img src="Resources/Figure 3.png">

*Figure 4: Sensitivity test on mortality rates with and without health incentive program.*
<img src="Resources/Figure 4.png">  
Note that the application of actuarial equivalence has resulted in an expected profit of Č0 under baseline scenarios for both SPWL and T20 insurance products without the implementation of the program.

According to *Figure 3*, where sensitivity analysis is conducted on interest rates, the results indicate that both insurance products are considered non-resilient against changes in interest rates, as significant movements are observed in the expected profit across different scenarios. Additionally, the introduction of the health incentive program does not significantly improve or deteriorate the robustness of both insurance products with regard to interest rates.

Next, the results of the sensitivity analysis on mortality rate in *Figure 4* demonstrate that the insurance products exhibit resilience against changes in mortality rates. Although the expected profit varies across different scenarios, the difference compared to the baseline expected profit appears to be constrained within a specific limit. However, similar to before, the implementation of the health incentive program does not significantly affect the robustness of both insurance products.

Therefore, the results of sensitivity analysis conclude that the health incentive program is capable of improving the expected profit of both SPWL and T20 insurance products while maintaining the same resilience to changes in interest rates and mortality rates as before implementation. 

***Considerations***  
There are potential considerations that can be taken into account to evaluate the performance and further enhance the effectiveness of the health incentive program. These considerations may include a potential decrease in lapse rates and increase in online buyers.

First, the implementation of the program may potentially lead to lower lapse rates in the future. The main reason behind this is because the program improves the flexibility and versatility of the insurance products, providing policyholders with opportunities to enjoy more rewards and benefits if they remain in the policy. Hence, offering rewards and benefits to existing customers can help boost customer loyalty, and ultimately leads to lower lapse rates. Therefore, potential changes in future lapse rates can be considered when improving the effectiveness of the program.

Second, the technological factor can be fundamental to the program in terms of performance. Since the emergence of modern technology, many policyholders have shifted their preference to purchasing insurance products online (refer to *Appendix H* for more details). This shift can significantly impact product pricing by potentially reducing expenses, particularly high agent commission fees. Nowadays, opting for online application can often be perceived as a simpler and cheaper option compared to purchasing through agents or telemarketers. Therefore, considering this factor may contribute to enhancing the performance of the program.

### Risk and Risk Mitigation

***Risk Identification and Assessment***  
The potential risks significant to the program have been identified in *Table 4* below, along with clarification detailing their impact on the program. These identified risks are then assessed and ranked based on their estimated likelihood and severity, as shown in *Figure 5*.
 
*Table 4: Risk identification and clarification under the health incentive programs*
<img src="Resources/Table 4.png">

*Figure 5: Risk Map for the health incentive program.*
<img src="Resources/Figure 5.png">

***Risk Mitigation***  
The significance of potential risks considered in *Table 4* can be addressed by minimising, or if feasible, eliminating the exposure to these risks with the strategies outlined in *Table 5*, to ensure the sustainability and profitability of the program.

*Table 5: Risk Mitigation Strategies implemented under the health incentive program.*
<img src="Resources/Table 5.png">

### Data and Data Limitations

The data sources and limitations in *Table 6* are utilised to conduct research and analysis on the health incentive program.

*Table 6: Data sources and data limitations for the health incentive program.*
<img src="Resources/Table 6.png">

### Conclusion

The implementation of the proposed health incentive program is projected to fulfill all the primary objectives. The program demonstrates promising results that improve mortality of policyholder, while bringing value to SuperLife in terms of competitiveness, marketability, and economic value. This is evident when examining the capability and reliability of the program across a range of unfavorable scenarios. However, the fundamentals of Actuarial Control Cycle must always be practiced. Therefore, the performance of the program has to be consistently monitored after implementation, necessitating amendments to improve its performance and effectiveness in achieving the primary objectives.

### Appendices


***Appendix A: Evaluating interventions data***

**Data Source**  
The interventions data assembled by SuperLife’s product development team that contains 50 distinct interventions together with approximate impact on mortality rates and approximate per capita cost.

**Intervention Selection Approach**  
When selecting a suitable intervention, factors such as affordability and effectiveness in reducing mortality rates are taken into account, along with the primary factors influencing mortality rates, which will be discussed later in *Appendix D*.

**Data Rearrangement**  
The data is first rearranged to a format where filtering is possible (refer to *Figure A.1*). Subsequently, comparisons are made between interventions based on their approximate impact on mortality rates, approximate per capita cost, and the intended purpose of the interventions. This ensures that the selected interventions are capable of addressing both affordability and reduction in mortality rates. Therefore, based on these criteria, the selected interventions are listed in *Table A.1* below.

*Table A.1: Interventions selected for the health incentive program.*
<img src="Resources/Table A1.png">

*Figure A.1: Rearranged interventions data for filtration.*
<img src="Resources/Figure A1.png">

***Appendix B: Further details on program design***

**List of preventive health screenings under incentives of preventive screenings**  
All preventive health screenings that are considered under incentives of preventive screenings are stated in *Table B.1* below.

*Table B.1: Preventive health screenings list for incentives of preventive screenings.*
<img src="Resources/Table B1.png">

**List of available resources and support for smoking cessation programs**
All available resources and support that are included under smoking cessation programs are stated in *Table B.2* below.

*Table B.2: Resources and support list for smoking cessation programs.*
<img src="Resources/Table B2.png">

***Appendix C: Modelling inflation and interest rates***

**Data Source**  
The economic time-series data provided consist of information on inflation and interest rates including overnight rates, one-year spot rates, and 10-year annual spot rates, spanning the years from 1962 to 2023. 

**Data Cleaning and Visualisation**  
To guarantee the quality of data, the initial step involves checking for any missing values, followed by ensuring consistency in the data format. Next, data exploration and visualisation are performed to inspect if there are any specific patterns, or trends, and also any potential outliers or abnormalities observed in the time-series data (refer to *Figure C.1*).

*Figure C.1: Plots for all inflation and interest rates from 1962 to 2023.*
<img src="Resources/Figure C1.png">

**Data Selection Criteria**
Autoregressive Integrated Moving Average (ARIMA) will be selected as the statistical approach to model and forecast the economic time-series data. To avoid model complexity and overfitting issues, the hyperparameters p and q are allowed to take values between 0 and 10, while the hyperparameter d is set to values between 0 and 5. The best ARIMA models are selected based on three information criteria, Corrected Akaike Information Criterion (AICC), Akaike Information Criterion (AIC), and Bayesian Information Criterion, for all inflation and interest rates, while ensuring the stationarity (refer to *Table C.1*). Subsequently, these models will be used to forecast for the next 100 years to observe the performance of these rates in the future 100 years (refer to *Figure C.2*).

*Table C.1: Best fitted ARIMA models for all inflation and interest rates based on the BIC.*
<img src="Resources/Table C1.png">

*Figure C.2: Forecast results using best fitted ARIMA models for all inflation and interest rates.*
<img src="Resources/Figure C2.png">

***Appendix D: Modelling mortality rates***

**Data Source**  
The SuperLife Inforce Dataset provided contains 978582 policy data, along with 16 covariates for the most recent 20 years. 

**Data Cleaning and Formatting**  
The policy numbers are first censored to ensure customer data privacy. The remaining information is then cleaned and reformatted to guarantee all missing data are well-treated and all data are in the right format before fitting models for mortality estimation. Additionally, four new covariates, including year of exit, cause of exit, survival time, and exist time, are added to the dataset for survival analysis purposes. These data are obtained through calculations from the existing data. 

**Statistical Model Approach**  
Two statistical models that are under considerations are the Cox Proportional Hazards (Cox PH) Model and Lee-Carter Model. While Lee-Carter Model effectively captures the time trend influencing the mortality rates, its accuracy may be limited in this specific case, as it does not account for covariate effects. Therefore, Cox PH Model is chosen as the preferred statistical approach due to its ability to capture the covariate effects on the mortality rates

**Statistical Model Application**  
Kaplan-Meier estimator is applied to each covariate to assess their influence on survival probabilities over time (refer to *Figure D.1a*, *Figure D.1b*, and *Figure D.1c* for Kaplan-Meier Estimator plots for covariates that are involved in the resulting Cox PH model). This is followed by the application of Cox PH statistical approach. The initial Cox PH model is built by accounting all possible covariates to evaluate their significance on mortality rates. Subsequently, less significant covariates are eliminated.

*Figure D.1a: Kaplan-Meier Estimator plots for sex.*
<img src="Resources/Figure D1a.png">

*Figure D.1b: Kaplan-Meier Estimator plots for policy type and smoker status.*
<img src="Resources/Figure D1b.png">

*Figure D.1c: Kaplan-Meier Estimator plots for distribution channel and underwriting class.*
<img src="Resources/Figure D1c.png">

**Model Selection**  
The resulting Cox PH model is built which focuses solely on only five most significant covariates. These covariates are sex, policy type, smoker status, distribution channel, and underwriting class. The effect  (refer to *Table D.1*).

*Table D.1: Resulting Cox PH model and all covariate effects.*
<img src="Resources/Table D1.png">

***Appendix E: Modelling lapse rates***

**Data Source**  
The SuperLife Inforce Dataset provided consists of attributes or information that can be utilised to study the lapse behaviour of the policyholders.

**Assumptions Made**  
In this analysis, there are four assumptions made when deriving the lapse model. These assumptions are as follows:
1.	To ensure model simplicity, all customers of the same age have the same probability of choosing lapse.
2.	Lapse only occurs for 20-year level-term (T20) insurance product.
3.	Since the dataset only contains the year where policyholder lapses, thus it is assumed that all lapses happen at the end of the policy year
4.	All T20 customers that are automatically lapsed are censored for lapse analysis purposes.
5.	Lapse rate for different policyholders remains the same for each ordinal year, meaning the lapse is only dependent on the time from entry year to now.

**Data Extraction and Censoring**  
In this analysis, there is no truncation to consider since the status of the customer is described as a Markov Chain with two absorbing states, the first one being death, and the second one being lapse. Next, as observed in the dataset, if a T20 policyholder dies or holds the policy for 20 years, he or she will have no opportunity to choose to lapse. Hence, these data are marked as censored. Subsequently, a Kaplan Meier Analysis is conducted (similar to modelling mortality rates) to derive the rate of not choosing to lapse before certain years (refer to *Figure E.1*).

*Figure E.1: Kaplan-Meier Estimator Plot for Policyholder Lapsing Behaviour.*
<img src="Resources/Table E1.png">

***Appendix F: Modelling future sales***

**Data Source**  
The SuperLife Inforce Dataset provided consists of two practical attributes containing information about the number of customers purchasing two specific insurance products, single premium whole life (SPWL) and 20-year level-term (T20). These attributes are the issue year and policy type.

**Data Extraction, Formatting and Visualisation**  
The data for both attributes is extracted, and the number of issued policies in each given year is calculated. Then, this data is split into two tables to illustrate the relationship between the number of customers purchasing specific insurance products and the corresponding year. This visualisation is achieved by plotting a scatterplot for each insurance product (refer to *Figure F.1*).

*Figure F.1: Scatterplots for number of SPWL and T20 customers from 2001 to 2023.*
<img src="Resources/Figure F1.png">

**Model Performance**  
Since a clear linear relationship between the number of customers entering a certain policy and the corresponding year is evident in *Figure F.1* above, thus it is reasonable to assume that the number of policies issued increases linearly per year. Therefore, linear regression modelling technique is chosen to model future sales. Subsequently, linear regression models are fitted to both SPWL and T20, and the results indicate that the number of customers is projected to rise by approximately 1306 per year for SPWL and 779 per year for T20 (refer to *Figure F.2*).

To evaluate the model performance, the adjusted R-squared for each model is obtained. With both models achieving high adjusted R-squared values, 0.9752 and 0.8802 respectively, it can be concluded that both models are performing well.

*Figure F.2: Linear regression models for number of SPWL and T20 customers from 2001 to 2023.*
<img src="Resources/Figure F2.png">

***Appendix G: Pricing formulae***

<img src="Resources/Appendix G.png">

***Appendix H: Online distribution channel***

**Data Source**  
The SuperLife Inforce Dataset provided contains information about the type of distribution channel of policyholders for each age and year.

**Distribution Channel Analysis**  
To study the impact of online distribution channels on the program, the distribution channel information is extracted to perform an analysis. Subsequently, the total number of buyers and the total number of online buyers are determined and the plots are drawn to visualise the performance of online distribution channels in this program (refer to *Figure H.1*). 

*Figure H.1: Plots to analyse the impact of online distribution channel.*
<img src="Resources/Figure H1.png">

**Findings**  
Based on the *Figure H.1*, some potential findings are listed below.
•	Most of the online buyers are middle-aged adults.
•	An emergence of online distribution channels can be observed in the year 2008.
•	The number of buyers has been affected within the early 2020s decade. This may be due to the impact of Covid-19.

### References

Aishwarya, S 2023, Build High Performance Time Series Models using Auto ARIMA in Python and R, Analytics Vidhya, accessed 27 February 2024,
<https://www.analyticsvidhya.com/blog/2018/08/auto-arima-time-series-modeling-python-r/#:~:text=the%20validation%20set-,What%20is%20Auto%20ARIMA%3F,moving%20average%20(MA)%20terms.>

Andersen, PK & Gill, RD 1982, Cox’s Regression Model for Counting Processes: A Large Sample Study, The Annals of Statistics, vol. 10, no. 4, pp. 1100-1120, accessed 1 March 2024,
<https://www.jstor.org/stable/2240714>

British Medical Journal 2020, Every month delayed in cancer treatment can raise risk of death by around 10%, accessed 10 March 2023,
<https://www.bmj.com/company/newsroom/every-month-delayed-in-cancer-treatment-can-raise-risk-of-death-by-around-10/>

Cox, DR 1972, Regression Models and Life-Tables, Journal of the Royal Statistical Society. Series B (Methodological), vol. 34, no. 2, pp. 187-220, accessed 1 March 2024,
<https://www.jstor.org/stable/2985181>

Fei, H 2020, Modelling life tables with advanced ages: An extreme value theory approach, Insurance: Mathematics and Economics, vol. 93, pp. 95-115, accessed 3 March 2024,
<https://doi.org/10.1016/j.insmatheco.2020.04.004>

Regina, S 2021, Solvency Series: The Role of Risk-Based Capital and Required Reserves for Insurance Carries, AgentSync, accessed 5 March 2024,
<https://agentsync.io/blog/insurance-101/solvency-series-the-role-of-risk-based-capital-and-required-reserves-for-insurance-carriers>

Ronald, DL & Lawrence, RC 1992, Modeling and Forecasting U.S. Mortality, Journal of the American Statistical Association, vol. 87, no. 419, pp. 659-671, accessed 2 March 2024,
<https://doi.org/10.1080/01621459.1992.10475265>

World Health Organization 2023, Tobacco, accessed 3 March 2024,
<https://www.who.int/news-room/fact-sheets/detail/tobacco>

Yves, D n.d., How insurance companies can prepare for risk from climate change, Deloitte, accessed 1 March 2024,
<https://www2.deloitte.com/be/en/pages/financial-services/articles/insurance-companies-climate-change-risk.html> 


<p align="center">
  <img src="Resources/Stay%20Healthy.gif" alt="Stay Healthy">
</p>

![](Resources/Actuarial.gif)
