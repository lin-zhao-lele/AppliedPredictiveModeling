# 应用预测建模 Applied Predictive Modeling
http://appliedpredictivemodeling.com

 


## Data
http://appliedpredictivemodeling.com/data

### Regression Data Sets

#### Main Text

- Fuel economy data: These data are found on the website for the U.S. Department of Energy’s Office of Energy Efficiency and Renewable Energy and the U.S. Environmental Protection Agency. Our analysis contains data on the relationship between fuel economy and engine displacement. The training data consists of model year 2010 data and the test set is comprised of cars from 2011 that were not in the 2010 data set. The data can be found in the AppliedPredictiveModeling R package.

- Solubility data: Tetko et al. (2001) and Huuskonen (2000) investigated a set of compounds in an effort to predict their solubility based on the chemical structure. We used a set of 228 simple predictors (e.g. the number of carbons) to model the data, which can be found in the AppliedPredictiveModeling R package.   

- Concrete mixture data: Yeh (1998) used designed experiments to find concrete formulations that maximize compressive strength. The data used here consists of separate experiments from 17 sources with common experimental factors were combined into one "meta–experiment". The data can be found in the UC Irvine Machine Learning Repository and in the AppliedPredictiveModeling R package. 


#### Exercises

- Blood-brain barrier data: These data are similar to the solubility data, except that the outcome measures how much a drug crosses the blood-brain barrier. The source is Mente and Lombardo (2005) and the data are in the caret package. 

- Chemical manufacturing data: This data set contains information about a chemical manufacturing process, in which the goal is to understand the relationship between the process and the resulting final product yield and can be found in the in the AppliedPredictiveModeling R package.  

- Tecator meat data: From the StatLib Datasets Archive: "These data are recorded on a Tecator Infratec Food and Feed Analyzer working in the wavelength range 850 - 1050 nm by the Near Infrared Transmission (NIT) principle... For each meat sample the data consists of a 100 channel spectrum of absorbances and the contents of moisture (water), fat and protein." The data points can be found at StatLib or in the caret R package. 

- Permeability data: This pharmaceutical data set was used to develop a model for predicting compounds' permeability (i.e. a molecule’s ability to cross a membrane). The data are also in the AppliedPredictiveModeling R package.  

- Friedman simulation data: Friedman (1991) described several simulation tools for creating highly non-linear data sets. We used the "Friedman1" simulation model from a function in the mlbench R package. 



### Classification Data Sets

#### Main Text

- Cell segmentation data: These are measurements taken in individual cells in a high content screen for cancer. The original data are from Hill et al. (2007). Our analyses used the training/test split determined by the authors. The original data can be found in the Supplemental Data section for the journal or in the AppliedPredictiveModeling R package. A version of the data after pre-processing can also be found in the caret R package. 

- German credit data: This well-known data set is used to classify customers as having good or bad credit based on customer attributes (e.g. information on bank accounts or property). The data can be found at the UC Irvine Machine Learning Repository and in the caret R package.   
 
- Direct marketing data: These data are from Larose (2006, Chapter 7) and contain information on shopping habits of customers and their response to promotional offers. The original data can be found at the website for the book Data Mining Methods and Models, along with other relevant data sets. 

- Grant application data: These data originated in a Kaggle competition. The goal was to predict success or failure of a grant application based on information about the grant and the associated investigators. 

- Insurance ownership data: The 2000 CoIL Challenge was to predict whether customers would purchase caravan insurance. Van Der Putten and Van Someren (2004) discuss these data. The outcome, whether the costumer purchased caravan insurance, is modeled as a function of customer subtype designation, demographic information and product ownership data. We used the raw data found in the DWD R package. 

- HPC job scheduling data: These data are used to predict the execution time of programs run in a high performance computing (HPC) environment. Information about the computing jobs are used to classify jobs as being either  very fast (1 minute or less), fast (1–5 minutes), moderate (5–30 minutes) or long (greater than 30 minutes). The data can be found in the AppliedPredictiveModeling R package.

- Cognitive impairment data: Craig-Schapiro et al. (2011) describes a clinical study of 333 patients where laboratory measurements are used to predict which subjects are most likely to develop cognitive impairment, such as Alzheimer's disease. The data can be found in the AppliedPredictiveModeling R package.

#### Exercises

- Oil identification data:  Brodnjak-Vonina et al. (2005) develop a methodology for food laboratories to determine the type of oil from a sample. In their procedure, they used a gas chromatograph (an instrument that separate chemicals in a sample) to measure 7 different fatty acids in an oil. These measurements would then be used to predict the type of oil in a food samples. The raw data can be found in their Table 1 or in the caret package. 

- Glass identification data: The UC Irvine Machine Learning Repository contains a data set related to glass identification. The data consist of 214 glass samples labeled as one of seven class categories. The predictors include 9 predictors, including the refractive index and percentages of 8 elements. The data are also in the mlbench R package.   

- Soybean data: The Soybean data can also be found at the UC Irvine Machine Learning Repository. Data were collected to predictor disease in soybeans. The predictors include mostly categorical and include information on the environmental conditions (e.g. temperature, precipitation) and plant conditions (e.g. left spots, mold growth). The outcome labels consist of 19 distinct classes. These data are also in the mlbench R package.  

- Hepatic injury data: Experimental data were used to develop a model for predicting compounds' probability of causing hepatic injury (i.e. liver damage). The response was categorical (either "does not cause injury", "mild injury" or "severe injury"), and was highly unbalanced. These data can be found in the AppliedPredictiveModeling R package.

- Customer churn data: The MLC++ software package contains a number of machine learning data sets. The "churn" data set was developed to predict telecom customer churn based on information about their account. The data files state that the data are "artificial based on claims similar to real world". These data are also contained in the C50 R package.

- Adult income data: The "Adult" data set at the UCI Machine learning repository is derived from census records. In these data, the goal is to predict whether a person’s income was large (defined in 1994 as more than $50K) or small. The predictors include: educational level, type of job (e.g. never worked, local government, etc), capital gains/losses, work hours per week, native country, and so on. The data are found in the arules R package. 

### Other Sources of Data

- The Association For Computing Machinery (ACM) has a special interest group on Knowledge Discovery in Data (KDD). The KDD group organizes annual machine learning competitions.
  
- http://www.cheminformatics.org contains many examples of computational chemistry data sets.
  
- The NCBI GEO website is "a public repository that archives and freely distributes microarray, next–generation sequencing, and other forms of high–throughput functional genomic data submitted by the scientific community".

- The R package SMCRM has data sets for Statistical Methods in Customer Relationship Management by Kumar and Petersen (2012) 