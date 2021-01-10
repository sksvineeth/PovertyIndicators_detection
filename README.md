# PovertyIndicators_detection
There are huge number of social programs, having a hard time
finding the right set of people to address. It becomes tricky when it comes to the
segmentation of poverty levels and focusing on the poorest segment available. The goal is
to devise a model for more appropriate means of classifying household into different levels
of poverty for Costa Rica(dataset). 

It is challenging to decide on factors contributing to the poverty
line, many such programs are currently going on, and still, the problem of determining the
right threshold for poverty line remains unsolved. The objective is to predict poverty on a
household level. Moreover, we must predict for every individual, but we should relate them
to each household to predict poverty on a household basis. 

An exploratory data analysis with Feature Engineering as the key idea was performed on the dataset.
Categorial and non-categorical data columns were studied in
detail. Redundant columns were removed, and highly correlated variables were also
removed from data set. MICE was implemented for missing data.
The data was prepared for mining and desired solutions were
developed. 

The performance of these solutions was evaluated, and best model was selected.
The best method of classification was undoubtedly the random forest because of its highly
auc. The number of trees used for training and averaging were 300 which served a good
purpose for giving an AUC score of 0.97.
