--- 
layout: page 
title: Attrition 
description: EDA on Attrition at Frito Lay 
img: assets/img/shutterstock_1696263217_edited.webp 
importance: 1 category: work
related_publications: true 
---

Attrition
Jacqueline Q. Vu
10/18/2025

Executive Summary of the EDA on Attrition at Frito Lay

Goals
Frito Lay wants DDSAnalytics to build models to predict attrition,
measure the cost impact of utilizing these models, and perform an
exploratory data analysis to identify the top three factors that lead to
attrition.

Which classification model was better at predicting attrition?
DDSAnalytics has performed two classification models to predict
attrition: 1. Naïve Bayes classification model and 2. KNN Classification
model. The Naïve Bayes classification model perform with an accuracy
rate of 80.08%, a sensitivity rate of 83.94%, and a specificity rate of
60.47%, and the KNN classification model perform with an accuracy rate
of 74.71%, a sensitivity rate of 81.65%, and a specificity rate of
39.53%. Since the Naïve Bayes classification model has a higher accuracy
rate, sensitivity rate, and specificity rate than the KNN classification
model, DDSAnalytics has concluded that the Naïve Bayes classification
model is the better model of the two.

Top 3 Factors that Lead to Attrition
1.  whether the employee works overtime or not,
2.  the age of the employee, and
3.  how frequently the employee goes on business trips

Financial Impact
Since costs Frito Lay between 50% and 400% of an employee's salary to
recruit a replacement for an employee who has left, using the Naïve
Bayes classification model would be a financially better option in the
long run compared to the KNN classification model. The Naïve Bayes
classification model predicted that 17 employees stayed at Frito Lay
when they actually left (false positive) compared to the 26 employees
that were predicted by the KNN classification model. This indicates that
it will cost less for Frito Lay to replace their employees when
utilizing the Naïve Bayes model (between \$644,367.66 and
\$5,154,941.28) compared to the KNN classification model (between
\$985,503.48 and \$7,884,027.84).

Similarity in Trends
When comparing the attrition among different age groups and the overtime
status among different age groups via grouped bar charts, both of them
display that employees who are in their 20s and 30s are more likely to
leave Frito Lay compared to the other age groups. Seeing that, Frito Lay
must be mindful on how much work it is placing on their employees
because more work leads to more of them working overtime, meaning they
will have a higher chance of burnout, and therefore contribute to more
attrition for Frito Lay.