# Chlamy-EnPhosSite

Chlamy-EnPhosSite: A deep learning-based approach for Chlamydomonas reinhardtii-specific phosphorylation site prediction. Developed in KC lab by Niraj Thapa.
# Requirement
  Backend = Tensorflow <br/>
  Keras <br/>
  Numpy <br/>
  Biopython <br/>
  Sklearn <br/>
  Imblearn <br/>
 # Files extraction
 Extract using winrar or any application that support *.rar files. Start with chlamy.part01. Place all files in same folder.
 # Dataset
 Dataset is in FASTA format which includes protein window size of 57. Both training and test datasets are provided. There are two dataset for positive and negative examples.
 # Model
 There are two models included. Multi-window based model(Chlamy-MwPhosSite) and ensemble stacking based model (Chlamy-EnPhosSite).The pretrained model file with format *.h5 is included.  
 # Prediction for given test dataset
 With all the prerequisite installed, run -> model_multi.py to run Chlamy-MwPhosSite or run -> model_stacking.py to run Chlamy-EnPhosSite respectively.
 # Prediction for your dataset
 The format should be same as the test dataset which is basically FASTA format. Input fasta file should have window size of 57 and added to test dataset portion in the model code. 
 # Contact 
 Feel free to contact us if you need any help : nirajthapa@gmail.com, dukka.kc@wichita.edu
