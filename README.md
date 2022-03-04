# HaitiPixels
Disaster relief project - identification of blue tarps over makeshift shelters from pixel data from photos of Haiti earthquake.
In the aftermath of a catastrophic earthquake in Haiti in the year 2010, rescue efforts were obstructed by difficulties in locating and providing aid to survivors. Due to infrastructure issues such as downed power lines, communication was made difficult or impossible, and ground transportation was limited by the amount of debris blocking roadways. Images were collected by Rochester Institute of Technology helicopters in order to try to locate makeshift shelters erected by survivors, but there were not enough workers to manually search each image for signs of people who urgently required food, water, and medical assistance.

Five binary classification methods were developed to more efficiently and accurately identify the shelters, which are identifiable by the bright blue tarps used to build them. If a program could quickly determine which images showed areas with survivors, and which did not, then workers could focus their work on reaching survivors and distributing necessary resources rather than studying photos. These classifiers were built with the goal to maximize the true positive rate (the ratio of correctly-identified blue tarps to correctly-identified blue tarps and tarps that were not identified by the model) and the overall accuracy based on a dataset containing only the red, green, and blue signal values of images captured by RIT. 

The models trained include logistic regression, LDA, QDA, elastic net, k-nearest neighbors, random forest, linear SVM, polynomial SVM, and radial basis function SVM.
