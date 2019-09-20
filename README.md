# AIA_taiwan_southern_2nd
臺灣人工智慧學校(AIA)南部分校技術班第二期

## Kaggle 競賽 - DNN Classifier for Forest Type

### Data 
The dataset is just subset from this [[source]](https://www.kaggle.com/jeonghunyoon/dnn-classifier-for-forest-type/data)
Original source has >50000 instances. Here we just use partial (~15000 instances) .

### Method
1. Kaggle_NN_85.ipynb [[ipynb]](Kaggle_NN_85.ipynb)
  - Enviroment
      - tensorflow-gpu==1.14.0
      - Keras==2.0
  - Model
      - DNN (fully-connected NN)
  - Result
      - Train set: ~90%
      - Test set: ~85%
      
2. Kaggle_NN_NSL_87.ipynb [[ipynb]](Kaggle_NN_NSL_87.ipynb)
  - Enviroment
      - tensorflow-gpu==1.14.0
      - neural_structured_learning==1.0.0
  - Model
      - DNN (fully-connected NN): totally the same with "Kaggle_NN_85.ipynb", but **add NSL scheme**
      - More about NSL, please refer to https://www.tensorflow.org/neural_structured_learning (2019/09 released) . 
   - Result
      - Train set: ~91%
      - Test set: ~87%     
      
