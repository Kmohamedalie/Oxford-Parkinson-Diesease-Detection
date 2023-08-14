# Oxford-Parkinson-Diesease-Detection

![image](https://github.com/Kmohamedalie/Oxford-Parkinson-Diesease-Detection/assets/63104472/a4673a89-67d5-40c8-b9b5-daf60e18293e)


**Task:** The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD. 

**Dataset:**  <a href="https://archive.ics.uci.edu/dataset/174/parkinsons">UCI Machine Learning</a>
    
**Notebook:** [Link](https://github.com/Kmohamedalie/Oxford-Parkinson-Diesease-Detection/blob/master/Notebook/Parkinson's%20Oxford%20-%20SnapML(Random%20Forest%20vs%20Boosting%20Machine).ipynb)

<br>

### **Additional Information**
This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from these individuals ("name" column). 

The data is in ASCII CSV format. The rows of the CSV file contain an instance corresponding to one voice recording. There are around six recordings per patient, the name of the patient is identified in the first column.For further information or to pass on comments, please contact Max Little (littlem '@' robots.ox.ac.uk).


<br>

### **Additional Information**
Matrix column entries (attributes): <br>
name - ASCII subject name and recording number <br>
MDVP:Fo(Hz) - Average vocal fundamental frequency <br>
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency <br>
MDVP:Flo(Hz) - Minimum vocal fundamental frequency  <br>
MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency <br>
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude <br>
NHR,HNR - Two measures of ratio of noise to tonal components in the voice     <br>
status - Health status of the subject (one) - Parkinson's, (zero) - healthy  <br>
RPDE,D2 - Two nonlinear dynamical complexity measures                          <br>
DFA - Signal fractal scaling exponent  <br>
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation
