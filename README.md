**SuccKD_MultiSpecies**: A novel approach exploiting Multi-Teacher Knowledge Distillation and Word Embedding for Cross-Species Prediction of Protein Succinylation Sites.

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

       ![dataset](https://github.com/user-attachments/assets/62b6edef-2c35-4b48-97b6-427eb802fbd5)


**Model Learning**

  We use Google colab pro buid this model
      Cross validation: CV_Generics_KD2_Succi.ipynb
      Train model: Generic_ KD2_Succi.ipynb. 
  Model saved and named: KD2_Succi.h5. You can use KD2_Succi.h5 in the Model folder for predicting and independent testing.
  Independent test and predict files are located in the Code_KD2_Succi _Generic_predict_Species folder:

      No.	 Codes using 2teacher_1student.h5 model to predict nine species	Species
      1	    predict_H.Sapien_from_Generic.ipynb	H.sapiens
      2	    predict_H.capsulatum_from_Generic.ipynb	H.capsulatum
      3	    predict_M.musculus_from_Generic.ipynb	M.musculus
      4	    predict_E.coli_from_Generic.ipynb	E.coli
      5	    predict_M.tuberculosis_from_Generic.ipynb	M.tuberculosis
      6	    predict_S. cerevisiae_from_Generic.ipynb	S.cerevisiae
      7	    predict_T.gondii_from_Generic.ipynb	T.gondii
      8	    predict_S.lycopersicum_from_Generic.ipynb	S.lycopersicum
      9	    predict_T.eastivum_from_Generic.ipynb	T.aestivum

**Contact**

Please feel free to contact us if you need any help: nvnui@ictu.edu.vn

