**KD_MultiSucc**: A framework that incorporates Multi-Teacher Knowledge Distillation and Word Embedding for Cross-Species Prediction of Protein Succinylation Sites

**Requirement**

    Goolge Colab pro
    Keras
    Numpy
    Sklearn
    Pandas
    Tensorflow

**Dataset**

    We have developed an architecture for predicting succinylation sites in both generic and cross-species contexts. 
    The dataset, sourced from SuccinSite2.0 [12] and GPSuc [10], mirrors their training and test sets to ensure consistency in model development and comparison. 
    It includes data from nine species: Homo sapiens (H.sapiens), Mus musculus (M.musculus), Escherichia coli (E.coli), Mycobacterium tuberculosis (M.tuberculosis), 
    Saccharomyces cerevisiae (S.cerevisiae), Toxoplasma gondii (T.gondii), Solanum lycopersicum (S.lycopersicum), and others.
![https://github.com/nuinvtnu/KD_MultiSucc/blob/main/Data/dataset_pic.PNG)](https://github.com/nuinvtnu/KD_MultiSucc/blob/main/Data/dataset_pic.PNG)


**Model Learning**

  We use Google colab pro buid this model
      Cross validation: CV_Generics_KD_MultiSucc.ipynb
      Train model: Generic_KD_MultiSucc.ipynb. 
  Model saved and named: KD_MultiSucc.h5. You can use KD_MultiSucc.h5 in the Model folder for predicting and independent testing.
  Independent test and predict files are located in the Code_KD_MultiSucc_Generic_predict_Species folder:

      No. Codes using KD_MultiSucc.h5 model to predict nine species	        Species
      1	  predict_H.Sapien_from_Generic.ipynb	                        H.sapiens
      2	  predict_H.capsulatum_from_Generic.ipynb	                   H.capsulatum
      3	  predict_M.musculus_from_Generic.ipynb	                        M.musculus
      4	  predict_E.coli_from_Generic.ipynb	                           E.coli
      5	  predict_M.tuberculosis_from_Generic.ipynb	                   M.tuberculosis
      6	  predict_S. cerevisiae_from_Generic.ipynb	                   S.cerevisiae
      7	  predict_T.gondii_from_Generic.ipynb	                        T.gondii
      8	  predict_S.lycopersicum_from_Generic.ipynb	                   S.lycopersicum
      9	  predict_T.eastivum_from_Generic.ipynb	                        T.aestivum

**Contact**

Please feel free to contact us if you need any help: nvnui@ictu.edu.vn

