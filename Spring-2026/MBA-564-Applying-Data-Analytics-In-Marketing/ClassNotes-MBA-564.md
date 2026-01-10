# ONSJHJSA
------------

## Module 1: Causal Analysis

#### Causal Analysis Explained Simply
- Causal analysis is a set of techniques that help marketers figure out why things happen, not just that they happen together. For example, if you notice that people who use your mobile app also spend more money, causal analysis helps you determine whether the app actually caused them to spend more, or if big spenders were just more likely to download the app in the first place.

- Causality means that one thing (A) directly causes another thing (B) to happen—changing A will change B. This is different from correlation, where two things just happen to move together without one causing the other (like ice cream sales and drowning deaths both rising in summer—ice cream doesn't cause drowning; hot weather affects both).
- The module teaches you that to prove causality, you need three things: (1) the cause must happen before the effect, (2) the cause and effect must be related, and (3) you must rule out other explanations. Since running perfect experiments (like randomly assigning customers to use an app or not) isn't always possible, marketers use clever workarounds like "difference-in-differences" (comparing changes over time between groups) or "matching" (finding similar people to compare).
- The big challenge is selection bias—when the people who choose to do something (like download an app) are already different from those who don't, making it hard to know if the app itself had any effect. Understanding these concepts helps marketers make smarter decisions about what actually drives results, rather than wasting money on things that only appear to work.

##### Key Takeaways from Causality: 
- The fundamental Problem: We can never know the treated or untrated outcome for the sanme person. Example, if the person dowanloaded the app and then its spending increase. In this case, we will never know the spending pattern of the same person if he/she might have not downloaded the app. 

- Selection Bias: App users may differ from non-app user. Thus comparing their bias towards the spending might be difficult. 

- Fair Comparison : To identify the cause and effect of app on person's spending requires the apple-to-apple comparison and the other factors should remains the same. 

- Randomization: Comparing the treated and untreated groups without randomization leads to biased estimates due to *Selection Bias* . Large samples do not eliminate the selection bias. Randomization eliminates the Selection Bias. But Randomization is not feasible in real-world. 

##### Causal Analysis - Identifying Quasi-experiments

- Quasi experiments: Quasi-experiments is type of randomization which is based on exogenous variations. Exogenous variation is the change that occurs outside the control of the individual or group involved. For example, if persons wage increased in one state but remains the same in another then this case is exogenous variation and it can be used to find cause-effect analysis of wages on spending. Because here the randomization apply to sample and it should be unrelated to the cha racteristics of individual being treated. 

- The best way to analyze this is by using Difference-in-Difference method: This methopd compares the changes in outcome before and after the treatement for the treated and control groups. (This method mostly used in medical fields in which we use Diff-in-Diff method to identify the outcome of the vaccine/medicine after giving vaccine to certain group which is called Treated group and placebo to other group which is called control group. Then we decide the effect of vaccine on people.)

##### Causal Analysis - Matching methods

- Propensity score matching : Identify the group with the same characteristics to better compare apple-to-apple comparison. Like to identify the effect of vaccine on two groups of people, we can put same type of people on both the groups - Treatement group and Control Group (Placebo group)

- Synthetic control group: Group the people based on their regions OR work on same company compare with others large group of people from other company Or region. For example, a company runs the advestisement on a certain city and not the other cities. Then find the cause-effect of this advertisement on sales by comparing sales in the city wherem they run advertisement and sales in other city without advertisement. 

##### Causal Analysis - Instrumental Variables: 

