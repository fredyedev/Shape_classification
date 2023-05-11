# Shape_classification
Applying the K-Means method to the Fourier descriptors to generate the 5 classes of shapes
The numpy array shapes.npy, of size 25 × 201 × 2, contains a set of 25 closed curves
in R2 , each one of them being discretized with 201 points. Each of the 20 other curves is obtained 
by applying a translation, a rotation and a scale transformation to one of these 5 curves. The aim of this process is to classify automatically
the set of 25 curves into 5 classes, each class containing the curves which are deduced from
each others by a translation, a rotation and a scale transformation. We know that the method
of Fourier descriptors can be used to solve this classification problem.
