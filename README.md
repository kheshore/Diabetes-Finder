**DIABETES PREDICTION USING MACHINE LEARNING**

![1s](https://github.com/kheshore/Diabetes-Finder/assets/43311731/074d6ef3-03d2-4d1f-a5aa-dfda8c48215e)

Diabetes affects millions of people around the world and is a growing public health issue. It is a chronic condition that occurs when the pancreas does not produce enough insulin or the body is unable to effectively use the insulin produced. Insulin is a hormone that is responsible for controlling the amount of glucose (sugar) in the body. Without insulin, glucose cannot get into the cells of the body, leading to high levels of glucose in the blood. The symptoms of diabetes include increased thirst, frequent urination, feeling tired, blurry vision, and slow healing wounds. Long-term effects of diabetes can include kidney disease, heart disease, stroke, nerve damage, vision loss, and even death **.** However, early prediction of diabetes is quite challenging task for medical practitioners due to complex interdependence on various factors as diabetes affects human organs such as kidney, eye, heart, nerves, foot etc. The primary aim of this project is to develop a machine learning model that is capable of accurately predicting the occurrence of diabetes in a given patient. The model will be developed using supervised learning algorithms such as Random Forest Regressor, Support Vector Machines, and Neural Networks. The performance of the model will be evaluated in terms of accuracy and other standard metrics. The results of this project will demonstrate the effectiveness of machine learning in predicting the occurrence of diabetes. This project will provide insights into various medical conditions associated with diabetes and help identify high-risk patients. Furthermore, it is expected that the results of this project will help medical practitioners in understanding the risk factors associated with diabetes and to provide better care for patients.In Existing System, the dataset has to be manually analysed with individual scripts which is a very slow process to analyse the complete data set, Whereas in Proposed System it is completely GUI based, so it is easy to analyse any dataset in a single execution with multiple graphs and charts, also it is cross-platform.

**INTRODUCTION**

Diabetes is the fast-growing disease among the people even among the youngsters. In understanding diabetes and how it develops, we need to understand what happens in the body without diabetes. Sugar (glucose) comes from the foods that we eat, specifically carbohydrate foods. Carbohydrate foods provide our body with its main energy source everybody, even those people with diabetes, needs carbohydrate. Carbohydrate foods include bread, cereal, pasta, rice, fruit, dairy products and vegetables (especially starchy vegetables). When we eat these foods, the body breaks them down into glucose. The glucose moves around the body in the bloodstream. Some of the glucose is taken to our brain to help us think clearly and function. The remainder of the glucose is taken to the cells of our body for energy and also to our liver, where it is stored as energy that is used later by the body. In order for the body to use glucose for energy, insulin is required. Insulin is a hormone that is produced by the beta cells in the pancreas. Insulin works like a key to a door. Insulin attaches itself to doors on the cell, opening the door to allow glucose to move from the blood stream, through the door, and into the cell. If the pancreas is not able to produce enough insulin (insulin deficiency) or if the body cannot use the insulin it produces (insulin resistance), glucose builds up in the bloodstream (hyperglycaemia) and diabetes develops. Diabetes Mellitus means high levels of sugar (glucose) in the blood stream and in the urine.

**SOFTWARE SPECIFICATION**

| **COMPONENTS** | **REQUIREMENTS** |
| --- | --- |
| OPERATING SYSTEM | Windows 8 and Above |
| FRONT END | Python (TKinter) |
| ML DATA SET | Reviews Dataset in CSV |
| BACK END | Python (Seaborn) |

**HARDWARE SPECIFICATION**

| **COMPONENTS** | **REQUIREMENTS** |
| --- | --- |
| CPU | x86 64-bit CPU (Intel / AMD architecture) |
| RAM | 2GB Minimum |
| STORAGE | 5GB Minimum disk space |
| PERIPHERALS | Common Peripherals (Mouse, Keyboard,..) |

**MODULE DESCRIPTION.**

The modules used in the project are:

- Dataset collection
- Data Exploration
- Data Cleaning
- Random Forest Regression

- Transform the categorical variables
- Split Training and test datasets
- Transform the numerical variables
- Fit the logistic regression model
- Evaluate the model
- The prediction

- User Interface

**DATASET COLLECTION**

The first step is the collection of data from the retrospective cohort of patient who has been diagnosed with diabetes. Data pre-processing is performed to improve the quality of a dataset to get clean data which can be helpful for modeling.

**The training dataset is used in training the machine learning model.**

Training data are the initial data used to train machine learning models. Training datasets are fed to machine learning algorithms to teach them how to make predictions or perform a desired task.

**DATA EXPLORATION**

The dataset we are going to use is from National Institute of Diabetes and Digestive and Kidney Diseases (Pima Indian Diabetes).The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian

This corresponds to the documentation on Kaggle that the datasets consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome. This include Pregnancies: Number of times pregnant, Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test, Blood Pressure: Diastolic blood pressure (mm Hg), Skin Thickness: Insulin: 2-Hour serum insulin (mu U/ml), BMI: Body mass index (weight in kg/(height in m)^2), Diabetes Pedigree Function, Age. By which a value of 1 shows the presence of Diabetes in the patient, otherwise 0.

Data exploration is an informative search used by data consumers to form a true analysis of the information gathered. Data exploration is used to analyze the data and information from the data to form a true analysis. After having a look at the dataset, certain information about the data was explored. Here the dataset is not unique while collecting the dataset. In this module, the uniqueness of the dataset can be created.

**DATA CLEANING**

Data cleaning involves removing noise and inconsistencies which are present in the data, thereby improving the quality of the data. During the data pre-processing stage, the data is partitioned into the training dataset and validation dataset.

In data cleaning module, is used to detect and correct the inaccurate dataset. It is used to remove the duplication of attributes. Data cleaning is used to correct dirty data which contains incomplete or outdated data, and the improper parsing of record fields from disparate systems. It plays a significant part in building a model.

The dataset we will use is is from National Institute of Diabetes and Digestive and Kidney Diseases (Pima Indian Diabetes).The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

To keep the cleaning process simple, we'll remove:

- The columns with many missing values are slope, ca, and that.
- The rows with missing values.

**RANDOM FOREST REGRESSION:**

Random forest regression is a popular machine learning algorithm for supervised learning.

Python Libraries Used in this Project:

- Pandas – a powerful tool for data analysis and manipulation.
- NumPy – the fundamental package for scientific computing.
- Scikit Learn (sklearn) – a popular tool for machine learning.
- Matplotlib - a powerful tool for data processing and analysis.
- Tkintertable - a powerful GUI toolkit for UI creation.

**USER INTERFACE**

The User Interference end is based on tKinker tools by python. Tk interface is the standard Python interface to the Tcl/Tk GUI toolkit. Both Tk and tkinter are available on most Unix platforms, including macOS, as well as on Windows systems.


**User Inputs:**

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)

**Outcome:**

- Class variable (0 or 1)

**Buttons:**

- Predict: Runs the Main Program
- Clear: Clear the Text boxes
