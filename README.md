# Understanding Eye Tracking of Electrocardiograms

### Signals processing final project.

This project solves the task of classifying medical practitioners into groups based on data of their eye tracking of electrocardiograms with differrent heart anomalities.

Categories for classification:
 - Cardiac Care Unit Nurses;
 - Catheterization Lab Nurses;
 - General Nurses;
 - Cardiology consultants;
 - Fellows (physicians undergoing post-graduate training in cardiology);
 - General Doctors;
 - Junior medical students;
 - Senior medical students;
 - Technicians;
 - Residents.
 
There appeared some issues when solving the task: the dataset was imbalanced and there was not enough data to accurately classify practitioners. There were many features, some of which leaked data. Some of these problems were solved with the usage of Synthetic Minority Oversampling Technique form Python's imbalanced-learn module and other technologies. However, the lack of data was too big and unfortunately the accuracy of the classifier was too small. 

You can read more about this project in the [report](https://drive.google.com/file/d/1E43MXqPNd-83svanDfFd-uqMALyGuRXo/view?usp=sharing) or in the [presentation](https://docs.google.com/presentation/d/1npcfvAdY2VmQ0dovrUNOYwrxAO9jsWz6e1lIqL5KwRw/edit?usp=sharing).
