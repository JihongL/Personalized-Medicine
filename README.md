## Personalized Medicine
- Multiclass classification based on text data
- https://www.kaggle.com/c/msk-redefining-cancer-treatment
- 15th on Public leaderboard (log loss 0.59379, 26th Sep)
- [view jupyter notebook](http://nbviewer.jupyter.org/github/JihongL/Personalized-Medicine/blob/master/Personal_Medicine.ipynb)

### Dataset
- The clinical evidence used to classify the genetic mutation

|Set|Rows|Columns|
|:---:|:---:|:---:|
|Train_vari|3321|4|
|Train_text|3321|2|
|Test_vari|5668|3|
|Test_text|5668|2|

#### Independent Values
|Index|Values|Type|Description|
|:---:|:---:|:---:|:---|
|1|ID|Category|Individual ID|
|2|Gene|Category|264 variables|
|3|Variation|Category|2996 variables|
|4|Text|Category|3321 variables|

#### Dependent Value
|Index|Values|Type|Description|
|:---:|:---:|:---:|:---|
|1|Class|Cetegory|9 variables|
