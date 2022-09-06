Exploratory analysis of ECG data provided by Physionet

The exercise can be found in the file Exercise_ECG.ipynb.
The exercise is done by using the signal corresponding to the patient002, but the code can be modified to use any other patient.
Anyways, the patient data use in the file are provided in the repository.

The patients data can be downloaded by launching the following in a shell terminal:

```
wget -r -N -c -np https://physionet.org/files/ptbdb/1.0.0/ 
```

The result of that command would download the folder ptb-diagnostic-ecg-database-1.0.0 with all the data patients. To be able to run the Colab notebook, this folder has to be placed in a Google Drive folder in the following path:

/MyDrive/ECG/ptb-diagnostic-ecg-database-1.0.0
