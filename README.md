## <p align="center">Functional Connectivity Fingerprints at Rest are Similar Across Youths and Adults and Vary with Genetic Similarity</p>    
<p align="center"> Scripts and other resources for replication of this work</p>   

[doi/link goes here once accepted](http://github.com/iamdamion)

---
### Scripts:
- Main SVM Classifier Script: Twin_Match.py   
- SVM Using Opposite Group Features Script: Opposite_Mask_SVM.py   

- Requirements: (Unfortunately) these scripts are written in python 2.7. Other requirements:
```
numpy
scipy
sklrean
pandas
seaborn
matplotlib
```
- Timecourse files should be in a group folder, with each pair given a family ID, then an individual ID separated with an underscore. Example with two "family" pairs. Family 201 and family 202:
```
/MZ_TWINS/
         /201_1.txt
         /201_2.txt
         /202_1.txt
         /202_2.txt
         /etc
```
- Beyond this, see the -h (help) argument in the scripts for full details of required arguments. 
- See in-code comments for notes about each step, etc. (I try to heavily comment my code....probably too much to be honest).

---
### Required Playlist:
The following playlist was used for data cleaning.
1.
2.
3.
4.
5.
6.
7.
8.
9.
10.




