# crisp-dm-modified
Personal custom CRISP-DM ml project development framework

# 1. Business Understanding
# 2. Analytical Approach
# 3. Data Collection
# 3. Data Understanding
# 4. Feature Engineering/Data Preparation
# 7. Analysis and Modeling

# END
CRISP-DM Framework (modified IBM modified)
1. Business Understanding
   - Business Situation
      - Needs and Pain Points
      - Opportunities
            - Increase revenue
            - Decrease costs
            - Increase profits
            - Optimize resource allocation
            - Improve measurement
            - Reduce process time
            - Reduce risk
      - Data environment assessment
      - Readiness assessment
      - Define Roadmap
      
  - Business Problem Definition
      - Clearly define business objectives
      - Clearly define problem and solution requirements
      - Hypothesis generation and definition
      - Clearly define project scope
      - Define success metrics and measurement plan
      - Discuss Critical Success Factors (CSFs)
      - Discuss key features and missing features
      - Discuss data enrichment requirements/costs
      - External data enrichment requirements/costs
      - Define WIP/deployment plan
      - Engage critical business sponsors
      - Discuss confusion matrix costs
      - Discuss security/privacy/AMS (access move store)
      
  - Analytics Approach
      - Define the analysis
      - Define the dependent variable
      - Define independent variable(s)
      - Discuss unstructured data
      - Express problem in context of ML techniques
      - Discuss sampling requirements
      - Identify most appropriate technique(s) considering:
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

                             ○ Data Requirements

                                           ○ Formats

                                           ○ Structured data

                                           ○ Unstructured data

                                           ○ Date/time data

                                           ○ Readily available data

                                           ○ Are less accessible data required?

                                           ○ Are external data required?

                                           ○ Are new data capture mechanisms required?

                                          

                             ○ Data Structure

                                           ○ Record counts

                                           ○ Missing variables

                                           ○ Frequencies - values

                                           ○ Frequencies - invalid values

                                           ○ Frequencies - missing values

                                           ○ Descriptives - basic

                                           ○ Descriptives - invalid values

                                           ○ Descriptives - missing values

                                           ○ Descriptives - outliers

                                           ○ Descriptives - normality

                                           ○ Date/time - ranges

                            

                             ○ Data Audit Report

                                          

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
