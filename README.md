# Cooktops Analysis Based on Survey
# Abstract

Our project is to identify people's preferences for different types of stoves --Gas, Electric and Induction. The motivation behind this study is the US Government's proposed shift to transition from gas to electric/induction stoves for safety and environmental reasons.

Our preliminary research about [Cooktop types](https://docs.google.com/spreadsheets/d/1t7P-EwncM1di8XoGIacFEEggvDJcXtPfUdSaPnEAlM4/edit?usp=sharing) helped us determine the features people are interested in while purchasing cooking stoves: Type, Final Cost, Number of Burners, Average Annual Usage Cost and Indoor Air Quality. Using these attributes, we are designing a survey and will be performing a Conjoint analysis of the results to better understand user preferences. The eventual goal is to be able to provide insights to policymakers for refining existing policies and facilitating a smooth shift from gas to electricity. Some of the insights we have gained from our pilot analysis were including both gender and Age in the preliminary questions would help us better understand our audience and that our exclusion criteria in the survey design should only be for underage individuals as we have limited resources for conducting surveys. The exclusion criteria of residence in the DMV region and Home Ownership should ideally be moved upstream to the respondents' selection platform ie. MTurk

# Introduction

Cooking is an essential part of daily life, and the cooktop individuals choose can significantly impact their culinary experience. Whether an individual is a professional chef or simply enjoys preparing meals at home, their preferences for cooktop types can vary widely. On the other hand, the shift from traditional gas stoves to induction or electric stoves has been a rising debate among climate advocates who have been proposing a reduction of fossil fuel usage. Considering all these factors, the US government brought in a law [(Inflation Reduction Act 2022)](https://www.democrats.senate.gov/imo/media/doc/inflation_reduction_act_of_2022.pdf) which amongst many other considerations is subsidies to homeowners who switch from gas to Electric/Induction Stoves.

The motivation behind our study is the proposed shift from gas to electric/Induction and the practical challenges that will come during its implementation. There is a genuine individual safety concern with gas cooktops and their adverse effects on the environment, on the other hand, the concerns of the people who are being asked to switch are equally valid. The cost differential, reliability, and efficacy while preparing certain cuisines are just some of the primary concerns that come up when considering a transition from gas to electric/induction.

### Type of Cooktops:

-   Gas Cooktop - Gas Cooktops work on natural gas which is ignited and the flame itself is the source of heat. It was patented by James Sharp in England in 1826 and has been an integral part of most households since the 1920's.

-   Electric Cooktop - Electric cooktops have an electrical current that flows through a metal coil underneath the glass or ceramic surface. The coil becomes hot and starts glowing due to the electrical resistance. It will transfer its heat through the glass using infrared energy. It was patented in 1896 by William Hadaway.

-   Induction Cooktop - Induction cooktops generate heat by combining electricity and the magnetic properties found in most pots and pans. Induction Cooktops were first released to the public at the Chicago "Century of Progress" World's Fair in 1933.

[Induction Video](https://www.youtube.com/watch?v=wu1Rcfonxps)


### Product Attributes and Decision Variables

We have limited our study to easily quantifiable attributes like Type of stove, Final Cost, Number of Burners, Average Annual Usage Cost, and Indoor Air Quality to understand user preferences as these are readily available and widely understandable. Reliability of technology and Cooking Efficacy are factors that are beyond the users' control and that is why we have not considered those.

| Attributes                | Type       | Value / Range                   |
|---------------------------|------------|---------------------------------|
| Cooktop Type              | Discrete   | Gas, Electric, Induction        |
| Final Cost Price          | Continuous | 500, 700, 900, 1100, 1300, 1500 |
| Average Annual Usage Cost | Continuous | 50, 60, 70, 80, 90, 100         |
| Number of Burners         | Discrete   | 3, 4, 5                         |

# Survey Design

### Eligibility

Our eligibility criteria was Homeowners in US. We chose homeowners because Cooktops are bought by Homeowners and we wanted to gauge the preferences of the people. We had earlier thought about restricting ouselves to the DMV region but we could not find enough survey participants so we expanded our criteria. This was in addition to the necessary requirement of being over 18 and providing consent for the survey.

### Respondent information

Along with the eligibility question, we were interested in obtaining information of people owning their household and how often they are cooking at home. We asked about the respondents' Year of Birth, their place of residence, and their frequency of cooking. We also collected information about gender, salary range and if they have a gas connection in their homes.

### Attributes and levels for Conjoint Quesitons:

Our conjoint questionnaire consisted of 8 questions after filtering out people from eligibility questions. Each question consists of 3 choices with each type of cooktop, final cost price, average annual usage cost and number of burners. After asking their preference questions, we asked for the heating efficiency and concerns of emissions from each respondent.

### Educational material presented to the respondents.

-   Cooktop type: Type of cooktop you prefer between gas, electric and induction.
-   Final cost price: Total price to buy and setup the stove to get it running including taxes
-   Average annual usage cost: Average price/yr to maintain the stove, like the price paid to gas or electricity
-   Indoor air quality: Quality of the air in a home, school, office, or other building environment
-   Number of burners in the cooktop: 3, 4, 5
-   Emissions: Average amount of carbon emissions your stove will emit in a year
-   Heating efficiency: This is time taken by the stove to reach cooking temperatures. Induction stoves take the shortest time to reach cooking temperature followed by electric and gas stoves.
-   Induction cookware: Induction compatible cookware are required while using Induction stoves. You can tell if your cookware is suitable for induction cooking if it has a coil symbol on the base, or if a magnet clings firmly to the cookware's underside. If you test a cookware and the magnet only sticks loosely to the base, you may find the cookware does not heat as effectively.

### Example figure of a random Conjoint Question

![Sample Question](https://raw.githubusercontent.com/tejasphirke/Cooktops/main/Final_images/sample_conjoint_question_image.JPG)

# Data Analysis

## Sample Description

We had 210 respondents for our survey who completed all the choice questions after filtering for consent and eligibility criteria. After that, we filtered out people who did not spend a reasonable time on the survey (those who went too fast), and we were left with 189 respondents. We further analyzed our respondents based on their demographics like age bracket, income range, and gender.

| Demographic Variable | Response Options                                                                                                                                      |
|---------------------------|---------------------------------------------|
| Gender               | Male, Female, Trans male/trans man, Trans female/trans woman Gender queer/gender non-conforming, prefer not to say                                    |
| Education Level      | Less than High school, High School, Bachelor Degree, Masters Degree, Vocational, Associate Degree, Prefer not to say                                  |
| Income               | Less than \$10,000, \$10,000-\$20,000, \$50,001-\$100,000, \$100,001 or more, prefer not to say                                                       |
| Ethnicity            | Asian, African American or Black, White, Hispanic or Latino, American Indian or Alaska Native, Native Hawaiian or Pacific Islander, Prefer not to say |

# Final Recommendations and Conclusions

- The change in utlity or increase in willingness to pay from 3 burner to 4 burner is much higher than 4 burner to 5 burner so companies should focus more on 4 burner stoves.
- There is a high willingness to pay for Induction Stoves compared to Gas stoves which indicates that consumers understand the benefits of Induction stove.
- The average price difference between induction and gas stove is still pretty high and the higher WTP does not cover it so a decrease in price or subsidy of Induction stoves will be required to increase the market share of Induction stoves to over 50%.

# Limitations

-   If the sample size would have been larger than currently available data, analysis would have made much more sense with respect to decision making. The Power analysis we conducted showed us that we needed roughly 450 participants to validate our findings.
-   Having region specific knowledge with respect to utilities and policies would have helped us tailor our survey in a much more granular level which will address the main problem.
-   Having stringent guidelines on the target population of the survey respondents would have been better to receive more authentic data to analyze, for example taking the survey to people in person rather than doing it online.
