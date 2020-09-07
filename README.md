# Face_Recognition_Using_Python

In the past few years, face recognition owned significant consideration and appreciated as one of the most promising applications in the field of image analysis. Face detection can consider a substantial part of face recognition operations. According to its strength to focus computational resources on the section of an image holding a face. The method of face detection in pictures is complicated because of variability present across human faces such as pose, expression, position and orientation, skin colour, the presence of glasses or facial hair, differences in camera gain, lighting conditions, and image resolution.

Face detection methods.
  1.Knowledge based 
  2.Feature based
  3.Template matching
  4.Appearance based
  
# 1.Knowledge based method
    The knowledge-based method depends on the set of rules, and it is based on human knowledge to detect the faces. Ex- A face must have a nose, eyes, and mouth within certain distances and positions with each other. The big problem with these methods is the difficulty in building an appropriate set of rules. There could be many false positive if the rules were too general or too detailed. This approach alone is insufficient and unable to find many faces in multiple images.
    
  
# 2.Feature based method
    The feature-based method is to locate faces by extracting structural features of the face. It is first trained as a classifier and then used to differentiate between facial and non-facial regions. The idea is to overcome the limits of our instinctive knowledge of faces. This approach divided into several steps and even photos with many faces they report a success rate of 94%.
    
    
# 3.Template matching method
    Template Matching method uses pre-defined or parameterised face templates to locate or detect the faces by the correlation between the templates and input images. Ex- a human face can be divided into eyes, face contour, nose, and mouth. Also, a face model can be built by edges just by using edge detection method. This approach is simple to implement, but it is inadequate for face detection. However, deformable templates have been proposed to deal with these problems.
    
    
# 4.Appearence based method
    The appearance-based method depends on a set of delegate training face images to find out face models. The appearance-based approach is better than other ways of performance. In general appearance-based method rely on techniques from statistical analysis and machine learning to find the relevant characteristics of face images. This method also used in feature extraction for face recognition.
    
    The appearance-based model further divided into sub-methods for the use of face detection which are as follows-
    
    4.1.Eigenface-Based:-
    Eigenface based algorithm used for Face Recognition, and it is a method for efficiently representing faces using Principal Component Analysis.
    
    
    4.2.Distribution-Based:-
    The algorithms like PCA and Fisher’s Discriminant can be used to define the subspace representing facial patterns. There is a trained classifier, which correctly identifies instances of the target pattern class from the background image patterns.


    4.3.Neural-Networks:-
    Many detection problems like object detection, face detection, emotion detection, and face recognition, etc. have been faced successfully by Neural Networks.
    4.4.Support Vector Machine:-
    Support Vector Machines are linear classifiers that maximise the margin between the decision hyperplane and the examples in the training set. Osuna et al. first applied this classifier to face detection.
    
    
    4.5.Sparse Network of Winnows:-
    They defined a sparse network of two linear units or target nodes; one represents face patterns and other for the non-face patterns. It is less time consuming and efficient.
    
    
    4.6.Naive Bayes Classifiers:-
    They computed the probability of a face to be present in the picture by counting the frequency of occurrence of a series of the pattern over the training images. The classifier captured the joint statistics of local appearance and position of the faces.
    
    
    4.7.Hidden Markov Model:-
    The states of the model would be the facial features, which usually described as strips of pixels. HMM’s commonly used along with other methods to build detection algorithms.
    
    
    4.8.Information Theoretical Approach:-
    Markov Random Fields (MRF) can use for face pattern and correlated features. The Markov process maximises the discrimination between classes using Kullback-Leibler divergence. Therefore this method can be used in Face Detection.
    
    
    4.9.Inductive Learning:-
    This approach has been used to detect faces. Algorithms like Quinlan’s C4.5 or Mitchell’s FIND-S used for this purpose.

