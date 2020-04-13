Software Libraries:
Keras with Tensorflow Backend, Python 3.6, 

Dataset: 
Too large to include, download from here https://github.com/rkadlec/ubuntu-ranking-dataset-creator
Once downloaded - if you want to repeat the pre-processing process, uncomment prepare_data call in keras_dual_encoder

To train:
Uncomment out the fit method in keras_dual_encoder.py

The final solution can be printed by changing the single encoders output_dim=50 and LSTM units = 50 instead of 20 and loading the final_solutuion.hd5, I have kept the test.pkl
so that this can occur without data download and preparation
EDIT: This is not possible due to file size. 