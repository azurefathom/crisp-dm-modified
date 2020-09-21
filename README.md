# crisp-dm-modified
Personal custom CRISP-DM ml project development framework

CRISP-DM Framework (modified IBM modified)
1. Business Understanding

   A. Business Situation
      a. Needs and Pain Points
      b. Opportunities
            - Increase revenue
            - Decrease costs
            - Increase profits
            - Optimize resource allocation
            - Improve measurement
            - Reduce process time
            - Reduce risk
      c. Data environment assessment
      d. Readiness assessment
      e. Define Roadmap
      
  B. Business Problem Definition
      a. Clearly define business objectives
      b. Clearly define problem and solution requirements
      c. Hypothesis generation and definition
      d. Clearly define project scope
      e. Define success metrics and measurement plan
      f. Discuss Critical Success Factors (CSFs)
      g. Discuss key features and missing features
      h. Discuss data enrichment requirements/costs
      i. External data enrichment requirements/costs
      j. Define WIP/deployment plan
      k. Engage critical business sponsors
      l. Discuss confusion matrix costs
      m. Discuss security/privacy/AMS (access move store)
      
  C. Analytics Approach
      a. Define the analysis
      b. Define the dependent variable
      c. Define independent variable(s)
      d. Discuss unstructured data
      e. Express problem in context of ML techniques
      f. Discuss sampling requirements
      g. Identify most appropriate technique(s) considering:
          - Project budget
          - Deployment complexity
          - Deployment costs
          - Missing variable acquisition costs
          - Workstream integration
          - Data security
          - Data variety, velocity, volume, veracity
          - Model opacity e.g., black box
          - Scoring requirements e.g., frequency, amounts


2. Data Understanding

   A. Data Requirements
       a. Formats
       b. Structured data
       c. Unstructured data
       d. Date/time data
       e. Readily available data
       f. Are less accessible data required?
       g. Are external data required?
       h. Are new data capture mechanisms required?
                  
   B. Data Structure
       a. Record counts
       b. Missing variables
       c. Frequencies - values
       d. Frequencies - invalid values
       e. Frequencies - missing values
       f. Descriptives - basic
       g. Descriptives - invalid values
       h. Descriptives - missing values
       i Descriptives - outliers
       j. Descriptives - normality
       k. Date/time - ranges

   C. Data Audit Report

                                          

              3. Data Preparation

                             ○ General

                                           ○ Pre-segment instances

                                           ○ DEFINE - date ranges

                                           ○ DERIVE - Target variable candidates

                                           ○ DERIVE - Features/variables

                                           ○ Prepare Time Series data

                                           ○ Discard unusable fields

                                          

                             ○ Sampling

                                           ○ DEFINE - sampling (e.g., 100%, 10%, 1%)

                                           ○ DEFINE - sampling (e.g., calibration, validation, test)

                            

                             ○ Exploratory Data Analysis (EDA)

                                           ○ Univariate plots (frequencies, histograms)

                                           ○ Multi-variate plots (scatters)

                                           ○ Detection - Linearity

                                           ○ Detection - Outliers

                                           ○ Detection - Skewness

                                           ○ Detection - Missing values

                                           ○ Detection - Target imbalance

                                           ○ Detection - Unmanageable classes

                                           ○ Detection - Valid negatives (scale values)

                                           ○ Detection - Scaling (variables with different scales)

                                           ○ Detection - Interactions! (trees)

                                           ○ Detection - Correlation (among features)

                                           ○ Detection - Correlation (with target)

                                           ○ Text analytics / sentiment

                                           ○ Clustering / auto-cluster

                                           ○ Quick and dirty models

                                           ○ LEAKAGE CHECK!

                            

                             ○ Transformations

                                           ○ Handling - Linearity

                                           ○ Handling - Outliers (Coerce/Drop)

                                           ○ Handling - Skewness (Binning, Transformations)

                                           ○ Handling - Missing values (impute: mean med regression)

                                           ○ Handling - Target imbalance (SMOTE)

                                           ○ Handling - Unmanageable classes (Binning)

                                           ○ Handling - Valid negatives (rescale: e.g., X + 10)

                                           ○ Handling - Scaling (z-scores, standardization)

                                           ○ Handling - Interactions! (DEFINE new features)

                                           ○ Handling - Correlations (among features) - combine (ratio)

                                           ○ Handling - Correlations (among features) - drop

                                           ○ Handling - Correlations (among features) - Data Reduction

                                           ○ Auto data preparation

                                          

              4. Analysis & Modeling

                            

                             ○ Feature Selection

                                           ○ Feature - Selection

                                           ○ Feature - Independence check

                                           ○ Feature - Target leakage check

                                           ○ Feature - Essential missing variable check

                                           ○ Data reduction

                                          

                             ○ Modeling & Analysis (iterative process)

                                           ○ Identify most appropriate techniques

                                           ○ Build Quick and Dirty models

                                           ○ Refine models

                                           ○ Select 3 -5 model candidates

                                          

              5. Evaluation

                             ○ Model Evaluation

                                           ○ Check - LEAKAGE

                                           ○ Check - Model performance (classification)

                                           ○ Check - Model performance (regression)

                                           ○ Check - Overfitting

                                           ○ Check - Quality (do variables make sense)

                                           ○ Check - Costs (are variables too expensive for production)

                                           ○ Check - Is output useful?

                                           ○ Check - Can the output be acted on?

                                           ○ Check - Workstream Integration Plan (WIP)

                                           ○ Check - Classification cost analysis

                                          

              6. Deployment

                             ○ Roadmap (revisit)

                             ○ Testing

                             ○ Production

                             ○ Monitoring

                             ○ ROI Assessment

                                          

END
