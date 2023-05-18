# SigD: A Cross-Session Dataset for PPG-Based User Authentication in Different Demographic Groups


Detailed waveform(Open Access):  https://physionet.org/content/mimic3wdb-matched/1.0/  

Individual information(Need sign the Data Use Agreement): https://physionet.org/content/mimiciii/1.4/ 


**Extracted_signal_records.pl** : Extracted individual annotations.


``` py
Example of data structure:
[   ## Subject ID
    'p007809': [
        ## Acquisition time: YYYY-MM-DD-HH-mm
        '2136-08-31-17-33': [
            ## Acquisition time offset HH-mm-ss
            '29: 40: 10-30: 11: 50',
            '30: 18: 40-30: 24: 20',
            
        ],
        '2137-05-28-16-04': [
            '51: 26: 40-51: 29: 00'
        ],
        
    ]
]

```


**GetMIMIC-IIIdata.ipynb** : Code to get the dataset. 
