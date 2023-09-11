# FAITH+

This is the code for the paper Learning Hierarchical Task Structures for Few-shot Graph Classification


### Requirement:
torch==1.8.1



### Code Runing:
Run the command: 
`unzip data.zip`  
`unzip split.zip`

Notice that the data.zip file includes five datasets used in our paper: Coil, ENZYMES, Letter_high, Reddit, and TRIANGLES. Another dataset R52 is too large to be put in the file. We have provided the file [here](https://drive.google.com/file/d/1bNKPKgzlLxJb3bHQnBUCpDmy7E9Z4zvg/view?usp=share_link).


Then run the command:
`python train.py`

### Note:
1. To switch the dataset, modify the "datasets" variable in train.py.

2. To switch the baseline, modify the "baseline_mode" variable in train.py. Choices: ['proto', 'relation', 'WL', 'Graphlet'].
   

