# Music-Genre-Classification using Machine Learning and Deep Learning

## Dataset
For this classification I am using GTZAN dataset.
This dataset can be accessed using the following link.
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

This dataset consists music samples of 10 different genres which are of duration 30sec. In addition to the music samples this dataset also has the extracted features of the music samples in the csv format.

The data records are evenly distributed i.e., each genre has the same number of samples. So we are dealing with balanced dataset. The distribution of the classes can be easily understood by the following bar graph.

![image](https://user-images.githubusercontent.com/52078988/209738146-9e23b19f-3390-45b1-b213-dbfaea3eddd7.png)

## Packages used
1. pandas
2. numpy
3. seaborn
4. matplotlib
5. glob
6. IPython
7. librosa
8. sklearn
9. xgboost
10. tensorflow
11. keras

If any of the package is not present in your environment you can download it with the following command

```
!pip install <name of the package>
```
Run this code in the jupyter notebook to install the package.

## Process to run the code
1. Once all the packages are ready, download/clone the repository and open the notebook.
2. Download the dataset from - https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
3. Note the file locations used to read the file should be changed according to files location in your system.
4. Run all the cells one by one and you can all done.


## Algorithms used in this project

### Machine Learning Algorithms
1. GaussianNB
2. BernoulliNB
3. KNeighborsClassifier
4. DecisiontreeClassifier
5. RandomForestClassifier
6. XGBClassifier

### Deep Neural Network
![image](https://user-images.githubusercontent.com/52078988/209738683-53145584-6aa6-4c48-ace5-94935deff0dc.png)

## Results
![image](https://user-images.githubusercontent.com/52078988/209738710-894c22fc-72ee-4dc5-8540-7cf541285597.png)
So the best performing algorithm is XGBoost with an accuracy of 89.2%

The DNN has given much better accuracy which is of 92.3%

So for this project DNN gave us more accurate result when compared to other ML algorithms.


## Future Scope
The ML algorithms used in this project are the basic versions that the libraries provide. These can be experimented with hyper parameter tuning and find the best performing model to get better accuracy.
The structure of the DNN can be changed and experimented to develop the accuracy.

