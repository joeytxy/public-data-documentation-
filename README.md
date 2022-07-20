# Public Data Documentation

A collection of public healthcare datasets

Type of datasets include 

1. Tabular 
2. Images 
3. Free Text 
4. Audio 

Table of Contents 

1. [Cancer Datasets](#Cancer-Datasets)
    - [Breast Cancer Data set](#Breast-Cancer-Data-set)
    - [Breast Cancer Wisconsin (Original) Data Set](#Breast-Cancer-Wisconsin-Original-Data-Set)
    - [Breast Cancer Wisconsin (Prognostic) Data Set](#Breast-Cancer-Wisconsin-Prognostic-Data-Set)
    - [Breast Cancer Wisconsin (Diagnostic) Data Set](#Breast-Cancer-Wisconsin-Diagnostic-Data-Set)
    - [Colorectal Cancer Dataset](#Colorectal-Cancer-Dataset)
    - [Cervical cancer (Risk Factors) Data Set](#Cervical-cancer-Risk-Factors-Data-Set)
    - [Leukemia Classification](#Leukemia-Classification)
    - [Lung and Colon Cancer Histopathological Images](#Lung-and-Colon-Cancer-Histopathological-Images)
    - [Skin Cancer MNIST: HAM10000](#Skin-Cancer-MNIST-HAM10000)
    - [Thoracic Surgery Data Data Set](#Thoracic-Surgery-Data-Data-Set)

2. [Brain Related Datasets](#Brain-Related-Datasets)
    - [Brain tumor data](#Brain-tumor-data)
    - [MRI and Alzheimers](#MRI-and-Alzheimers)
    - [Stroke Prediction](#Stroke-Prediction)
    
3. [Eye Related Datasets](#Eye-Related-Datasets)
   - [Bajwa Hospital (Multi Eye Disease Dataset)](#Bajwa-Hospital-Multi-Eye-Disease-Dataset)
   - [Retinal OCT Images(optical coherence tomography)](#Retinal-OCT-Images-optical-coherence-tomography)

4. [Gastrointestinal Related Datasets](#Gastrointestinal-Related-Datasets)
   -  [Bowel Sounds](#Bowel-Sounds) 
   -  [Kvasir Dataset](#Kvasir-Dataset)

5. [Heart Related Datasets](#Heart-Related-Datasets)
    - [An Extensive Dataset for the Heart Disease Classification System](#An-Extensive-Dataset-for-the-Heart-Disease-Classification-System)
    - [Heart Failure Prediction](#Heart-Failure-Prediction)

6. [Kidney Related Datasets](#Kidney-Related-Datasets)
    - [A Brazilian dataset for screening the risk of the Chronic Kidney Disease](#A-Brazilian-dataset-for-screening-the-risk-of-the-Chronic-Kidney-Disease)
    - [Risk Factor prediction of Chronic Kidney Disease Data Set](#Risk-Factor-prediction-of-Chronic-Kidney-Disease-Data-Set)

7. [Lung Related Datasets](#Lung-Related-Datasets)
    - [A dataset of lung sounds recorded from the chest wall using an electronic stethoscope](#A-dataset-of-lung-sounds-recorded-from-the-chest-wall-using-an-electronic-stethoscope)
    - [NIH Chest X-ray Dataset](#NIH-Chest-X-ray-Dataset) 
    - [Chest X-ray Images Pneumonia](#Chest-X-ray-Images-Pneumonia)
    - [QaTa COV19 Dataset](#QaTa-COV19-Dataset)
    - [Respiratory Sound Database](#Respiratory-Sound-Database)

8. [Others](#Others) 
    - [Chula RBC-12-Dataset](#Chula-RBC-12-Dataset)
    - [Coswara Dataset](#Coswara-Dataset)
    - [CT Medical Images](#CT-Medical-Images)  
    - [Association of body mass index and age with incident diabetes in Chinese adults](Association-of-body-mass-index-and-age-with-incident-diabetes-in-Chinese-adults)
    - [Clinical characteristics, types and complications of diabetics with young age at the onset](#Clinical-characteristics-types-and-complications-of-diabetics-with-young-age-at-the-onset)
    - [Diabetes 130-US hospitals for years 1999-2008 Data Set](#Diabetes-130-US-hospitals-for-years-1999-2008-Data-Set) 
    - [Diabetic Retinopathy Debrecen Data Set Data Set](#Diabetic-Retinopathy-Debrecen-Data-Set-Data-Set)
    - [Early Classification of Diabetes](#Early-Classification-of-Diabetes)
    - [Fetal Health Classification](#Fetal-Health-Classification)
    - [Lymphography Data Set](#Lymphography-Data-Set)
    - [Monkeypox Skin Lesion Dataset](#Monkeypox-Skin-Lesion-Dataset)
    - [Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set](#Parkinson-Speech-Dataset-with-Multiple-Types-of-Sound-Recordings-Data-Set)
    - [Parkinson Tappy Keystroke Data](#Parkinson-Tappy-Keystroke-Data)
    - [Patient Physician Medical Interviews](#Patient-Physician-Medical-Interviews) 
    
### Cancer Datasets

#### Breast Cancer Data set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer)
  -   Data Type: Text/Tabular 
  -   Size: 19 KB
  -   Example of data + Special Instructions(if any) 
      1. Download breast-cancer.data stored in Data Folder from Source 
      2. Example: CSV version
      
         <img width="652" alt="Screenshot 2022-07-14 at 4 33 48 PM" src="https://user-images.githubusercontent.com/66881214/178939273-d1810b64-d7c3-46ac-9ddd-bb9c076c89cb.png">
         
         Columns present (from left to right):
            
         * Class: no-recurrence-events, recurrence-events
         * age: 10-19, 20-29, 30-39, 40-49, 50-59, 60-69, 70-79, 80-89, 90-99.
         * menopause: lt40, ge40, premeno.
         * tumor-size: 0-4, 5-9, 10-14, 15-19, 20-24, 25-29, 30-34, 35-39, 40-44, 45-49, 50-54, 55-59.
         * inv-nodes: 0-2, 3-5, 6-8, 9-11, 12-14, 15-17, 18-20, 21-23, 24-26, 27-29, 30-32, 33-35, 36-39.
         * node-caps: yes, no.
         * deg-malig: 1, 2, 3.
         * breast: left, right.
         * breast-quad: left-up, left-low, right-up, right-low, central.
         * irradiat: yes, no.

  -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
            
      To download as .csv file, right click on breast-cancer.data as shown :
            
      <img width="698" alt="Screenshot 2022-07-14 at 4 44 53 PM" src="https://user-images.githubusercontent.com/66881214/178941770-0c1bf718-e4c1-4eb3-bc65-7e755211f723.png">
            
      Proceed to add the .csv extention in file name and save to desired location
            
      <img width="323" alt="Screenshot 2022-07-14 at 4 46 13 PM" src="https://user-images.githubusercontent.com/66881214/178942033-445f2292-c76f-4967-b090-2dc35f269737.png">

  -   Citations
      - This breast cancer domain was obtained from the University Medical Centre, Institute of Oncology, Ljubljana, Yugoslavia. Thanks go to M. Zwitter and M. Soklic for providing the data. Please include this citation if you plan to use this database.
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
      
#### Breast Cancer Wisconsin (Original) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29)
  -   Data Type: Text/Tabular 
  -   Size: 20 KB
  -   Example of data + Special Instructions(if any) 
      1. Download breast-cancer-wiscoinsin.data stored in Data Folder from Source 
      2. Example: CSV version
            
         <img width="718" alt="Screenshot 2022-07-14 at 6 11 27 PM" src="https://user-images.githubusercontent.com/66881214/178959171-12d41257-eadc-4bea-bedd-0f13b67adbbb.png">
         
         Columns present (from left to right):
         
         * Sample code number: id number
         * Clump Thickness: 1 - 10
         * Uniformity of Cell Size: 1 - 10
         * Uniformity of Cell Shape: 1 - 10
         * Marginal Adhesion: 1 - 10
         * Single Epithelial Cell Size: 1 - 10
         * Bare Nuclei: 1 - 10
         * Bland Chromatin: 1 - 10
         * Normal Nucleoli: 1 - 10
         * Mitoses: 1 - 10
         * Class: (2 for benign, 4 for malignant)
  
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       To download as .csv file, right click on breast-cancer-wiscoinsin.data as shown :
            
       <img width="700" alt="Screenshot 2022-07-14 at 5 58 13 PM" src="https://user-images.githubusercontent.com/66881214/178956694-8c413b09-d736-49be-9776-50b8a8a5db5d.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="322" alt="Screenshot 2022-07-14 at 5 58 32 PM" src="https://user-images.githubusercontent.com/66881214/178956742-b203502f-0e8d-4eae-b31b-02dc2da7d2ac.png">
         
  -   Citations
      - This breast cancer databases was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg. If you publish results when using this database, then please include this information in your acknowledgements. Also, please cite one or more of:
     
        1. O. L. Mangasarian and W. H. Wolberg: "Cancer diagnosis via linear programming", SIAM News, Volume 23, Number 5, September 1990, pp 1 & 18.
            
        2. William H. Wolberg and O.L. Mangasarian: "Multisurface method of pattern separation for medical diagnosis applied to breast cytology", Proceedings of the National Academy of Sciences, U.S.A., Volume 87, December 1990, pp 9193-9196.
            
        3. O. L. Mangasarian, R. Setiono, and W.H. Wolberg: "Pattern recognition via linear programming: Theory and application to medical diagnosis", in: "Large-scale numerical optimization", Thomas F. Coleman and Yuying Li, editors, SIAM Publications, Philadelphia 1990, pp 22-30.
            
        4. K. P. Bennett & O. L. Mangasarian: "Robust linear programming discrimination of two linearly inseparable sets", Optimization Methods and Software 1, 1992, 23-34 (Gordon & Breach Science Publishers).
       - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Breast Cancer Wisconsin (Prognostic) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Prognostic%29)
  -   Data Type: Text/Tabular 
  -   Size: 44 KB
  -   Example of data + Special Instructions(if any) 
      1. Download wpbc.data stored in Data Folder from Source 
      2. Example (No headers): 
       
            | 119513 | N | 31 | 18.02 | 27.6  | 117.5 | 1013 | 0.09489 | 0.1036 | 0.1086 | 0.07055 | 0.1865 | 0.06333 | 0.6249 | 1.89   | 3.972 | 71.55 | 0.004433 | 0.01421 | 0.03233 | 0.009854 | 0.01694 | 0.003495 | 21.63 | 37.08 | 139.7 | 1436 | 0.1195 | 0.1926 | 0.314  | 0.117  | 0.2677 | 0.08113 | 5 | 5     |
            | ------ | - | -- | ----- | ----- | ----- | ---- | ------- | ------ | ------ | ------- | ------ | ------- | ------ | ------ | ----- | ----- | -------- | ------- | ------- | -------- | ------- | -------- | ----- | ----- | ----- | ---- | ------ | ------ | ------ | ------ | ------ | ------- | - | ----- |
            | 8423   | N | 61 | 17.99 | 10.38 | 122.8 | 1001 | 0.1184  | 0.2776 | 0.3001 | 0.1471  | 0.2419 | 0.07871 | 1.095  | 0.9053 | 8.589 | 153.4 | 0.006399 | 0.04904 | 0.05373 | 0.01587  | 0.03003 | 0.006193 | 25.38 | 17.33 | 184.6 | 2019 | 0.1622 | 0.6656 | 0.7119 | 0.2654 | 0.4601 | 0.1189  | 3 | 2     |

         
         Columns present (from left to right):
         * ID number 
         * Outcome (R = recur, N = nonrecur)
         * Time (recurrence time if field 2 = R, disease-free time if field 2 = N)
         * Ten real-valued features are computed for each cell nucleus (Column 4 to Column 33):
           - radius (mean of distances from center to points on the perimeter)
           - texture (standard deviation of gray-scale values)
           - perimeter
           - area
           - smoothness (local variation in radius lengths)
           - compactness (perimeter^2 / area - 1.0)
           - concavity (severity of concave portions of the contour)
           - concave points (number of concave portions of the contour)
           - symmetry
           - fractal dimension ("coastline approximation" - 1)
            
            In other words, column 4 to column 13 represent the above 10 values for the first cell nucleus and so on. 
            
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       To download as .csv file, right click on wpbc.data as shown :
            
       <img width="909" alt="Screenshot 2022-07-14 at 9 07 11 PM" src="https://user-images.githubusercontent.com/66881214/178989493-b7de3cca-da5f-4598-83cb-a28838ec52e0.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="326" alt="Screenshot 2022-07-14 at 9 08 03 PM" src="https://user-images.githubusercontent.com/66881214/178989650-9b61aa22-48be-4c78-ad15-5d488fbbf0a7.png">
       
   -   Citations
       - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Breast Cancer Wisconsin (Diagnostic) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
  -   Data Type: Text/Tabular 
  -   Size: 124 KB
  -   Example of data + Special Instructions(if any) 
      1. Download wdbc.data stored in Data Folder from Source 
      2. Example(No headers): 

            | 842302 | M | 17.99 | 10.38 | 122.8 | 1001 | 0.1184  | 0.2776  | 0.3001 | 0.1471  | 0.2419 | 0.07871 | 1.095  | 0.9053 | 8.589 | 153.4 | 0.006399 | 0.04904 | 0.05373 | 0.01587 | 0.03003 | 0.006193 | 25.38 | 17.33 | 184.6 | 2019 | 0.1622 | 0.6656 | 0.7119 | 0.2654 | 0.4601 | 0.1189  |
            | ------ | - | ----- | ----- | ----- | ---- | ------- | ------- | ------ | ------- | ------ | ------- | ------ | ------ | ----- | ----- | -------- | ------- | ------- | ------- | ------- | -------- | ----- | ----- | ----- | ---- | ------ | ------ | ------ | ------ | ------ | ------- |
            | 842517 | M | 20.57 | 17.77 | 132.9 | 1326 | 0.08474 | 0.07864 | 0.0869 | 0.07017 | 0.1812 | 0.05667 | 0.5435 | 0.7339 | 3.398 | 74.08 | 0.005225 | 0.01308 | 0.0186  | 0.0134  | 0.01389 | 0.003532 | 24.99 | 23.41 | 158.8 | 1956 | 0.1238 | 0.1866 | 0.2416 | 0.186  | 0.275  | 0.08902 |

            
         Columns present (from left to right):
         * ID number 
         * Diagnosis (M = malignant, B = benign)
         * Ten real-valued features are computed for each cell nucleus (Column 3 to Column 32):
           - radius (mean of distances from center to points on the perimeter)
           - texture (standard deviation of gray-scale values)
           - perimeter
           - area
           - smoothness (local variation in radius lengths)
           - compactness (perimeter^2 / area - 1.0)
           - concavity (severity of concave portions of the contour)
           - concave points (number of concave portions of the contour)
           - symmetry
           - fractal dimension ("coastline approximation" - 1)
            
            In other words, column 3 to column 12 represent the above 10 values for the first cell nucleus and so on. 
            
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       To download as .csv file, right click on wdbc.data as shown :
            <img width="915" alt="Screenshot 2022-07-14 at 11 08 42 PM" src="https://user-images.githubusercontent.com/66881214/179015321-d168c542-291a-40af-8b6c-1703ce17a751.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="322" alt="Screenshot 2022-07-14 at 11 09 00 PM" src="https://user-images.githubusercontent.com/66881214/179015383-cdb7a990-cc67-47ec-ac68-3e1390ac657e.png">

       
   -   Citations
       - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Colorectal Cancer Dataset

  - Source:  [Click here to proceed to site](https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest/download/)
  - Data Type: Images 
  -   Size: 259.4MB
  -   Example of data + Special Instructions(if any) 
      1. Download by clicking 'Warwick-QU-dataset' on Source
      2. Example: 
         
         train_1.bmp (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179518421-dfb0da1b-3f34-480f-93c0-5d514a96ed7d.jpg" width="150" height="150">
         
         Each image will have its corresponding annotated image (filename_anno.bmp) and its grade in the Grade.csv file as shown:
         
         train_1_anno.bmp : <img src="https://user-images.githubusercontent.com/66881214/179518541-ffbe18d2-303f-4220-9378-5dc5be06f0e5.jpg" width="150" height="150">
         
         
         Grade: <img width="582" alt="Screenshot 2022-07-18 at 9 12 13 PM" src="https://user-images.githubusercontent.com/66881214/179518739-e211b4ea-69d4-4665-ac15-01ae2f2d97d1.png">

  - Note: 
  
    Comment regarding the annotated images can be found in the Q&A section in the same source link. A screenshot is attached below: <img width="511" alt="Screenshot 2022-07-18 at 9 16 42 PM" src="https://user-images.githubusercontent.com/66881214/179519661-a5465462-7033-479e-a641-9cae3c5889f8.png">
  
  - Citations
    - K. Sirinukunwattana, J. P. W. Pluim, H. Chen, X Qi, P. Heng, Y. Guo, L. Wang, B. J. Matuszewski, E. Bruni, U. Sanchez, A. Böhm, O. Ronneberger, B. Ben Cheikh, D. Racoceanu, P. Kainz, M. Pfeiffer, M. Urschler, D. R. J. Snead, N. M. Rajpoot, "Gland Segmentation in Colon Histology Images: The GlaS Challenge Contest" [Link](http://arxiv.org/abs/1603.00275)
    - K. Sirinukunwattana, D.R.J. Snead, N.M. Rajpoot, "A Stochastic Polygons Model for Glandular Structures in Colon Histology Images," in IEEE Transactions on Medical Imaging, 2015
doi: 10.1109/TMI.2015.2433900 

#### Cervical cancer (Risk Factors) Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29)
  - Data Type: Tabular 
  -   Size: 102 KB
  -   Example of data + Special Instructions(if any) 
      1. Download risk_factors_cervical_cancer.csv from Data Folder from Source 
      2. Example: 
           
            | Age | Number of sexual partners | First sexual intercourse | Num of pregnancies | Smokes | Smokes (years) | Smokes (packs/year) | Hormonal Contraceptives | Hormonal Contraceptives (years) | IUD | IUD (years) | STDs | STDs (number) | STDs:condylomatosis | STDs:cervical condylomatosis | STDs:vaginal condylomatosis | STDs:vulvo-perineal condylomatosis | STDs:syphilis | STDs:pelvic inflammatory disease | STDs:genital herpes | STDs:molluscum contagiosum | STDs:AIDS | STDs:HIV | STDs:Hepatitis B | STDs:HPV | STDs: Number of diagnosis | STDs: Time since first diagnosis | STDs: Time since last diagnosis | Dx:Cancer | Dx:CIN | Dx:HPV | Dx | Hinselmann | Schiller | Citology | Biopsy |
            | --- | ------------------------- | ------------------------ | ------------------ | ------ | -------------- | ------------------- | ----------------------- | ------------------------------- | --- | ----------- | ---- | ------------- | ------------------- | ---------------------------- | --------------------------- | ---------------------------------- | ------------- | -------------------------------- | ------------------- | -------------------------- | --------- | -------- | ---------------- | -------- | ------------------------- | -------------------------------- | ------------------------------- | --------- | ------ | ------ | -- | ---------- | -------- | -------- | ------ |
            | 18  | 4                         | 15                       | 1                  | 0      | 0              | 0                   | 0                       | 0                               | 0   | 0           | 0    | 0             | 0                   | 0                            | 0                           | 0                                  | 0             | 0                                | 0                   | 0                          | 0         | 0        | 0                | 0        | 0                         | ?                                | ?                               | 0         | 0      | 0      | 0  | 0          | 0        | 0        | 0      |
            | 15  | 1                         | 14                       | 1                  | 0      | 0              | 0                   | 0                       | 0                               | 0   | 0           | 0    | 0             | 0                   | 0                            | 0                           | 0                                  | 0             | 0                                | 0                   | 0                          | 0         | 0        | 0                | 0        | 0                         | ?                                | ?                               | 0         | 0      | 0      | 0  | 0          | 0        | 0        | 0      |


            
         Columns present (from left to right):
         * Age
         * Number of sexual partners
         * First sexual intercourse (age)
         * Num of pregnancies
         * Smokes
         * Smokes (years)
         * Smokes (packs/year)
         * Hormonal Contraceptives
         * Hormonal Contraceptives (years)
         * IUD
         * IUD (years)
         * STDs
         * STDs (number)
         * STDs:condylomatosis
         * STDs:cervical condylomatosis
         * STDs:vaginal condylomatosis
         * STDs:vulvo-perineal condylomatosis
         * STDs:syphilis
         * STDs:pelvic inflammatory disease
         * STDs:genital herpes
         * STDs:molluscum contagiosum
         * STDs:AIDS
         * STDs:HIV
         * STDs:Hepatitis B
         * STDs:HPV
         * STDs: Number of diagnosis
         * STDs: Time since first diagnosis
         * STDs: Time since last diagnosis
         * Dx:Cancer
         * Dx:CIN
         * Dx:HPV
         * Dx
         * Hinselmann: target variable
         * Schiller: target variable
         * Cytology: target variable
         * Biopsy: target variable
  - Note: NA
  - Citations
    - Kelwin Fernandes, Jaime S. Cardoso, and Jessica Fernandes. 'Transfer Learning with Partial Observability Applied to Cervical Cancer Screening.' Iberian Conference on Pattern Recognition and Image Analysis. Springer International Publishing, 2017.
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Leukemia Classification 

- Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification)  
- Data Type: Images 
-   Size: 10.42GB   
-   Example of data + Special Instructions(if any) 
      1. Download from Source
      2. Example: 
 
         Acute lymphoblastic leukemia (ALL): <img src="https://user-images.githubusercontent.com/66881214/179482213-1aec30af-9390-4f52-b582-7916ab44ce50.jpg" width="150" height="150">
         
         Normal (Images in hem folder): <img src="https://user-images.githubusercontent.com/66881214/179482557-ae81cbe2-037b-4ae7-a138-d6669c7c2019.jpg" width="150" height="150">

  - Note: Labels for images in validation_data can be found in the csv file that is stored in the same folder. 

    For example: 
    
    1.bmp (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179483000-488156a0-9a80-44b8-8081-175e8a96f229.jpg" width="150" height="150"> 
    
    The label for this image can be found in its corresponding row in the csv file. The image file name will be the value of new_names in the csv file as shown below (second column):  
    
    <img width="291" alt="Screenshot 2022-07-18 at 5 28 01 PM" src="https://user-images.githubusercontent.com/66881214/179483054-360c06f1-4890-41de-ba67-bcb247de6af8.png">
    
    The labels for the testing data was not given. [Click here for more information](https://competitions.codalab.org/competitions/20395#learn_the_details-overview)

  - Citations
    - Gupta, A., & Gupta, R. (2019). ALL Challenge dataset of ISBI 2019 [Data set]. The Cancer Imaging Archive. [Link](https://doi.org/10.7937/tcia.2019.dc64i46r)
    - Publication Citation (if required): 
      - Anubha Gupta, Rahul Duggal, Ritu Gupta, Lalit Kumar, Nisarg Thakkar, and Devprakash Satpathy, “GCTI-SN: Geometry-Inspired Chemical and Tissue Invariant Stain Normalization of Microscopic Medical Images,”, under review. Ritu Gupta, Pramit Mallick, Rahul Duggal, Anubha Gupta, and Ojaswa Sharma, "Stain Color Normalization and Segmentation of Plasma Cells in Microscopic Images as a Prelude to Development of Computer Assisted Automated Disease Diagnostic Tool in Multiple Myeloma," 16th International Myeloma Workshop (IMW), India, March 2017.
      - Rahul Duggal, Anubha Gupta, Ritu Gupta, Manya Wadhwa, and Chirag Ahuja, “Overlapping Cell Nuclei Segmentation in Microscopic Images UsingDeep Belief Networks,” Indian Conference on Computer Vision, Graphics and Image Processing (ICVGIP), India, December 2016. Rahul Duggal, Anubha Gupta, and Ritu Gupta, “Segmentation of overlapping/touching white blood cell nuclei using artificial neural networks,” CME Series on Hemato-Oncopathology, All India Institute of Medical Sciences (AIIMS), New Delhi, India, July 2016.
      - Rahul Duggal, Anubha Gupta, Ritu Gupta, and Pramit Mallick, "SD-Layer: Stain Deconvolutional Layer for CNNs in Medical Microscopic Imaging," In: Descoteaux M., Maier-Hein L., Franz A., Jannin P., Collins D., Duchesne S. (eds) Medical Image Computing and Computer-Assisted Intervention − MICCAI 2017, MICCAI 2017. Lecture Notes in Computer Science, Part III, LNCS 10435, pp. 435–443. Springer, Cham. DOI: https://doi.org/10.1007/978-3-319-66179-7_50 .


#### Lung and Colon Cancer Histopathological Images
  - Source:  [Click here to proceed to Kaggle site](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images) 
    - The data set can also be downloaded from [here](https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af)
    - Relevant [github](https://github.com/tampapath/lung_colon_image_set/)
  - Data Type: Images 
  -   Size of files
      - 959.8MB for colon_image_sets
      - 929.7MB for lung_image_sets
  -   Example of data + Special Instructions(if any) 
      1. For colon images download colon_image_sets from Source. For lung images, download lung_image_sets from Source. 
      2. Example: 

         Colon adenocarcinoma (from colon_aca folder in colon_image_sets):
         <img src="https://user-images.githubusercontent.com/66881214/179151676-341f0158-bd7b-4c86-9363-bebbe006054c.jpeg" width="150" height="150">

         Colon benign tissue (from colon_n folder in colon_image_sets):
         <img src="https://user-images.githubusercontent.com/66881214/179151688-3daef551-d0ee-4e22-9dc4-00d0abcbf263.jpeg" width="150" height="150">
         
         Lung benign tissue(from lung_n folder in lung_image_sets):
         <img src="https://user-images.githubusercontent.com/66881214/179151970-76a1616f-33fd-43da-8425-7277615da0b3.jpeg" width="150" height="150">

         Lung adenocarcinoma(from lung_aca folder in lung_image_sets):
         <img src="https://user-images.githubusercontent.com/66881214/179151977-1325c474-99ce-4b73-994d-ed852583c3a1.jpeg" width="150" height="150">

         Lung squamous cell carcinoma(from lung_scc folder in lung_image_sets):
         <img src="https://user-images.githubusercontent.com/66881214/179151986-1a1019c1-ff53-413f-9e63-514c583f2c94.jpeg" width="150" height="150">
  - Note: NA
  - Citations
    - [Original Article](https://arxiv.org/abs/1912.12142v1): Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM. Lung and Colon Cancer Histopathological Image Dataset (LC25000). arXiv:1912.12142v1 [eess.IV], 2019
   
#### Skin Cancer MNIST: HAM10000
  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
    - The original challenge can be found [here](https://challenge2018.isic-archive.com) and the dataset can also be downloaded [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) after accepting their terms and conditions. 
  
  - Data Type: Images + Tabular
  -   Size of files
      - 1.37GB for HAM10000_images_part_1 
      - 1.4GB for HAM10000_images_part_2
      - 563KB for HAM10000_metadata.csv
  -   Example of data + Special Instructions(if any) 
      1. Download HAM10000_images_part_1.zip, HAM10000_images_part_2 and HAM10000_metadata.csv from Source 
      2. Example: ISIC_0024306.jpg 
      
         <img src="https://user-images.githubusercontent.com/66881214/179134479-fc6a9393-17e5-4af3-93dc-81d8d8341073.jpg" width="150" height="150"> 
         
         Each image has its corresponding row in HAM10000_metadata.csv where its file name is its image_id as shown: 
         
         <img width="582" alt="Screenshot 2022-07-15 at 10 29 29 AM" src="https://user-images.githubusercontent.com/66881214/179134926-35dd84e3-f4b1-4f7d-a3f1-46ac395fb067.png">
  - Note: NA
  - Citations
    - Noel Codella, Veronica Rotemberg, Philipp Tschandl, M. Emre Celebi, Stephen Dusza, David Gutman, Brian Helba, Aadi Kalloo, Konstantinos Liopyris, Michael Marchetti, Harald Kittler, Allan Halpern: “Skin Lesion Analysis Toward Melanoma Detection 2018: A Challenge Hosted by the International Skin Imaging Collaboration (ISIC)”, 2018; https://arxiv.org/abs/1902.03368
    - Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).
    
#### Thoracic Surgery Data Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Thoracic+Surgery+Data)
  
  - Data Type: Text/Tabular
  
  -   Size: 24 KB
 
  -   Example of data + Special Instructions(if any) 
      1. Download  ThoraricSurgery.arff from Data Folder from Source
      2. Example: 
         
         <img width="351" alt="Screenshot 2022-07-15 at 2 42 52 PM" src="https://user-images.githubusercontent.com/66881214/179166600-f02bd66d-f08f-44f5-9606-1035ee64cca2.png">
         
         Columns present (from left to right):   
         * DGN 
         * PRE4
         * PRE5
         * PRE6
         * PRE7
         * PRE8
         * PRE9
         * PRE10
         * PRE11
         * PRE14
         * PRE17
         * PRE19
         * PRE25
         * PRE30
         * PRE32
         * AGE
         * Risk1Yr
         
  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    To convert to csv file, remove the highlighted text as shown and save:
    
    <img width="675" alt="Screenshot 2022-07-15 at 2 45 46 PM" src="https://user-images.githubusercontent.com/66881214/179167036-4318946c-4875-42e3-80e1-60bebcfd487b.png">
    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="1106" alt="Screenshot 2022-07-15 at 2 53 11 PM" src="https://user-images.githubusercontent.com/66881214/179168276-453388e5-0741-481c-abbf-39d207e20bd4.png">
    
  - Citations
    - ZiÄ™ba, M., Tomczak, J. M., Lubicz, M., & ÅšwiÄ…tek, J. (2013). Boosted SVM for extracting rules from imbalanced data in application to prediction of the post-operative life expectancy in the lung cancer patients. Applied Soft Computing [Link](https://www.sciencedirect.com/science/article/abs/pii/S0166432811002221?via%3Dihub)
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
       
### Brain Related Datasets

#### Brain tumor data

  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/mvhssriraj/brain-tumor-dataset)
  -   Data Type: Images
  -   Size: 733.1MB
  -   Example of data + Special Instructions(if any) 
      1. Download relevant files from Source 
      2. Example: 
         
         meningioma(1): <img src="https://user-images.githubusercontent.com/66881214/179969696-01a64b3f-053b-4b82-b4eb-ae82eececd10.png" width="150" height="150"> 

         glioma(2): <img src="https://user-images.githubusercontent.com/66881214/179969724-a8bf71a4-ea1a-4f6d-aebf-fe8e2d906fa6.png" width="150" height="150">
         
         pituitary tumor(3): <img src="https://user-images.githubusercontent.com/66881214/179969753-135aff9c-a033-4061-bd5b-a3a458cf231f.png" width="150" height="150">

  -   Note: NA
  -   Citations
      - Cheng, Jun (2017): brain tumor dataset. figshare. Dataset. https://doi.org/10.6084/m9.figshare.1512427.v5

#### MRI and Alzheimers

  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers)
  -   Data Type: Tabular (According to discussion, images was said to be found [here](https://www.oasis-brains.org/#data), where a request for access has to be made to OASIS)
  -   Size of files
      -  22KB for oasis_coss-sectional.csv
      -  28KB for oasis_longitudinal.csv
  -   Example of data + Special Instructions(if any) 
      1. Download relevant files from Source 
      2. Example: 
         
         oasis_coss-sectional.csv: <img width="843" alt="Screenshot 2022-07-19 at 2 18 24 PM" src="https://user-images.githubusercontent.com/66881214/179679183-ccec7e4a-4ec7-43bc-9394-5ff367c2c572.png">
         
         oasis_longitudinal.csv: <img width="1098" alt="Screenshot 2022-07-19 at 2 17 45 PM" src="https://user-images.githubusercontent.com/66881214/179679071-26a5b79c-c532-4c66-a3ff-3009fd8b803c.png">

  -   Note: NA
  -   Citations
      - When publishing findings that benefit from OASIS data, please include the following grant numbers in the acknowledgements section and in the associated Pubmed Central submission: P50 AG05681, P01 AG03991, R01 AG021910, P20 MH071616, U24 RR0213

#### Stroke Prediction

  -   Source: [Click here to proceed to site](https://data.mendeley.com/datasets/x8ygrw87jw/1)
  -   Data Type: Tabular 
  -   Size: 2.6 MB
  -   Example of data + Special Instructions(if any) 
      1. Download dataset.rar from Source 
      2. Example: 
         
         <img width="906" alt="Screenshot 2022-07-19 at 4 00 39 PM" src="https://user-images.githubusercontent.com/66881214/179698751-b9b39338-4503-4011-a0e1-823959c0574a.png">
       
  -   Note: NA
  -   Citations
      - Liu, Tianyu; Fan, Wenhui; Wu, Cheng (2019), “Data for: A hybrid machine learning approach to cerebral stroke prediction based on imbalanced medical-datasets”, Mendeley Data, V1, doi: 10.17632/x8ygrw87jw.1
           
### Eye Related Datasets 

#### Bajwa Hospital (Multi Eye Disease Dataset)

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/rgwpd4m785/2)  
- Data Type: Images 
-   Size: 3.59GB    
-   Example of data + Special Instructions(if any) 
      1. Download file from Source
      2. Example: 
         
         Normal: <img src="https://user-images.githubusercontent.com/66881214/179783463-a84dbf58-653f-4dbc-8a23-a4f1c5bb5b2c.png" width="150" height="150">
         
         Cataract: <img src="https://user-images.githubusercontent.com/66881214/179783530-bc98dfad-f095-401a-b6e4-3b620deef3eb.png" width="150" height="150">
         
         Glaucoma: <img src="https://user-images.githubusercontent.com/66881214/179783577-fd4346d9-2b18-4ee3-ba70-f0ff857c07ac.png" width="150" height="150">
         
         Retina Disease: <img src="https://user-images.githubusercontent.com/66881214/179783649-e58274ce-1ae9-4993-b434-e675b8dbf79b.png" width="150" height="150">

  - Note: [Click here for more information on how to access .rar files](https://www.hellotech.com/guide/for/how-to-open-rar-files-mac-windows-10)
  - Citations
    - Kaur, Palwinder (2022), “Bajwa Hospital (Multi Eye Disease Dataset)”, Mendeley Data, V2, doi: 10.17632/rgwpd4m785.2

#### Retinal OCT Images (optical coherence tomography)

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/rscbjbr9sj/3)  
- Data Type: Images 
-   Size: 7.19GB  
-   Example of data + Special Instructions(if any) 
      1. Download from Source
      2. Example: 
         
         NORMAL: <img src="https://user-images.githubusercontent.com/66881214/179479055-048a3b6a-ee7a-4f0c-ae73-fdf7e07784e2.jpeg" width="150" height="150">
         
         CNV: <img src="https://user-images.githubusercontent.com/66881214/179479097-161cb450-7dd8-4ab0-a214-316b3582c740.jpeg" width="150" height="150">
         
         DME: <img src="https://user-images.githubusercontent.com/66881214/179479179-f8f138fb-ff86-4166-9e3c-e39b9d8685e2.jpeg" width="150" height="150">
         
         DRUSEN: <img src="https://user-images.githubusercontent.com/66881214/179479213-ed54e3cc-052e-47d1-b897-006fc29d2581.jpeg" width="150" height="150">

  - Note: In the same folder, a folder named chest_xray can be found. These images belong to the latest version mentioned in [Chest X-ray Images (Pneumonia)](#Chest-X-ray-Images-Pneumonia) 
  - Citations
    - Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Large Dataset of Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images”, Mendeley Data, V3, doi: 10.17632/rscbjbr9sj.3

### Gastrointestinal Related Datasets

#### Bowel Sounds 

- Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/robertnowak/bowel-sounds)  
- Data Type: Audio  
-   Size: 283.8MB 
-   Example of data + Special Instructions(if any) 
      1. Download from Source
      2. Example: 
         
         https://user-images.githubusercontent.com/66881214/179934116-d8c16f98-2319-4814-86ca-c77516a3b6b0.mp4
         
         Each audio file has its corresponding csv file:
         
         <img width="326" alt="Screenshot 2022-07-20 at 4 23 48 PM" src="https://user-images.githubusercontent.com/66881214/179934214-797e2584-bfb1-4b62-b276-87bf3ac8e523.png">

 - Note: NA
 - Citations
   - Jakub Ficek and Kacper Radzikowski and Jan Nowak and Osamu Yoshie and Jarosław Walkowiak and Robert Nowak, "Analysis of gastrointestinal acoustic activity using deep neural networks", MDPI Sensors, 2021, doi:10.3390/s21227602, http://dx.doi.org/10.3390/s21227602
 

#### Kvasir Dataset


  -   Source: [Click here to proceed to site](https://datasets.simula.no/kvasir/)
  -   Data Type: Images
  -   Size of files:
      -  2.52GB for kvasir-dataset-v2
      -  40.2MB for kvasir-dataset-v2-features   
  -   Example of data + Special Instructions(if any) 
      1. Download relevant folders from Source 
      2. Example: 
         
         <details><summary>Click here to view sample images from dataset</summary>
         <p>
             
         dyed-lifted-polyps: <img src="https://user-images.githubusercontent.com/66881214/179727101-c8dbe0a3-a1db-45b4-97b4-4bd99f8056bf.jpg" width="150" height="150">
         
         dyed-resection-margins: <img src="https://user-images.githubusercontent.com/66881214/179727222-655752a7-6069-4bd7-83fc-0d3a7a7a1b90.jpg" width="150" height="150">
        
         esophagitis: <img src="https://user-images.githubusercontent.com/66881214/179727280-447b7298-fd63-4e33-9431-9211dabd01d9.jpg" width="150" height="150">    
         
         normal-cecum: <img src="https://user-images.githubusercontent.com/66881214/179727334-b2b46012-545b-40d7-9c40-15c92518826e.jpg" width="150" height="150">
         
         normal-pylorus: <img src="https://user-images.githubusercontent.com/66881214/179727384-4791ebd6-7f43-4199-b174-47e10c7452a5.jpg" width="150" height="150">
         
         normal-z-line: <img src="https://user-images.githubusercontent.com/66881214/179727428-91cc9ef4-908e-46de-9357-b745e083793f.jpg" width="150" height="150">
         
         polyps: <img src="https://user-images.githubusercontent.com/66881214/179727473-b0604275-0b39-48ae-a6fe-a9e166d126cf.jpg" width="150" height="150">
        
         ulcerative-colitis: <img src="https://user-images.githubusercontent.com/66881214/179727531-0e4191d2-8d76-4224-9570-d30e5f978181.jpg" width="150" height="150">
        
         </p>
         </details>   
        
  -   Note: NA
  -   Citations
      - Pogorelov, K., Randel, K., Griwodz, C., Eskeland, S., Lange, T., Johansen, D., Spampinato, C., Dang-Nguyen, D.T., Lux, M., Schmidt, P., Riegler, M., & Halvorsen, P. (2017). KVASIR: A Multi-Class Image Dataset for Computer Aided Gastrointestinal Disease Detection. In Proceedings of the 8th ACM on Multimedia Systems Conference (pp. 164–169). ACM.

### Heart Related Datasets

#### An Extensive Dataset for the Heart Disease Classification System

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/65gxgy2nmg/2)  
- Data Type: Text/Tabular 
-   Size: 51 KB   
-   Example of data + Special Instructions(if any) 
      1. Download Medicaldataset.arff from Source
      2. Example: 
       
         <img width="273" alt="Screenshot 2022-07-19 at 4 17 35 PM" src="https://user-images.githubusercontent.com/66881214/179702124-4324e73b-8569-43a0-9f1c-0906f63765c8.png">
         
         Columns present (from left to right):
            
         * age
         * gender
         * impulse
         * pressurehight
         * pressurelow
         * glucose
         * kcm
         * troponin
         * class

  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    To convert to csv file, remove the highlighted text as shown and save:
    
    <img width="751" alt="Screenshot 2022-07-19 at 4 18 48 PM" src="https://user-images.githubusercontent.com/66881214/179702389-5b3600d9-58ec-43be-b810-e58a25e3a26f.png">
    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="586" alt="Screenshot 2022-07-19 at 4 19 37 PM" src="https://user-images.githubusercontent.com/66881214/179702539-cb30bdc9-30ff-4102-a299-8070f0b64e0b.png">

  - Citations
    - Maghdid, Sozan; Rashid, Tarik A. (2022), “An Extensive Dataset for the Heart Disease Classification System ”, Mendeley Data, V2, doi: 10.17632/65gxgy2nmg.2

#### Heart Failure Prediction

- Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)  
- Data Type: Tabular 
-   Size: 12KB   
-   Example of data + Special Instructions(if any) 
      1. Download heart_failure_clinical_records_dataset.csv from Source
      2. Example: <img width="1036" alt="Screenshot 2022-07-18 at 12 24 40 PM" src="https://user-images.githubusercontent.com/66881214/179445189-7e885834-643e-4c73-9d42-78e4abdae1fa.png">
  - Note: NA
  - Citations
    - Davide Chicco, Giuseppe Jurman: Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making 20, 16 (2020). [Link](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5)

### Kidney Related Datasets 

#### A Brazilian dataset for screening the risk of the Chronic Kidney Disease

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/2gkg7vvcrm/3)  
- Data Type: Text/Tabular  
-   Size of files:
    - 2 KB for Original.arff
    - 2 KB for Augmented.arff         
-   Example of data + Special Instructions(if any) 
      1. Download relevant file from Source
         - In Augmented.arff, authors have augmented the dataset to decrease the impact of imbalanced data.  
      2. Example: <img width="406" alt="Screenshot 2022-07-19 at 5 27 05 PM" src="https://user-images.githubusercontent.com/66881214/179717003-2ae83296-68d1-4940-aaa5-12c2589cd18a.png">
  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    To convert to csv file, remove the highlighted text as shown and save:
    
    <img width="679" alt="Screenshot 2022-07-19 at 5 28 38 PM" src="https://user-images.githubusercontent.com/66881214/179717333-24a0b174-8506-466e-ab26-a72ef79ad542.png">

    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="616" alt="Screenshot 2022-07-19 at 5 29 09 PM" src="https://user-images.githubusercontent.com/66881214/179717458-25397a0d-0c4d-4146-b33a-6016d02ceca1.png">

  - Citations
    - Sobrinho, Alvaro; Dias da Silva, Leandro ; Perkusich, Angelo; Queiroz, Andressa; Eliete Pinheiro, Maria (2021), “A Brazilian dataset for screening the risk of the Chronic Kidney Disease”, Mendeley Data, V3, doi: 10.17632/2gkg7vvcrm.3

#### Risk Factor prediction of Chronic Kidney Disease Data Set

  -   Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Risk+Factor+prediction+of+Chronic+Kidney+Disease)
  -   Data Type: Tabular
  -   Size: 34KB
  -   Example of data + Special Instructions(if any) 
      1. Download ckd-dataset-v2.csv from Data Folder from Source
      2. Example: 
      
            | **bp (Diastolic)** | **bp limit** | **sg**        | **al**   | **class** | **rbc**  | **su**   | **pc**   | **pcc**  | **ba**   | **bgr**   | **bu**      | **sod**   | **sc**   | **pot**  | **hemo**    | **pcv**     | **rbcc**    | **wbcc**      | **htn**  | **dm**   | **cad**  | **appet** | **pe**   | **ane**  | **grf**           | **stage** | **affected** | **age**  |
            | ------------------ | ------------ | ------------- | -------- | --------- | -------- | -------- | -------- | -------- | -------- | --------- | ----------- | --------- | -------- | -------- | ----------- | ----------- | ----------- | ------------- | -------- | -------- | -------- | --------- | -------- | -------- | ----------------- | --------- | ------------ | -------- |
            | discrete           | discrete     | discrete      | discrete | discrete  | discrete | discrete | discrete | discrete | discrete | discrete  | discrete    | discrete  | discrete | discrete | discrete    | discrete    | discrete    | discrete      | discrete | discrete | discrete | discrete  | discrete | discrete | discrete          | discrete  | discrete     | discrete |
            |                    |              |               |          |           |          |          |          |          |          |           |             |           |          |          |             |             |             |               |          |          |          |           |          |          |                   |           | class        | meta     |
            | 0                  | 0            | 1.019 - 1.021 | 1 - 1    | ckd       | 0        | < 0      | 0        | 0        | 0        | < 112     | < 48.1      | 138 - 143 | < 3.65   | < 7.31   | 11.3 - 12.6 | 33.5 - 37.4 | 4.46 - 5.05 | 7360 - 9740   | 0        | 0        | 0        | 0         | 0        | 0        | ≥ 227.944         | s1        | 1            | < 12     |
            | 0                  | 0            | 1.009 - 1.011 | < 0      | ckd       | 0        | < 0      | 0        | 0        | 0        | 112 - 154 | < 48.1      | 133 - 138 | < 3.65   | < 7.31   | 11.3 - 12.6 | 33.5 - 37.4 | 4.46 - 5.05 | 12120 - 14500 | 0        | 0        | 0        | 0         | 0        | 0        | ≥ 227.944         | s1        | 1            | < 12     |
            | 0                  | 0            | 1.009 - 1.011 | ≥ 4      | ckd       | 1        | < 0      | 1        | 0        | 1        | < 112     | 48.1 - 86.2 | 133 - 138 | < 3.65   | < 7.31   | 8.7 - 10    | 29.6 - 33.5 | 4.46 - 5.05 | 14500 - 16880 | 0        | 0        | 0        | 1         | 0        | 0        | 127.281 - 152.446 | s1        | 1            | < 12     |
            | 1                  | 1            | 1.009 - 1.011 | 3 - 3    | ckd       | 0        | < 0      | 0        | 0        | 0        | 112 - 154 | < 48.1      | 133 - 138 | < 3.65   | < 7.31   | 13.9 - 15.2 | 41.3 - 45.2 | 4.46 - 5.05 | 7360 - 9740   | 0        | 0        | 0        | 0         | 0        | 0        | 127.281 - 152.446 | s1        | 1            | < 12     |

      
  -   Note: According to site, pre-processing has to be done for any machine learning algorithm to be applied. Some special characters might be observed in Microsoft Excel. Using other applications such as Numbers(Macbook), these special characters correspond to mathematical symbols such as >= or <=
  -   Citations
      - M. A. Islam, S. Akter, M. S. Hossen, S. A. Keya, S. A. Tisha and S. Hossain, 'Risk Factor Prediction of Chronic Kidney Disease based on Machine Learning Algorithms,' 2020 3rd International Conference on Intelligent Sustainable Systems (ICISS), Thoothukudi, India, 2020, pp. 952-957, doi: 10.1109/ICISS49785.2020.9315878.  [Link](https://ieeexplore.ieee.org/document/9315878)
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

### Lung Related Datasets

#### A dataset of lung sounds recorded from the chest wall using an electronic stethoscope

  - Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/jwyy9np4gv/3)
  - Data Type: Audio 
  -   Size: 
  -   Example of data + Special Instructions(if any) 
      1. Download by Audio Files.zip and Data annotation.xlsx from Source
         - "Stethoscope Files.zip" contains the original records imported from the stethoscope  
      2. Example: 
        
         BP1_Asthma,I E W,P L L,70,M:  
         
         https://user-images.githubusercontent.com/66881214/179915810-22a7b2cf-7c7c-42e7-851c-8441a157b7f8.mp4
         
         Filename correspond to values in its corresponding row in Data annotation.xlsx.
         
         <img width="448" alt="Screenshot 2022-07-20 at 2 51 39 PM" src="https://user-images.githubusercontent.com/66881214/179916058-0115e768-d731-4e29-b8af-234e9de492c5.png">
         
         <img width="440" alt="Screenshot 2022-07-20 at 2 58 32 PM" src="https://user-images.githubusercontent.com/66881214/179917244-f6866ec0-2a9d-4717-a5dd-c4a29c3aec8b.png">

  - Note:  If .wav files are not supported, try using online converter tools to convert to a audio file type that is supported by your device.
    - For example: [FreeConvert](https://www.freeconvert.com/audio-converter)     
  - Citations
    - Fraiwan, Mohammad; Fraiwan, Luay; Khassawneh, Basheer; Ibnian, Ali (2021), “A dataset of lung sounds recorded from the chest wall using an electronic stethoscope”, Mendeley Data, V3, doi: 10.17632/jwyy9np4gv.3

#### NIH Chest X-ray Dataset
  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/nih-chest-xrays/data?resource=download)
  -   Data Type: Images + Tabular
  -   Size of files
      -  2 to 4 GB per image zip folder depending on number of images in the folder 
      -  7.9 MB for Data_Entry_2017.csv
      -  92 KB for BBox_List_2017.csv 
  -   Example of data + Special Instructions(if any) 
      1. Download image folders images_001 to images_012 from Source. Class labels are to be obtained from Data_Entry_2017.csv. Extra information regarding the patient and image can be found in the file as well. Coordinates of the disease region bounding boxes can be obtained from BBox_List_2017.csv.
      2. Example: 00000032_037.png
      
         <img src="https://user-images.githubusercontent.com/66881214/178676386-7c3c1163-6972-443f-8525-ba8d22e3bf89.png" width="150" height="150">
         
         Each image has its corresponding row in Data_Entry_2017.csv where its file name (with extension) is its Image Index as shown: 
         
         <img width="1191" alt="Screenshot 2022-07-13 at 3 55 31 PM" src="https://user-images.githubusercontent.com/66881214/178681269-37873e8b-6749-4658-843a-6ab3a6ff7c8d.png"> In this example, the image is classified to 3 different diseases, namely Cadiomegaly, Edema and Infiltration. There are a total of 15 class labels as follows:
         
            - Atelectasis
            - Consolidation
            - Infiltration
            - Pneumothorax
            - Edema
            - Emphysema
            - Fibrosis
            - Effusion
            - Pneumonia
            - Pleural_thickening
            - Cardiomegaly
            - Nodule Mass
            - Hernia
            
      3. Data in BBox_List_2017.csv is very limited. An image may be classified to one of the diseases but do not have a corresponding record in BBox_List_2017.csv file. Referencing to the same example above shows that there is only one disease region bounding box identified in BBox_List_2017.csv file.
         
         <img width="574" alt="Screenshot 2022-07-13 at 4 19 17 PM" src="https://user-images.githubusercontent.com/66881214/178685815-7503b9c5-0b09-4a4f-9adb-5226fd0867d9.png">

  -   Note: Some image labels may not be accurate. A more accurate version is said to be available [here](https://cloud.google.com/healthcare-api/docs/resources/public-datasets/nih-chest#additional_labels). You would be required to submit the following google form to obtain the updated data.  
  
      <img width="479" alt="Screenshot 2022-07-13 at 2 24 23 PM" src="https://user-images.githubusercontent.com/66881214/178664900-deb7670c-3451-4049-98b5-bc253878be0a.png">

  -   Citations
      - Wang X, Peng Y, Lu L, Lu Z, Bagheri M, Summers RM. ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases. IEEE CVPR 2017, [ChestX-ray8Hospital-ScaleChestCVPR2017_paper.pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)
      - NIH News release: [NIH Clinical Center provides one of the largest publicly available chest x-ray datasets to scientific community](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community)
      - Original source files and documents: [Click here to proceed to folder](https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345)


#### Chest X-ray Images (Pneumonia)
  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
  -   Data Type: Images 
  -   Size: 2 GiB
  -   Example of data + Special Instructions(if any) 
      1. Download relevant folders from Source. Images have been split into train, val and test folders. Within each folder, there are two folders NORMAL and PNEUMONIA.
      2. Example: 
      
         NORMAL: <img src="https://user-images.githubusercontent.com/66881214/178702525-0eb5a853-a771-4821-8518-3bcc0dc8e642.jpeg" width="150" height="150">
         
         PNEUMONIA: <img src="https://user-images.githubusercontent.com/66881214/178702776-eeee3f64-c6c1-45ba-90b8-ec8ffa045631.jpeg" width="150" height="150">
         
  -   Note: A newer version of the dataset can be found [here.](https://data.mendeley.com/datasets/rscbjbr9sj/3) Please cite accordingly. 
  -   Citations
      -  Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification”, Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2
         -  The paper can be found [here](http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5)
         
#### QaTa COV19 Dataset 
  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/aysendegerli/qatacov19-dataset)
  - Data Type: Images
  -   Size of files 
      - 215.8MB for QaTa-COV19-v2 folder
      - 4.45GB for Control_Group 
  -   Example of data + Special Instructions(if any) 
      1. Download the relevant files from Source 

      2. Example:  
            
         **QaTa-COV19-v2**
         
         covid_1: <img src="https://user-images.githubusercontent.com/66881214/179535373-8cabf179-92ac-4d19-86d9-9ee31cd27b13.png" width="150" height="150">
         
         Each image for covid cases has its corresponding image, named mask_FILENAME.png in the Ground-truths folder
         
         mask_covid_1: <img src="https://user-images.githubusercontent.com/66881214/179535721-7810fd94-2b6d-45b9-ac2e-1412191586e5.png" width="150" height="150">
         
         **Control_Group**
         
         In Control_Group_I, all are normal.
         
         normal_1: <img src="https://user-images.githubusercontent.com/66881214/179536163-4b909717-dd40-4713-bc68-444c51995637.png" width="150" height="150">
         
         In Control_Group_II, there is a variety of cases. More details can be found in their readme.txt file in the downloaded folder.
         
                Control_Group: The chest X-rays that are in the control group can be found under Control_Group/ folder. 
                There are two control groups in this folder. Control Group-I  consists  of  only  normal  (healthy) chest X-rays with 12,544 images. 
                On the other hand, Control Group-II consists of 116,365 chest X-rays from normal and 14 different thoracic disease images. 
                In Control Group II, the CHESTXRAY-14 folder includes train and test sets of ChestXray-14 dataset. 
                In addition to this, bacterial and viral pneumonia from pediatric patients can be found in this folder. 
                However, for the pediatric patient data, there are no train and test sets predefined.

  - Note: If you would like to use other versions in the source, please cite accordingly as stated in the source.    
  - Citations
    - A. Degerli, S. Kiranyaz, M. E. H. Chowdhury, and M. Gabbouj, "OSegNet: Operational Segmentation Network for COVID-19 Detection using Chest X-ray Images," arXiv:2202.10185, 2022.
    
#### Respiratory Sound Database 
  - Source:  [Click here to proceed to site](https://bhichallenge.med.auth.gr/)
  
  - Data Type: Audio + Text/Tabular  
  
  -   Size of files
      -  1KB for diagnosis file
      -  3KB for demographic data file
      -  2.18GB for database folder 
  -   Example of data + Special Instructions(if any) 
      1. Download the relevant files from Source 
         - To obtain class labels/diagnosis of each subject: <img width="803" alt="Screenshot 2022-07-16 at 11 51 25 PM" src="https://user-images.githubusercontent.com/66881214/179362176-ca8cc73f-7801-4833-9345-d812d179e8bf.png">
         - To obtain demographic information regarding subjects: <img width="968" alt="Screenshot 2022-07-16 at 11 57 06 PM" src="https://user-images.githubusercontent.com/66881214/179362433-dbff5d53-a2a0-4c6b-a112-c7318676e34c.png">
         - To obtain recordings: <img width="960" alt="Screenshot 2022-07-16 at 11 59 00 PM" src="https://user-images.githubusercontent.com/66881214/179362510-9f76cd39-cdf6-4be6-8bcb-da11028885f7.png">
      2. Example:  
         Diagnosis file: 
         <img width="182" alt="Screenshot 2022-07-17 at 12 03 45 AM" src="https://user-images.githubusercontent.com/66881214/179362686-2666aaee-5fb8-4ef5-87e0-7359ac6f3ad5.png">
         
         Demographic data: <img width="303" alt="Screenshot 2022-07-17 at 12 04 46 AM" src="https://user-images.githubusercontent.com/66881214/179362726-0b64c3d2-1797-4c96-a068-d13192b6b640.png">
         
         Columns present (from left to right):
         * Participant ID
         * Age
         * Sex
         * Adult BMI (kg/m2)
         * Child Weight (kg)
         * Child Height (cm)
         
         Recording (101_1b1_Al_sv_Meditron.wav): 
         
         https://user-images.githubusercontent.com/66881214/179362930-9cebcdf7-41c4-4115-8d84-348992d008d2.mp4
         
         File name is divided into 5 elements. Refer to image below for more details: 
         <img width="506" alt="Screenshot 2022-07-17 at 12 13 01 AM" src="https://user-images.githubusercontent.com/66881214/179363061-13dbed57-72fb-4c2c-ab71-8bd9f89fb85b.png">
         
         A corresponding text file (in this case 101_1b1_Al_sv_Meditron.txt) can also be found in the database folder: <img width="198" alt="Screenshot 2022-07-17 at 12 14 14 AM" src="https://user-images.githubusercontent.com/66881214/179363104-28ef50ec-ac22-4df1-b5c4-f4b44a0d9e3c.png">
         
         Columns present (from left to right): 
         * Beginning of respiratory cycle(s)
         * End of respiratory cycle(s)
         * Presence/absence of crackles (presence=1, absence=0)
         * Presence/absence of wheezes (presence=1, absence=0)
  - Note: If .wav files are not supported, try using online converter tools to convert to a audio file type that is supported by your device.
    - For example: [FreeConvert](https://www.freeconvert.com/audio-converter)     
  - Citations
    - Rocha BM, Filos D, Mendes L, Vogiatzis I, Perantoni E, Kaimakamis E, Natsiavas P, Oliveira A, Jácome C, Marques A, Paiva RP (2018) In Precision Medicine Powered by pHealth and Connected Health (pp. 51-55). Springer, Singapore 
      - The paper can be found [here](https://eden.dei.uc.pt/~ruipedro/publications/Conferences/ICBHI2017a.pdf)

### Other Diseases 

#### Chula RBC-12-Dataset
  -   Source:  [Click here to proceed to site](https://github.com/Chula-PIC-Lab/Chula-RBC-12-Dataset)
  
  -   Data Type: Images + Text/Tabular
  
  -   Size: Depends. One image is about 79KB. 
      - 73.5MB for Dataset folder 
      - 216KB for Labels folder
  
  -   Example of data + Special Instructions(if any) 
      1. Download images in Dataset folder and corresponding text files in Label folder from Source.
         - You could also download the entire folder by downloading the zip folder as shown below:
           <img width="927" alt="Screenshot 2022-07-18 at 10 23 20 PM" src="https://user-images.githubusercontent.com/66881214/179533073-c46fcd53-bf27-4148-b3f7-71744719a75b.png">

      2. Example: 1.jpg in Dataset folder will correspond to 1.txt in Label folder
      
         <img src="https://user-images.githubusercontent.com/66881214/178712949-f819cf02-e1cc-4cb8-994c-d83d28823179.jpg" width="150" height="150"> <img width="115" alt="Screenshot 2022-07-13 at 6 38 07 PM" src="https://user-images.githubusercontent.com/66881214/178714773-24a74e22-dcd2-47a8-acec-f37606ebf1b4.png"> 
         
         Each row contains 3 values which corresponds to the x coordinate, y coordinate and the type of red blood cell found at the coordinate. There are 13 types as follows:
         
         Number  | Type of Red Blood Cell
         ------------- | -------------
         0  | Normal cell
         1  | Macrocyte
         2 | Microcyte 
         3 | Spherocyte
         4 | Target cell
         5 | Stomatocyte
         6 | Ovalocyte
         7 | Teardrop
         8 | Burr cell
         9 | Schistocyte
         10 | uncategorised
         11 | Hypochromia
         12 | Elliptocyte
         
      3. There are other images that correspond to other red blood diseases that can be found in the RBC Diseases folder from Source. 
  -   Note: NA
  
  -   Citations
      - Naruenatthanaset, K., Chalidabhongse, T. H., Palasuwan, D., Anantrasirichai, N., &amp; Palasuwan, A. (2021, November 3). Red blood cell segmentation with overlapping cell separation and classification on Imbalanced Dataset. arXiv.org. Retrieved July 14, 2022, from https://arxiv.org/abs/2012.01321   

#### Coswara Dataset

  -   Source:  [Click here to proceed to site](https://github.com/iiscleap/Coswara-Data)
 
  -   Data Type: Audio + Tabular
  
  -   Size:  
  
  -   Example of data + Special Instructions(if any) 
      1. Download relevant files from Source

      2. Example: 
          
           Audio sample to be included soon.
            
           Summary of metadata found in combined_data.csv in source:
           
           | id                           | a  | cold | record\_date | covid\_status  | ctScan | dT  | ep | fV | fever | g    | l\_c  | l\_l            | l\_s      | others\_resp | rU | smoker | testType | test\_date | test\_status | um | vacc | cough | ftg | mp   | st | diabetes | ht | bd | cld | diarrhoea | ctDate | ctScore | asthma | loss\_of\_smell | others\_preexist | ihd | pneumonia |
           | ---------------------------- | -- | ---- | ------------ | -------------- | ------ | --- | -- | -- | ----- | ---- | ----- | --------------- | --------- | ------------ | -- | ------ | -------- | ---------- | ------------ | -- | ---- | ----- | --- | ---- | -- | -------- | -- | -- | --- | --------- | ------ | ------- | ------ | --------------- | ---------------- | --- | --------- |
           | eK8ikIYnLQPWGetLBHzkJVCGfpq2 | 27 | TRUE | 18/1/22      | positive\_mild | n      | web | y  | 2  | TRUE  | male | India | Shimoga         | Karnataka | TRUE         | n  | n      | rtpcr    | 17/1/22    | p            | y  | y    |       |     |      |    |          |    |    |     |           |        |         |        |                 |                  |     |           |
           | AeP4E7hKFtOmcWye2MghbvDfGlo2 | 41 |      | 29/1/22      | positive\_mild | n      | web | y  | 2  | TRUE  | male | India | Bangalore rural | Karnataka |              | n  | n      | rtpcr    | 27/1/22    | p            | y  | y    | TRUE  |     | TRUE |    |          |    |    |     |           |        |         |        |                 |                  |     |           |

  
  -   Note: Audio files are in a zip file (example 20220224.tar.gz.aa). A extract_data.py is provided in source to extract the audio files which are of .wav format.
  
  -   Citations
      - Coswara - A Database of Breathing, Cough, and Voice Sounds for COVID-19 Diagnosis (https://arxiv.org/abs/2005.10548)

#### CT Medical Images

  -   Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/kmader/siim-medical-images?select=dicom_dir)
  
  -   Data Type: Images 
  
  -   Size of files
      - 52.8MB for dicom_dir folder 
      - 209.7MB for tiff_images folder
  
  -   Example of data + Special Instructions(if any) 
      1. Download relevant folders from Source.

      2. Example: 
       
         ID_0000_AGE_0060_CONTRAST_1_CT.dcm (converted to jpg [here](https://convertio.co/dcm-jpg/)): <img src="https://user-images.githubusercontent.com/66881214/179672281-09bf949d-3204-4f6f-a6e5-5e91bfffdee4.jpg" width="150" height="150">
   
         ID_0000_AGE_0060_CONTRAST_1_CT.tif (converted to jpg [here](https://www.freeconvert.com/tif-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179672420-3f9ea3e7-de97-4107-9fbd-52b0eb1702f9.jpg" width="150" height="150">

         <img width="1158" alt="Screenshot 2022-07-19 at 1 32 27 PM" src="https://user-images.githubusercontent.com/66881214/179672551-6c76f8c4-1327-4936-90a9-df32283f72bb.png">
               
  -   Note: The dataset from Source is only a subset from the cancer imaging archive. For more, [click here](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LUAD)
  
  -   Citations
      - Albertina, B., Watson, M., Holback, C., Jarosz, R., Kirk, S., Lee, Y., … Lemmerman, J. (2016). Radiology Data from The Cancer Genome Atlas Lung Adenocarcinoma [TCGA-LUAD] collection. The Cancer Imaging Archive. http://doi.org/10.7937/K9/TCIA.2016.JGNIHEP5
      - Clark K, Vendt B, Smith K, Freymann J, Kirby J, Koppel P, Moore S, Phillips S, Maffitt D, Pringle M, Tarbox L, Prior F. The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository, Journal of Digital Imaging, Volume 26, Number 6, December, 2013, pp 1045-1057. (paper)  

#### Association of body mass index and age with incident diabetes in Chinese adults

  -   Source:  [Click here to proceed to site](https://zenodo.org/record/4997196#.YtZvkpNBw-Q)
  
  -   Data Type: Tabular  
  
  -   Size: 28.3 KB
  
  -   Example of data + Special Instructions(if any) 
      1. Download RC Health Care Data-20180820.xlsx from Source.

      2. Example: 
            
           | id | Age (y) | Gender(1, male; 2, female) | site | height(cm) | weight(kg) | BMI(kg/m2) | SBP(mmHg) | DBP(mmHg) | FPG (mmol/L) | Cholesterol(mmol/L) | Triglyceride(mmol/L) | HDL-c(mmol/L) | LDL(mmol/L) | ALT(U/L) | AST(U/L) | BUN(mmol/L) | CCR(umol/L) | FPG of final visit(mmol/L) | Diabetes diagnosed during followup（1,Yes） | censor of diabetes at followup(1, Yes; 0, No) | year of followup | smoking status(1,current smoker;2, ever smoker;3,never smoker) | drinking status(1,current drinker;2, ever drinker;3,never drinker) | family histroy of diabetes(1,Yes;0,No) |
           | -- | ------- | -------------------------- | ---- | ---------- | ---------- | ---------- | --------- | --------- | ------------ | ------------------- | -------------------- | ------------- | ----------- | -------- | -------- | ----------- | ----------- | -------------------------- | ----------------------------------------- | --------------------------------------------- | ---------------- | -------------------------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------- |
           | 1  | 43      | 2                          | 16   | 166.4      | 53.5       | 19.3       | 96        | 57        | 4.99         | 5.13                | 0.78                 |               |             | 10       |          | 3.08        | 50.3        | 4.97                       |                                           | 0                                             | 2.15195          | 3                                                              | 3                                                                  | 1                                      |
           | 2  | 34      | 1                          | 2    | 169        | 57         | 20         | 124       | 69        | 3.51         | 4.61                | 1.75                 | 1.09          | 3.13        | 29.1     |          | 6.13        | 83.7        | 5.5                        |                                           | 0                                             | 3.96988          |                                                                |                                                                    | 0                                      |
           | 3  | 32      | 2                          | 2    | 157        | 51         | 20.7       | 98        | 68        | 4.25         | 4.73                | 0.47                 |               |             | 6.9      | 19.5     | 4.45        | 42.8        | 4.9                        |                                           | 0                                             | 3.93977          |                                                                |                                                                    | 0                                      |
               
  -   Note: NA
  
  -   Citations
      - Chen, Ying, Zhang, Xiao-Ping, Yuan, Jie, Cai, Bo, Wang, Xiao-Li, Wu, Xiao-Li, Zhang, Yue-Hua, Zhang, Xiao-Yi, Yin, Tong, Zhu, Xiao-Hui, Gu, Yun-Juan, Cui, Shi-Wei, Lu, Zhi-Qiang, & Li, Xiao-Ying. (2018). Data from: Association of body mass index and age with incident diabetes in Chinese adults: a population-based cohort study [Data set]. https://doi.org/10.5061/dryad.ft8750v
      
#### Clinical characteristics, types and complications of diabetics with young age at the onset

  -   Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/jf429jpgwt/1)
  
  -   Data Type: Tabular  
  
  -   Size: 22 KB
  
  -   Example of data + Special Instructions(if any) 
      1. Download 9. Master Chart.xlsx from Source.

      2. Example: 
         <img width="1130" alt="Screenshot 2022-07-19 at 4 45 06 PM" src="https://user-images.githubusercontent.com/66881214/179707993-1c6512f6-7b93-4605-b968-c44bfb4417b8.png">
               
  -   Note: NA
  
  -   Citations
      - SAHU, PRANABANANDA; Das, Sidhartha (2019), “Data for: Clinical characteristics, types and complications of diabetics with young age at the onset ( 14 to 25 years).”, Mendeley Data, V1, doi: 10.17632/jf429jpgwt.1

#### Diabetes 130-US hospitals for years 1999-2008 Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
  
  - Data Type: Tabular 
  
  -   Size of files
      -  19.2MB for diabetic_data.csv
      -  3KB for IDs_mapping.csv
  -   Example of data + Special Instructions(if any) 
      1. Download dataset_diabetes.zip from Data Folder from Source 
      2. Example: 

           | encounter_id | patient_nbr | race      | gender | age     | weight | admission_type_id | discharge_disposition_id | admission_source_id | time_in_hospital | payer_code | medical_specialty        | num_lab_procedures | num_procedures | num_medications | number_outpatient | number_emergency | number_inpatient | diag_1 | diag_2 | diag_3 | number_diagnoses | max_glu_serum | A1Cresult | metformin | repaglinide | nateglinide | chlorpropamide | glimepiride | acetohexamide | glipizide | glyburide | tolbutamide | pioglitazone | rosiglitazone | acarbose | miglitol | troglitazone | tolazamide | examide | citoglipton | insulin | glyburide-metformin | glipizide-metformin | glimepiride-pioglitazone | metformin-rosiglitazone | metformin-pioglitazone | change | diabetesMed | readmitted |
           |--------------|-------------|-----------|--------|---------|--------|-------------------|--------------------------|---------------------|------------------|------------|--------------------------|--------------------|----------------|-----------------|-------------------|------------------|------------------|--------|--------|--------|------------------|---------------|-----------|-----------|-------------|-------------|----------------|-------------|---------------|-----------|-----------|-------------|--------------|---------------|----------|----------|--------------|------------|---------|-------------|---------|---------------------|---------------------|--------------------------|-------------------------|------------------------|--------|-------------|------------|
           | 2278392      | 8222157     | Caucasian | Female | [0-10)  | ?      | 6                 | 25                       | 1                   | 1                | ?          | Pediatrics-Endocrinology | 41                 | 0              | 1               | 0                 | 0                | 0                | 250.83 | ?      | ?      | 1                | None          | None      | No        | No          | No          | No             | No          | No            | No        | No        | No          | No           | No            | No       | No       | No           | No         | No      | No          | No      | No                  | No                  | No                       | No                      | No                     | No     | No          | NO         |
           | 149190       | 55629189    | Caucasian | Female | [10-20) | ?      | 1                 | 1                        | 7                   | 3                | ?          | ?                        | 59                 | 0              | 18              | 0                 | 0                | 0                | 276    | 250.01 | 255    | 9                | None          | None      | No        | No          | No          | No             | No          | No            | No        | No        | No          | No           | No            | No       | No       | No           | No         | No      | No          | Up      | No                  | No                  | No                       | No                      | No                     | Ch     | Yes         | >30        |

  - Note: NA
  - Citations
    - Beata Strack, Jonathan P. DeShazo, Chris Gennings, Juan L. Olmo, Sebastian Ventura, Krzysztof J. Cios, and John N. Clore, “Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records,” BioMed Research International, vol. 2014, Article ID 781670, 11 pages, 2014. [Link](https://www.hindawi.com/journals/bmri/2014/781670/)
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
    
#### Diabetic Retinopathy Debrecen Data Set Data Set

  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Diabetic+Retinopathy+Debrecen+Data+Set)
  
  - Data Type: Text/Tabular
  
  -   Size: 117 KB
 
  -   Example of data + Special Instructions(if any) 
      1. Download  messidor_features.arff from Data Folder from Source
      2. Example: 
         
         <img width="823" alt="Screenshot 2022-07-15 at 4 05 20 PM" src="https://user-images.githubusercontent.com/66881214/179180696-f57026cd-1a4c-423d-921d-2a36c18c1f50.png">

         Columns present (from left to right):   
         * The binary result of quality assessment. 0 = bad quality 1 = sufficient quality.
         * The binary result of pre-screening, where 1 indicates severe retinal abnormality and 0 its lack.
         * The results of MA detection. Each feature value stand for the
number of MAs found at the confidence levels alpha = 0.5, . . . , 1, respectively. (Columns 2-7)
         * contain the same information as 2-7) for exudates. However, as exudates are represented by a set of points rather than the number of pixels constructing the lesions, these features are normalized by dividing the number of lesions with the diameter of the ROI to compensate different image
sizes (Columns 8-15)
         * The euclidean distance of the center of the macula and the center of the optic disc to provide important information regarding the patient's condition. This feature is also normalized with the diameter of the ROI.
         * The diameter of the optic disc.
         * The binary result of the AM/FM-based classification.
         * Class label. 1 = contains signs of DR (Accumulative label for the Messidor classes 1, 2, 3), 0 = no signs of DR.
         
  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    To convert to csv file, remove the highlighted text as shown and save:
    
    <img width="1016" alt="Screenshot 2022-07-15 at 4 05 56 PM" src="https://user-images.githubusercontent.com/66881214/179180814-8066caa4-de81-486d-8b19-f1dc9ce05534.png">
    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="1304" alt="Screenshot 2022-07-15 at 4 06 37 PM" src="https://user-images.githubusercontent.com/66881214/179180932-1d57f15a-783c-4da7-8c43-d3fe4afbda58.png">
    
  - Citations
    - Balint Antal, Andras Hajdu: An ensemble-based system for automatic screening of diabetic retinopathy, Knowledge-Based Systems 60 (April 2014), 20-27.
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Early Classification of Diabetes

  -   Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/early-diabetes-classification)
  
  -   Data Type: Tabular  
  
  -   Size: 21 KB
  
  -   Example of data + Special Instructions(if any) 
      1. Download diabetes_data.csv from Source.

      2. Example: 
      
           | **age** | **gender** | **polyuria** | **polydipsia** | **sudden\_weight\_loss** | **weakness** | **polyphagia** | **genital\_thrush** | **visual\_blurring** | **itching** | **irritability** | **delayed\_healing** | **partial\_paresis** | **muscle\_stiffness** | **alopecia** | **obesity** | **class** |
          | ------- | ---------- | ------------ | -------------- | ------------------------ | ------------ | -------------- | ------------------- | -------------------- | ----------- | ---------------- | -------------------- | -------------------- | --------------------- | ------------ | ----------- | --------- |
          | 40      | Male       | 0            | 1              | 0                        | 1            | 0              | 0                   | 0                    | 1           | 0                | 1                    | 0                    | 1                     | 1            | 1           | 1         |
          | 58      | Male       | 0            | 0              | 0                        | 1            | 0              | 0                   | 1                    | 0           | 0                | 0                    | 1                    | 0                     | 1            | 0           | 1         |
          | 41      | Male       | 1            | 0              | 0                        | 1            | 1              | 0                   | 0                    | 1           | 0                | 1                    | 0                    | 1                     | 1            | 0           | 1         |
         
               
  -   Note: Viewing file on Microsoft Excel might be an issue as the delimeter used is a semicolon. 
  
  -   Citations
      - Islam M.M.F., Ferdousi R., Rahman S., Bushra H.Y. (2020) Likelihood Prediction of Diabetes at Early Stage Using Data Mining Techniques. In: Gupta M., Konar D., Bhattacharyya S., Biswas S. (eds) Computer Vision and Machine Intelligence in Medical Image Analysis. Advances in Intelligent Systems and Computing, vol 992. Springer, Singapore. https://doi.org/10.1007/978-981-13-8798-2_12

    
#### Fetal Health Classification 

  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
  - Data Type: Tabular 
  -   Size: 229KB
  -   Example of data + Special Instructions(if any) 
      1. Download from Source
      2. Example: 
                
            | baseline value | accelerations | fetal\_movement | uterine\_contractions | light\_decelerations | severe\_decelerations | prolongued\_decelerations | abnormal\_short\_term\_variability | mean\_value\_of\_short\_term\_variability | percentage\_of\_time\_with\_abnormal\_long\_term\_variability | mean\_value\_of\_long\_term\_variability | histogram\_width | histogram\_min | histogram\_max | histogram\_number\_of\_peaks | histogram\_number\_of\_zeroes | histogram\_mode | histogram\_mean | histogram\_median | histogram\_variance | histogram\_tendency | fetal\_health |
            | -------------- | ------------- | --------------- | --------------------- | -------------------- | --------------------- | ------------------------- | ---------------------------------- | ----------------------------------------- | ------------------------------------------------------------- | ---------------------------------------- | ---------------- | -------------- | -------------- | ---------------------------- | ----------------------------- | --------------- | --------------- | ----------------- | ------------------- | ------------------- | ------------- |
            | 120            | 0             | 0               | 0                     | 0                    | 0                     | 0                         | 73                                 | 0.5                                       | 43                                                            | 2.4                                      | 64               | 62             | 126            | 2                            | 0                             | 120             | 137             | 121               | 73                  | 1                   | 2             |
            | 132            | 0.006         | 0               | 0.006                 | 0.003                | 0                     | 0                         | 17                                 | 2.1                                       | 0                                                             | 10.4                                     | 130              | 68             | 198            | 6                            | 1                             | 141             | 136             | 140               | 12                  | 0                   | 1             |
            | 133            | 0.003         | 0               | 0.008                 | 0.003                | 0                     | 0                         | 16                                 | 2.1                                       | 0                                                             | 13.4                                     | 130              | 68             | 198            | 5                            | 1                             | 141             | 135             | 138               | 13                  | 0                   | 1             |
        
  - Note: NA
  - Citations
    - Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318 [Link](https://onlinelibrary.wiley.com/doi/10.1002/1520-6661(200009/10)9:5%3C311::AID-MFM12%3E3.0.CO;2-9)


#### Lymphography Data Set

  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Lymphography)
  -   Data Type: Tabular 
  -   Size: 6 KB
  -   Example of data + Special Instructions(if any) 
      1. Download lymphography.data stored in Data Folder from Source 
      2. Example: CSV version
         <img width="1236" alt="Screenshot 2022-07-18 at 3 13 38 PM" src="https://user-images.githubusercontent.com/66881214/179461104-07f53663-be9a-4641-9bb5-d8f6d5f2eb6f.png">
         
         Columns present (from left to right): 
         * class: normal find, metastases, malign lymph, fibrosis
         * lymphatics: normal, arched, deformed, displaced
         * block of affere: no, yes
         * bl. of lymph. c: no, yes
         * bl. of lymph. s: no, yes
         * by pass: no, yes
         * extravasates: no, yes
         * regeneration of: no, yes
         * early uptake in: no, yes
         * lym.nodes dimin: 0-3
         * lym.nodes enlar: 1-4
         * changes in lym.: bean, oval, round
         * defect in node: no, lacunar, lac. marginal, lac. central
         * changes in node: no, lacunar, lac. margin, lac. central
         * changes in stru: no, grainy, drop-like, coarse, diluted, reticular, stripped, faint,
         * special forms: no, chalices, vesicles
         * dislocation of: no, yes
         * exclusion of no: no, yes
         * no. of nodes in: 0-9, 10-19, 20-29, 30-39, 40-49, 50-59, 60-69, >=70
         
         All attribute values in the database have been entered as numeric values corresponding to their index in the list of attribute values for that attribute domain as given above. 
         
         For example, a '3' in first column (refer to first row of image above) will correspond to class = malign lymph
         
  -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
            
      To download as .csv file, right click on lymphography.data as shown :
            
      <img width="828" alt="Screenshot 2022-07-18 at 3 10 34 PM" src="https://user-images.githubusercontent.com/66881214/179460679-5a5e0e31-01d6-4f82-b77d-17e8b9c04872.png">

      Proceed to add the .csv extention in file name and save to desired location
      
      <img width="329" alt="Screenshot 2022-07-18 at 3 10 55 PM" src="https://user-images.githubusercontent.com/66881214/179460724-4e670fc5-c8e5-4dc0-aac5-f64ee191e21b.png">

  -   Citations
      - This breast cancer domain was obtained from the University Medical Centre, Institute of Oncology, Ljubljana, Yugoslavia. Thanks go to M. Zwitter and M. Soklic for providing the data. Please include this citation if you plan to use this database.
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science


#### Monkeypox Skin Lesion Dataset 
  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/nafin59/monkeypox-skin-lesion-dataset)
  
  - Data Type: Image + Tabular   
  
  -   Size of files
      -  1.5MB for Original Images folder
      -  5KB for Monkeypox_Dataset_metadata.csv
      -  25.9MB for Augmented_Images.zip
      -  20.9MB for Fold1
  -   Example of data + Special Instructions(if any) 
      1. Download relevant files from Source 
         - Users may choose to use the folds/augmented images directly (Refer to source for more information)
      2. Example:  
         
         Monkeypox: <img src="https://user-images.githubusercontent.com/66881214/179441844-22a9b005-841c-41f4-8d59-e3cde0d03843.jpg" width="150" height="150">
         
         Others:  <img src="https://user-images.githubusercontent.com/66881214/179441888-5c49b47e-00da-4a05-a4c7-43f583ad1110.jpg" width="150" height="150">
        
  - Note: There is a csv file that indicates the labels of the images. This may not be needed as the images are already sorted into their respective folders in main folder  
          <img width="132" alt="Screenshot 2022-07-18 at 11 46 15 AM" src="https://user-images.githubusercontent.com/66881214/179442387-5fbe6faa-bade-497d-bdc0-e8e4749543b2.png">

  - Citations
    - If this dataset helped your research, please cite:
Ali, S. N., Ahmed, M. T., Paul, J., Jahan, T., Sani, S. M. Sakeef, Noor, N., & Hasan, T. (2022). [Monkeypox Skin Lesion Detection Using Deep Learning Models: A Preliminary Feasibility Study](https://arxiv.org/abs/2207.03342). arXiv preprint arXiv:2207.03342.


#### Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Parkinson+Speech+Dataset+with++Multiple+Types+of+Sound+Recordings)
  
  - Data Type: Text/Tabular  
  
  -   Size of files
      -  194KB for train_data.txt 
      -  47KB for test_data.txt
  -   Example of data + Special Instructions(if any) 
      1. Download Parkinson_Multiple_Sound_Recording.rar from Data Folder from Source 
      2. Example:  
 
         <img width="1270" alt="Screenshot 2022-07-15 at 3 28 31 PM" src="https://user-images.githubusercontent.com/66881214/179174170-e8b8e140-44ba-48f7-b1d1-198b3a6cd8d0.png">
         
         Columns present (from left to right):
         * Subject id
         * features(column 2 to 27)
           - features 1-5: Jitter (local),Jitter (local, absolute),Jitter (rap),Jitter (ppq5),Jitter (ddp)
           - features 6-11: Shimmer (local),Shimmer (local, dB),Shimmer (apq3),Shimmer (apq5), Shimmer (apq11),Shimmer (dda)
           - features 12-14: AC,NTH,HTN
           - features 15-19: Median pitch,Mean pitch,Standard deviation,Minimum pitch,Maximum pitch
           - features 20-23: Number of pulses,Number of periods,Mean period,Standard deviation of period
           - features 24-26: Fraction of locally unvoiced frames,Number of voice breaks,Degree of voice breaks
         * UPDRS
         * class information (not present in test_data.txt)
         
  - Note: Dataset from Source is of .rar file. To open: 
    - For Macbook
      1. Download The Unarchiver from App Store. Ensure that RAR Archive is selected under Preferences as shown (Others are optional):
  
         <img width="596" alt="Screenshot 2022-07-15 at 3 17 47 PM" src="https://user-images.githubusercontent.com/66881214/179172301-6678bb1f-1637-4040-8279-9c19a36f69c2.png">
         
      2. Right click on downloaded file and click open with The Unarchiver and both files (train_data.txt and test_data.txt) can be accessed.
      3. To convert to CSV file, rename train_data.txt to train_data.csv
      
    - For Windows 
      [Click here for more information](https://www.hellotech.com/guide/for/how-to-open-rar-files-mac-windows-10)  
      
  - Citations
    - Erdogdu Sakar, B., Isenkul, M., Sakar, C.O., Sertbas, A., Gurgen, F., Delil, S., Apaydin, H., Kursun, O., 'Collection and Analysis of a Parkinson Speech Dataset with Multiple Types of Sound Recordings', IEEE Journal of Biomedical and Health Informatics, vol. 17(4), pp. 828-834, 2013.
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Parkinson Tappy Keystroke Data

  -   Source:  [Click here to proceed to site](https://physionet.org/content/tappy/1.0.0/)
  
  -   Data Type: Text  
  
  -   Size of files
      - 43KB for Archived users  
      - 549.7MB for Tappy Data 
         
  -   Example of data + Special Instructions(if any) 
      1. Download files from Source.
      2. Example: 
         
         Each user will have their corresponding text file in Archived users with the following information: 
         
         <img width="454" alt="Screenshot 2022-07-20 at 5 10 10 PM" src="https://user-images.githubusercontent.com/66881214/179944256-b890ab5f-1d29-45ed-9c6c-13d9d0057d53.png">
         
         In Tappy Data folder, a participant may have more than one file. The filename comprises the 10 character code (matching the user details file) and the YYMM of the data:
         
         <img width="541" alt="Screenshot 2022-07-20 at 5 12 33 PM" src="https://user-images.githubusercontent.com/66881214/179944770-d19779aa-a9ba-43b2-89d9-94b9b5c42ec7.png">


  -   Citations
      - Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
      - Adams WR (2017) High-accuracy detection of early Parkinson's Disease using multiple characteristics of finger movement while typing. PLOS ONE 12(11): e0188226. https://doi.org/10.1371/journal.pone.0188226

#### Patient Physician Medical Interviews 
  - Source:  [Click here to proceed to site](https://figshare.com/s/d83162fad67407081b32/articles/16550013)
  - Data Type: Audio + Free Text 
  -   Size: 1.05 GB 
  -   Example of data + Special Instructions(if any) 
      1. Download Data.zip from source 
      2. Example: CAR0001.mp3 in Audio Recordings will correspond to CAR0001.txt in Clean Transcripts
         
         https://user-images.githubusercontent.com/66881214/179450404-a22b08df-2073-4193-ab42-fbf1483f25ba.mp4
         
         <details><summary>Click here to expand full clean transcript</summary>
         <p>
    
              D: What brought you in today?

              P: Sure, I'm I'm just having a lot of chest pain and and so I thought I should get it checked out.

              D: OK, before we start, could you remind me of your gender and age? 

              P: Sure 39, I'm a male.

              D: OK, and so when did this chest pain start?

              P: It started last night, but it's becoming sharper.

              D: OK, and where is this pain located? 

              P: It's located on the left side of my chest.

              D: OK, and, so how long has it been going on for then if it started last night?

              P: So I guess it would be a couple of hours now, maybe like 8.

              D: OK. Has it been constant throughout that time, or uh, or changing? 

              P: I would say it's been pretty constant, yeah.

              D: OK, and how would you describe the pain? People will use words sometimes like sharp, burning, achy. 

              P: I'd say it's pretty sharp, yeah.

              D: Sharp OK. Uh, anything that you have done tried since last night that's made the pain better?

              P: Um not laying down helps.

              D: OK, so do you find laying down makes the pain worse?

              P: Yes, definitely.

              D: OK, do you find that the pain is radiating anywhere?

              P: No.

              D: OK, and is there anything else that makes the pain worse besides laying down? 

              P: Not that I've noticed, no.

              D: OK, so not like taking a deep breath or anything like that?

              P: Maybe taking a deep breath. Yeah.

              D: OK. And when the pain started, could you tell me uh, could you think of anything that you were doing at the time?

              P: I mean, I was moving some furniture around, but, that I've done that before.

              D: OK, so you didn't feel like you hurt yourself when you were doing that?

              P: No.

              D: OK, and in regards to how severe the pain is on a scale of 1 to 10, 10 being the worst pain you've ever felt, how severe would you say the pain is?

              P: I'd say it's like a seven or eight. It's pretty bad.

              D: OK, and with the pain, do you have any other associated symptoms?

              P: I feel a little lightheaded and I'm having some trouble breathing.

              D: OK. Have you had any loss of consciousness?

              P: No.

              D: OK. Uh, have you been experiencing any like racing of the heart? 

              P: Um, a little bit, yeah.

              D: OK. And have you been sweaty at all?

              P: Just from the from having issues breathing.

              D: OK, have you been having issues breathing since the pain started? 

              P: Yes.

              D: OK. Um recently have you had any periods of time where you like have been immobilized or or, you haven't been like able to move around a lot?

              P: No no. 

              D: OK. And have you been feeling sick at all? Any infectious symptoms? 

              P: No. 

              D: OK, have you had any nausea or vomiting? 

              P: No. 

              D: Any fevers or chills?

              P: No. 

              D: OK, how about any abdominal pain?

              P: No.

              D: Any urinary problems?

              P: No.

              D: Or bowel problems?

              P: No.

              D: OK, have you had a cough?

              P: No.

              D: OK. You haven't brought up any blood?

              P: No. 

              D: OK, have you had a wheeze with your difficulty breathing?

              P: No, not that I've heard.

              D: OK, any changes to the breath sounds at all like any noisy breathing?

              P: No. Well, I guess if when I'm really having trouble breathing, yeah.

              D: OK. Has anything like this ever happened to you before?

              P: No. 
             
              D: No, OK. And have you had any night sweats?
             
              P: No
             
              D: Alright, and then how about any rashes or skin changes?
             
              P: No rashes, but I guess like my neck seems to be a little swollen. 

              D: OK, do you have any neck pain? 

              P: No. 

              D: OK, have you had any like accidents like a car accident or anything where you really jerked your neck? 

              P: No.

              D: OK. Um any any trauma at all to the chest or or back?

              P: No.

              D: OK, so just in regards to past medical history, do you have any prior medical conditions? 

              P: No.

              D: OK, any recent hospitalizations?

              P: No. 

              D: OK, any prior surgeries?

              P: No.

              D: OK, do you take any medications regularly? Are they prescribed or over the counter?

              P: No. 

              D: Alright, how about any allergies to medications? 

              P: None.

              D: Alright, any immunizations or are they up to date? 

              P: They are all up to date.

              D: Excellent. Alright, and could you tell me a little bit about your living situation currently? 

              P: Sure, I live in an apartment by myself. I, uh, yep, that's about it.

              D: OK, and how do you support yourself financially?

              P: I'm an accountant.

              D: OK, sounds like a pretty stressful job or that it can be. Do you smoke cigarettes? 

              P: I do.

              D: OK, and how much do you smoke?

              P: I smoke about a pack a day.

              D: OK, how long have you been smoking for?

              P: For the past 10 to 15 years.

              D: OK, and do you smoke cannabis?

              P: Uh sometimes. 

              D: Uh, how much marijuana would you smoke per per week? 

              P: Per week, maybe about 5 milligrams. Not that much.

              D: OK, and do you use any other recreational drugs like cocaine, crystal, meth, opioids?

              P: No.

              D: OK. Have you used IV drugs before?

              P: No. 

              D: OK. And do you drink alcohol?

              P: I do.

              D: OK. How much alcohol do you drink each week?

              P: Uhm about I would say I have like one or two drinks a day, so about 10 drinks a week. 

              D: OK, uh, yeah and um alright, and then briefly, could you tell me a little bit about your like diet and exercise?

              P: Sure, I try to eat healthy for dinner at least, but most of my lunches are, uh I eat out. And then in terms of exercise, I try to exercise every other day, I run for about half an hour.

              D; OK, well that's great that you've been working on the the activity and the diet as well. So has anything like this happened in your family before?

              P: No. 

              D: OK, has anybody in the family had a heart attack before?

              P: Actually, yes, my father had a heart attack when he was 45.

              D: OK, and anybody in the family have cholesterol problems?

              P: I think my father did.

              D: I see OK, and how about anybody in the family have a stroke?

              P: No strokes.

              D: OK, and then any cancers in the family?

              P: No.

              D: OK, and is there anything else that you wanted to tell me about today that that I on on history? 

              P: No, I don't think so. I think you asked me everything.

         </p>
         </details>
                 
  - Note: First 3 characters of the file name represent the categories the case belong to. 
    - Respiratory cases (designated “RES”)
    - Musculoskeletal cases (designated “MSK”)
    - Cardiac cases (designated “CAR”)
    - Dermatological case (designated “DER”)
    - Gastrointestinal cases (designated “GAS”)       
      
  - Citations
    - Fareez, F., Parikh, T., Wavell, C. et al. A dataset of simulated patient-physician medical interviews with a focus on respiratory cases. Sci Data 9, 313 (2022). [Link](https://doi.org/10.1038/s41597-022-01423-1)
