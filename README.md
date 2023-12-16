# NTX2023
Data-Challenge!!

The current data challenge is to build a Multi-Label Classification Model that classifies EEG input data by the help of it's labelled BioMarkers.
The data is a Sleep-study data collected from 4 subjects over one night/participant. The data is is cleaned and labelled for 2 subjects that represents the data into 16 columns: 

1. Timestamps
2. Epoch's (30sec = 1)
3. & Bio-markers = Sleepspindles, K-Complex, REM, Sleep onset, Sleep offset, Arousal, and Microsleep.

Each Bio-marker is one-hot encoded. These bio-markers are used to label the data and are imbalances among these labels.

Data from subject 2 & 3 were used to train the machine learning model
Data (Unlabelled) from subejct 4 was used to test the model.
The Model is validated with Subject 1's data.
