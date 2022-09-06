Exploratory analysis of ECG data provided by Physionet

The exercise can be found in the file Exercise_ECG.ipynb. The folder ptb-diagnostic-ecg-database-1.0.0 includes two of the patients of the whole sample.
The exercise is done by using the signal corresponding to the patient002.

In order to test the exercise with other patients, the whole patients data can be downloaded by launching the following in a shell terminal:

```
wget -r -N -c -np https://physionet.org/files/ptbdb/1.0.0/ 
```

The result of that command would download the folder ptb-diagnostic-ecg-database-1.0.0 with all the data patients. 

The exercise is provided in a jupyter notebook with a link to a google colab running environment. It can be replicated either locally (by cloning the repository, ignoring the second code tab and then writing the path to https://physionet.org/files/ptbdb/1.0.0/) or online. 

To be able to run the Colab notebook online, either the folder provided in the repository or the full physionet download described above have to be placed in a Google Drive folder in the following path:

/MyDrive/ECG/ptb-diagnostic-ecg-database-1.0.0

