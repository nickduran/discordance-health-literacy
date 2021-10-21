# Precision Communication: Physicians’ Linguistic Adaptation to Patients’ Health Literacy 
D Schillinger, N Duran (joint first authors), S Crossley, R Balyan, DS McNamara, AJ Karter. Science Advances.

## What does this respository and README include?

> - R source code (.Rmd files) that provides a step-by-step tutorial of all statistical procedures 
>   - HTML output of executed R source code that reproduces results reported in manuscript   
> - Explanation of restricted data availability; intructions for how to access data to run .Rmd files 
> - Variable descriptions used in source code to generate analysis

## R source code (.Rmd)

Each file contains the sequence of steps in R to generate the results, tables, and figures as reported in the manuscript. Detailed notes and annotations are included. Complete replication possible assuming access to the available source data files (see below for details). 

> **Relevant Files:**
> - **scienceAdvancesDemographic.Rmd**
>   - Code for "Table 1. Characteristics of patients in overall sample"  
> - **scienceAdvancesModels1.Rmd**
>   - Code for subhead section: "Grouping by dyadic-level SM concordance" 
>   - Code for subhead section: "Association between dyadic-level SM concordance and patient-reported understanding" 
> - **scienceAdvancesModels2_3.Rmd**
>   - Code for replicating subhead section: "Physicians’ communication strategies and patient-reported understanding" 
>   - Code for replicating subhead section: "Effects of combining dyadic-level SM concordance and physicians’ communication strategy" 
>   - Code for replicating subhead section: "Classifying physician-level communication strategies" 
>   - Code for generating Figure 1

## R source output (.HTML)

To view in web browser, please right-click on each file below to open in a new tab or window. 

> **Relevant Files:**
> - http://dynamicog.org/concordance/scienceAdvancesDemographic.html 
> - http://dynamicog.org/concordance/scienceAdvancesModels1.html
> - http://dynamicog.org/concordance/scienceAdvancesModels2_3.html

## Data restrictions and availability

There were two major data components in producing the reported results in this manuscript. Each component has different restrictions and compatibility with source code provided in this repository.  

**Component 1** includes all steps to generate results reported in the following manuscript sections: 

* Subhead: "Setting and study sample"
* Subhead: "Corpus extraction"
* Subhead: "Development and generation of patients’ health literacy score" 
* Subhead: "Development and generation of physicians’ linguistic complexity score" 

The relevant analyses in this component mostly involve creating linguistic scores and generating classifications of patients' high or low health literacy and physicians' high or low language complexity. These analyses required direct manipulation of the content in secure message. Given the highly sensitive and confidential nature of the data, all analyses in this component were entirely conducted behind Kaiser Permanente Northern California's firewalls on secure servers that prevented downloading, printing, or copying. All researchers involved in Component 1 were required to receive security clearances to access the servers through VPN and multi-factor identification. **None of the data or steps to generate the output of Component 1 are reported in this document or are publicly available.**

**Component 2** relies on the aggregated data output from Component 1 to generate the bulk of results, tables, and figures as reported in the manuscript. Although this data has been de-identified to preserve patient and physician anonymity, it is nevertheless considered protected health information by its owners: Kaiser Permanente Northern California. Requests for the output from **Component 1** may be sent to the Kaiser Permanente Northern California Institutional Review Board at kpnc.irb@kp.org. Only qualified researchers trained in human subject confidentiality protocols will be recognized. 

## Data requests

> **Restricted data sources available with permission:**
> - **Duran_Schillinger_KPNC_restricted_demographics.csv** 
> - **Duran_Schillinger_KPNC_restricted_models.csv**


