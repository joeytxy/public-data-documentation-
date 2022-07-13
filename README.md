# Public Data Documentation

A collection of public healthcare datasets

Type of datasets include 

1. Tabular 
2. Images 
3. Free Text 
4. Audio 

Note: If you are unable to download the data from the site, you may proceed to the respective folders above to download directly. 

### Chest Related Datasets

#### NIH Chest X-ray Dataset
  -   Source: [Click here to proceed to site](https://www.kaggle.com/datasets/nih-chest-xrays/data?resource=download)
  -   Data Type: Images + Tabular 
  -   Folder Contents (Size 45 GiB)
      - 112,120 images with 1024 x 1024 resolution stored in 12 zip folders
        - Each image has corresponding row(s) in Data_Entry_2017.csv   
      - Data_Entry_2017.csv
        - Contains various information on the patient 
        - Indicates class labels of each image 
      - BBox_List_2017.csv 
        - Contains coordinates of disease region bounding boxes
      - Various pdf and text files 
        - FAQ_CHESTXRAY.pdf 
        - LOG_CHESTXRAY.pdf
        - README_CHESTXRAY.pdf
        - test_list.txt
        - train_val_list.txt
  -   Example of data + Instructions 
      1. 

  -   Note: Some image labels may not be accurate. A more accurate version is said to be available [here](https://cloud.google.com/healthcare-api/docs/resources/public-datasets/nih-chest#additional_labels). You would be required to submit the following google form to obtain the updated data.  <img width="479" alt="Screenshot 2022-07-13 at 2 24 23 PM" src="https://user-images.githubusercontent.com/66881214/178664900-deb7670c-3451-4049-98b5-bc253878be0a.png">

  -   Citations
      - Wang X, Peng Y, Lu L, Lu Z, Bagheri M, Summers RM. ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases. IEEE CVPR 2017, [ChestX-ray8Hospital-ScaleChestCVPR2017_paper.pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)
      - NIH News release: [NIH Clinical Center provides one of the largest publicly available chest x-ray datasets to scientific community](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community)
      - Original source files and documents: [Box application link](https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345)
