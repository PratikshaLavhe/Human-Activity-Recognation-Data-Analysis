# Human-Activity-Recognation-Data-Analysis
 Human Activity Recognition Using Smartphones:-

Abstract: -
	Human activity recognition has wide applications in medical research and human survey system. In this project, we design a robust activity recognition system based on a smartphone. The system uses a 3-dimentional smartphone accelerometer as the only sensor to collect time series signals, from which 31 features are generated in both time and frequency domain. Activities are classified using 4 different passive learning methods, i.e., quadratic classifier, k-nearest neighbor algorithm, support vector machine, and artificial neural networks.

Introduction: -
	The demands for understanding human activities have grown in health-care domain, especially in elder care support, rehabilitation assistance, diabetes, and cognitive disorders. [1,2,3]. A huge number of resources can be saved if sensors can help caretakers record and monitor the patients all the time and report automatically when any abnormal behaviour is detected. In this project you will design a robust activity recognition system based on the smartphones. As you know mobile devices have accelerometer as the sensor which collects the activities. These activities can be classified using K-nearest neighbour. 

 Database Information: -
	The data was collected from 30 subjects aged between 19 and 48 years old performing one of 6 standard activities while wearing a waist-mounted smartphone that recorded the movement data. Video was recorded of each subject performing the activities and the movement data was labeled manually from these videos.

Attribute Information: -
	For each record in the dataset, it is provided:
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope.
- A 561-feature vector with time and frequency domain variables.
- Its activity label.
- An identifier of the subject who carried out the experiment.





Flowchart: -
 
 Machine Learning Model Used:-
1. k-nearest neighbours

KNN: -
	k-Nearest Neighbours Application of distance measure is not feasible for the kNN technique. The uncertainty is measured using the concept of Shannon entropy H . In mathematical terms, c c u(x)  H(x)   pc log p where c denotes classes and c p is the probability that instance x belongs to a specific class. c p is calculated through dividing the number of neighbours that belong to a specific class over the total number of neighbours k.

 

 






Requirement: -
1. Pandas
2. NumPy
3. Matplotlib
4. Scikit Learn

 Steps:-
1. Importing Libraries
2. Exploring the Dataset
3. Exploratory Data Analysis
4. Data Pre-processing
5. Model Building
    >* KNeighborsClassifier
6. Evaluation
7. Conclusion

Citation Request: -
- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.

License:-
https://creativecommons.org/publicdomain/zero/1.0/

Conclusion:-
	 Human activity recognition has broad applications in medical research and human survey system. In this project, we designed a smartphone-based recognition system that recognizes five human activities: walking, limping, jogging, going upstairs and going downstairs.

References:-
[1] Morris, M., Lundell, J., Dishman, E., Needham, B.: New Perspectives on Ubiquitous Computing from Ethnographic Study of Elders with Cognitive Decline. In: Proc. Ubicomp (2003). 
[2] Lawton, M. P.: Aging and Performance of Home Tasks. Human Factors (1990) 
[3] Consolvo, S., Roessler, P., Shelton, B., LaMarcha, A., Schilit, B., Bly, S.: Technology for Care Networks of Elders. In: Proc. IEEE Pervasive Computing Mobile and Ubiquitous Systems: Successful Aging (2004)
