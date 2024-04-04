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

This program aims to tackle the main objectives by implementing two interventions tailored to non-smoking and smoking policyholders in Lumaria (refer to Appendix A for more details on the invention selection approach).

*Figure 1: Features and design of health incentive program.*
<img src="Resources/Figure 1.png">

***Incentives for Preventive Screenings***  
Late detection of potential health issues or diseases has generally increased the risk of mortality due to more severe health outcomes, limited treatment options, and higher treatment cost. One common example involves the late detection and treatment for cancer diseases. According to the British Medical Journal (2020), the risk of mortality is raised by approximately 10% for each month of delay in cancer treatment. Therefore, the implementation of incentives for preventive screenings in this program aims to encourage policyholders, regardless of smoking status, to undergo preventive health screenings by offering monetary rewards. The list of preventive health screenings are provided in Appendix B. Consequently, policyholders who participate in the listed preventive health screenings will receive monetary rewards annually. With the implementation of this intervention, policyholders are empowered to proactively manage their health and well-being, resulting in a higher quality of life and a reduced risk of mortality.

***Smoking Cessation Programs***  
Smoking, as one of the leading causes of mortality, should be considered to achieve the main objectives of the program. This is evident from the mortality analysis conducted, which highlights smoking as the predominant factor influencing mortality rates in Lumaria (refer to Appendix D for further details). Furthermore, the latest available estimate from the World Health Organization (2023), as of November 2023, suggests that tobacco claims the lives of over 7 million smokers worldwide annually. Therefore, smoking cessation programs are implemented to directly address smoking policyholders by offering resources and ample support, with the goal of reducing smoking frequency or ideally facilitating smoking cessation, and ultimately, reduce the mortality rates. The list of available resources and support for smoking policyholders is provided in Appendix B. By introducing this intervention, smoking policyholders are provided with access to all available resources and support aimed at assisting them in overcoming nicotine addiction, which harms their health and increases their risk of mortality.

### Pricing and Modelling

***Methodologies***  
The methodologies involved to model and forecast specific factors that can significantly impact the performance of the program are stated in Table 1 below.

*Table 1: Methodologies applied to economic factors, mortality rates, policyholder lapsing behaviour and future sales.*

*Note that SPWL represents single premium whole life and T20 represents 20-year level-term.*

***Assumptions***  
During the process of conducting analyses, constructing models, and carrying out calculations, assumptions are considered and implemented to steer the decision-making process as a result of data limitations and insufficient information. The central assumptions considered in the analyses, models and calculations are thoroughly discussed.

The central assumptions considered are as follows.
* After the implementation of the program, policyholders are expected to pay level premiums annually for 20-year term insurance and single-premium for whole-life insurance products.
* All policyholders enter at the start of the year where the policy issued and premiums are received at the start of each year, while all benefit payments are made at end of the corresponding year where the policyholder dies or lapses.
* Lapses can occur only for policyholders with a 20-year term insurance policy and are not possible for those with a whole-life insurance policy.

Central assumptions are also considered when implementing each intervention under the health incentive program. These central assumptions are listed in the Table 2 below.

*Table 2: Central assumptions for the health incentive program.*





<p align="center">
  <img src="Resources/Stay%20Healthy.gif" alt="Stay Healthy">
</p>

![](Resources/Actuarial.gif)
