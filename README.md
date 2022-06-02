# ML-MODELS-using-SFFS

>Compared the performance of the 5 different classifiers: Naïve Base, Decision Tree,
K nearest neighbor, linear discriminate analysis, and quadratic discriminate analysis to classify
subjects to the two groups of healthy subjects and CVD patients using 20% of the data for
testing. 

>First calculated the performances of the classifiers using all 13 features. Then calculated the
performances of the classifiers when the best features are selected with “Sequential floating
forward selection (SFFS)” feature selection method.

>Compared the performance of the classifiers using all 13 features with the best features in terms of
sensitivity, specificity, and total accuracy. 

>Indicated which classifier has the best performance.

>Dataset Info:
>
Cardiovascular disease (CVD) is a primary cause of death. An estimated 17.5 million people
died from CVD in 2012, representing 31% of all global deaths. In the United States, heart
disease kills one person every 34 seconds. Numerous factors are involved in the diagnosis of
heart disease, which complicates a physician’s task. To help physicians make quick decisions
and minimize errors in diagnosis, classification systems enable physicians to rapidly examine
medical data in considerable detail. These systems are implemented by developing a model that
can classify existing records using sample data. Various classification algorithms have been
developed and used as classifiers to assist doctors in diagnosing heart disease patients.
In this study, we use 4 databases concerning heart disease diagnosis. The data was collected from
the four following locations:

1. Cleveland Clinic Foundation (cleveland.data)
2. Hungarian Institute of Cardiology, Budapest (hungarian.data)
3. V.A. Medical Center, Long Beach, CA (long-beach-va.data)
4. University Hospital, Zurich, Switzerland (switzerland.data)

The attached database has 270 subjects (150 healthy and 120 CVD patients) with 13
discriminating features between CVD patients and healthy population that includes:
1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholesterol in mg/dl
6. fasting blood sugar &gt; 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
The last column of data indicates the class of subject: “1” for healthy and “2” for CVD.
