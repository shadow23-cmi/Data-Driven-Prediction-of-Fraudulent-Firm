# Data-Driven-Prediction-of-Fraudulent-Firm
Abstract.

Business organisations doing fraud have direct grievous consequences on economy of a region or countrybased on perspective size.Auditingis defined as practice of examining all the business records of a com­pany to corroborate that their financial statements are in compliance with the standard accounting laws andprinciples. It is very laborious and time consuming task to audit a single company .The number of compa­nies is enormous. So, detecting fraud while necessary might not be feasible and we have to rely on internalaudit of the company(Which a fraudulent company can use in their advantage to lie about their business prac­tices.). Thus many a frauds are undetected to the point where no preventive measures can be taken resultingin bankruptcy,dis­solvency of companies and job loss ,economic output loss.

Introduction:

A firm that has large amount of discrepancy in their planned or unplanned expenditure might be doingfraud. Past record of fraud is also a indicator of doing fraud in future. Prior to in depth analysis of a firmif raw data collected (or revealed by the firm itself)about a firm can indicate fraud then fraud detection andoverall auditing would become much more efficient.Experts in the field use many analytical tool to extract information from features like discrepancy in theirplanned expenditure,misstatements in the past audits. Based on their assessment they assign risk scores foreach feature. And based on these scores they calculate overall risk score(Audit Risk Score).If the Audit RiskScore cross a certain threshold then the firm is considered to be fraudulent.

Problem Statement:

The goal of this paper is to use only the raw data(only the collected data and not the auditors assessmentsbased on the raw data.e.g. The feature ”Discrepancy found in the planned­expenditure in rs” would be usedand not the ”risk score” based on this feature) and past data to determine fraudulent nature of a firm prior toany in depth assessment by any auditor.

This is a classification Problem i.e either a firm is fraud(Risk=1) or not fraud (Risk=0).

Objective:

The objective of this paper is to implement various machine learning algorithms (e.g. Decision Tree,SVM, Logistic Regression etc) to build models that can predict the nature of a firm(i.e. Risk = 0 or 1) giventhe raw data about the firm.
