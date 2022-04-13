# Robustness-of-Electrocardiogram-ECG-Signal-Quality-Indices

## Step-1: Download all data from the given link and extracted zip file.

- ECG-ID dataset: https://physionet.org/content/ecgiddb/1.0.0/
- Tele ECG dataset: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2FQTG0EP&version=&q=&fileAccess=&fileTag=&fileSortField=&fileSortOrder=
-  BIDMC Dataset: https://physionet.org/content/bidmc/1.0.0/
- MIT/BIH arrhythmia dataset: https://physionet.org/content/mitdb/1.0.0/
- CINC 2011 dataset: SET_a: https://physionet.org/content/challenge-2011/1.0.0/
- CINC 2014 dataset: set_p: https://physionet.org/content/challenge-2014/1.0.0/

## Step-2:  Download and extracted zip file from this repository
- Load .mat file in matlab
    -   Example for BIDMC datasets
    -   ![Screenshot](load_mat.JPG)
    -    ![Screenshot](mat_workplace.JPG)
- There are one array:
    - label_of_data,[ binary array with zeros and ones]
    - Zero means noise-free ECG and ones means noisy ECG data
---
## Step-3: Read the file from step-1 data folder according to the Step-2 data folder and subject name
---
## If you find it is useful and used for publication. Please kindly cite our work as:

```latex
@article{Rahman2022,
abstract = {Electrocardiogram (ECG) signal quality indices (SQIs) are essential for improving diagnostic accuracy and reliability of ECG analysis systems. In various practical applications, the ECG signals are...},
author = {Rahman, Saifur and Karmakar, Chandan and Natgunanathan, Iynkaran and Yearwood, John and Palaniswami, Marimuthu},
doi = {10.1098/RSIF.2022.0012},
file = {:C$\backslash$:/Users/msrahman/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Rahman et al. - 2022 - Robustness of electrocardiogram signal quality indices.pdf:pdf},
issn = {1742-5662},
journal = {Journal of the Royal Society Interface},
keywords = {SQA,cardiovascular diseases,electrocardiogram,signal quality indices,statistical signal quality indices,threshold‌},
mendeley-groups = {sensor},
month = {apr},
number = {189},
publisher = {
The Royal Society
},
title = {{Robustness of electrocardiogram signal quality indices}},
url = {https://royalsocietypublishing.org/doi/full/10.1098/rsif.2022.0012},
volume = {19},
year = {2022}
}
```
