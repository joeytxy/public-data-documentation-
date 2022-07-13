# Public Data Documentation

A collection of public healthcare datasets

Type of datasets include 

1. Tabular 
2. Images 
3. Free Text 
4. Audio 

Table of Contents 

1. [Common Diseases](#Common-Diseases)
    - Diabetic Retinopathy Detection
2. Chest Related Datasets 
    - NIH Chest X-ray Dataset 
    - Chest X-ray Images Pneumonia
3. Other Diseases 
    - Chula RBC-12-Dataset  

### Common Diseases 

#### Diabetic Retinopathy Detection 
  - Source:  [Click here to proceed to site](https://www.kaggle.com/competitions/diabetic-retinopathy-detection/data)
  - Data Type: Images 
  - Size

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
         <img width="1191" alt="Screenshot 2022-07-13 at 3 55 31 PM" src="https://user-images.githubusercontent.com/66881214/178681269-37873e8b-6749-4658-843a-6ab3a6ff7c8d.png"> In this example, the image is classified to 3 different diseases, namely Cadiomegaly, Edema and Infiltration.
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

         
         
    

