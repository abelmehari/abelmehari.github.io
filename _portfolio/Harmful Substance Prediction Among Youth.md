---
title: "Portfolio Optimization -Modern Portfolio Theory"
excerpt: "Alcohol consumption among youth is a significant public health concern with potentially harmful consequences for both individuals and society. In this study, we aim to predict alcohol consumption among youth using data from the National Survey on Drug Use and Health (NSDUH). The NSDUH is an annual survey that collects data on substance use and related behaviors among individuals aged 12 years and older in the United States. Our attention is directed towards various factors such as religious convictions, the dynamic between parents and their children, academic performance, and engagement in groups aimed at improving self-esteem and problem-solving abilities. By analyzing these factors, we hope to identify potential risk and protective factors that could inform prevention and intervention efforts to reduce alcohol consumption among youth.<br/>"
reading_order: 2
---


- [Github Code Repository](https://github.com/akankshasharmadid/Harmful-Substance-Prediction-Among-Youth)


**Predicting Use of Harmful Substances Based on Parental Involvement, Religious Beliefs, and Education**

**Abstract:**

It is fair to assume that the parental involvement, education, and religion beliefs affect the outcome on how child will perceive the use of harmful substance later in their life. This research, based on the National Survey on Drug Use and Health (NSDUH), aims to predict alcohol consumption among youth using behavioral factors and variables such as religious beliefs, parent-child relationship, academic factors, and participation in self-esteem and problem-solving groups were analyzed. The study highlights the importance of family and community support in reducing harmful behaviors among youth. Decision tree models were employed in this study to anticipate the behavior of young people in terms of consuming alcohol later in life. Additionally, the research expands to predicting the age at which young people will have their first encounter with alcohol.

**Introduction:**

Our University Endowment Fund employs portfolio theory to determine the optimal portfolio. We have constructed a well-diversified portfolio consisting of 13 different asset classes to maximize the reward-to-risk ratio. These asset classes include US large-cap stocks, US small-cap stocks, developed market equities, emerging market equities, commodities, US real estate, T-bills, US Treasury bonds, US investment-grade corporate bonds, US high-yield bonds, global high-yield bonds, global high-yield corporate bonds, and global treasury bonds. The portfolio analysis process begins by assessing the risk and return relationship. To estimate future rates of return and determine appropriate levels of risk, we have utilized 20 years of historical data for all 13 asset classes. While our analysis assumes a normal distribution of data, we have also considered any deviations from normality by examining the skewness and kurtosis of the data to account for potential asymmetry and the probability of extreme returns. Modern Portfolio Theory, based on the principle of diversification, guides our approach. Developed by Harry Markowitz, the theory emphasizes the importance of not putting all our eggs in one basket. We seek to efficiently diversify our portfolio by identifying the efficient set of portfolios. By employing Markowitz's theory, we can determine the highest level of return for a given level of risk. We have conducted various analyses using 23 different models, incorporating factors such as changes in interest rates, investment constraints, and different target returns. Additionally, we have explored the applicability of optimal weights from previous periods to assess their relevance for the future. By employing this comprehensive approach, our University Endowment Fund strives to construct an optimal portfolio that balances risk and reward while maximizing returns for our stakeholders.
**Naïve Diversification VS Efficient diversification**

An equal-weighted portfolio increases the risks of securities stocks in the investment portfolio of an investor. Risk in such a portfolio cannot be eliminated easily because diversification is not possible. The value of an investment portfolio may decline over a given time period simply because of economic changes or other events (change in tax reforms, change in the world energy situation, etc.) that impact large portions of the market.
The Optimal Portfolio (OPA), which is constructed based on the mean-variance optimization technique, aims to achieve the highest possible return for a given level of risk. In our case, the OPA had a risk of 3.117% and a return of 0.689%. This means that the OPA was able to generate a relatively higher return for the level of risk taken. As we can see from Figure 1 the OPA is able 
to generate a higher return by investing 20% of our assets in Real estate and 80% of our assets in US high-yield bonds. 
On the other hand, the EQA, which involves allocating equal weights to all assets in the portfolio, had a lower risk of 2.693% but also a lower return of 0.473%. The equal-weighted approach assumes that all assets in the portfolio have an equal contribution to the overall performance. The difference in performance between the EQA and OPA can be attributed to several factors. One 
factor is that the assets in the portfolio had varying levels of risk and return, which were not considered in the equal-weighted approach. By assigning equal weights to all assets, the EQA have been overexposed to lower-performing assets and underexposed to higher-performing assets, resulting in a lower overall return. Furthermore, the OPA takes into account the correlation between assets, allowing for diversification benefits. This means that the OPA is able to construct a portfolio that minimizes risk by selecting assets that have a lower correlation with each other. The EQA, on the other hand, does not consider correlations and may not have achieved the same level of diversification.

**Difference between Sub-Periods**  
During sub-period 1, the portfolio had a greater emphasis on US Real Estate (20.1252%) and US High-Yield Corporate Bonds (79.8748%). This allocation indicates that the real estate market may have experienced advantageous conditions, including factors like low interest rates, heightened demand, or optimistic performance expectations. Investors likely expected superior returns from US Real Estate in comparison to alternative asset classes. One of the interesting economic events during this period was the 2008 financial crisis which had a significant effect on the US market. In sub-period 2, the portfolio weights demonstrate a complete shift from US Real Estate and US High-Yield Corporate Bonds. The entire allocation is focused solely on US Large Cap Equities (100%). This indicates that during sub-period 2, the prevailing economic environment and market 
conditions were favorable for Large-Cap US Equities, making them the most attractive investment choice. Several factors could have contributed to the shift toward US Large Cap Equities in sub-period 2. During that time, the stock market experienced a bullish trend, demonstrating robust performance. The allocation might also reflect the expectation of greater returns from US Large Cap Equities compared to other asset classes, driven by factors like encouraging economic indicators. 

**Difference Between Risk-Free Rates**
A downward change in the risk-free rate would have a positive effect on portfolio performance. As the risk-free rate decreases it becomes easier for companies to be able to borrow money at a better rate. This is shown in our portfolio performance when we adjust the risk-free rate. If we look at our OPA4 portfolio we can see that with a 4% risk-free rate we have a monthly return of .6889% and an RTV ratio of .114, when we reduce the risk-free rate to 3% in OPA3 we get a return of .6533% and an RTV ratio of .142, when we reduce the risk-free rate further to 2% in OPA2 we get a return of .4589% and an RTV ratio of .183. These scenarios all show a slight decrease in the expected return because of the decline in risk-free rate but the risk-adjusted performance is actually better because when the portfolio return has the risk-free rate subtracted the risk-free rate is smaller.  
Figure 2
**Adding Investment Limits and Target Return**  
Adding investment limits to our portfolio or adding a 9% return target will cause some detrimental effects on our portfolio. Starting with the investment limits when we compare our limited portfolio in COPA to our original OPA4 portfolio we see a 9.1% increase in required return but a 14.9% decrease in RTV. This is due to the increase in risk from adding the investment limits. When we look at the combined investment limit and target required return portfolio COPA9 there is a 9.1% decrease in return and a 14.9% decrease in RTV. These results indicate that although we may see some increased return when adding these investment limits this is at the cost of significantly increased risk and decrease in RTV ratio. Based on these results I would not recommend adding these investment limitations without specific reasons for a required return amount or asset allocation limitations.
![Figure 1: Number of non-null values for each column out of 5500 records.](/images/Fig1Harmful.png)



To accurately predict alcohol consumption, we employed decision tree models for classification tasks using a range of demographic and behavioral factors such as age, gender, race, education level, and family income as predictors. To evaluate the performance, we utilized cross-validation techniques. Later, we extended our model to multiclass classification to identify the usage of alcohol, marijuana, or tobacco. The multiclass classification model combined the flags for alcohol, tobacco, and marijuana use to create a single variable called substance use flag, which allowed us to analyze their impact on substance use habits.

To broaden the scope of our research, we aimed to predict whether an individual will consume alcohol and the age at which they will begin doing so. To achieve this objective, we developed a regression model. Initially, we examined the data to identify any outliers, and we found that some individuals reported consuming alcohol before the age of 7, which is highly improbable. We resolved this issue by replacing such values with 7 as the age indicator when a person first tried drinking alcohol. Furthermore, we examined the distribution of the age at which youth reported their first alcohol consumption, which is presented in Figure 2. We observed that many teenagers tend to take their first sip at the age of 15, and there is a significant number of individuals who have not yet consumed alcohol. To test whether our regression model can accurately forecast this behavior, we will evaluate its performance. In summary, our methodology involves identifying outliers and addressing them, analyzing the distribution of age at which youth consume alcohol, testing our regression model's accuracy, and evaluating its performance.

![Figure 2: Frequency at what age people try their first drink](/images/Figure2Harmful.png)



By using this methodology, we were able to accurately predict alcohol usage among youth and gain insights into the role of demographic and behavioral factors in predicting substance use. Our research findings have important implications for the development of interventions and policies aimed at preventing youth substance use.

Bottom of Form

**Computational Results:**

In a binary classification problem where the task was to predict whether youth would consume alcohol or not, the dataset was found to be imbalanced, with 4138 out of 5550 adult datapoints not consuming alcohol. To address this, we used stratified sampling and considered class imbalance while training various decision tree and ensemble models. Upon training the decision tree model, we discovered that the accuracy of the binary classification was highly dependent on the youth's feelings about attending school, emphasizing the importance of education in predicting alcohol consumption. Moreover, we observed that parental communication about substance use, and the child's accomplishments also had an impact on the decision. Interestingly, the number of school days missed had a relatively lesser impact on the prediction compared to other variables in the dataset. Figure 1 highlights the crucial features for predicting whether a person will consume alcohol or not.

![Figure 3: Importance of features in classifying whether a person will consume alcohol or not.](/images/Figure3Harmful.png)


We got the same accuracy with pruned tree as a normal decision tree with just one single node. It's worth noting that we achieved a 75.2% accuracy on the test results when predicting whether a person will drink or not. Additionally, it's intriguing to observe that we're encountering the same level of error as the unpruned tree.


| Image 1 | Image 2 |
| ------- | ------- |
| ![Figure 4.a: Pruned tree with accuracy 75.2](/images/Figure4.a.png) | ![Figure 4.b: Cross-Validation accuracy VS tree size](/images/Figure4.b.png)|



 

Multiclass classification: In the context of multiclass classification, our goal is to determine whether a person will use any form of substance. To achieve this, we have categorized the output into four distinct classes, as previously mentioned.

| **Multi-class Classification** |
| --- |
| **Substance Use** | **Output Value** |
| Alcohol | 1 |
| --- | --- |
| Marijuana | 2 |
| Tobacco | 3 |
| No Substance Use | 0 |

_Table 1: Multiclass classification output_

After attempting several methods, we discovered that the bagging model was the most effective for this dataset. However, if we had additional information about youth behavior, we could further enhance the accuracy of the model. This can be observed in the confusion matrix, which illustrates the model's performance. It is worth noting that the model performs well in predicting instances where there is no substance use. The model is currently achieving an accuracy rate of 65%.

![Figure 5: Confustion Matrix: Random Forest Classifier](/images/Figure5.png)



Regression model: In the context of a regression problem, we were trying to predict the age at which young people will try alcohol for the first time. To accomplish this, we used various models to predict the output. One of the methods we used was pruned decision tree to do regression analysis, which allowed us to predict the age of the first drink with an accuracy of approximately 96.84%, considering the limitations of the data we had.

During our analysis, we found that the "alcohol use" flag in the pruned tree was a significant predictor of the age at which a person started drinking. This means that whether a person has used alcohol or not can have a significant impact on the age at which they try it for the first time. Additionally, we found that the occurrence of serious fights at school or work was the second most important predictor for determining the age of first drink. This suggests that such incidents can have a significant impact on a person's behavior and mental health, potentially leading to long-term health concerns like depression.

![Figure 6: Regression Decision Tree](/images/Figure6.png)


To visualize our findings, we created a decision tree, which is a tool used to predict outcomes based on different conditions. The tree starts with a condition about whether or not a person has used alcohol. If they have used it very little or not at all, the tree goes to the left and predicts a certain outcome. If they have used alcohol more than a little, the tree goes to the right and looks at whether or not they have been involved in a serious fight at school or work. Based on the different conditions, the tree predicts different outcomes, represented by numerical values.

Our findings were based on data from a sample of 2750 people, and the accuracy of the predictions varied depending on the conditions that applied to each group of people. Overall, our analysis sheds light on important factors that can impact the age at which young people try alcohol for the first time and highlights the importance of considering these factors in prevention and intervention strategies.

![Figure 7: Predicted age value VS Actual Age value](/images/Figure7.png)



Looking at the pruned decision tree output model graph, we can observe that the predicted values are generally close to the actual values, indicating that our regression model performed well in predicting the age at which a person will try alcohol for the first time, given the limitations of the data.

**Discussion:**

It is worth noting that the NSDUH dataset includes a vast array of data that can be used to answer many more questions related to substance use and other topics. Our study's specific focus on religious beliefs and school behavior was just one aspect of the available data. Nonetheless, our findings provide valuable insights into the potential risk and protective factors that can inform prevention and intervention efforts aimed at reducing substance use among youth. Our findings indicate that these factors significantly influence a person's likelihood of consuming substances later in life. Therefore, it is essential to engage students in fostering positive relationships with the people in their lives, including parents and teachers, to reduce the risk of harmful behaviors.

The study aimed to predict alcohol consumption among youth using various behavioral factors and to identify potential risk and protective factors for informing prevention and intervention efforts. The findings showed that parental communication about substance use, academic accomplishments, and the child's feelings about attending school were highly influential in predicting whether a person would consume alcohol or not. The decision tree model achieved an accuracy of 75.2% on test results, indicating its effectiveness in predicting alcohol consumption. Furthermore, the model's accuracy was not compromised by pruning.

Regarding multiclass classification, the study aimed to determine whether a person would use any form of substance, including alcohol, tobacco, and marijuana. The analysis revealed that parental communication, academic performance, and participation in self-esteem and problem-solving groups were significant predictors of substance use.

However, the study had limitations such as the cross-sectional nature of the data, which limits the ability to infer causality, and self-reported data on substance use subject to social desirability bias, which could impact the accuracy of predictions. Additionally, the dataset's sample size was relatively small, which may limit the generalizability of findings to the larger population.

In conclusion, the study provides valuable insights into potential risk and protective factors for reducing alcohol consumption among youth. The findings underscore the need for targeted interventions aimed at reducing substance use among youth and highlight the importance of education and family support in reducing harmful behaviors.

**Conclusions:**

Our study aimed to predict alcohol consumption using decision tree models and tree-based ensemble models such as Random Forest, Bagging, and Boosting. We utilized data from the NSDUH survey and found that the models were able to achieve impressive accuracies. For the binary classification problem, the decision tree after pruning yielded an accuracy of 75.09%. Furthermore, the Pruned Decision Tree model demonstrated an accuracy of 96%, using less than half the number of predictors.

These findings suggest that decision tree models and ensemble methods are effective tools for predicting if an individual will consume alcohol or not. They can also be utilized to determine the age at which a person is likely to try their first drink or whether a young person will try alcohol. The models' performance is encouraging and highlights their potential in aiding early intervention strategies to prevent alcohol misuse.

Overall, our study contributes to the existing body of literature on the use of decision tree models and ensemble methods in predicting alcohol consumption. These tools offer a promising approach for identifying individuals who are at risk of alcohol misuse and providing appropriate interventions.

**References:**

Substance Abuse and Mental Health Services Administration. (2020). National Survey on Drug Use and Health (NSDUH) 2020. [Codebook]. Retrieved from [https://www.datafiles.samhsa.gov/sites/default/files/field-uploads-protected/studies/NSDUH-2020/NSDUH-2020-datasets/NSDUH-2020-DS0001/NSDUH-2020-DS0001-info/NSDUH-2020-DS0001-info-codebook.pdf](https://www.datafiles.samhsa.gov/sites/default/files/field-uploads-protected/studies/NSDUH-2020/NSDUH-2020-datasets/NSDUH-2020-DS0001/NSDUH-2020-DS0001-info/NSDUH-2020-DS0001-info-codebook.pdf)
