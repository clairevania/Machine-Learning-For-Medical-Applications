# Machine-Learning-For-Medical-Applications
## This repository contains projects wherein machine learning algorithms was used for various medical applications.
### [Project 1: Decision Trees - The Cart Algorithm](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/DecisionTrees.ipynb)
In this project, we will be programming our own decision tree CART algorithm with Gini criterion. 

To evaluate the algorithm we will be working with the [Early stage diabetes risk prediction dataset](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.) containing predictor variables about patients with diabetes and controls. 


### [Project 2: Prognosis and Survival Function](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/Prognosis%20and%20survival.ipynb)
In this project, we will analyze observations from different patients who suffered a heart attack and we will create different survival functions employing univariate (Kaplan-Meier estimate) and multivariate (Cox proportional hazards and survival forests) analysis.

The data that we are going to use in this lab is described in the paper ["Survival analysis of heart failure patients: A case study"](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0181001). According to the authors: 
*Current study is based on 299 patients of heart failure comprising of 105 women and 194 men. All the patients were more than 40 years old, having left ventricular systolic dysfunction and falling in NYHA class III and IV. Follow up time was 4–285 days with an average of 130 days. Disease was diagnosed by cardiac echo report or notes written by physician. Age, serum sodium, serum creatinine, gender, smoking, Blood Pressure (BP), Ejection Fraction (EF), anemia, platelets, Creatinine Phosphokinase (CPK) and diabetes were considered as potential variables explaining mortality caused by CHD [...]. The information related to risk factors were taken from blood reports while smoking status and blood pressure were taken from physician’s notes.*


### Project 3: Abnormal heartbeat detection with LSTMs and CNNs
Today, detecting abnormal heartbeat patterns is important in smartwatches.In this project, we will try to predict heart arrhythmia with LSTMs and 1-D CNNs.

We will use MIT-BIH Arrythmia dataset (https://www.physionet.org/content/mitdb/1.0.0/). It consists of ECG recordings of several patients (patient IDs being 100, 101, etc.) with sampling frequency of 360 (samples/sec). Experts annotated/classified specific points in the signals as normal, abnormal, or non beat.
