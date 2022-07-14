# Public Data Documentation

A collection of public healthcare datasets

Type of datasets include 

1. Tabular 
2. Images 
3. Free Text 
4. Audio 

Table of Contents 

1. [Common Diseases](#Common-Diseases)
    - [Diabetes 130-US hospitals for years 1999-2008 Data Set](#Diabetes-130-US-hospitals-for-years-1999-2008-Data-Set) 
2. [Cancer Datasets](#Cancer-Datasets)
    - [Breast Cancer Data set](#Breast-Cancer-Data-set)
    - [Breast Cancer Wisconsin (Original) Data Set](#Breast-Cancer-Wisconsin-Original-Data-Set)
    - [Breast Cancer Wisconsin (Prognostic) Data Set](#Breast-Cancer-Wisconsin-Prognostic-Data-Set)
    - [Breast Cancer Wisconsin (Diagnostic) Data Set](#Breast-Cancer-Wisconsin-Diagnostic-Data-Set)
3. [Chest Related Datasets](#Chest-Related-Datasets)
    - [NIH Chest X-ray Dataset](#NIH-Chest-X-ray-Dataset) 
    - [Chest X-ray Images Pneumonia](#Chest-X-ray-Images-Pneumonia)
4. [Other Diseases](#Other-Diseases) 
    - [Chula RBC-12-Dataset](#Chula-RBC-12-Dataset)  

### Common Diseases 

#### Diabetes 130-US hospitals for years 1999-2008 Data Set
  - Source:  [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
  
  - Data Type: Tabular 
  
  -   Size of files
      -  19.2MB for diabetic_data.csv
      -  3KB for IDs_mapping.csv
  -   Example of data + Special Instructions(if any) 
      1. Download dataset_diabetes.zip from Data Folder from Source 
      2. Example: [Click here to preview top 2 records of dataset](https://github.com/joeytxy/public-data-documentation-/blob/main/Common%20Disease/Diabetes%20130-US%20hospitals%20for%20years%201999-2008%20Data%20Set/Preview%20of%20Data) 
  - Citations
    - Beata Strack, Jonathan P. DeShazo, Chris Gennings, Juan L. Olmo, Sebastian Ventura, Krzysztof J. Cios, and John N. Clore, “Impact of HbA1c Measurement on Hospital Readmission Rates: Analysis of 70,000 Clinical Database Patient Records,” BioMed Research International, vol. 2014, Article ID 781670, 11 pages, 2014. [Link](https://www.hindawi.com/journals/bmri/2014/781670/)
 
### Cancer Datasets

#### Breast Cancer Data set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer)
  -   Data Type: Free Text/Tabular 
  -   Size: 19 KB
  -   Example of data + Special Instructions(if any) 
      1. Download breast-cancer.data stored in Data Folder from Source 
      2. Example:
      
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
      
#### Breast Cancer Wisconsin (Original) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29)
  -   Data Type: Free Text/Tabular 
  -   Size: 20 KB
  -   Example of data + Special Instructions(if any) 
      1. Download breast-cancer-wiscoinsin.data stored in Data Folder from Source 
      2. Example:
            
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

#### Breast Cancer Wisconsin (Prognostic) Data Set
  -   Source: [Click here to proceed to site](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Prognostic%29)
  -   Data Type: Free Text/Tabular 
  -   Size: 20 KB
  -   Example of data + Special Instructions(if any) 
      1. Download wpbc.data stored in Data Folder from Source 
      2. Example:
            
         
         
         Columns present (from left to right):
         * 
   -   Note: Dataset from Source is of .data file. If you are unable to view the file after downloading directly, right click on the file and open with any text editor application(eg Notepad). 
   
       To download as .csv file, right click on wpbc.data as shown :
            
       <img width="909" alt="Screenshot 2022-07-14 at 9 07 11 PM" src="https://user-images.githubusercontent.com/66881214/178989493-b7de3cca-da5f-4598-83cb-a28838ec52e0.png">
            
       Proceed to add the .csv extention in file name and save to desired location 
            
       <img width="326" alt="Screenshot 2022-07-14 at 9 08 03 PM" src="https://user-images.githubusercontent.com/66881214/178989650-9b61aa22-48be-4c78-ad15-5d488fbbf0a7.png">
       
   -   Citations
      - 

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
         
  -   Note: NA
  -   Citations
      -  Please cite [this](http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5)

### Other Diseases 

#### Chula RBC-12-Dataset
  -   Source:  [Click here to proceed to site](https://github.com/Chula-PIC-Lab/Chula-RBC-12-Dataset)
  
  -   Data Type: Images + Free Text 
  
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
      - Please cite [this](https://arxiv.org/abs/2012.01321)    

         
         
    

