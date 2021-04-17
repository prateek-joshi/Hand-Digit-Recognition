# Hand Digit Recognition
## Dataset
The [dataset](https://www.kaggle.com/ardamavi/sign-language-digits-dataset/download) used was downloaded from the [Kaggle](https://www.kaggle.com) website, which contains two *.npy* files.
 
![image](https://user-images.githubusercontent.com/70139937/115114670-22afbb00-9fae-11eb-9f25-d13a17e83add.png)
 
Images are 64x64 grayscale.

Load dataset as:
```
data = np.load('/path-to-repo/Hand-Digit-Recognition/X.npy')
label = np.load('/path-to-repo/Hand-Digit-Recognition/Y.npy')
```
