
This dataset contains the dynamic analysis of 582 samples of ransomware and 942 of good applications (goodware), i.e. 1524 samples in total.The dataset was retrieved and analysed with Cuckoo Sandbox at the end of February 2016. Further details about the dataset can be found in the paper (see below).

Please, reference our work when using this dataset:

Daniele Sgandurra, Luis Muñoz-González, Rabih Mohsen, Emil C. Lupu. "Automated Dynamic Analysis of Ransomware: Benefits, Limitations and use for Detection." arXiv preprint arXiv:1609.03020, 2016.

For BIBTEX you can use this:

@article{sgandurra2016,
  title={{Automated Dynamic Analysis of Ransomware: Benefits, Limitations and use for Detection}},
  author={Sgandurra, Daniele and Mu{\~n}oz-Gonz{\'a}lez, Luis and Mohsen, Rabih and Lupu, Emil C},
  journal={arXiv preprint arXiv:1609.03020},
  year={2016}
}


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
RANSOMWARE FAMILIES
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

The Ransomware samples belong to different families that are identified with the following codes:

FAMILY NAME          ID
------------------------------
Goodware              0
'Critroni'            1
'CryptLocker'         2
'CryptoWall'          3
'KOLLAH'              4
'Kovter'              5
'Locker'              6
'MATSNU'              7
'PGPCODER'            8
'Reveton'             9
'TeslaCrypt'         10
'Trojan-Ransom'      11

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
SETS OF FEATURES
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
The different sets of features are identified with the following codes (see also VariableNames.txt):

ID          Description
---------------------------------
API         API invocations
DROP        Extensions of the dropped files
REG         Registry key operations
FILES       File operations
FILES_EXT   Extension of the files involved in file operations
DIR         File directory operations
STR         Embedded strings

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
IDS of the Software analysed
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

The file IDS.txt contains the correspondence of the local IDS we use in our dataset with the SHA1 and MD5
of the software analysed (both goodware and ransomware). The description of the header in that file is 
the following:

- ID: local identifier used in our dataset.
- SHA1: SHA1 hash identifier for the software.
- MD5: MD5 hash identifier for the software.
- Ransomware: 1 if it's ransomware / 0 for Goodware.
- Ransomware_Family: numeric identifier for the ransomware family (same codification as explained above).

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++