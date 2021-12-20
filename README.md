# Credit_Risk_Analysis
## Overview of Project
### Purpose
###### Jill wants our help in seeing if we can more accurately predict credit card risk. She wants us to use all methods that we've covered regarding machine learning to see if there is a preferred method moving forward.
## Results
###### {Before we get started - I didn't fully finish the first deliverable before moving on to the next deliverable, since resampling using SMOTEEN took my computer a great deal of time. With the second deliverable, I had to uninstall SciKit 1.0.1 and install 1.0.0, which meant I had to restart Jupyter. Now when I try to run the resampling deliverable, it won't go past the ClusterCentroids line, which is not an issue I was having before. I attached a picture of the error but even though the code is there, the kernel keeps dying and I can't see the output - which is obviously going to affect this analysis. Curtis recommended I download "pyenv" environment so I'm going to try that and hopefully get my whole code to run.}
![2017 original script run time](https://github.com/liabrooke/Credit_Risk_Analysis/blob/main/kernel_died_error.png) 
* ###### The first method, random oversampling, produced a balanced accuracy score of .641923.
* ###### The next method, SMOTE oversampling, produced a balanced accuracy score of .657571.
* ###### For undersampling, we tested the data using the ClusterCentroids resampler (which unfortunately won't run for me at the moment so stay tuned.
* ###### For the combination sampling methods, we tested the data using SMOTEENN.
* ###### Moving on to ensemble algorithims, we first tested the balanced random forest classifier. This resulted in a balanced accuracy score of .7740943.
* ###### The last method that was tested was the EasyEnsembleClassifier which resulted in a balanced accuracy score of .932859.
![2017 original script run time](https://github.com/liabrooke/Pewlett-Hackard-Analysis/blob/main/Retirement_titles_count.png) 

## Summary
###### I agree with Jill in the fact that even a small improvement is very important, so identifying the best approach is key. Out of the six approaches, both ensemble algorithims were superior, with the EasyEnsembleClassifier taking a jump at .932859. The two worst methods were random oversmapling and SMOTE oversampling. My recommondation would be to use the EasyEnsembleClassifier, but to also keep testing out the numerous other methods that are out there.
