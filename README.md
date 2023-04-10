# FAITH_Plus

This is the code for the paper Learning Hierarchical Task Structures for Few-shot Graph Classification


### Requirement:
torch==1.8.1



### Code Runing:
Run the command: 
`unzip data.zip`

Notice that the data.zip file includes five datasets used in our paper: Coil, ENZYMES, Letter_high, Reddit, and TRIANGLES. Another dataset R52 is too large to be put in the file. You can find it here 


Then run the command:
`python train.py`

To switch the dataset, modify the "datasets" variable in line 1192 of train.py.



