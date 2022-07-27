# Public Data Documentation

A collection of public healthcare datasets

Type of datasets include 

1. Tabular 
2. Images 
3. Free Text 
4. Audio 

## Table of Contents

1. [Cancer Datasets](#Cancer-Datasets)
    - [Breast Cancer Data set](#Breast-Cancer-Data-set)
    - [Breast Cancer Wisconsin (Original) Data Set](#Breast-Cancer-Wisconsin-Original-Data-Set)
    - [Breast Cancer Wisconsin (Prognostic) Data Set](#Breast-Cancer-Wisconsin-Prognostic-Data-Set)
    - [Breast Cancer Wisconsin (Diagnostic) Data Set](#Breast-Cancer-Wisconsin-Diagnostic-Data-Set)
    - [Breast Cancer Dataset(SEER)](#Breast-Cancer-Dataset-SEER)
    - [Lymphography Data Set](#Lymphography-Data-Set)
    - [Colorectal Cancer Dataset](#Colorectal-Cancer-Dataset)
    - [Cervical cancer (Risk Factors) Data Set](#Cervical-cancer-Risk-Factors-Data-Set)
    - [CT Medical Images](#CT-Medical-Images)
    - [Leukemia Classification](#Leukemia-Classification)
    - [Lung and Colon Cancer Histopathological Images](#Lung-and-Colon-Cancer-Histopathological-Images)
    - [Skin Cancer MNIST: HAM10000](#Skin-Cancer-MNIST-HAM10000)
    - [Thoracic Surgery Data Data Set](#Thoracic-Surgery-Data-Data-Set)
    
2. [Diabetes Dataset](#Diabetes-Dataset)
    - [Association of body mass index and age with incident diabetes in Chinese adults](#Association-of-body-mass-index-and-age-with-incident-diabetes-in-Chinese-adults)
    - [Clinical characteristics, types and complications of diabetics with young age at the onset](#Clinical-characteristics-types-and-complications-of-diabetics-with-young-age-at-the-onset)
    - [Diabetes 130-US hospitals for years 1999-2008 Data Set](#Diabetes-130-US-hospitals-for-years-1999-2008-Data-Set) 
    - [Diabetic Retinopathy Debrecen Data Set Data Set](#Diabetic-Retinopathy-Debrecen-Data-Set-Data-Set)
    - [Early Classification of Diabetes](#Early-Classification-of-Diabetes)

3. [Monkeypox](#Monkeypox)
   - [Monkeypox Skin Lesion Dataset](#Monkeypox-Skin-Lesion-Dataset)
   - [Clinical features of 21 human monkeypox cases seen at NDUTH 2017](#Clinical-features-of-21-human-monkeypox-cases-seen-at-NDUTH-2017)
    
4. [Parkinson Disease](#Parkinson-Disease)
    - [Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set](#Parkinson-Speech-Dataset-with-Multiple-Types-of-Sound-Recordings-Data-Set)
    - [Parkinson Tappy Keystroke Data](#Parkinson-Tappy-Keystroke-Data)
    - [Safety and Preliminary Efficacy of Intranasal Insulin for Cognitive Impairment in Parkinson Disease and Multiple System Atrophy](#Safety-and-Preliminary-Efficacy-of-Intranasal-Insulin-for-Cognitive-Impairment-in-Parkinson-Disease-and-Multiple-System-Atrophy)

5. [Brain Related Datasets](#Brain-Related-Datasets)
    - [Brain tumor data](#Brain-tumor-data)
    - [MRI and Alzheimers](#MRI-and-Alzheimers)
    - [Stroke Prediction](#Stroke-Prediction)
    
6. [Eye Related Datasets](#Eye-Related-Datasets)
   - [Bajwa Hospital (Multi Eye Disease Dataset)](#Bajwa-Hospital-Multi-Eye-Disease-Dataset)
   - [Retinal OCT Images(optical coherence tomography)](#Retinal-OCT-Images-optical-coherence-tomography)

7. [Gastrointestinal Related Datasets](#Gastrointestinal-Related-Datasets)
   -  [Bowel Sounds](#Bowel-Sounds) 
   -  [Kvasir Dataset a](#Kvasir-Dataset)

8. [Heart Related Datasets](#Heart-Related-Datasets)
    - [An Extensive Dataset for the Heart Disease Classification System](#An-Extensive-Dataset-for-the-Heart-Disease-Classification-System)
    - [Heart Failure Prediction](#Heart-Failure-Prediction)

9. [Kidney Related Datasets](#Kidney-Related-Datasets)
    - [A Brazilian dataset for screening the risk of the Chronic Kidney Disease](#A-Brazilian-dataset-for-screening-the-risk-of-the-Chronic-Kidney-Disease)
    - [Risk Factor prediction of Chronic Kidney Disease Data Set](#Risk-Factor-prediction-of-Chronic-Kidney-Disease-Data-Set)

10. [Lung Related Datasets](#Lung-Related-Datasets)
    - [A dataset of lung sounds recorded from the chest wall using an electronic stethoscope](#A-dataset-of-lung-sounds-recorded-from-the-chest-wall-using-an-electronic-stethoscope)
    - [NIH Chest X-ray Dataset](#NIH-Chest-X-ray-Dataset) 
    - [Chest X-ray Images Pneumonia](#Chest-X-ray-Images-Pneumonia)
    - [Covid19 Coswara Dataset](#Covid19-Coswara-Dataset)  
    - [QaTa COV19 Dataset](#QaTa-COV19-Dataset)
    - [Respiratory Sound Database](#Respiratory-Sound-Database)
    
11. [Medical Transcripts](#Medical-Transcript)
    - [Adapting Phrase-based Machine Translation to Normalise Medical Terms in Social Media Messages](#Adapting-Phrase-based-Machine-Translation-to-Normalise-Medical-Terms-in-Social-Media-Messages)
    - [ADE Corpus V2](#ADE-Corpus-V2)
    - [CDR BioCreative V Chemical Disease Relation corpus](#CDR-BioCreative-V-Chemical-Disease-Relation-corpus)
    - [i2b2 dataset(no preview)](#i2b2-dataset-no-preview)
    - [MeDAL Dataset](#MeDAL-Dataset)
    - [MedMCQA](#MedMCQA)
    - [MedMentions](#MedMentions)
    - [MedQA](#MedQA)
    - [MedQuAD](#MedQuAD)
    - [NCBI Disease Corpus](#NCBI-Disease-Corpus)
    - [Patient Physician Medical Interviews](#Patient-Physician-Medical-Interviews)
    - [PubMed 200k RCT dataset](#PubMed-200k-RCT-dataset)

12. [Others](#Others) 
    - [Chula RBC-12-Dataset](#Chula-RBC-12-Dataset)
    - [Fetal Health Classification](#Fetal-Health-Classification)
    - [Disease-symptom associations generated by an automated method based on information in textual discharge summaries of patients at New York Presbyterian Hospital admitted during 2004](#Disease-symptom-associations-generated-by-an-automated-method-based-on-information-in-textual-discharge-summaries-of-patients-at-New-York-Presbyterian-Hospital-admitted-during-2004)
---  

## Cancer Datasets

#### Breast Cancer Data set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer)
  -   Data Type: Text/Tabular 
  -   Possible uses: Building a predictive machine learning model for breast cancer
  -   Size: 19 KB
  -   Example of data + Special Instructions(if any):
   
         Download breast-cancer.data stored in Data Folder from Source 
         <details><summary>Example: CSV version</summary>
         <p>
      
         <img width="652" alt="Screenshot 2022-07-14 at 4 33 48 PM" src="https://user-images.githubusercontent.com/66881214/178939273-d1810b64-d7c3-46ac-9ddd-bb9c076c89cb.png">
         
         </p>
         </details>
         
         <details><summary>Columns present (from left to right):</summary>
         <p>
            
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
         </p>
         </details>

  -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
            
      <details><summary>To download as .csv file</summary>
      <p> 
          
      Right click on breast-cancer.data as shown :
            
      <img width="698" alt="Screenshot 2022-07-14 at 4 44 53 PM" src="https://user-images.githubusercontent.com/66881214/178941770-0c1bf718-e4c1-4eb3-bc65-7e755211f723.png">
            
      Proceed to add the .csv extention in file name and save to desired location
            
      <img width="323" alt="Screenshot 2022-07-14 at 4 46 13 PM" src="https://user-images.githubusercontent.com/66881214/178942033-445f2292-c76f-4967-b090-2dc35f269737.png">
          
      </p>
      </details>

  -   Citations
      ```
      - This breast cancer domain was obtained from the University Medical Centre, Institute of Oncology, Ljubljana, Yugoslavia. Thanks go to M. Zwitter and M. Soklic for providing the data. Please include this citation if you plan to use this database.
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
      ```
      
#### Breast Cancer Wisconsin (Original) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29)
  -   Data Type: Text/Tabular 
  -   Possible uses: Building a predictive machine learning model for breast cancer
  -   Size: 20 KB
  -   Example of data + Special Instructions(if any):
     
         Download breast-cancer-wiscoinsin.data stored in Data Folder from Source 
         <details><summary>Example: CSV version</summary>
         <p>
             
         <img width="718" alt="Screenshot 2022-07-14 at 6 11 27 PM" src="https://user-images.githubusercontent.com/66881214/178959171-12d41257-eadc-4bea-bedd-0f13b67adbbb.png">
          
         </p>
         </details>
         
         <details><summary>Columns present (from left to right):</summary>
         <p>
         
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
             
         </p>
         </details>
  
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       <details><summary>To download as .csv file</summary>
       <p>
           
       Right click on breast-cancer-wiscoinsin.data as shown :
            
       <img width="700" alt="Screenshot 2022-07-14 at 5 58 13 PM" src="https://user-images.githubusercontent.com/66881214/178956694-8c413b09-d736-49be-9776-50b8a8a5db5d.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="322" alt="Screenshot 2022-07-14 at 5 58 32 PM" src="https://user-images.githubusercontent.com/66881214/178956742-b203502f-0e8d-4eae-b31b-02dc2da7d2ac.png">
           
       </p>
       </details>
         
  -   Citations
      ```
      - This breast cancer databases was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg. If you publish results when using this database, then please include this information in your acknowledgements. Also, please cite one or more of:
     
        1. O. L. Mangasarian and W. H. Wolberg: "Cancer diagnosis via linear programming", SIAM News, Volume 23, Number 5, September 1990, pp 1 & 18.
            
        2. William H. Wolberg and O.L. Mangasarian: "Multisurface method of pattern separation for medical diagnosis applied to breast cytology", Proceedings of the National Academy of Sciences, U.S.A., Volume 87, December 1990, pp 9193-9196.
            
        3. O. L. Mangasarian, R. Setiono, and W.H. Wolberg: "Pattern recognition via linear programming: Theory and application to medical diagnosis", in: "Large-scale numerical optimization", Thomas F. Coleman and Yuying Li, editors, SIAM Publications, Philadelphia 1990, pp 22-30.
            
        4. K. P. Bennett & O. L. Mangasarian: "Robust linear programming discrimination of two linearly inseparable sets", Optimization Methods and Software 1, 1992, 23-34 (Gordon & Breach Science Publishers).
       - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
       ```

#### Breast Cancer Wisconsin (Prognostic) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Prognostic%29)
  -   Data Type: Text/Tabular 
  -   Possible uses: Building a predictive machine learning model for breast cancer
  -   Size: 44 KB
  -   Example of data + Special Instructions(if any):
      
         Download wpbc.data stored in Data Folder from Source 
         <details><summary>Example (No headers)</summary>
         <p>
             
       
         | 119513 | N | 31 | 18.02 | 27.6  | 117.5 | 1013 | 0.09489 | 0.1036 | 0.1086 | 0.07055 | 0.1865 | 0.06333 | 0.6249 | 1.89   | 3.972 | 71.55 | 0.004433 | 0.01421 | 0.03233 | 0.009854 | 0.01694 | 0.003495 | 21.63 | 37.08 | 139.7 | 1436 | 0.1195 | 0.1926 | 0.314  | 0.117  | 0.2677 | 0.08113 | 5 | 5     |
         | ------ | - | -- | ----- | ----- | ----- | ---- | ------- | ------ | ------ | ------- | ------ | ------- | ------ | ------ | ----- | ----- | -------- | ------- | ------- | -------- | ------- | -------- | ----- | ----- | ----- | ---- | ------ | ------ | ------ | ------ | ------ | ------- | - | ----- |
         | 8423   | N | 61 | 17.99 | 10.38 | 122.8 | 1001 | 0.1184  | 0.2776 | 0.3001 | 0.1471  | 0.2419 | 0.07871 | 1.095  | 0.9053 | 8.589 | 153.4 | 0.006399 | 0.04904 | 0.05373 | 0.01587  | 0.03003 | 0.006193 | 25.38 | 17.33 | 184.6 | 2019 | 0.1622 | 0.6656 | 0.7119 | 0.2654 | 0.4601 | 0.1189  | 3 | 2     |

         </p>
         </details>
    
         <details><summary>Columns present (from left to right):</summary>
         <p>
             
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
         </p>
         </details>
            
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       <details><summary>To download as .csv file</summary>
       <p>
           
       Right click on wpbc.data as shown :
            
       <img width="909" alt="Screenshot 2022-07-14 at 9 07 11 PM" src="https://user-images.githubusercontent.com/66881214/178989493-b7de3cca-da5f-4598-83cb-a28838ec52e0.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="326" alt="Screenshot 2022-07-14 at 9 08 03 PM" src="https://user-images.githubusercontent.com/66881214/178989650-9b61aa22-48be-4c78-ad15-5d488fbbf0a7.png">
           
       </p>
       </details>
       
   -   Citations
       ```
       - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
       ```

#### Breast Cancer Wisconsin (Diagnostic) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
  -   Data Type: Text/Tabular 
  -   Possible uses: Building a predictive machine learning model for breast cancer
  -   Size: 124 KB
  -   Example of data + Special Instructions(if any):
    
         Download wdbc.data stored in Data Folder from Source 
         <details><summary>Example(No headers)</summary>
         <p>

         | 842302 | M | 17.99 | 10.38 | 122.8 | 1001 | 0.1184  | 0.2776  | 0.3001 | 0.1471  | 0.2419 | 0.07871 | 1.095  | 0.9053 | 8.589 | 153.4 | 0.006399 | 0.04904 | 0.05373 | 0.01587 | 0.03003 | 0.006193 | 25.38 | 17.33 | 184.6 | 2019 | 0.1622 | 0.6656 | 0.7119 | 0.2654 | 0.4601 | 0.1189  |
         | ------ | - | ----- | ----- | ----- | ---- | ------- | ------- | ------ | ------- | ------ | ------- | ------ | ------ | ----- | ----- | -------- | ------- | ------- | ------- | ------- | -------- | ----- | ----- | ----- | ---- | ------ | ------ | ------ | ------ | ------ | ------- |
         | 842517 | M | 20.57 | 17.77 | 132.9 | 1326 | 0.08474 | 0.07864 | 0.0869 | 0.07017 | 0.1812 | 0.05667 | 0.5435 | 0.7339 | 3.398 | 74.08 | 0.005225 | 0.01308 | 0.0186  | 0.0134  | 0.01389 | 0.003532 | 24.99 | 23.41 | 158.8 | 1956 | 0.1238 | 0.1866 | 0.2416 | 0.186  | 0.275  | 0.08902 |
             
         </p>
         </details>

         <details><summary>Columns present (from left to right):</summary>
         <p>
             
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
             
         </p>
         </details>
            
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       <details><summary>To download as .csv file</summary>
       <p>
       Right click on wdbc.data as shown :
            <img width="915" alt="Screenshot 2022-07-14 at 11 08 42 PM" src="https://user-images.githubusercontent.com/66881214/179015321-d168c542-291a-40af-8b6c-1703ce17a751.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="322" alt="Screenshot 2022-07-14 at 11 09 00 PM" src="https://user-images.githubusercontent.com/66881214/179015383-cdb7a990-cc67-47ec-ac68-3e1390ac657e.png">
        
       </p>
       </details>
       
   -   Citations
       ```
       - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
       ``` 
#### Breast Cancer Dataset(SEER)
  -   Source:  [Click here to proceed to site](https://ieee-dataport.org/open-access/seer-breast-cancer-data)
  -   Data Type: Tabular 
  -   Possible uses: Building a predictive machine learning model for breast cancer
  -   Size: 520KB
  -   Example of data + Special Instructions(if any):
       
         Download SEER Breast Cancer Dataset .csv from Source.

         <details><summary>Example</summary>
         <p>
         
         <img width="1371" alt="Screenshot 2022-07-27 at 4 46 46 PM" src="https://user-images.githubusercontent.com/66881214/181203944-a7271d26-88a9-4b7d-a683-5eecf55feb94.png">
             
         </p>
         </details>
               
  -   Note: NA
  -   Citations
      ```
      - JING TENG. (2019). SEER Breast Cancer Data. IEEE Dataport. https://dx.doi.org/10.21227/a9qy-ph35
      ```
#### Lymphography Data Set

  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Lymphography)
  -   Data Type: Tabular 
  -   Possible uses: Building a predictive machine learning model for malignant tumor 
  -   Size: 6 KB
  -   Example of data + Special Instructions(if any):
  
         Download lymphography.data stored in Data Folder from Source
         <details><summary>Example: CSV version</summary>
         <p>
         
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
         
         </p>
         </details>
         
  -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
            
      <details><summary>To download as .csv file</summary>
      <p>
      
      Right click on lymphography.data as shown :
            
      <img width="828" alt="Screenshot 2022-07-18 at 3 10 34 PM" src="https://user-images.githubusercontent.com/66881214/179460679-5a5e0e31-01d6-4f82-b77d-17e8b9c04872.png">

      Proceed to add the .csv extention in file name and save to desired location
      
      <img width="329" alt="Screenshot 2022-07-18 at 3 10 55 PM" src="https://user-images.githubusercontent.com/66881214/179460724-4e670fc5-c8e5-4dc0-aac5-f64ee191e21b.png">
      
      </p>
      </details>

  -   Citations
      ```
      - This lymphography domain was obtained from the University Medical Centre, Institute of Oncology, Ljubljana, Yugoslavia. Thanks go to M. Zwitter and M. Soklic for providing the data. Please include this citation if you plan to use this database.
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
      ```
       
#### Colorectal Cancer Dataset

  -   Source:  [Click here to proceed to site](https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest/download/)
  -   Data Type: Images 
  -   Possible uses: Gland segmentation problem with images of Haematoxylin and Eosin (H&E) stained slides
  -   Size: 259.4MB
  -   Example of data + Special Instructions(if any): 
    
         Download by clicking 'Warwick-QU-dataset' on Source
         <details><summary>Example</summary>
         <p>
         
         train_1.bmp (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179518421-dfb0da1b-3f34-480f-93c0-5d514a96ed7d.jpg" width="150" height="150">
         
         Each image will have its corresponding annotated image (filename_anno.bmp) and its grade in the Grade.csv file as shown:
         
         train_1_anno.bmp (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)) : <img src="https://user-images.githubusercontent.com/66881214/179518541-ffbe18d2-303f-4220-9378-5dc5be06f0e5.jpg" width="150" height="150">
         
         
         Grade: <img width="582" alt="Screenshot 2022-07-18 at 9 12 13 PM" src="https://user-images.githubusercontent.com/66881214/179518739-e211b4ea-69d4-4665-ac15-01ae2f2d97d1.png">
             
         </p>
         </details>

  - Note: 
  
    Comment regarding the annotated images can be found in the Q&A section in the same source link. 
    
    <details><summary>View screenshot</summary> 
    <p>
    
    <img width="511" alt="Screenshot 2022-07-18 at 9 16 42 PM" src="https://user-images.githubusercontent.com/66881214/179519661-a5465462-7033-479e-a641-9cae3c5889f8.png">
    
    </p>
    </details>
  
  - Citations
    ```
    - K. Sirinukunwattana, J. P. W. Pluim, H. Chen, X Qi, P. Heng, Y. Guo, L. Wang, B. J. Matuszewski, E. Bruni, U. Sanchez, A. Böhm, O. Ronneberger, B. Ben Cheikh, D. Racoceanu, P. Kainz, M. Pfeiffer, M. Urschler, D. R. J. Snead, N. M. Rajpoot, "Gland Segmentation in Colon Histology Images: The GlaS Challenge Contest" (http://arxiv.org/abs/1603.00275)
    - K. Sirinukunwattana, D.R.J. Snead, N.M. Rajpoot, "A Stochastic Polygons Model for Glandular Structures in Colon Histology Images," in IEEE Transactions on Medical Imaging, 2015 doi: 10.1109/TMI.2015.2433900 
    ```

#### Cervical cancer (Risk Factors) Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29)
  - Data Type: Tabular 
  - Possible uses: Building a predictive machine learning model for cervical cancer
  -   Size: 102 KB
  -   Example of data + Special Instructions(if any):
    
         Download risk_factors_cervical_cancer.csv from Data Folder from Source 
         <details><summary>Example</summary>
         <p>
           
         | Age | Number of sexual partners | First sexual intercourse | Num of pregnancies | Smokes | Smokes (years) | Smokes (packs/year) | Hormonal Contraceptives | Hormonal Contraceptives (years) | IUD | IUD (years) | STDs | STDs (number) | STDs:condylomatosis | STDs:cervical condylomatosis | STDs:vaginal condylomatosis | STDs:vulvo-perineal condylomatosis | STDs:syphilis | STDs:pelvic inflammatory disease | STDs:genital herpes | STDs:molluscum contagiosum | STDs:AIDS | STDs:HIV | STDs:Hepatitis B | STDs:HPV | STDs: Number of diagnosis | STDs: Time since first diagnosis | STDs: Time since last diagnosis | Dx:Cancer | Dx:CIN | Dx:HPV | Dx | Hinselmann | Schiller | Citology | Biopsy |
         | --- | ------------------------- | ------------------------ | ------------------ | ------ | -------------- | ------------------- | ----------------------- | ------------------------------- | --- | ----------- | ---- | ------------- | ------------------- | ---------------------------- | --------------------------- | ---------------------------------- | ------------- | -------------------------------- | ------------------- | -------------------------- | --------- | -------- | ---------------- | -------- | ------------------------- | -------------------------------- | ------------------------------- | --------- | ------ | ------ | -- | ---------- | -------- | -------- | ------ |
         | 18  | 4                         | 15                       | 1                  | 0      | 0              | 0                   | 0                       | 0                               | 0   | 0           | 0    | 0             | 0                   | 0                            | 0                           | 0                                  | 0             | 0                                | 0                   | 0                          | 0         | 0        | 0                | 0        | 0                         | ?                                | ?                               | 0         | 0      | 0      | 0  | 0          | 0        | 0        | 0      |
         | 15  | 1                         | 14                       | 1                  | 0      | 0              | 0                   | 0                       | 0                               | 0   | 0           | 0    | 0             | 0                   | 0                            | 0                           | 0                                  | 0             | 0                                | 0                   | 0                          | 0         | 0        | 0                | 0        | 0                         | ?                                | ?                               | 0         | 0      | 0      | 0  | 0          | 0        | 0        | 0      |

         </p>
         </details>
  
  - Note: NA
  - Citations
    ```     
    - Kelwin Fernandes, Jaime S. Cardoso, and Jessica Fernandes. 'Transfer Learning with Partial Observability Applied to Cervical Cancer Screening.' Iberian Conference on Pattern Recognition and Image Analysis. Springer International Publishing, 2017.
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
    ```

#### CT Medical Images

  -   Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/kmader/siim-medical-images?select=dicom_dir)
  -   Data Type: Images 
  -   Possible uses: Examining the trends in CT image data associated with using contrast and patient age/Build tools for automatically classifying these images when they have been misclassified
  -   Size of files
      - 52.8MB for dicom_dir folder 
      - 209.7MB for tiff_images folder
  -   Example of data + Special Instructions(if any):
       
         Download relevant folders from Source.

         <details><summary>Example</summary>
         <p>
       
         ID_0000_AGE_0060_CONTRAST_1_CT.dcm (converted to jpg [here](https://convertio.co/dcm-jpg/)): <img src="https://user-images.githubusercontent.com/66881214/179672281-09bf949d-3204-4f6f-a6e5-5e91bfffdee4.jpg" width="150" height="150">
   
         ID_0000_AGE_0060_CONTRAST_1_CT.tif (converted to jpg [here](https://www.freeconvert.com/tif-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179672420-3f9ea3e7-de97-4107-9fbd-52b0eb1702f9.jpg" width="150" height="150">

         <img width="1158" alt="Screenshot 2022-07-19 at 1 32 27 PM" src="https://user-images.githubusercontent.com/66881214/179672551-6c76f8c4-1327-4936-90a9-df32283f72bb.png">
         
         </p>
         </details>
               
  -   Note: The dataset from Source is only a subset from the cancer imaging archive. For more, [click here](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LUAD)
  
  -   Citations
      ```
      - Albertina, B., Watson, M., Holback, C., Jarosz, R., Kirk, S., Lee, Y., … Lemmerman, J. (2016). Radiology Data from The Cancer Genome Atlas Lung Adenocarcinoma [TCGA-LUAD] collection. The Cancer Imaging Archive. http://doi.org/10.7937/K9/TCIA.2016.JGNIHEP5
      - Clark K, Vendt B, Smith K, Freymann J, Kirby J, Koppel P, Moore S, Phillips S, Maffitt D, Pringle M, Tarbox L, Prior F. The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository, Journal of Digital Imaging, Volume 26, Number 6, December, 2013, pp 1045-1057. (paper) 
      ```

#### Leukemia Classification 

- Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification)  
- Data Type: Images 
- Possible uses: Creating a model to classify normal from abnormal cell images
-   Size: 10.42GB   
-   Example of data + Special Instructions(if any):
    
       Download from Source
       <details><summary>Example</summary>
       <p>
 
       Acute lymphoblastic leukemia (ALL) (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179482213-1aec30af-9390-4f52-b582-7916ab44ce50.jpg" width="150" height="150">
         
       Normal (Images in hem folder) (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179482557-ae81cbe2-037b-4ae7-a138-d6669c7c2019.jpg" width="150" height="150">
           
       Labels for images in validation_data can be found in the csv file that is stored in the same folder. 

       For example: 
    
       1.bmp (converted to jpg [here](https://www.freeconvert.com/bmp-to-jpg)): <img src="https://user-images.githubusercontent.com/66881214/179483000-488156a0-9a80-44b8-8081-175e8a96f229.jpg" width="150" height="150"> 
    
       The label for this image can be found in its corresponding row in the csv file. The image file name will be the value of new_names in the csv file as shown below (second column):  
    
       <img width="291" alt="Screenshot 2022-07-18 at 5 28 01 PM" src="https://user-images.githubusercontent.com/66881214/179483054-360c06f1-4890-41de-ba67-bcb247de6af8.png">  
           
       </p>
       </details>

  - Note: The labels for the testing data was not given. [Click here for more information](https://competitions.codalab.org/competitions/20395#learn_the_details-overview)

  - Citations
    ```
    - Gupta, A., & Gupta, R. (2019). ALL Challenge dataset of ISBI 2019 [Data set]. The Cancer Imaging Archive.(https://doi.org/10.7937/tcia.2019.dc64i46r)
    - Publication Citation (if required): 
      - Anubha Gupta, Rahul Duggal, Ritu Gupta, Lalit Kumar, Nisarg Thakkar, and Devprakash Satpathy, “GCTI-SN: Geometry-Inspired Chemical and Tissue Invariant Stain Normalization of Microscopic Medical Images,”, under review. Ritu Gupta, Pramit Mallick, Rahul Duggal, Anubha Gupta, and Ojaswa Sharma, "Stain Color Normalization and Segmentation of Plasma Cells in Microscopic Images as a Prelude to Development of Computer Assisted Automated Disease Diagnostic Tool in Multiple Myeloma," 16th International Myeloma Workshop (IMW), India, March 2017.
      - Rahul Duggal, Anubha Gupta, Ritu Gupta, Manya Wadhwa, and Chirag Ahuja, “Overlapping Cell Nuclei Segmentation in Microscopic Images UsingDeep Belief Networks,” Indian Conference on Computer Vision, Graphics and Image Processing (ICVGIP), India, December 2016. Rahul Duggal, Anubha Gupta, and Ritu Gupta, “Segmentation of overlapping/touching white blood cell nuclei using artificial neural networks,” CME Series on Hemato-Oncopathology, All India Institute of Medical Sciences (AIIMS), New Delhi, India, July 2016.
      - Rahul Duggal, Anubha Gupta, Ritu Gupta, and Pramit Mallick, "SD-Layer: Stain Deconvolutional Layer for CNNs in Medical Microscopic Imaging," In: Descoteaux M., Maier-Hein L., Franz A., Jannin P., Collins D., Duchesne S. (eds) Medical Image Computing and Computer-Assisted Intervention − MICCAI 2017, MICCAI 2017. Lecture Notes in Computer Science, Part III, LNCS 10435, pp. 435–443. Springer, Cham. DOI: https://doi.org/10.1007/978-3-319-66179-7_50 .
    ```
    
#### Lung and Colon Cancer Histopathological Images
  - Source:  [Click here to proceed to Kaggle site](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images) 
    - The data set can also be downloaded from [here](https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af)
    - Relevant [github](https://github.com/tampapath/lung_colon_image_set/)
  - Data Type: Images 
  - Possible uses: Creating a model to identify lung/colon cancer images from normal lung/colon images
  -   Size of files
      - 959.8MB for colon_image_sets
      - 929.7MB for lung_image_sets
  -   Example of data + Special Instructions(if any):
    
         For colon images download colon_image_sets from Source. For lung images, download lung_image_sets from Source. 
         <details><summary>Example</summary>
         <p>

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
             
         </p>
         </details>
         
  - Note: NA
  - Citations
    ```
    - Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM. Lung and Colon Cancer Histopathological Image Dataset (LC25000). arXiv:1912.12142v1 [eess.IV], 2019 (https://arxiv.org/abs/1912.12142v1)
    ```
   
#### Skin Cancer MNIST: HAM10000
  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
    - The original challenge can be found [here](https://challenge2018.isic-archive.com) and the dataset can also be downloaded [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T) after accepting their terms and conditions. 
  
  - Data Type: Images + Tabular
  - Possible uses: Create a model to predict diagnosis for pigmented lesions
  - Size of files
    - 1.37GB for HAM10000_images_part_1 
    - 1.4GB for HAM10000_images_part_2
    - 563KB for HAM10000_metadata.csv
  -   Example of data + Special Instructions(if any):
    
         Download HAM10000_images_part_1.zip, HAM10000_images_part_2 and HAM10000_metadata.csv from Source 
         <details><summary>Example: ISIC_0024306.jpg</summary>
         <p>
      
         <img src="https://user-images.githubusercontent.com/66881214/179134479-fc6a9393-17e5-4af3-93dc-81d8d8341073.jpg" width="150" height="150"> 
         
         Each image has its corresponding row in HAM10000_metadata.csv where its file name is its image_id as shown: 
         
         <img width="582" alt="Screenshot 2022-07-15 at 10 29 29 AM" src="https://user-images.githubusercontent.com/66881214/179134926-35dd84e3-f4b1-4f7d-a3f1-46ac395fb067.png">
             
         </p>
         </details>
         
  - Note: NA
  - Citations
    ```
    - Noel Codella, Veronica Rotemberg, Philipp Tschandl, M. Emre Celebi, Stephen Dusza, David Gutman, Brian Helba, Aadi Kalloo, Konstantinos Liopyris, Michael Marchetti, Harald Kittler, Allan Halpern: “Skin Lesion Analysis Toward Melanoma Detection 2018: A Challenge Hosted by the International Skin Imaging Collaboration (ISIC)”, 2018; https://arxiv.org/abs/1902.03368
    - Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).
    ```
    
#### Thoracic Surgery Data Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Thoracic+Surgery+Data)
  - Data Type: Text/Tabular
  - Possible uses: Classification problem related to the post-operative life expectancy in the lung cancer patients
  -   Size: 24 KB
  -   Example of data + Special Instructions(if any):
      
         Download  ThoraricSurgery.arff from Data Folder from Source
         <details><summary>Example</summary>
         <p>
         
         <img width="351" alt="Screenshot 2022-07-15 at 2 42 52 PM" src="https://user-images.githubusercontent.com/66881214/179166600-f02bd66d-f08f-44f5-9606-1035ee64cca2.png">
             
         </p>
         </details>
         
         <details><summary>Columns present (from left to right):</summary>
         <p>
             
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
         
         </p>
         </details>
         
  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    <details><summary>To convert to csv file</summary>
    <p>
    
    Remove the highlighted text as shown and save:
    
    <img width="675" alt="Screenshot 2022-07-15 at 2 45 46 PM" src="https://user-images.githubusercontent.com/66881214/179167036-4318946c-4875-42e3-80e1-60bebcfd487b.png">
    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="1106" alt="Screenshot 2022-07-15 at 2 53 11 PM" src="https://user-images.githubusercontent.com/66881214/179168276-453388e5-0741-481c-abbf-39d207e20bd4.png">
    
    </p>
    </details>
    
  - Citations
    ```
    - ZiÄ™ba, M., Tomczak, J. M., Lubicz, M., & ÅšwiÄ…tek, J. (2013). Boosted SVM for extracting rules from imbalanced data in application to prediction of the post-operative life expectancy in the lung cancer patients. Applied Soft Computing (https://www.sciencedirect.com/science/article/abs/pii/S0166432811002221?via%3Dihub)
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
    ```
---

## Diabetes Dataset

#### Association of body mass index and age with incident diabetes in Chinese adults

  -   Source:  [Click here to proceed to site](https://zenodo.org/record/4997196#.YtZvkpNBw-Q)
  -   Data Type: Tabular  
  -   Possible uses: Building a model to study association of BMI and Age with Diabetes 
  -   Size: 28.3 KB
  -   Example of data + Special Instructions(if any):
      
         Download RC Health Care Data-20180820.xlsx from Source.

         <details><summary>Example</summary>
         <p>
            
         | id | Age (y) | Gender(1, male; 2, female) | site | height(cm) | weight(kg) | BMI(kg/m2) | SBP(mmHg) | DBP(mmHg) | FPG (mmol/L) | Cholesterol(mmol/L) | Triglyceride(mmol/L) | HDL-c(mmol/L) | LDL(mmol/L) | ALT(U/L) | AST(U/L) | BUN(mmol/L) | CCR(umol/L) | FPG of final visit(mmol/L) | Diabetes diagnosed during followup（1,Yes） | censor of diabetes at followup(1, Yes; 0, No) | year of followup | smoking status(1,current smoker;2, ever smoker;3,never smoker) | drinking status(1,current drinker;2, ever drinker;3,never drinker) | family histroy of diabetes(1,Yes;0,No) |
         | -- | ------- | -------------------------- | ---- | ---------- | ---------- | ---------- | --------- | --------- | ------------ | ------------------- | -------------------- | ------------- | ----------- | -------- | -------- | ----------- | ----------- | -------------------------- | ----------------------------------------- | --------------------------------------------- | ---------------- | -------------------------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------- |
         | 1  | 43      | 2                          | 16   | 166.4      | 53.5       | 19.3       | 96        | 57        | 4.99         | 5.13                | 0.78                 |               |             | 10       |          | 3.08        | 50.3        | 4.97                       |                                           | 0                                             | 2.15195          | 3                                                              | 3                                                                  | 1                                      |
         | 2  | 34      | 1                          | 2    | 169        | 57         | 20         | 124       | 69        | 3.51         | 4.61                | 1.75                 | 1.09          | 3.13        | 29.1     |          | 6.13        | 83.7        | 5.5                        |                                           | 0                                             | 3.96988          |                                                                |                                                                    | 0                                      |
         | 3  | 32      | 2                          | 2    | 157        | 51         | 20.7       | 98        | 68        | 4.25         | 4.73                | 0.47                 |               |             | 6.9      | 19.5     | 4.45        | 42.8        | 4.9                        |                                           | 0                                             | 3.93977          |                                                                |                                                                    | 0                                      |
          
         </p>
         </details>
               
  -   Note: NA
  
  -   Citations
      ```
      - Chen, Ying, Zhang, Xiao-Ping, Yuan, Jie, Cai, Bo, Wang, Xiao-Li, Wu, Xiao-Li, Zhang, Yue-Hua, Zhang, Xiao-Yi, Yin, Tong, Zhu, Xiao-Hui, Gu, Yun-Juan, Cui, Shi-Wei, Lu, Zhi-Qiang, & Li, Xiao-Ying. (2018). Data from: Association of body mass index and age with incident diabetes in Chinese adults: a population-based cohort study [Data set]. https://doi.org/10.5061/dryad.ft8750v
      ```
      
#### Clinical characteristics, types and complications of diabetics with young age at the onset

  -   Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/jf429jpgwt/1)
  -   Data Type: Tabular 
  -   Possible uses: To determine the distribution, clinical features and complications of the different types of diabetes in young age
  -   Size: 22 KB
  
  -   Example of data + Special Instructions(if any):
  
         Download 9. Master Chart.xlsx from Source.

         <details><summary>Example</summary>
         <p>
         
         <img width="1130" alt="Screenshot 2022-07-19 at 4 45 06 PM" src="https://user-images.githubusercontent.com/66881214/179707993-1c6512f6-7b93-4605-b968-c44bfb4417b8.png">
         
         </p>
         </details>
               
  -   Note: NA
  
  -   Citations
      ```
      - SAHU, PRANABANANDA; Das, Sidhartha (2019), “Data for: Clinical characteristics, types and complications of diabetics with young age at the onset ( 14 to 25 years).”, Mendeley Data, V1, doi: 10.17632/jf429jpgwt.1
      ```

#### Diabetes 130-US hospitals for years 1999-2008 Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
  - Data Type: Tabular 
  - Possible uses: Identifying significant features in predicting readmission rates of diabetic patients
  -   Size of files
      -  19.2MB for diabetic_data.csv
      -  3KB for IDs_mapping.csv
  -   Example of data + Special Instructions(if any):
  
         Download dataset_diabetes.zip from Data Folder from Source
         <details><summary>Example</summary>
         <p>

         | encounter_id | patient_nbr | race      | gender | age     | weight | admission_type_id | discharge_disposition_id | admission_source_id | time_in_hospital | payer_code | medical_specialty        | num_lab_procedures | num_procedures | num_medications | number_outpatient | number_emergency | number_inpatient | diag_1 | diag_2 | diag_3 | number_diagnoses | max_glu_serum | A1Cresult | metformin | repaglinide | nateglinide | chlorpropamide | glimepiride | acetohexamide | glipizide | glyburide | tolbutamide | pioglitazone | rosiglitazone | acarbose | miglitol | troglitazone | tolazamide | examide | citoglipton | insulin | glyburide-metformin | glipizide-metformin | glimepiride-pioglitazone | metformin-rosiglitazone | metformin-pioglitazone | change | diabetesMed | readmitted |
         |--------------|-------------|-----------|--------|---------|--------|-------------------|--------------------------|---------------------|------------------|------------|--------------------------|--------------------|----------------|-----------------|-------------------|------------------|------------------|--------|--------|--------|------------------|---------------|-----------|-----------|-------------|-------------|----------------|-------------|---------------|-----------|-----------|-------------|--------------|---------------|----------|----------|--------------|------------|---------|-------------|---------|---------------------|---------------------|--------------------------|-------------------------|------------------------|--------|-------------|------------|
         | 2278392      | 8222157     | Caucasian | Female | [0-10)  | ?      | 6                 | 25                       | 1                   | 1                | ?          | Pediatrics-Endocrinology | 41                 | 0              | 1               | 0                 | 0                | 0                | 250.83 | ?      | ?      | 1                | None          | None      | No        | No          | No          | No             | No          | No            | No        | No        | No          | No           | No            | No       | No       | No           | No         | No      | No          | No      | No                  | No                  | No                       | No                      | No                     | No     | No          | NO         |
         | 149190       | 55629189    | Caucasian | Female | [10-20) | ?      | 1                 | 1                        | 7                   | 3                | ?          | ?                        | 59                 | 0              | 18              | 0                 | 0                | 0                | 276    | 250.01 | 255    | 9                | None          | None      | No        | No          | No          | No             | No          | No            | No        | No        | No          | No           | No            | No       | No       | No           | No         | No      | No          | Up      | No                  | No                  | No                       | No                      | No                     | Ch     | Yes         | >30        |

  - Note: NA
  - Citations
    ```
    - Beata Strack, Jonathan P. DeShazo, Chris Gennings, Juan L. Olmo, Sebastian Ventura, Krzysztof J. Cios, and John N. Clore, “Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records,” BioMed Research International, vol. 2014, Article ID 781670, 11 pages, 2014. (https://www.hindawi.com/journals/bmri/2014/781670/)
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
    ```
    
#### Diabetic Retinopathy Debrecen Data Set Data Set

  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Diabetic+Retinopathy+Debrecen+Data+Set)
  - Data Type: Text/Tabular
  - Possible uses: Build a model to predict whether an image contains signs of diabetic retinopathy or not
  -   Size: 117 KB
  -   Example of data + Special Instructions(if any):
          
         Download messidor_features.arff from Data Folder from Source
         <details><summary>Example</summary>
         <p>
         
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
         
         </p>
         </details>
         
  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    <details><summary>To convert to csv file</summary>
    <p>
    
    Remove the highlighted text as shown and save:
    
    <img width="1016" alt="Screenshot 2022-07-15 at 4 05 56 PM" src="https://user-images.githubusercontent.com/66881214/179180814-8066caa4-de81-486d-8b19-f1dc9ce05534.png">
    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="1304" alt="Screenshot 2022-07-15 at 4 06 37 PM" src="https://user-images.githubusercontent.com/66881214/179180932-1d57f15a-783c-4da7-8c43-d3fe4afbda58.png">
    
    </p>
    </details>
    
  - Citations
    ```
    - Balint Antal, Andras Hajdu: An ensemble-based system for automatic screening of diabetic retinopathy, Knowledge-Based Systems 60 (April 2014), 20-27.
        - The dataset is based on features extracted from the Messidor image dataset. However, link provided is no longer available: http://messidor.crihan.fr/index-en.php 
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
    ```

#### Early Classification of Diabetes

  -   Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/early-diabetes-classification)
  -   Data Type: Tabular  
  -   Possible uses: Create a classification model to predict diabetes/ Explore the most common features associated with diabetic risk
  -   Size: 21 KB
  -   Example of data + Special Instructions(if any):
  
         Download diabetes_data.csv from Source.

         <details><summary>Example</summary>
         <p>
      
         | **age** | **gender** | **polyuria** | **polydipsia** | **sudden\_weight\_loss** | **weakness** | **polyphagia** | **genital\_thrush** | **visual\_blurring** | **itching** | **irritability** | **delayed\_healing** | **partial\_paresis** | **muscle\_stiffness** | **alopecia** | **obesity** | **class** |
         | ------- | ---------- | ------------ | -------------- | ------------------------ | ------------ | -------------- | ------------------- | -------------------- | ----------- | ---------------- | -------------------- | -------------------- | --------------------- | ------------ | ----------- | --------- |
         | 40      | Male       | 0            | 1              | 0                        | 1            | 0              | 0                   | 0                    | 1           | 0                | 1                    | 0                    | 1                     | 1            | 1           | 1         |
         | 58      | Male       | 0            | 0              | 0                        | 1            | 0              | 0                   | 1                    | 0           | 0                | 0                    | 1                    | 0                     | 1            | 0           | 1         |
         | 41      | Male       | 1            | 0              | 0                        | 1            | 1              | 0                   | 0                    | 1           | 0                | 1                    | 0                    | 1                     | 1            | 0           | 1         |
         
               
  -   Note: Viewing file on Microsoft Excel might be an issue as the delimeter used is a semicolon. 
  
  -   Citations
      ```
      - Islam M.M.F., Ferdousi R., Rahman S., Bushra H.Y. (2020) Likelihood Prediction of Diabetes at Early Stage Using Data Mining Techniques. In: Gupta M., Konar D., Bhattacharyya S., Biswas S. (eds) Computer Vision and Machine Intelligence in Medical Image Analysis. Advances in Intelligent Systems and Computing, vol 992. Springer, Singapore. https://doi.org/10.1007/978-981-13-8798-2_12
      ```
---
## Monkeypox

#### Monkeypox Skin Lesion Dataset 
  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/nafin59/monkeypox-skin-lesion-dataset)
  - Data Type: Image + Tabular   
  - Possible uses: Build a model to classify monkeypox images from non monkeypox images 
  -   Size of files
      -  1.5MB for Original Images folder
      -  5KB for Monkeypox_Dataset_metadata.csv
      -  25.9MB for Augmented_Images.zip
      -  20.9MB for Fold1
  -   Example of data + Special Instructions(if any):
  
         Download relevant files from Source 
         - Users may choose to use the folds/augmented images directly (Refer to source for more information)
         <details><summary>Example</summary>
         <p>
         
         Monkeypox: <img src="https://user-images.githubusercontent.com/66881214/179441844-22a9b005-841c-41f4-8d59-e3cde0d03843.jpg" width="150" height="150">
         
         Others:  <img src="https://user-images.githubusercontent.com/66881214/179441888-5c49b47e-00da-4a05-a4c7-43f583ad1110.jpg" width="150" height="150">
        
        </p>
        </details>
        
  - Note: There is a csv file that indicates the labels of the images. This may not be needed as the images are already sorted into their respective folders in main folder  
          
    <details><summary>CSV file</summary>
    <p>
          
    <img width="132" alt="Screenshot 2022-07-18 at 11 46 15 AM" src="https://user-images.githubusercontent.com/66881214/179442387-5fbe6faa-bade-497d-bdc0-e8e4749543b2.png">
          
    </p>
    </details>

  - Citations
    ```
    - If this dataset helped your research, please cite: Ali, S. N., Ahmed, M. T., Paul, J., Jahan, T., Sani, S. M. Sakeef, Noor, N., & Hasan, T. (2022). Monkeypox Skin Lesion Detection Using Deep Learning Models: A Preliminary Feasibility Study(https://arxiv.org/abs/2207.03342). arXiv preprint arXiv:2207.03342.
    ```                   
#### Clinical features of 21 human monkeypox cases seen at NDUTH 2017

  - Source:  [Click here to proceed to site](https://figshare.com/articles/dataset/The_2017_human_monkeypox_outbreak_in_Nigeria_Report_of_outbreak_experience_and_response_in_the_Niger_Delta_University_Teaching_Hospital_Bayelsa_State_Nigeria/8007536)
  -   Data Type: Tabular   
  -   Possible uses: Study clinical characteristics of confirmed cases of monkeypox
  -   Size: 11KB
  -   Example of data + Special Instructions(if any):
  
         Download relevant files from Source 
         <details><summary>Example</summary>
         <p>
         
         <img width="1208" alt="Screenshot 2022-07-27 at 2 02 10 PM" src="https://user-images.githubusercontent.com/66881214/181172707-ed3bc06c-b46e-47a2-96df-c7e281b43c8f.png">

        </p>
        </details>
        
  - Note: Small dataset with only 21 records (All positive: 18 laboratory-confirmed and three probable cases). Two of the 21 cases had laboratory evidence of concomitant chicken pox (by PCR/serology)
          
  - Citations
    ```
    - Ogoina, Dimie; Izibewule, James Hendris; Ogunleye, Adesola; Ederiane, Ebi; Anebonam, Uchenna; Neni, Aworabhi; et al. (2019): Clinical features of 21 human monkeypox cases seen at NDUTH.. PLOS ONE. Dataset. https://doi.org/10.1371/journal.pone.0214229.s001 
    ```
             
             
---              
## Parkinson Disease

#### Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Parkinson+Speech+Dataset+with++Multiple+Types+of+Sound+Recordings)
  - Data Type: Text/Tabular  
  - Possible uses: Build a model to identify parkinson disease from audio details
  -   Size of files
      -  194KB for train_data.txt 
      -  47KB for test_data.txt
  -   Example of data + Special Instructions(if any):
       
         Download Parkinson_Multiple_Sound_Recording.rar from Data Folder from Source 
         <details><summary>Example</summary>
         <p>
 
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
         
         </p>
         </details>
         
  - Note: [Click here for more information on how to open .rar files](https://www.hellotech.com/guide/for/how-to-open-rar-files-mac-windows-10)  
      
  - Citations
    ```
    - Erdogdu Sakar, B., Isenkul, M., Sakar, C.O., Sertbas, A., Gurgen, F., Delil, S., Apaydin, H., Kursun, O., 'Collection and Analysis of a Parkinson Speech Dataset with Multiple Types of Sound Recordings', IEEE Journal of Biomedical and Health Informatics, vol. 17(4), pp. 828-834, 2013.
    - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
    ```

#### Parkinson Tappy Keystroke Data

  -   Source:  [Click here to proceed to site](https://physionet.org/content/tappy/1.0.0/)
  -   Data Type: Text  
  -   Possible uses: Build a model for the detection of early Parkinson's Disease using multiple characteristics of finger movement while typing
  -   Size of files
      - 43KB for Archived users  
      - 549.7MB for Tappy Data 
         
  -   Example of data + Special Instructions(if any):
  
         Download files from Source.
         <details><summary>Example</summary>
         <p>
         
         Each user will have their corresponding text file in Archived users with the following information: 
         
         <img width="454" alt="Screenshot 2022-07-20 at 5 10 10 PM" src="https://user-images.githubusercontent.com/66881214/179944256-b890ab5f-1d29-45ed-9c6c-13d9d0057d53.png">
         
         In Tappy Data folder, a participant may have more than one file. The filename comprises the 10 character code (matching the user details file) and the YYMM of the data:
         
         <img width="541" alt="Screenshot 2022-07-20 at 5 12 33 PM" src="https://user-images.githubusercontent.com/66881214/179944770-d19779aa-a9ba-43b2-89d9-94b9b5c42ec7.png">
         
         </p>
         </details>
     
  -   Note: NA
         
  -   Citations
      ```
      - Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
      - Adams WR (2017) High-accuracy detection of early Parkinson's Disease using multiple characteristics of finger movement while typing. PLOS ONE 12(11): e0188226. https://doi.org/10.1371/journal.pone.0188226
      ```
             
#### Safety and Preliminary Efficacy of Intranasal Insulin for Cognitive Impairment in Parkinson Disease and Multiple System Atrophy

  -   Source:  [Click here to proceed to site](https://physionet.org/content/inipdmsa/1.0/)
  -   Data Type: Tabular   
  -   Possible uses: Study the effects of intranasal insulin (INI) on cognition and motor performance in Parkinson Disease
  -   Size of files
      - 3KB for PD-Table1.csv
      - 818 bytes for PD-Table2.csv
  -   Example of data + Special Instructions(if any):
  
         Download files from Source.
         <details><summary>Example</summary>
         <p>
         
         PD-Table1.csv:
             
         | Study No | Pharmacy | excluded                | IversusP | Pre-Post | Age | Gender | Etnicity | Smoking | Height (in) | Weight | BMI   | Disease | Disease Duration | SBP | DBP | HR | Walk-Duration | Walk-NoSteps | AverStride (in) | MOCA | Glucose | SBP | DBP | HR | BMI 2 | Walk-Duration 2 | Walk-NoSteps 2 | AverStrid (in) 2 | Gait Speed 2 | HnH | PGI-I | BDI | MOCA 2 | F#words | A#words | S#words | FAS  | Pre-Post | Glucose 2 | MOCA 3 | Walk-Duration 3 | Walk-NoSteps 3 | AverStrid (in) 3 | Gait Speed 3 | HnH 2 | PGI-I 2 | BDI 2 | F#words 2 | A#words 2 | S#words 2 | FAS 2 |
         | -------- | -------- | ----------------------- | -------- | -------- | --- | ------ | -------- | ------- | ----------- | ------ | ----- | ------- | ---------------- | --- | --- | -- | ------------- | ------------ | --------------- | ---- | ------- | --- | --- | -- | ----- | --------------- | -------------- | ---------------- | ------------ | --- | ----- | --- | ------ | ------- | ------- | ------- | ---- | -------- | --------- | ------ | --------------- | -------------- | ---------------- | ------------ | ----- | ------- | ----- | --------- | --------- | --------- | ----- |
         | 1        | n/a      | excluded/screen failure |          |          |     |        |          |         |             |        |       |         |                  |     |     |    |               |              |                 |      |         |     |     |    |       |                 |                |                  |              |     |       |     |        |         |         |         | Post |          |           |        |                 |                |                  |              |       |         |       |           |           |           |
         | 2        | 1-PD     |                         | 0        | Pre      | 79  | 1      | w        | 0       | 69          | 176    | 26.02 | PD      | 3                | 154 | 88  | 66 | 5.81          | 9            | 16              | 26   | 84      | 148 | 82  | 62 | 26.02 | 4.76            | 7              | 21               | 1.05042017   | 2.5 | 3     | 17  | 27     | 16      | 7       | 8       | 31   | Post     | 73        | 24     | 5.45            | 9              | 16               | 0.91743119   | 2.5   | 3       | 13    | 6         | 4         | 10        | 20    |
         | 3        | 2-PD     |                         | 1        | Pre      | 64  | 1      | w        | 0       | 76.5        | 184    | 22.1  | PD      | 9                | 129 | 83  | 70 | 3.72          | 7            | 21              | 30   | 89      | 129 | 83  | 70 | 22.1  | 3.9             | 7              | 21               | 1.28205128   | 2.5 | 3     | 3   | 30     | 15      | 16      | 15      | 46   | Post     | 83        | 29     | 4.08            | 7              | 21               | 1.2254902    | 2.5   | 3       | 3     | 15        | 17        | 16        | 48    |
         | 4        | 3-PD     |                         | 0        | Pre      | 53  | 2      | w        | 0       | 67          | 155    | 24.3  | PD      | 5                | 113 | 69  | 70 | 3.84          | 8            | 18              | 28   | 98      | 113 | 69  | 70 | 24.3  | 4.4             | 8              | 18               | 1.13636364   | 2.5 | 3     | 15  | 29     | 11      | 11      | 12      | 34   | Post     | 98        | 30     | 4.55            | 8              | 18               | 1.0989011    | 2.5   | 3       | 13    | 11        | 8         | 9         | 28    |
         
         PD-Table2.csv:
             
         | Study\_No | Group    | Pharmacy | Disease | Disease\_Dur | Age | Gender | Ethnicity | updrs1\_base | updrs1\_tre1 | updrs2\_base | updrs2\_tre1 | updrs3\_base | updrs3\_tre1 | brady\_base | brady\_tre1 |
         | --------- | -------- | -------- | ------- | ------------ | --- | ------ | --------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ----------- | ----------- |
         | 1         | excluded |          |         |              |     |        |           | \-99         |              |              |              |              |              |             |             |
         | 2         | 0        | 1-PD     | PD      | 3            | 79  | 1      | w         | 15           | 9            | 14           | 11           | 32           | 24           | 13.5        | 11          |
         | 3         | 1        | 2-PD     | PD      | 9            | 64  | 1      | w         | 9            | 9            | 15           | 15           | 23           | 23           | 5           | 5           |
         | 4         | 0        | 3-PD     | PD      | 5            | 53  | 2      | w         | 15           | 15           | 13           | 13           | 26           | 23           | 7           | 7           |
        
         </p>
         </details>
     
  -   Note: Small dataset with only 16 rows
         
  -   Citations
      ```
      - Novak, V., & Novak, P. (2019). Safety and Preliminary Efficacy of Intranasal Insulin for Cognitive Impairment in Parkinson Disease and Multiple System Atrophy (version 1.0). PhysioNet. https://doi.org/10.13026/bn1x-my19.
         
      - Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
      ```             
             
           
---
             
## Brain Related Datasets

#### Brain tumor data

  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/mvhssriraj/brain-tumor-dataset)
  -   Data Type: Images
  -   Possible uses: Build a model to to identify the types of brain tumor 
  -   Size: 733.1MB
  -   Example of data + Special Instructions(if any):
   
         Download relevant files from Source 
         <details><summary>Example</summary>
         <p>
         
         meningioma(1): <img src="https://user-images.githubusercontent.com/66881214/179969696-01a64b3f-053b-4b82-b4eb-ae82eececd10.png" width="150" height="150"> 

         glioma(2): <img src="https://user-images.githubusercontent.com/66881214/179969724-a8bf71a4-ea1a-4f6d-aebf-fe8e2d906fa6.png" width="150" height="150">
         
         pituitary tumor(3): <img src="https://user-images.githubusercontent.com/66881214/179969753-135aff9c-a033-4061-bd5b-a3a458cf231f.png" width="150" height="150">
         
         </p>
         </details:>

  -   Note: NA
  -   Citations
      ```
      - Cheng, Jun (2017): brain tumor dataset. figshare. Dataset. https://doi.org/10.6084/m9.figshare.1512427.v5
      ```
      
#### MRI and Alzheimers

  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers)
  -   Data Type: Tabular (According to discussion, images was said to be found [here](https://www.oasis-brains.org/#data), where a request for access has to be made to OASIS)
  -   Possible uses: Build a model to predict Alzheimer based on MRI data
  -   Size of files
      -  22KB for oasis_coss-sectional.csv
      -  28KB for oasis_longitudinal.csv
  -   Example of data + Special Instructions(if any):
      
         Download relevant files from Source 
         <details><summary>Example</summary>
         <p>
         
         oasis_coss-sectional.csv: <img width="843" alt="Screenshot 2022-07-19 at 2 18 24 PM" src="https://user-images.githubusercontent.com/66881214/179679183-ccec7e4a-4ec7-43bc-9394-5ff367c2c572.png">
         
         oasis_longitudinal.csv: <img width="1098" alt="Screenshot 2022-07-19 at 2 17 45 PM" src="https://user-images.githubusercontent.com/66881214/179679071-26a5b79c-c532-4c66-a3ff-3009fd8b803c.png">
         
         </p>
         </details>

  -   Note: NA
  -   Citations
      ```
      - When publishing findings that benefit from OASIS data, please include the following grant numbers in the acknowledgements section and in the associated Pubmed Central submission: P50 AG05681, P01 AG03991, R01 AG021910, P20 MH071616, U24 RR0213
      ```

#### Stroke Prediction

  -   Source: [Click here to proceed to site](https://data.mendeley.com/datasets/x8ygrw87jw/1)
  -   Data Type: Tabular 
  -   Possible uses: Build a model to predict stroke from given features
  -   Size: 2.6 MB
  -   Example of data + Special Instructions(if any):
      
         Download dataset.rar from Source 
         <details><summary>Example</summary>
         <p>
         
         <img width="906" alt="Screenshot 2022-07-19 at 4 00 39 PM" src="https://user-images.githubusercontent.com/66881214/179698751-b9b39338-4503-4011-a0e1-823959c0574a.png">
         
         </p>
         </details>
       
  -   Note: [Click here for more information on how to access .rar files](https://www.hellotech.com/guide/for/how-to-open-rar-files-mac-windows-10)
  -   Citations
      ```
      - Liu, Tianyu; Fan, Wenhui; Wu, Cheng (2019), “Data for: A hybrid machine learning approach to cerebral stroke prediction based on imbalanced medical-datasets”, Mendeley Data, V1, doi: 10.17632/x8ygrw87jw.1
      ```
---

## Eye Related Datasets 

#### Bajwa Hospital (Multi Eye Disease Dataset)

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/rgwpd4m785/2)  
- Data Type: Images 
- Possible uses: Build a model that can provide a highly accurate diagnosis from an eye image
-   Size: 3.59GB    
-   Example of data + Special Instructions(if any):
    
       Download file from Source
       <details><summary>Example</summary>
       <p> 
         
       Normal: <img src="https://user-images.githubusercontent.com/66881214/179783463-a84dbf58-653f-4dbc-8a23-a4f1c5bb5b2c.png" width="150" height="150">
         
       Cataract: <img src="https://user-images.githubusercontent.com/66881214/179783530-bc98dfad-f095-401a-b6e4-3b620deef3eb.png" width="150" height="150">
         
       Glaucoma: <img src="https://user-images.githubusercontent.com/66881214/179783577-fd4346d9-2b18-4ee3-ba70-f0ff857c07ac.png" width="150" height="150">
         
       Retina Disease: <img src="https://user-images.githubusercontent.com/66881214/179783649-e58274ce-1ae9-4993-b434-e675b8dbf79b.png" width="150" height="150">
           
       </p>
       </details>

  - Note: [Click here for more information on how to access .rar files](https://www.hellotech.com/guide/for/how-to-open-rar-files-mac-windows-10)
  - Citations
    ```
    - Kaur, Palwinder (2022), “Bajwa Hospital (Multi Eye Disease Dataset)”, Mendeley Data, V2, doi: 10.17632/rgwpd4m785.2
    ```
    
#### Retinal OCT Images (optical coherence tomography)

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/rscbjbr9sj/3)  
- Data Type: Images 
- Possible uses: Building a model to identify normal OCT images from those with diseases
-   Size: 7.19GB  
-   Example of data + Special Instructions(if any):
      
       Download from Source
       <details><summary>Example</summary>
       <p>
         
       NORMAL: <img src="https://user-images.githubusercontent.com/66881214/179479055-048a3b6a-ee7a-4f0c-ae73-fdf7e07784e2.jpeg" width="150" height="150">
         
       CNV: <img src="https://user-images.githubusercontent.com/66881214/179479097-161cb450-7dd8-4ab0-a214-316b3582c740.jpeg" width="150" height="150">
         
       DME: <img src="https://user-images.githubusercontent.com/66881214/179479179-f8f138fb-ff86-4166-9e3c-e39b9d8685e2.jpeg" width="150" height="150">
         
       DRUSEN: <img src="https://user-images.githubusercontent.com/66881214/179479213-ed54e3cc-052e-47d1-b897-006fc29d2581.jpeg" width="150" height="150">
       
       </p>
       </details>

  - Note: In the same folder, a folder named chest_xray can be found. Information regarding this image dataset can be found at the [Chest X-ray Images (Pneumonia)](#Chest-X-ray-Images-Pneumonia) section.
  - Citations
    ```
    - Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Large Dataset of Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images”, Mendeley Data, V3, doi: 10.17632/rscbjbr9sj.3
    ```
---

## Gastrointestinal Related Datasets

#### Bowel Sounds 

- Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/robertnowak/bowel-sounds)  
- Data Type: Audio
- Possible uses: Build an algorithm such as deep neural network to detect bowel sounds
-   Size: 283.8MB 
-   Example of data + Special Instructions(if any):

       Download from Source
       <details><summary>Example:</summary>
       <p>
         
       https://user-images.githubusercontent.com/66881214/179934116-d8c16f98-2319-4814-86ca-c77516a3b6b0.mp4
         
       Each audio file has its corresponding csv file:
         
       <img width="326" alt="Screenshot 2022-07-20 at 4 23 48 PM" src="https://user-images.githubusercontent.com/66881214/179934214-797e2584-bfb1-4b62-b276-87bf3ac8e523.png">
       
       </p>
       </details>

 - Note: NA
 - Citations
   ```
   - Jakub Ficek and Kacper Radzikowski and Jan Nowak and Osamu Yoshie and Jarosław Walkowiak and Robert Nowak, "Analysis of gastrointestinal acoustic activity using deep neural networks", MDPI Sensors, 2021, doi:10.3390/s21227602, http://dx.doi.org/10.3390/s21227602
   ```
 

#### Kvasir Dataset

  -   Source: [Click here to proceed to site](https://datasets.simula.no/kvasir/)
  -   Data Type: Images
  -   Possible uses: Build a model to classify gastrointenstinal disease
  -   Size of files:
      -  2.52GB for kvasir-dataset-v2
      -  40.2MB for kvasir-dataset-v2-features   
  -   Example of data + Special Instructions(if any):
      
         Download relevant folders from Source 

         <details><summary>Example</summary>
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
      ```
      - Pogorelov, K., Randel, K., Griwodz, C., Eskeland, S., Lange, T., Johansen, D., Spampinato, C., Dang-Nguyen, D.T., Lux, M., Schmidt, P., Riegler, M., & Halvorsen, P. (2017). KVASIR: A Multi-Class Image Dataset for Computer Aided Gastrointestinal Disease Detection. In Proceedings of the 8th ACM on Multimedia Systems Conference (pp. 164–169). ACM.
      ```
---

## Heart Related Datasets

#### An Extensive Dataset for the Heart Disease Classification System

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/65gxgy2nmg/2)  
- Data Type: Text/Tabular 
- Possible uses: Build a model to predict heart disease/Identify important characteristics/factors that contribute to a heart attack 
-   Size: 51 KB   
-   Example of data + Special Instructions(if any):
 
       Download Medicaldataset.arff from Source
       <details><summary>Example</summary>
       <p>
       
       <img width="273" alt="Screenshot 2022-07-19 at 4 17 35 PM" src="https://user-images.githubusercontent.com/66881214/179702124-4324e73b-8569-43a0-9f1c-0906f63765c8.png">
       
       </p>
       </details>
         
       <details><summary>Columns present (from left to right):</summary>
       <p>
            
       * age
       * gender
       * impulse
       * pressurehight
       * pressurelow
       * glucose
       * kcm
       * troponin
       * class
        
    </p>
    </details>

  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    <details><summary>To convert to csv file</summary>
    <p>
    
    Remove the highlighted text as shown and save:
    
    <img width="751" alt="Screenshot 2022-07-19 at 4 18 48 PM" src="https://user-images.githubusercontent.com/66881214/179702389-5b3600d9-58ec-43be-b810-e58a25e3a26f.png">
    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="586" alt="Screenshot 2022-07-19 at 4 19 37 PM" src="https://user-images.githubusercontent.com/66881214/179702539-cb30bdc9-30ff-4102-a299-8070f0b64e0b.png">
        
    </p>
    </details>

  - Citations
    ```
    - Maghdid, Sozan; Rashid, Tarik A. (2022), “An Extensive Dataset for the Heart Disease Classification System ”, Mendeley Data, V2, doi: 10.17632/65gxgy2nmg.2
    ```

#### Heart Failure Prediction

- Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)  
- Data Type: Tabular 
- Possible uses: Create a model for predicting mortality caused by Heart Failure
-   Size: 12KB   
-   Example of data + Special Instructions(if any):
 
       Download heart_failure_clinical_records_dataset.csv from Source
       <details><summary>Example</summary>
       <p>
       
       <img width="1036" alt="Screenshot 2022-07-18 at 12 24 40 PM" src="https://user-images.githubusercontent.com/66881214/179445189-7e885834-643e-4c73-9d42-78e4abdae1fa.png">
           
    </p>
    </details>
    
  - Note: NA
  - Citations
    ```
    - Davide Chicco, Giuseppe Jurman: Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making 20, 16 (2020). https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5
    ```

---

## Kidney Related Datasets 

#### A Brazilian dataset for screening the risk of the Chronic Kidney Disease

- Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/2gkg7vvcrm/3)  
- Data Type: Text/Tabular  
- Possible uses: Build a model to predict level of risk of Chronic Kidney Disease
-   Size of files:
    - 2 KB for Original.arff
    - 2 KB for Augmented.arff         
-   Example of data + Special Instructions(if any):

       Download relevant file from Source
       - In Augmented.arff, authors have augmented the dataset to decrease the impact of imbalanced data.  
       
       <details><summary>Example</summary>
       <p>
           
       <img width="406" alt="Screenshot 2022-07-19 at 5 27 05 PM" src="https://user-images.githubusercontent.com/66881214/179717003-2ae83296-68d1-4940-aaa5-12c2589cd18a.png">
           
       </p>
       </details>
       
  - Note: Dataset from Source is of .arff file.If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad) 
  
    <details><summary>To convert to csv file</summary>
    <p>
    
    Remove the highlighted text as shown and save:
    
    <img width="679" alt="Screenshot 2022-07-19 at 5 28 38 PM" src="https://user-images.githubusercontent.com/66881214/179717333-24a0b174-8506-466e-ab26-a72ef79ad542.png">

    
    Rename the new file by changing ".arff" to ".csv" extension. 
    
    Updated file:  
    
    <img width="616" alt="Screenshot 2022-07-19 at 5 29 09 PM" src="https://user-images.githubusercontent.com/66881214/179717458-25397a0d-0c4d-4146-b33a-6016d02ceca1.png">
        
    </p>
    </details>

  - Citations
    ```
    - Sobrinho, Alvaro; Dias da Silva, Leandro ; Perkusich, Angelo; Queiroz, Andressa; Eliete Pinheiro, Maria (2021), “A Brazilian dataset for screening the risk of the Chronic Kidney Disease”, Mendeley Data, V3, doi: 10.17632/2gkg7vvcrm.3
    ```

#### Risk Factor prediction of Chronic Kidney Disease Data Set

  -   Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Risk+Factor+prediction+of+Chronic+Kidney+Disease)
  -   Data Type: Tabular
  -   Possible uses: Create a model for predicting Chronic Kidney Disease
  -   Size: 34KB
  -   Example of data + Special Instructions(if any):
      
         Download ckd-dataset-v2.csv from Data Folder from Source
         <details><summary>Example</summary>
         <p>
      
         | **bp (Diastolic)** | **bp limit** | **sg**        | **al**   | **class** | **rbc**  | **su**   | **pc**   | **pcc**  | **ba**   | **bgr**   | **bu**      | **sod**   | **sc**   | **pot**  | **hemo**    | **pcv**     | **rbcc**    | **wbcc**      | **htn**  | **dm**   | **cad**  | **appet** | **pe**   | **ane**  | **grf**           | **stage** | **affected** | **age**  |
         | ------------------ | ------------ | ------------- | -------- | --------- | -------- | -------- | -------- | -------- | -------- | --------- | ----------- | --------- | -------- | -------- | ----------- | ----------- | ----------- | ------------- | -------- | -------- | -------- | --------- | -------- | -------- | ----------------- | --------- | ------------ | -------- |
         | discrete           | discrete     | discrete      | discrete | discrete  | discrete | discrete | discrete | discrete | discrete | discrete  | discrete    | discrete  | discrete | discrete | discrete    | discrete    | discrete    | discrete      | discrete | discrete | discrete | discrete  | discrete | discrete | discrete          | discrete  | discrete     | discrete |
         |                    |              |               |          |           |          |          |          |          |          |           |             |           |          |          |             |             |             |               |          |          |          |           |          |          |                   |           | class        | meta     |
         | 0                  | 0            | 1.019 - 1.021 | 1 - 1    | ckd       | 0        | < 0      | 0        | 0        | 0        | < 112     | < 48.1      | 138 - 143 | < 3.65   | < 7.31   | 11.3 - 12.6 | 33.5 - 37.4 | 4.46 - 5.05 | 7360 - 9740   | 0        | 0        | 0        | 0         | 0        | 0        | ≥ 227.944         | s1        | 1            | < 12     |
         | 0                  | 0            | 1.009 - 1.011 | < 0      | ckd       | 0        | < 0      | 0        | 0        | 0        | 112 - 154 | < 48.1      | 133 - 138 | < 3.65   | < 7.31   | 11.3 - 12.6 | 33.5 - 37.4 | 4.46 - 5.05 | 12120 - 14500 | 0        | 0        | 0        | 0         | 0        | 0        | ≥ 227.944         | s1        | 1            | < 12     |
         | 0                  | 0            | 1.009 - 1.011 | ≥ 4      | ckd       | 1        | < 0      | 1        | 0        | 1        | < 112     | 48.1 - 86.2 | 133 - 138 | < 3.65   | < 7.31   | 8.7 - 10    | 29.6 - 33.5 | 4.46 - 5.05 | 14500 - 16880 | 0        | 0        | 0        | 1         | 0        | 0        | 127.281 - 152.446 | s1        | 1            | < 12     |
         | 1                  | 1            | 1.009 - 1.011 | 3 - 3    | ckd       | 0        | < 0      | 0        | 0        | 0        | 112 - 154 | < 48.1      | 133 - 138 | < 3.65   | < 7.31   | 13.9 - 15.2 | 41.3 - 45.2 | 4.46 - 5.05 | 7360 - 9740   | 0        | 0        | 0        | 0         | 0        | 0        | 127.281 - 152.446 | s1        | 1            | < 12     |
             
         </p>
         </details>
      
  -   Note: According to site, pre-processing has to be done for any machine learning algorithm to be applied. Some special characters might be observed in Microsoft Excel. Using other applications such as Numbers(Macbook), these special characters correspond to mathematical symbols such as >= or <=
  -   Citations
      ```
      - M. A. Islam, S. Akter, M. S. Hossen, S. A. Keya, S. A. Tisha and S. Hossain, 'Risk Factor Prediction of Chronic Kidney Disease based on Machine Learning Algorithms,' 2020 3rd International Conference on Intelligent Sustainable Systems (ICISS), Thoothukudi, India, 2020, pp. 952-957, doi: 10.1109/ICISS49785.2020.9315878.(https://ieeexplore.ieee.org/document/9315878)
      - Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science
      ```
---

## Lung Related Datasets

#### A dataset of lung sounds recorded from the chest wall using an electronic stethoscope

  - Source:  [Click here to proceed to site](https://data.mendeley.com/datasets/jwyy9np4gv/3)
  - Data Type: Audio 
  - Possible uses: Create a model to predict disease from lung sounds 
  -   Size of files:
      - 46.8MB for Audio Files
      - 13KB for Data annotation.xlsx   
  -   Example of data + Special Instructions(if any):
        
         Download by Audio Files.zip and Data annotation.xlsx from Source
         - "Stethoscope Files.zip" contains the original records imported from the stethoscope  
         <details><summary>Example</summary>
         <p>
        
         BP1_Asthma,I E W,P L L,70,M (converted to mp4 [here](https://www.freeconvert.com/wav-to-mp4)):  
         
         https://user-images.githubusercontent.com/66881214/179915810-22a7b2cf-7c7c-42e7-851c-8441a157b7f8.mp4
         
         Filename correspond to values in its corresponding row in Data annotation.xlsx.
         
         <img width="448" alt="Screenshot 2022-07-20 at 2 51 39 PM" src="https://user-images.githubusercontent.com/66881214/179916058-0115e768-d731-4e29-b8af-234e9de492c5.png">
         
         <img width="440" alt="Screenshot 2022-07-20 at 2 58 32 PM" src="https://user-images.githubusercontent.com/66881214/179917244-f6866ec0-2a9d-4717-a5dd-c4a29c3aec8b.png">
             
         </p>
         </details>

  - Note:  If .wav files are not supported, try using online converter tools to convert to a audio file type that is supported by your device.
    - For example: [FreeConvert](https://www.freeconvert.com/audio-converter)     
  - Citations
    ```
    - Fraiwan, Mohammad; Fraiwan, Luay; Khassawneh, Basheer; Ibnian, Ali (2021), “A dataset of lung sounds recorded from the chest wall using an electronic stethoscope”, Mendeley Data, V3, doi: 10.17632/jwyy9np4gv.3
    ```

#### NIH Chest X-ray Dataset
  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/nih-chest-xrays/data?resource=download)
  -   Data Type: Images + Tabular
  -   Possible uses: Create a model to predict diseases from chest x-rays
  -   Size of files
      -  2 to 4 GB per image zip folder depending on number of images in the folder 
      -  7.9 MB for Data_Entry_2017.csv
      -  92 KB for BBox_List_2017.csv 
  -   Example of data + Special Instructions(if any):
   
         Download image folders images_001 to images_012 from Source. Class labels are to be obtained from Data_Entry_2017.csv. Extra information regarding the patient and image can be found in the file as well. Coordinates of the disease region bounding boxes can be obtained from BBox_List_2017.csv.
         <details><summary>Example: 00000032_037.png</summary>
         <p>
      
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
               
        Data in BBox_List_2017.csv is very limited. An image may be classified to one of the diseases but do not have a corresponding record in BBox_List_2017.csv file. Referencing to the same example above shows that there is only one disease region bounding box identified in BBox_List_2017.csv file.
         
        <img width="574" alt="Screenshot 2022-07-13 at 4 19 17 PM" src="https://user-images.githubusercontent.com/66881214/178685815-7503b9c5-0b09-4a4f-9adb-5226fd0867d9.png">
             
        </p>
        </details>

  -   Note: Some image labels may not be accurate. A more accurate version is said to be available [here](https://cloud.google.com/healthcare-api/docs/resources/public-datasets/nih-chest#additional_labels). You would be required to submit the following google form to obtain the updated data.  
      <details><summary>View form</summary>
      <p>
          
      <img width="479" alt="Screenshot 2022-07-13 at 2 24 23 PM" src="https://user-images.githubusercontent.com/66881214/178664900-deb7670c-3451-4049-98b5-bc253878be0a.png">
          
      </p>
      </details>

  -   Citations
      ```
      - Wang X, Peng Y, Lu L, Lu Z, Bagheri M, Summers RM. ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases. IEEE CVPR 2017 (https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)
      - NIH News release: https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community
      - Original source files and documents: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345
      ```

#### Chest X-ray Images (Pneumonia)
  -   Source: [Click here to proceed to site](https://data.mendeley.com/datasets/rscbjbr9sj/3)
  -   Data Type: Images 
  -   Possible uses: Create a model to identify classify Pneumonia from chest x-ray images
  -   Size: 1.27GB
  -   Example of data + Special Instructions(if any):
  
      Download file from Source. Images can be found in the chest_xray folder. They have been split into train, val and test folders. Within each folder, there are two folders NORMAL and PNEUMONIA.
      <details><summary>Example</summary>
      <p>
      
      NORMAL: <img src="https://user-images.githubusercontent.com/66881214/179992729-42493677-e051-4e13-ae91-c6ce18f4882c.jpeg" width="150" height="150">

      PNEUMONIA: <img src="https://user-images.githubusercontent.com/66881214/179992754-6a94cfae-a873-46ac-8f67-0bbdc01f6faf.jpeg" width="150" height="150">
      
      </p>
      </details>
         
  -   Note: NA
  -   Citations
      ```
      -  Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Large Dataset of Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images”, Mendeley Data, V3, doi: 10.17632/rscbjbr9sj.3
      ```
#### Covid19 Coswara Dataset

  -   Source:  [Click here to proceed to site](https://github.com/iiscleap/Coswara-Data)
  -   Data Type: Audio + Tabular
  -   Possible uses: Build an algorithm to distinguish cough between non-covid19 patients and covid19 patients 
  -   Size:  -
  -   Example of data + Special Instructions(if any):
         
         Download relevant files from Source
         
         <details><summary>Example</summary>
         <p>
          
         Audio sample to be included soon.
            
         Summary of metadata found in combined_data.csv in source:
           
         | id                           | a  | cold | record\_date | covid\_status  | ctScan | dT  | ep | fV | fever | g    | l\_c  | l\_l            | l\_s      | others\_resp | rU | smoker | testType | test\_date | test\_status | um | vacc | cough | ftg | mp   | st | diabetes | ht | bd | cld | diarrhoea | ctDate | ctScore | asthma | loss\_of\_smell | others\_preexist | ihd | pneumonia |
         | ---------------------------- | -- | ---- | ------------ | -------------- | ------ | --- | -- | -- | ----- | ---- | ----- | --------------- | --------- | ------------ | -- | ------ | -------- | ---------- | ------------ | -- | ---- | ----- | --- | ---- | -- | -------- | -- | -- | --- | --------- | ------ | ------- | ------ | --------------- | ---------------- | --- | --------- |
         | eK8ikIYnLQPWGetLBHzkJVCGfpq2 | 27 | TRUE | 18/1/22      | positive\_mild | n      | web | y  | 2  | TRUE  | male | India | Shimoga         | Karnataka | TRUE         | n  | n      | rtpcr    | 17/1/22    | p            | y  | y    |       |     |      |    |          |    |    |     |           |        |         |        |                 |                  |     |           |
         | AeP4E7hKFtOmcWye2MghbvDfGlo2 | 41 |      | 29/1/22      | positive\_mild | n      | web | y  | 2  | TRUE  | male | India | Bangalore rural | Karnataka |              | n  | n      | rtpcr    | 27/1/22    | p            | y  | y    | TRUE  |     | TRUE |    |          |    |    |     |           |        |         |        |                 |                  |     |           |

         </p>
         </details>
         
  -   Note: Audio files are in a zip file (example 20220224.tar.gz.aa). A extract_data.py is provided in source to extract the audio files which are of .wav format.
  
  -   Citations
      ```
      - Coswara - A Database of Breathing, Cough, and Voice Sounds for COVID-19 Diagnosis (https://arxiv.org/abs/2005.10548)
      ```      
#### QaTa COV19 Dataset 
  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/aysendegerli/qatacov19-dataset)
  - Data Type: Images
  - Possible uses: Build a model to classify covid19 patients using chest x-ray images
  -   Size of files 
      - 215.8MB for QaTa-COV19-v2 folder
      - 4.45GB for Control_Group 
  -   Example of data + Special Instructions(if any):
         
         Download the relevant files from Source 

         <details><summary>Example</summary>
         <p>
            
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
                
         </p>
         </details>

  - Note: If you would like to use other versions in the source, please cite accordingly as stated in the source.    
  - Citations
    ```
    - A. Degerli, S. Kiranyaz, M. E. H. Chowdhury, and M. Gabbouj, "OSegNet: Operational Segmentation Network for COVID-19 Detection using Chest X-ray Images," arXiv:2202.10185, 2022.
    ```
    
#### Respiratory Sound Database 
  - Source:  [Click here to proceed to site](https://bhichallenge.med.auth.gr/)
  - Data Type: Audio + Text/Tabular  
  - Possible uses: Build an algorithm to give an accurate diagnosis based on respiratory sounds
  -   Size of files
      -  1KB for diagnosis file
      -  3KB for demographic data file
      -  2.18GB for database folder 
  -   Example of data + Special Instructions(if any):
  
         <details><summary>Download the relevant files from Source:</summary>
         <p>
         
         To obtain class labels/diagnosis of each subject: <img width="803" alt="Screenshot 2022-07-16 at 11 51 25 PM" src="https://user-images.githubusercontent.com/66881214/179362176-ca8cc73f-7801-4833-9345-d812d179e8bf.png">
         To obtain demographic information regarding subjects: <img width="968" alt="Screenshot 2022-07-16 at 11 57 06 PM" src="https://user-images.githubusercontent.com/66881214/179362433-dbff5d53-a2a0-4c6b-a112-c7318676e34c.png">
         To obtain recordings: <img width="960" alt="Screenshot 2022-07-16 at 11 59 00 PM" src="https://user-images.githubusercontent.com/66881214/179362510-9f76cd39-cdf6-4be6-8bcb-da11028885f7.png">
         
         </p>
         </details>
         
         Example
   
         <details><summary>Diagnosis file</summary>
         <p>
         
         <img width="182" alt="Screenshot 2022-07-17 at 12 03 45 AM" src="https://user-images.githubusercontent.com/66881214/179362686-2666aaee-5fb8-4ef5-87e0-7359ac6f3ad5.png">
         
         </p>
         </details>
         
         <details><summary>Demographic data</summary>
         <p>
         
         <img width="303" alt="Screenshot 2022-07-17 at 12 04 46 AM" src="https://user-images.githubusercontent.com/66881214/179362726-0b64c3d2-1797-4c96-a068-d13192b6b640.png">
         
         Columns present (from left to right):
         * Participant ID
         * Age
         * Sex
         * Adult BMI (kg/m2)
         * Child Weight (kg)
         * Child Height (cm)
   
         </p>
         </details>
         
         <details><summary>Recording (101_1b1_Al_sv_Meditron.wav)</summary>
         <p>
         
         File was converted to mp4 [here](https://www.freeconvert.com/wav-to-mp4)
             
         https://user-images.githubusercontent.com/66881214/179362930-9cebcdf7-41c4-4115-8d84-348992d008d2.mp4
         
         File name is divided into 5 elements. Refer to image below for more details: 
         <img width="506" alt="Screenshot 2022-07-17 at 12 13 01 AM" src="https://user-images.githubusercontent.com/66881214/179363061-13dbed57-72fb-4c2c-ab71-8bd9f89fb85b.png">
         
         A corresponding text file (in this case 101_1b1_Al_sv_Meditron.txt) can also be found in the database folder: <img width="198" alt="Screenshot 2022-07-17 at 12 14 14 AM" src="https://user-images.githubusercontent.com/66881214/179363104-28ef50ec-ac22-4df1-b5c4-f4b44a0d9e3c.png">
         
         Columns present (from left to right): 
         * Beginning of respiratory cycle(s)
         * End of respiratory cycle(s)
         * Presence/absence of crackles (presence=1, absence=0)
         * Presence/absence of wheezes (presence=1, absence=0)
         
         </p>
         </details>
         
  - Note: If .wav files are not supported, try using online converter tools to convert to a audio file type that is supported by your device.
    - For example: [FreeConvert](https://www.freeconvert.com/audio-converter)     
  - Citations
    ```
    - Rocha BM, Filos D, Mendes L, Vogiatzis I, Perantoni E, Kaimakamis E, Natsiavas P, Oliveira A, Jácome C, Marques A, Paiva RP (2018) In Precision Medicine Powered by pHealth and Connected Health (pp. 51-55). Springer, Singapore 
      - The paper can be found at https://eden.dei.uc.pt/~ruipedro/publications/Conferences/ICBHI2017a.pdf
    ```
---

## Medical Transcripts

#### Adapting Phrase-based Machine Translation to Normalise Medical Terms in Social Media Messages

  -   Source: [Click here to proceed to site](https://zenodo.org/record/27354#.YuALs-xBw-Q)
  -   Data Type: Free Text
  -   Possible uses: Develop a tool to translate laymen's terms to a particular medical concept (Text normalization)
  -   Size: 11MB
  -   Example of data + Special Instructions(if any):
      
         Download EMNLP_gold_standard.txt from Source. 
             
         <details><summary>Example</summary>
         <p>
         
         <img width="660" alt="Screenshot 2022-07-26 at 11 58 05 PM" src="https://user-images.githubusercontent.com/66881214/181053678-4971a234-136b-49ae-b78a-5534591fca0c.png">

         </p>
         </details>

  -   Note: NA
  -   Citations
      ```
      - Limsopatham, N., & Collier, N. (2015). Adapting Phrase-based Machine Translation to Normalise Medical Terms in Social Media Messages [Data set]. Conference on Empirical Methods in Natural Language Processing (EMNLP 2015), Lisboa, Portugal. Zenodo. https://doi.org/10.5281/zenodo.27354
      ```        
      
#### ADE Corpus V2

  -   Source: [Click here to proceed to site](https://github.com/JohnSnowLabs/spark-nlp-workshop/tree/master/tutorials/Certification_Trainings/Healthcare/data/ADE_Corpus_V2)
      - Entire zip file is also available [here](https://sites.google.com/site/adecorpus/home/document)  
  -   Data Type: Free Text
  -   Possible uses: Build a model to extract information regarding Adverse Drug Effects from medical text
  -   Size of files:
      - 2.3MB for ADE-NEG.txt
      - 1.4MB for DRUG-AE.rel
      - 60KB for DRUG-DOSE.rel
  -   Example of data + Special Instructions(if any):
      
         Download relevant files from Source 
             
         Example:
         
         <details><summary>ADE-NEG.txt</summary>
         <p>
             
         ADE-NEG.txt provides all sentences in the ADE corpus that DO NOT contain any drug-related adverse effects.
         
         ADE-NEG.txt: <img width="1168" alt="Screenshot 2022-07-22 at 10 20 24 PM" src="https://user-images.githubusercontent.com/66881214/180459154-d25309e5-f17f-4dac-9555-02b79126fdea.png">
         
         </p>
         </details>
        
         <details><summary>DRUG-AE.rel</summary>
         <p>
         
         DRUG-AE.rel provides relations between drugs and adverse effects.
        
         DRUG-AE.rel: <img width="1082" alt="Screenshot 2022-07-22 at 10 21 12 PM" src="https://user-images.githubusercontent.com/66881214/180459339-7d30f9ad-5ffe-4045-8e82-742e7641dab8.png">
             
         The format of DRUG-AE.rel is as follows with pipe delimiters:
    
         * Column-1: PubMed-ID
         * Column-2: Sentence 
         * Column-3: Adverse-Effect
         * Column-4: Begin offset of Adverse-Effect at 'document level'
         * Column-5: End offset of Adverse-Effect at 'document level'
         * Column-6: Drug
         * Column-7: Begin offset of Drug at 'document level'
         * Column-8: End offset of Drug at 'document level'
         
         </p>
         </details>
             
         <details><summary>DRUG-DOSE.rel</summary>
         <p>
             
         DRUG-DOSE.rel provides relations between drugs and dosages.
         
         DRUG-DOSE.txt <img width="985" alt="Screenshot 2022-07-22 at 10 22 11 PM" src="https://user-images.githubusercontent.com/66881214/180459542-231715bb-731d-4da3-bcb2-6de8b1a9e952.png">
             
        The format of DRUG-DOSE.rel is as follows with pipe delimiters:

        * Column-1: PubMed-ID
        * Column-2: Sentence 
        * Column-3: Dose
        * Column-4: Begin offset of Dose at 'document level'
        * Column-5: End offset of Dose at 'document level'
        * Column-6: Drug
        * Column-7: Begin offset of Drug at 'document level'
        * Column-8: End offset of Drug at 'document level'

         </p>
         </details>

  -   Note: NA
  -   Citations
      ```
      - If you use this corpus for any publication purposes, you are requested to cite the source article:

       Gurulingappa et al., Benchmark Corpus to Support Information Extraction for Adverse Drug Effects, JBI, 2012.
       http://www.sciencedirect.com/science/article/pii/S1532046412000615

      ```
#### CDR BioCreative V Chemical Disease Relation corpus
           
  -   Source: [Click here to proceed to site](http://gcancer.org/clstmdata/)
  -   Data Type: Free Text
  -   Possible uses: Disease named entity recognition and chemical-induced disease relation extraction
  -   Size: 11.2MB
  -   Example of data + Special Instructions(if any):
      
         Download folder from CDR section from Source. 
             
         <details><summary>Example</summary>
         <p>
        
         <img width="867" alt="Screenshot 2022-07-25 at 5 15 23 PM" src="https://user-images.githubusercontent.com/66881214/180742377-cec3a59a-ab43-4433-b317-c8b4dc8d50b1.png">
         
         </p>
         </details>

  -   Note: Medical Subject Headings(MeSH) is used in this dataset 
  -   Citations
      ```
      - Li, J., Sun, Y., Johnson, R. J., Sciaky, D., Wei, C. H., Leaman, R., Davis, A. P., Mattingly, C. J., Wiegers, T. C., & Lu, Z. (2016). BioCreative V CDR task corpus: a resource for chemical disease relation extraction. Database : the journal of biological databases and curation, 2016, baw068. https://doi.org/10.1093/database/baw068
      ```
#### i2b2 dataset (no preview)
      
  -   Source: [Click here to proceed to site](https://portal.dbmi.hms.harvard.edu/projects/n2c2-nlp/)
  -   Data Type: Free Text
  -   Possible uses: NLP research on clinical text
  -   Size: Unknown 
  -   Example of data + Special Instructions(if any):
      
      <details><summary>Links to key citations</summary>   
      <p>    
      
      <details><summary>2006 - Deidentification & Smoking</summary>   
      <p>    
      
        - [Evaluating the state-of-the-art in automatic de-identification](https://academic.oup.com/jamia/article/14/5/550/720189?login=true)
          - Sample Discharge Summary Excerpt: <img width="389" alt="Screenshot 2022-07-26 at 1 48 05 PM" src="https://user-images.githubusercontent.com/66881214/180932608-42fe4eaf-0c49-4ee0-b16d-db63409277b7.png">
        - [Identifying patient smoking status from medical discharge records](https://academic.oup.com/jamia/article/15/1/14/779738?login=true)
          - Annotator Training Samples: <img width="1066" alt="Screenshot 2022-07-26 at 1 51 06 PM" src="https://user-images.githubusercontent.com/66881214/180933012-6f965946-10ee-45b5-97dc-4efa0d3b731b.png">
          
      </p>
      </details>
          
      <details><summary>2008 - Obesity</summary>   
      <p>    
      
        - [Recognizing Obesity and Co-morbidities in Sparse Data](https://academic.oup.com/jamia/article/16/4/561/766997?login=true)
          - Obesity Challenge data consisted of 1237 discharge summaries from the Partners HealthCare Research Patient Data Repository. These data were chosen from the discharge summaries of patients who were overweight or diabetic and had been hospitalized for obesity or diabetes sometime since 12/1/04.
      </p>
      </details>          
      <details><summary>2009 - Medication</summary>   
      <p>    
      
        - [Extracting Medication Information from Clinical Text](https://academic.oup.com/jamia/article/17/5/514/2909108?login=true)
          - Sample discharge summary narrative and the output for the italicized portion: <img width="530" alt="Screenshot 2022-07-26 at 2 08 23 PM" src="https://user-images.githubusercontent.com/66881214/180935400-f688947d-538f-42b6-bcb7-031cb2471465.png">
          
            m, do, mo, f, du, r, and ln stand for medication, dosage, mode, frequency, duration, reason, and list/narrative, respectively.
            
            nm stands for not mentioned

        - [Community Annotation Experiment for Ground Truth Generation for the i2b2 Medication Challenge](https://academic.oup.com/jamia/article/17/5/519/831043?login=true)
      </p>
      </details>
          
      <details><summary>2010 - Relations</summary>   
      <p>    
      
        - [2010 i2b2/VA Challenge on Concepts, Assertions, and Relations in Clinical Text](https://academic.oup.com/jamia/article/18/5/552/830538?login=true)
           - Sample text excerpt, its concepts, assertions, and relations: <img width="544" alt="Screenshot 2022-07-26 at 2 14 24 PM" src="https://user-images.githubusercontent.com/66881214/180936281-6a7219d7-cfb6-4a1b-beac-d9204f9720fb.png">
      </p>
      </details>          
      <details><summary>2011 - Coreference</summary>   
      <p>    
      
        - [Evaluating the state of the art in coreference resolution for electronic medical records](https://academic.oup.com/jamia/article/19/5/786/716138?login=true)
          - i2b2/VA corpus: de-identified discharge summaries from Beth Israel Deaconess Medical Center, Partners Healthcare, and University of Pittsburgh Medical Center (UPMC)
          - Ontology Development and Information Extraction corpus: de-identified clinical reports and pathology reports from Mayo Clinic, and de-identified discharge records, radiology reports, surgical pathology reports, and other reports from UPMC
      </p>
      </details>
      <details><summary>2012 - Temporal Relations</summary>   
      <p>    
      
        - [Evaluating temporal relations in clinical text: 2012 i2b2 Challenge](https://academic.oup.com/jamia/article/20/5/806/726374?login=true)
          - 310 discharge summaries consisting of 178 000 tokens
        - [Annotating temporal information in clinical narratives](https://www.sciencedirect.com/science/article/pii/S1532046413001032?via%3Dihub)
          - Sample clinical record snippet: <img width="472" alt="Screenshot 2022-07-26 at 2 25 37 PM" src="https://user-images.githubusercontent.com/66881214/180938077-6a111052-6244-4416-8222-4c2da808eced.png">
      </p>
      </details>
      <details><summary>2014 - Deidentification & Heart Disease</summary>   
      <p>    
      
        - [Creation of a new longitudinal corpus of clinical narratives](https://www.sciencedirect.com/science/article/pii/S1532046415002129?via%3Dihub)
          - Letters between medical professionals: “Dear [Dr]: I had the pleasure of seeing [patient] today for a follow up visit. I last saw him in November of last year. As you know, [patient] is a 72 year old man…” (Background information on the patient + details on the patient’s current health and latest check-up)
          - Discharge summaries and notes written by the doctor after a patient visit: “The patient is a 40-year-old woman with history of coronary disease and has had intermittent chest pain over the past 4 days…” 
        - [Automated systems for the de-identification of longitudinal clinical narratives: Overview of 2014 i2b2/UTHealth shared task Track 1](https://www.sciencedirect.com/science/article/pii/S1532046415001173?via%3Dihub)
          - Consists of 1,304 medical records for 296 diabetic patients
        - [Annotating longitudinal clinical narratives for de-identification: The 2014 i2b2/UTHealth corpus](https://www.sciencedirect.com/science/article/pii/S1532046415001823?via%3Dihub)
          - Sample of clinical text before and after surrogate generation using simplified XML representation: <img width="481" alt="Screenshot 2022-07-26 at 2 40 42 PM" src="https://user-images.githubusercontent.com/66881214/180940359-b2c31de4-541c-4d6b-8812-d33b293d169d.png">
      </p>
      </details>
      <details><summary>2018 (Track 1) - Clinical Trial Cohort Selection</summary>   
      <p>    
      
        - [Cohort selection for clinical trials: n2c2 2018 shared task track 1](https://academic.oup.com/jamia/article-abstract/26/11/1163/5575392?redirectedFrom=fulltext&login=true)
          - Note: I did not have access to this article
      </p>
      </details>
      <details><summary>2018 (Track 2) - Adverse Drug Events and Medication Extraction</summary>   
      <p>    
      
        - [2018 n2c2 shared task on adverse drug events and medication extraction in electronic health records](https://academic.oup.com/jamia/article-abstract/27/1/3/5581277?redirectedFrom=fulltext&login=true)
          - Note: I did not have access to this article
      </p>
      </details>
          
      </p>
      </details>
             
      <details><summary>Steps to request data</summary>
      <p>
          
      Step 1: Sign up and verify your email 
             
      Step 2: Complete your profile
      - Your first name, last name, primary email (auto-filled when you sign up with your email), professional title, country are required fields
          
      Step 3: Complete NLP Research Purpose form
      
      Step 4: Complete NLP Data Use Agreement(DUA) 
      - There are two types of data use agreement type. Both Academic user DUA and Corporate user DUA forms can be found [here](https://n2c2.dbmi.hms.harvard.edu/data-use-agreement)
   
      Step 5: Click request access. It will take about 5 business days to process.
          
      </p>
      </details>

  -   Note: NA
  -   Citations
      ```
      - Informatics for Integrating Biology to the Bedside, Partners Healthcare Systems.
        URL: www.i2b2.org [date (month, yr) accessed].
      ```             
#### MeDAL Dataset 

  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/xhlulu/medal-emnlp)
  -   Data Type: Free Text
  -   Possible uses: Medical Dataset for Abbreviation Disambiguation for Natural Language Understanding (MeDAL) is a large medical text dataset curated for abbreviation disambiguation, designed for natural language understanding pre-training in the medical domain. It was published at the ClinicalNLP workshop at EMNLP.
  -   Size: 21.06GB
      - 15.16GB for full_data.csv
      - 5.9GB for pretrain_subset
        - 3.54GB for train.csv 
        - 1.18GB for valid.csv
        - 1.18GB for test.csv
  -   Example of data + Special Instructions(if any):
      
         Download relevant folder from Source. 
             
         <details><summary>Example</summary>
         <p>
         
         | ABSTRACT\_ID | TEXT | LOCATION | LABEL                             |  
         | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------- | --------------------------------- |
         | 5017844      | different electrocardiographic changes have been described during thrombolytic therapy for AIM to indicate successful reperfusion the occluded coronary artery also can be reopened by percutaneous TCA ptca this study was performed to compare electrocardiographic changes during primary or rescue ptca and thrombolytic therapy the electrocardiographic changes were studied directly at the moment of reperfusion during ptca| 25       | transluminal coronary angioplasty |
         | 8923525      | there are limited data regarding cdx expression in rectal carcinoma the ckck immunoprofile of CRC has been described in studies which have mostly lumped Tc and rectal PT together in this study we investigated the diagnostic utility of immunohistochemical stains for ck ck and cdx in a series of rectal adenocarcinoma fiftyfive specimens of rectal adenocarcinomas were retrieved and immunostained for ck dakom ck novocastra ncllck and cdx novocastra nclcdx thirty cases of pancreatic adenocarcinoma and CC were also studied as a comparison group ck was expressed in and ck in cases of rectal adenocarcinoma the ckck immunophenotype was identified in ckck in and ckck in rectal adenocarcinoma cdx showed moderatestrong positivity in all cases and was not related to RT differentiation benign rectal mucosa was available in cases and showed the following results ckck in ckck in and ckck in cases in pancreatic adenocarcinomas and cholangiocarcinomas were ckck and were ckck cdx was positive in only of these cases all were pancreatic adenocarcinomas in conclusion ck can be expressed in rectal adenocarcinoma and should not be used as the sole basis for excluding a rectal primary cdx is a CS marker for rectal origin of adenocarcinoma it can be helpful in cases with metastatic rectal carcinoma especially those with ckck or ckck immunophenotype in this study cdx expression was not influenced by the grade differentiation of rectal adenocarcinoma | 14       | colorectal adenocarcinoma         |
         
         </p>
         </details>

  -   Note: The files might take some time to open due to its large size
  -   Citations
      ```
      - Wen, Z., Lu, X., & Reddy, S. (2020). MeDAL: Medical Abbreviation Disambiguation Dataset for Natural Language Understanding Pretraining. In Proceedings of the 3rd Clinical Natural Language Processing Workshop (pp. 130–135). Association for Computational Linguistics.
      ``` 
      
#### MedMCQA
  -   Source: [Click here to proceed to site](https://drive.google.com/uc?export=download&id=15VkJdq5eyWIkfb_aoD3oS8i4tScbHYky)
  -   Data Type: Free Text
  -   Possible uses: AI for answering medical questions
  -   Size: 151.6MB
  -   Example of data + Special Instructions(if any):
      
         Download folder from Source. 
             
         <details><summary>Example</summary>
         <p>
         
         <img width="1091" alt="Screenshot 2022-07-27 at 12 38 03 AM" src="https://user-images.githubusercontent.com/66881214/181062158-3878ff9c-e049-444b-abbd-ff675c3cc205.png">
         
         </p>
         </details>

  -   Note: NA
  -   Citations
      ```
      - Pal, A., Umapathi, L., & Sankarasubbu, M. (2022). MedMCQA: A Large-scale Multi-Subject Multi-Choice Dataset for Medical domain Question Answering. In Proceedings of the Conference on Health, Inference, and Learning (pp. 248–260). PMLR.
      ``` 

#### MedMentions

  -   Source: [Click here to proceed to site](https://github.com/chanzuckerberg/MedMentions/tree/master/full/data)
  -   Data Type: Free Text
  -   Possible uses: NLP research on Biomedical text/Build a tool to recognise biomedical concepts in long medical texts
  -   Size: 22.5MB
  -   Example of data + Special Instructions(if any):
      
         Download corpus_pubtator.txt.gz from Source. 
             
         <details><summary>Example</summary>
         <p>
         
         <img width="1151" alt="Screenshot 2022-07-25 at 2 53 03 PM" src="https://user-images.githubusercontent.com/66881214/180715966-ee2b765f-ec6d-4548-a3ff-3403b3cf9962.png">
         
         Format: 
             
         PMID | t | Title text
             
         PMID | a | Abstract text
             
         PMID TAB StartIndex TAB EndIndex TAB MentionTextSegment TAB SemanticTypeID TAB EntityID
         
         </p>
         </details>

  -   Note: The IDs are linked to UMLS concept
  -   Citations
      ```
      - Sunil Mohan and Donghui Li. 2019. MedMentions: A Large Biomedical Corpus Annotated with UMLS Concepts. In Proceedings of the 2019 Conference on Automated Knowledge Base Construction (AKBC 2019). Amherst, Massachusetts, USA. May 2019 (https://arxiv.org/abs/1902.09476)
      ```        
#### MedQA
            
  -   Source: [Click here to proceed to site](https://github.com/jind11/MedQA)
  -   Data Type: Free Text
  -   Possible uses: Building models for open domain question answering(OpenQA) tasks in the medical field(This is a free-form multiple-choice OpenQA dataset for solving medical problems)    
  -   Size: 391.4MB
  -   Example of data + Special Instructions(if any):
      
         Download data from Google Drive folder from Source. 
             
         Example:
         
         <details><summary>US_qbank.jsonl from Questions US folder</summary>
         <p>
             
         <img width="677" alt="Screenshot 2022-07-25 at 3 43 35 PM" src="https://user-images.githubusercontent.com/66881214/180724634-4970b106-3dc0-4258-b9e5-fa9855bf0974.png"> 

         </p>
         </details>             
         
         <details><summary>Textbook</summary>
         <p>
         
         There is a list of text files regarding various medical topics in this folder:
             
         <img width="243" alt="Screenshot 2022-07-25 at 3 42 13 PM" src="https://user-images.githubusercontent.com/66881214/180724342-df630bd3-12cd-49a0-8c9c-ff50e2657792.png">
             
         Example of abstract from Anatomy_Gray.txt:

         <img width="676" alt="Screenshot 2022-07-25 at 3 42 37 PM" src="https://user-images.githubusercontent.com/66881214/180724426-0124db05-94f9-4386-ad40-0aeceb37f5bd.png">

         </p>
         </details>          

  -   Note: NA
  -   Citations
      ```
      - Jin, D., Pan, E., Oufattole, N., Weng, W.H., Fang, H., & Szolovits, P. (2020). What Disease does this Patient Have? A Large-scale Open Domain Question Answering Dataset from Medical Exams. arXiv preprint arXiv:2009.13081.
      ```
             
#### MedQuAD

  -   Source: [Click here to proceed to site](https://github.com/abachaa/MedQuAD)
  -   Data Type: Free Text
  -   Possible uses: Develop a tool that could answer medical questions automatically by mapping new questions to formally answered questions that are "similar"
  -   Size of folders:
      - 3MB for CancerGov
      - 9.6MB for GARD
      - 6.3MB for GHR
      - 1.5MB for MPlus_Health_Topics
      - 2.3MB for NIDDK
      - 1MB for NINDS
      - 1.3MB for SeniorHealth 
      - 1.9MB for NHLBI
      - 455KB for CDC
      - 5.4MB for MPlus_ADAM
      - 2.8MB MPlusDrugs 
      - 175KB for MPlusHerbsSupplements 
  -   Example of data + Special Instructions(if any):
      
         Download relevant files from Source. There are 12 categories available.

         Example:
         
         <details><summary>CancerGov_QA</summary>
         <p>
        
         <img width="900" alt="Screenshot 2022-07-25 at 1 55 16 PM" src="https://user-images.githubusercontent.com/66881214/180707746-1be8d6aa-278d-4935-9584-dc2ae054ee9b.png">
         
         </p>
         </details>

  -   Note: NA
  -   Citations
      ```
      - Asma Ben Abacha, & Dina Demner-Fushman (2019). A Question-Entailment Approach to Question Answering. BMC Bioinform., 20(1), 511:1–511:23. (https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3119-4)
      ```
#### NCBI Disease Corpus

  -   Source: [Click here to proceed to site](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/)
  -   Data Type: Free Text
  -   Possible uses: Disease name recognition and normalization for biomedical research    
  -   Size of files:
      - 1.3MB for NCBI Disease Corpus(Mention Level)
      - 1MB for NCBI Disease Corpus(Complete - Train set)
      - 178KB for NCBI Disease Corpus(Complete - Development set)
      - 189KB for NCBI Disease Corpus(Complete - Test set)
  -   Example of data + Special Instructions(if any):
      
         Download relevant files from Source 
                  
         Example:
             
         <details><summary>NCBI Disease Corpus (Mention Level) </summary>
         <p>
        
         Training: <img width="679" alt="Screenshot 2022-07-25 at 4 55 14 PM" src="https://user-images.githubusercontent.com/66881214/180738302-43d37853-3597-41e9-a36a-0c1dc8c75e2a.png">

         </p>
         </details>   
             
         <details><summary>NCBI Disease Corpus(Complete - Train set)</summary>
         <p>
        
         <img width="951" alt="Screenshot 2022-07-25 at 4 56 27 PM" src="https://user-images.githubusercontent.com/66881214/180738573-7ed702e9-9c3d-4781-824a-3633adaa52d3.png">

         </p>
         </details> 
             
  -   Note: Medical Subject Headings (MeSH) and Online Mendelian Inheritance in Man (OMIM) are used in this dataset
  -   Citations
      ```
      - Rezarta Islamaj Doğan, Robert Leaman, & Zhiyong Lu (2014). NCBI disease corpus: A resource for disease name recognition and concept normalization. Journal of Biomedical Informatics, 47, 1-10.
      ```             
             
#### Patient Physician Medical Interviews 
  - Source:  [Click here to proceed to site](https://figshare.com/collections/A_dataset_of_simulated_patient-physician_medical_interviews_with_a_focus_on_respiratory_cases/5545842)
  - Data Type: Audio + Free Text 
  - Possible uses: Speech recognition detection for speech-to-text errors/ Training NLP models to extract symptoms, detect diseases/ For educational purposes such as training an avatar to converse with healthcare professional students as a standardized patient during clinical examinations
  -   Size: 1.05 GB 
  -   Example of data + Special Instructions(if any):
  
         Download from source 

         <details><summary>Example</summary>
         <p>
         
         CAR0001.mp3 in Audio Recordings will correspond to CAR0001.txt in Clean Transcripts
             
         (File was converted to mp4 [here](https://www.freeconvert.com/mp3-to-mp4))
         
         https://user-images.githubusercontent.com/66881214/179450404-a22b08df-2073-4193-ab42-fbf1483f25ba.mp4
         
         </p>
         </details>
         
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
    ```
    - Smith, Christopher William; Fareez, Faiha; Parikh, Tishya; Wavell, Christopher; Shahab, Saba; Chevalier, Meghan; et al. (2022): Collection of simulated medical exams. figshare. Dataset. 
    ```

#### PubMed 200k RCT dataset

  -   Source: [Click here to proceed to site](https://github.com/Franck-Dernoncourt/pubmed-rct)
  -   Data Type: Free Text
  -   Possible uses: Develop an algorithm that can summarise a long medical abstract accurately
  -   Size of folders (each folder has a train.txt, test.txt and dev.txt):
      - 39.2MB for PubMed_20k_RCT 
      - 38.6MB for PubMed_20k_RCT_numbers_replaced_with_at_sign 
      - 367.1MB for PubMed_200k_RCT 
      - 361MB for PubMed_200k_RCT_numbers_replaced_with_at_sign 
  -   Example of data + Special Instructions(if any):
      
         Download relevant files from Source 
         <details><summary>Example</summary>
         <p>

         <img width="1174" alt="Screenshot 2022-07-22 at 9 14 59 PM" src="https://user-images.githubusercontent.com/66881214/180446748-20361dba-3bcb-4163-9288-ff60f18d1fed.png">

         </p>
         </details>

  -   Note: NA
  -   Citations
      ```
      - Franck Dernoncourt, Ji Young Lee. PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts. International Joint Conference on Natural Language Processing (IJCNLP). 2017. https://arxiv.org/abs/1710.06071
      ```
---

## Other Diseases 

#### Chula RBC-12-Dataset
  -   Source:  [Click here to proceed to site](https://github.com/Chula-PIC-Lab/Chula-RBC-12-Dataset)
  -   Data Type: Images + Text/Tabular
  -   Possible uses: Build a model to classify type of red blood cell disease from red blood cell images
  -   Size: Depends. One image is about 79KB. 
      - 73.5MB for Dataset folder 
      - 216KB for Labels folder
  
  -   Example of data + Special Instructions(if any):
  
         Download images in Dataset folder and corresponding text files in Label folder from Source.
         <details><summary>You could also download the entire folder by downloading the zip folder as shown below</summary>
         <p>
         
         <img width="927" alt="Screenshot 2022-07-18 at 10 23 20 PM" src="https://user-images.githubusercontent.com/66881214/179533073-c46fcd53-bf27-4148-b3f7-71744719a75b.png">
           
         </p>
         </details>

         <details><summary>Example: 1.jpg in Dataset folder will correspond to 1.txt in Label folder</summary>
         <p>
      
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
         
         </p>
         </details>
         
  -   Note: There are other images that correspond to other red blood diseases that can be found in the RBC Diseases folder from Source. 
  
  -   Citations
      ```
      - Naruenatthanaset, K., Chalidabhongse, T. H., Palasuwan, D., Anantrasirichai, N., &amp; Palasuwan, A. (2021, November 3). Red blood cell segmentation with overlapping cell separation and classification on Imbalanced Dataset. arXiv.org. Retrieved July 14, 2022, from https://arxiv.org/abs/2012.01321   
      ```

#### Fetal Health Classification 

  - Source:  [Click here to proceed to site](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
  - Data Type: Tabular 
  - Possible uses: Build a model to classify fetal health in order to prevent child and maternal mortality 
  -   Size: 229KB
  -   Example of data + Special Instructions(if any):
            
         Download from Source
         <details><summary>Example</summary>
         <p>
                
         | baseline value | accelerations | fetal\_movement | uterine\_contractions | light\_decelerations | severe\_decelerations | prolongued\_decelerations | abnormal\_short\_term\_variability | mean\_value\_of\_short\_term\_variability | percentage\_of\_time\_with\_abnormal\_long\_term\_variability | mean\_value\_of\_long\_term\_variability | histogram\_width | histogram\_min | histogram\_max | histogram\_number\_of\_peaks | histogram\_number\_of\_zeroes | histogram\_mode | histogram\_mean | histogram\_median | histogram\_variance | histogram\_tendency | fetal\_health |
         | -------------- | ------------- | --------------- | --------------------- | -------------------- | --------------------- | ------------------------- | ---------------------------------- | ----------------------------------------- | ------------------------------------------------------------- | ---------------------------------------- | ---------------- | -------------- | -------------- | ---------------------------- | ----------------------------- | --------------- | --------------- | ----------------- | ------------------- | ------------------- | ------------- |
         | 120            | 0             | 0               | 0                     | 0                    | 0                     | 0                         | 73                                 | 0.5                                       | 43                                                            | 2.4                                      | 64               | 62             | 126            | 2                            | 0                             | 120             | 137             | 121               | 73                  | 1                   | 2             |
         | 132            | 0.006         | 0               | 0.006                 | 0.003                | 0                     | 0                         | 17                                 | 2.1                                       | 0                                                             | 10.4                                     | 130              | 68             | 198            | 6                            | 1                             | 141             | 136             | 140               | 12                  | 0                   | 1             |
         | 133            | 0.003         | 0               | 0.008                 | 0.003                | 0                     | 0                         | 16                                 | 2.1                                       | 0                                                             | 13.4                                     | 130              | 68             | 198            | 5                            | 1                             | 141             | 135             | 138               | 13                  | 0                   | 1             |
        
      </p> 
      </details>       
  - Note: NA
  - Citations
    ```
    - Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318(https://onlinelibrary.wiley.com/doi/10.1002/1520-6661(200009/10)9:5%3C311::AID-MFM12%3E3.0.CO;2-9)
    ```
#### Disease-symptom associations generated by an automated method based on information in textual discharge summaries of patients at New York Presbyterian Hospital admitted during 2004

  - Source:  [Click here to proceed to site](https://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html)
  - Data Type: Tabular 
  - Possible uses: Build a model to predict disease from symptoms
  -   Size: 84KB
  -   Example of data + Special Instructions(if any):
         
         You can download the data [here](https://github.com/joeytxy/public-data-documentation-/blob/main/disease_symptom.csv)
             
         <details><summary>Example</summary>
         <p>
             
         <img width="1055" alt="Screenshot 2022-07-27 at 2 55 51 PM" src="https://user-images.githubusercontent.com/66881214/181181658-9bfcfc4b-5b26-4cc9-b0d6-57ec7a18fdbc.png">

         </p>
         </details>
             
  - Note: NA
  - Citations
    ```
    - Wang X, Chused A, Elhadad N, Friedman C, Markatou M. Automated knowledge acquisition from clinical narrative reports. AMIA Annu Symp Proc. 2008 Nov 6;2008:783-7. PMID: 18999156; PMCID: PMC2656103.
    ```            
             
