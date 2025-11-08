# "You Snooze You Win" Challenge

Tackled a past [PhysioNet/Computing in Cardiology (CinC) Challenge](https://www.physionet.org/challenge/) on the classification of nonarousal and arousal time frames. Check out PhysioNet's [introduction](https://physionet.org/content/challenge-2018/1.0.0/) of the challenge for additional details.

<ins>Objective</ins>: classify non arousal and arousal time frames into 5 classes (Arousal, NREM1, NREM2, NREM3, REM)

<ins>Data</ins>: obtained from  Massachusetts General hospital’s (MGH) Computational Clinical Neurophysiology Laboratory and the Clinical Data Animation Laboratory (CDAC)
Each sample consists of 7 physiological signals measured at 200 Hz over 60 seconds 
02-M1, E1-M2, Chi1-Chin2, ABD, CHEST, AIRFLOW, ECG 

Implemented cross validation (K-Fold Validation) to reduce overfitting, and experimented with different methods of feature extraction.


