
# Project Title

Car Damage Detection







## Installation

Install File from Google Drive Link

Train Data = 'https://drive.google.com/drive/folders/18_3G_c49punpzjPvnhNB0DN-RAwkZfLE?usp=sharing'

Test Data = 'https://drive.google.com/drive/folders/1JdLukt1x4LgIZHxZ3n0LDUSs95oTe2tO?usp=sharing'

Pretrained Model1 = 'https://drive.google.com/file/d/1R-JCX4s9qQulMTVnxR7aDxCeX0RVEaw5/view?usp=sharing'

Pretrained Model2 = 'https://drive.google.com/file/d/12pnHm9MEuw3prpRZRur6ddN9iV3vc8Vy/view?usp=sharing'



    
## Features

- This is a project on predicting Car Damage which is a Multi-label classification problem of Deep Learning.
- We have use tensorflow, keras, sklearn, tqdm, numpy, pandas Library to accomplish our task.
- we are mainly focused on 6 classes of Damages.i.e. dent, glass_shatter, head_lamp, scratch, tail_lamp, unknown
- There is a column in trained data set is Extent of Damage in between 0,1,2,3 scale.
- We used Pre-trained DenseNet201 model weights to transfer learning purpose. since we have 801 training data and 300 test data.
- Here Trianing time of model is large therfore I am attaching model1.h5 file which is trained for our task. Now, we can directly import weights.
- Similarly model2.h5 file is trained for finding Extent of Damage. It is used for 4 class Classification task.
- I have attahed Model1.code file to understande how We use pretrained model.
## Results

- After training on the dataset we have achived 74% accuracy in classifing the class of damage.
- We achived 84% accuracy for predicting Extent of damage of validation Dataset.


