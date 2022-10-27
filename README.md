# Machine-Learning-For-Medical-Applications
## This repository contains projects wherein machine learning algorithms was used for various medical applications.
### [Project 1: Decision Trees - The Cart Algorithm](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/DecisionTrees.ipynb)
In this project, we will be programming our own decision tree CART algorithm with Gini criterion. 

To evaluate the algorithm we will be working with the [Early stage diabetes risk prediction dataset](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.) containing predictor variables about patients with diabetes and controls. 


### [Project 2: Prognosis and Survival Function](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/Prognosis%20and%20survival.ipynb)
In this project, we will analyze observations from different patients who suffered a heart attack and we will create different survival functions employing univariate (Kaplan-Meier estimate) and multivariate (Cox proportional hazards and survival forests) analysis.

The data that we are going to use in this lab is described in the paper ["Survival analysis of heart failure patients: A case study"](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0181001). According to the authors: 
*Current study is based on 299 patients of heart failure comprising of 105 women and 194 men. All the patients were more than 40 years old, having left ventricular systolic dysfunction and falling in NYHA class III and IV. Follow up time was 4–285 days with an average of 130 days. Disease was diagnosed by cardiac echo report or notes written by physician. Age, serum sodium, serum creatinine, gender, smoking, Blood Pressure (BP), Ejection Fraction (EF), anemia, platelets, Creatinine Phosphokinase (CPK) and diabetes were considered as potential variables explaining mortality caused by CHD [...]. The information related to risk factors were taken from blood reports while smoking status and blood pressure were taken from physician’s notes.*


### [Project 3: Abnormal heartbeat detection with LSTMs and CNNs](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/LSTM_CNNarrhythmia.ipynb)
Today, detecting abnormal heartbeat patterns is important in smartwatches.In this project, we will try to predict heart arrhythmia with LSTMs and 1-D CNNs.

We will use MIT-BIH Arrythmia dataset (https://www.physionet.org/content/mitdb/1.0.0/). It consists of ECG recordings of several patients (patient IDs being 100, 101, etc.) with sampling frequency of 360 (samples/sec). Experts annotated/classified specific points in the signals as normal, abnormal, or non beat.


### [Project 4: Data Augmentation and Visualization for XRay](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/DataAugmentation_and_Visualization_for_XRay.ipynb)
In this project, we will learn to classify pneumonia using Chest X-Ray dataset which can be downloaded from [here](https://www.dropbox.com/s/cwvaqip12wpex6o/Lab7_XRay_chest_pnemonia.zip?dl=0). This data is already split into train, test and validation directories, so you do not have to split it yourself.


### [Project 5: Representation Learning with Autoencoder](https://github.com/clairevania/Machine-Learning-For-Medical-Applications/blob/main/Autoencoder_EEG.ipynb)
In this project, we will solve a 2-class classification problem using Epilespy EEG data.

The dataset is available from https://zenodo.org/record/3684992. This dataset was generated with a motive to build predictive epilepsy diagnosis models. It was generated on a similar acquisition and settings i.e., sampling frequency, bandpass filtering and number of signals and time duration as its much more famous counterpart - the University of Bonn dataset. It has overcome the limitations faced by the University of Bonn dataset, such as different EEG recording sites (inter-cranial and scalp) for healthy and epileptic patients. All the data were taken exclusively using surface EEG electrodes.
