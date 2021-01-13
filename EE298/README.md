# EE 298 Project
# PCA-GMM on STL10 Dataset

## Notes
Due to the slow download of the dataset from external libraries, the dataset was downloaded from source and loaded manually. The program will potentially produce and error 


## Instructions
1. In your working directory create a folder named '__datasets__'
2. Go inside the datasets folder:
```
cd datasets
```
2. Download the raw dataset from:  [Standford Archive](https://ai.stanford.edu/~acoates/stl10/) or [Mega](https://mega.nz/folder/vJ0E0axB#_7V6zzfNJNBLzy0YdwkFqw). Mega link might be faster due to bandwidth limitations on academic sites.

3. Extract the contents of the previously downloaded file to the datasets folder.
4. Your working directory should now look like the following:

```
Current Working Directory
|
|--datasets
|       |---stl10_binary
|                     |-class_names.txt
|                     |-fold_indices.txt
|                     |-test_X.bin
|                     |-test_y.bin
|                     |-train_X.bin
|                     |-train_y.bin
|--Javier_EE298_STL10.ipynb

```

5. Follow further instructions in the notebook to run the program. 