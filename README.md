# AIA_taiwan_southern_2nd
臺灣人工智慧學校(AIA)南部分校技術班第二期

## Kaggle 競賽 - DNN Classifier for Forest Type

### Data [[source]](https://www.kaggle.com/jeonghunyoon/dnn-classifier-for-forest-type/data)
The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. Each observation is a 30m x 30m patch. You are asked to predict an integer classification for the forest cover type. 

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
      
## Project : TBD   
