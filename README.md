# Public Data Documentation

A collection of public healthcare datasets

Type of datasets include 

1. Tabular 
2. Images 
3. Free Text 
4. Audio 

For large datasets, a short preview can be found in their respective folders in this repository. A link is provided in their sections below.

Table of Contents 

1. [Cancer Datasets](#Cancer-Datasets)
    - [Breast Cancer Data set](#Breast-Cancer-Data-set)
    - [Breast Cancer Wisconsin (Original) Data Set](#Breast-Cancer-Wisconsin-Original-Data-Set)
    - [Breast Cancer Wisconsin (Prognostic) Data Set](#Breast-Cancer-Wisconsin-Prognostic-Data-Set)
    - [Breast Cancer Wisconsin (Diagnostic) Data Set](#Breast-Cancer-Wisconsin-Diagnostic-Data-Set)
    - [Cervical cancer (Risk Factors) Data Set](#Cervical-cancer-Risk-Factors-Data-Set)
    - [Lung and Colon Cancer Histopathological Images](#Lung-and-Colon-Cancer-Histopathological-Images)
    - [Skin Cancer MNIST: HAM10000](#Skin-Cancer-MNIST-HAM10000)
    - [Thoracic Surgery Data Data Set](#Thoracic-Surgery-Data-Data-Set)
    
2. [Chest Related Datasets](#Chest-Related-Datasets)
    - [NIH Chest X-ray Dataset](#NIH-Chest-X-ray-Dataset) 
    - [Chest X-ray Images Pneumonia](#Chest-X-ray-Images-Pneumonia)
    - [Respiratory Sound Database](#Respiratory-Sound-Database)

3. [Heart Related Datasets](#Heart-Related-Datasets)
    - [Heart Failure Prediction](#Heart-Failure-Prediction)

4. [Kidney Related Datasets](#Kidney-Related-Datasets)
    - [Risk Factor prediction of Chronic Kidney Disease Data Set](#Risk-Factor-prediction-of-Chronic-Kidney-Disease-Data-Set)

5. [Other Diseases](#Other-Diseases) 
    - [Chula RBC-12-Dataset](#Chula-RBC-12-Dataset)  
    - [Diabetes 130-US hospitals for years 1999-2008 Data Set](#Diabetes-130-US-hospitals-for-years-1999-2008-Data-Set) 
    - [Diabetic Retinopathy Debrecen Data Set Data Set](#Diabetic-Retinopathy-Debrecen-Data-Set-Data-Set)
    - [Lymphography Data Set](#Lymphography-Data-Set)
    - [Monkeypox Skin Lesion Dataset](#Monkeypox-Skin-Lesion-Dataset)
    - [Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set](#Parkinson-Speech-Dataset-with-Multiple-Types-of-Sound-Recordings-Data-Set)
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
      2. Example: [Click here to preview top 2 records of dataset](https://github.com/joeytxy/public-data-documentation-/blob/main/Cancer%20Datasets/Breast%20Cancer%20Wisconsin%20(Prognostic)%20Data%20Set/Preview%20of%20Data)
            
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
      2. Example: [Click here to preview top 2 records of dataset](https://github.com/joeytxy/public-data-documentation-/blob/main/Cancer%20Datasets/Breast%20Cancer%20Wisconsin%20(Diagnostic)%20Data%20Set/Preview%20of%20Data)
            
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

#### Cervical cancer (Risk Factors) Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29)
  - Data Type: Tabular 
  -   Size: 102 KB
  -   Example of data + Special Instructions(if any) 
      1. Download risk_factors_cervical_cancer.csv from Data Folder from Source 
      2. Example: [Click here to preview top 2 records of dataset](https://github.com/joeytxy/public-data-documentation-/blob/main/Cancer%20Datasets/Cervical%20cancer%20(Risk%20Factors)%20Data%20Set/Preview%20of%20Data)
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
       
### Chest Related Datasets

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

### Heart Related Datasets

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

#### Risk Factor prediction of Chronic Kidney Disease Data Set

  -   Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Risk+Factor+prediction+of+Chronic+Kidney+Disease)
  -   Data Type: Tabular
  -   Size: 34KB3
  -   Example of data + Special Instructions(if any) 
      1. Download ckd-dataset-v2.csv from Data Folder from Source
      2. Example: [Click here to preview dataset without special characters](https://github.com/joeytxy/public-data-documentation-/blob/main/Kidney%20Related%20Datasets/Risk%20Factor%20prediction%20of%20Chronic%20Kidney%20Disease%20Data%20Set/Preview%20of%20Data%20(Without%20special%20characters))
      
  -   Note: According to site, pre-processing has to be done for any machine learning algorithm to be applied. Some special characters might be observed in Microsoft Excel ([See here](https://github.com/joeytxy/public-data-documentation-/blob/main/Kidney%20Related%20Datasets/Risk%20Factor%20prediction%20of%20Chronic%20Kidney%20Disease%20Data%20Set/Preview%20of%20Data%20(Microsoft%20Excel))). Using other applications such as Numbers(Macbook), these special characters correspond to mathematical symbols such as >= or <=
  -   Citations
      - M. A. Islam, S. Akter, M. S. Hossen, S. A. Keya, S. A. Tisha and S. Hossain, 'Risk Factor Prediction of Chronic Kidney Disease based on Machine Learning Algorithms,' 2020 3rd International Conference on Intelligent Sustainable Systems (ICISS), Thoothukudi, India, 2020, pp. 952-957, doi: 10.1109/ICISS49785.2020.9315878.  [Link](https://ieeexplore.ieee.org/document/9315878)
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

### Other Diseases 

#### Chula RBC-12-Dataset
  -   Source:  [Click here to proceed to site](https://github.com/Chula-PIC-Lab/Chula-RBC-12-Dataset)
  
  -   Data Type: Images + Text/Tabular
  
  -   Size: Depends. One image is about 79KB. 
  
  -   Example of data + Special Instructions(if any) 
      1. Download images in Dataset folder and corresponding text files in Label folder from Source.
         
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

#### Diabetes 130-US hospitals for years 1999-2008 Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
  
  - Data Type: Tabular 
  
  -   Size of files
      -  19.2MB for diabetic_data.csv
      -  3KB for IDs_mapping.csv
  -   Example of data + Special Instructions(if any) 
      1. Download dataset_diabetes.zip from Data Folder from Source 
      2. Example: [Click here to preview top 2 records of dataset](https://github.com/joeytxy/public-data-documentation-/blob/main/Other%20Diseases/Diabetes%20130-US%20hospitals%20for%20years%201999-2008%20Data%20Set/Preview%20of%20Data)
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
      
    -For Windows (to be filled)
      
  - Citations
    - Erdogdu Sakar, B., Isenkul, M., Sakar, C.O., Sertbas, A., Gurgen, F., Delil, S., Apaydin, H., Kursun, O., 'Collection and Analysis of a Parkinson Speech Dataset with Multiple Types of Sound Recordings', IEEE Journal of Biomedical and Health Informatics, vol. 17(4), pp. 828-834, 2013.
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science

#### Patient Physician Medical Interviews 
  - Source:  [Click here to proceed to site](https://figshare.com/s/d83162fad67407081b32/articles/16550013)
  - Data Type: Audio + Free Text 
  -   Size: 1.05 GB 
  -   Example of data + Special Instructions(if any) 
      1. Download Data.zip from source 
      2. Example: CAR0001.mp3 in Audio Recordings will correspond to CAR0001.txt in Clean Transcripts
         
         https://user-images.githubusercontent.com/66881214/179450404-a22b08df-2073-4193-ab42-fbf1483f25ba.mp4
         
         The clean transcript can be found [here](https://github.com/joeytxy/public-data-documentation-/blob/main/Other%20Diseases/Patient-Physician%20Medical%20Interviews/Clean%20Transcript%20Example)
                 
  - Note: First 3 characters of the file name represent the categories the case belong to. 
    - Respiratory cases (designated “RES”)
    - Musculoskeletal cases (designated “MSK”)
    - Cardiac cases (designated “CAR”)
    - Dermatological case (designated “DER”)
    - Gastrointestinal cases (designated “GAS”)       
      
  - Citations
    - Fareez, F., Parikh, T., Wavell, C. et al. A dataset of simulated patient-physician medical interviews with a focus on respiratory cases. Sci Data 9, 313 (2022). [Link](https://doi.org/10.1038/s41597-022-01423-1)


