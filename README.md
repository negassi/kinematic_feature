# Kinematic Feature Analysis  
Data was extracted from MoVAlyzer system. MoVAlyzer is a device that records the kinematic features of handwriting. The features were recorded at different segments of an alphabet in line of phrases. 25 Features were extracted from each segment. The features include.  
Vertical and horizontal Speed of the hand,  Pen down duration, Horizontal and vertical jerks and etc.  
### Objective  
The goal of the project is to answer the following questions from the data:  
Who is the writer?  
What style was used ?  
Which line of phrase was ?   

## Data Collection  
40 writers were selected. The wrote 6 lines of phrases each in 2 styles (Cursive and Print) and this process was repeated 3 times.  
The kinematic features were recorded at different segments of the alphabets. A line of phrase might was divided up 75 segments.  
103000 segments were recorde in total.

## Data preparation for modeling  
2 variables with constat value were removed   
The feature of the segments were aggregated in to a single value to denote as one observation. Hence the data was reduced to 1440(2x6x40x3)  

## Dimension Reduction  
Principal component analysis was used and 10 components were used for 93% variation.

## Model 
Knn, LDA, SVM were used to predict the model.




