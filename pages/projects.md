---
layout: page
title: Projects
description: Student's Presentations in Data Analytics
---
<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
        	<li><a href="#ml"><u>Machine Learning</u></a></li>
            <li><a href="#statistical"><u>Statistical Modeling: PCA & Regression</u></a></li>
            <li><a href="#Capstone"><u>Capstone: Predicting Failure to Appear DC Superior Court</u></a></li>
            <li><a href="#fm"><u>Financial Modelling </u></a></li>
            <!--<<li><a href="#MTurk"><u>Crowd Sourcing Project: Used Car Prices</u></a></li>
            <li><a href="#master"><u>Master's Project</u></a></li>
            <li><a href="#R"><u>R Project</u></a></li>
            <li><a href="#Bank-Campaign"><u>Bank Campaign Prediction</u></a></li>
            <li><a href="#capitalbikeshare"><u>Business Intelligence</u></a></li>
            <li><a href="#kingcounty"><u>Price Prediction</u></a></li> 
        -->
        </ul>
    </div>
</div>
---



---

### <a name="ml"></a>Machine Learning

#### <a name="fta"></a>DC Mayor's Office: Predicting Failure to Appear in Court Cases: DC Superior Court , 2019.08-2019.12
<br/>&nbsp; &nbsp; &nbsp; 
Charges of failure to appear (FTA) are common across both court and arrest records. FTA was the top felony arrest charge from FY 2015 and FY 2017, making up nearly 20% of felony arrests, and was the fifth most common offense in court records between 2010 and 2016. While there might be a multiplicity of reasons for an FTA, Focus groups and interviews with Public Defender Services (PDS) and Pretrial Services (PSA) staff suggest that lack of transportation is a significant factor in failures to appear. Some defendants may be indigent or may prioritize other needs like food or rent above transportation.  Anecdotally, some defendants already receive metro cards from their attorney with a positive effect on their appearance by their attorneys. Given that transportation is reported as a barrier to court appearances, our objective is to develop machine learning models to predict the likelihood of the appearance of a defendant using data that is available at the outset of a case. This will allow for greater precision through a stratified random controlled trial in assessing the treatment effects associated with receiving a free MetroCard at the time of their release.
NB: Due to a signed Non-disclosure agreement API codes and data, cannot be publicly shared
<br/>&nbsp; &nbsp; &nbsp;[Download the Presentation![Excel](icons16/ppt-icon.png)]({{ BASE_PATH }}/assets/FTA.pptx)&nbsp; &nbsp; &nbsp;[Download Project Report![pdf](icons16/pdf-icon.png)]({{ BASE_PATH }}/assets/FTA.pdf)
[Download Some Code Files![zip](icons16/pdf-icon.png)]({{ BASE_PATH }}/assets/FTA_nda_compliant_files.zip)
<br/>

#### <a name="opioids"></a>Detecting Opioid-Related Risk Factors in Cincinnati, Ohio and Tempe, Arizona, 2019.08-2019.12
<br/>&nbsp; &nbsp; &nbsp; This paper presents an analysis plan, complete with pilot results, for a relational study of demographic and geographic covariates and their association with opioid-related EMS calls.  Building on prior literature, the paper successfully replicates the findings of a Poisson model testing for these relationships in Cincinnati Ohio. Additionally, it extends this method to Tempe, Arizona and introduces a similarly specified logistic regression model for both cities of interest. In general, we find that results do not extrapolate well between cities. Hence, further research is needed to identify generalizable opioid-related risk factors at the community level. 
<br/>&nbsp; &nbsp; &nbsp;[Download the Presentation![PPT](icons16/ppt-icon.png)]({{ BASE_PATH }}/assets/Opioids.pptx)&nbsp; &nbsp; &nbsp;[Download the Report![pdf](icons16/pdf-icon.png)]({{ BASE_PATH }}/assets/Opioids.pdf)

<br/>
#### <a name="aircraft"></a>Aircraft Predictive Maintenance , 2018.08-2018.12
<br/>&nbsp; &nbsp; &nbsp; 
Coming in after Pilot error, aircraft systems failure is one of the most common reasons for accidents. Catastrophic equipment failures still account for around 20% of aircraft losses despite the improvements in design and manufacturing quality. It is a fact nowadays that aircraft generate more data than ever. In this project, we will implement Logistic regression,
Principle Component Analysis (PCA) and K-Means
clustering on the dataset that contains Remaining Useful Life engine data and service statuses in order to determine whether an engine unit need to go through major servicing or not.
<br/>&nbsp; &nbsp; &nbsp;[Download the Report![pdf](icons16/pdf-icon.png)]({{ BASE_PATH }}/assets/PredictiveMaintenance.pdf)&nbsp; &nbsp; &nbsp;[Download the Jupyter Notebook![jupyter](icons16/jupyter-icon.png)]({{ BASE_PATH }}/assets/PredictiveMaintenance.ipynb)

<br/>

### <a name="fm"></a>Financial Modelling
#### <a name="finmodel"></a>Hedging Options with Futures - OOP Code Implementation , 2019.08-2019.12
<br/>&nbsp; &nbsp; &nbsp; 

<br/>&nbsp; &nbsp; &nbsp;
[Download the Jupyter Notebook![jupyter](icons16/jupyter-icon.png)]({{ BASE_PATH }}/assets/PredictiveMaintenance.ipynb)
<br/>

### <a name="statistical"></a>Statistical Modeling
#### <a name="peas"></a>Principal Component Analysis, 2018.08-2018.12
<br/>&nbsp; &nbsp; &nbsp; The spreadsheet "JudgeResultsPeas"
contains average response results on 17
attributes of 60 pea variations. Write a
detailed analysis report as if you are
conducting the analysis for a client and
detail your analysis steps for this client.
Analyze the pea attribute data using
principal components.

Decide on the number of principal components to retain and why, and interprete
the components. Decide if an increasing value of a pea attribute means "a pea" is
judged better or worse in terms of that attribute and next design a "pea metric"
using your pea attribute analysis, fit an appropriate theoretical distribution to the
score results of your "pea metric" and select using your fitted distribution the top
ten percent of peas that outperform the others.
<br/>&nbsp; &nbsp; &nbsp;[Download the Excel![Excel](icons16/ms-excel.png)]({{ BASE_PATH }}/assets/PeaQuality.xlsx)&nbsp; &nbsp; &nbsp;[Download the Report![pdf](icons16/pdf-icon.png)]({{ BASE_PATH }}/assets/PEAQualityAnalysis_PCA.pdf)

<br/>

<!--
Scree Plot and Loading Plot from MiniTab.
&nbsp; &nbsp; &nbsp; <br/><img src="Scree.png" alt="R/A1" style="width:400px;height:300px;">
&nbsp; &nbsp; &nbsp; <br/><img src="loading.png" alt="R/A1" style="width:400px;height:300px;"><br/>
-->

#### <a name="regression"></a>Regression, 2018.08-2018.12
<br/>&nbsp; &nbsp; &nbsp;
The Loan Startup Incorporated (LSI) provides crowdsourced loans to qualified individuals through an online portal. The objective of this research is to analyze LSI’s customer loan application data and create an enhanced and competitive Credit Score Metric that would improve customer satisfaction, increase profitability and present opportunities to expand into related markets using Linear Regression. . Be wary though, the data is non-Gaussian, find a way to reduce the non-normality in the data using some clever data transformations if possible. Otherwise you might want to find a subset that is more "normal". Be creative!
<br/>&nbsp; &nbsp; &nbsp;[Download the Report![pdf](icons16/pdf-icon.png)]({{ BASE_PATH }}/assets/FACO.pdf)

<br/>