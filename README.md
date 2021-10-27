# BHT_FashionAI_Project

## Project Flow

1. Sales Perfromance Data Analysis
2. Collection and Pre-processing of Fashion Images based on sales data analysis-for product 'Trousers/Hose'
4. Generation of Fashion Images with the help of DCGAN

## 1. Sales Perfromance Data Analysis
1. For the sales performance data analysis, the sales data is provided in the csv file. Run the '**Sales Performance Analysis.ipynb**' file. 
2. Result: For this use case, The analysis shows, 'Trousers/Hose' is the trending product for customer in FS 21.

## 2. Collection and Pre-processing of Fashion Images based on sales data analysis-- for product 'Trousers/Hose'
 1. For Collecting the Fashion images for item 'Trousers/Hose', the bulk bing downloader and Fatkun Imanges Batch Downloder (Chrome Extension) is used.
 2. Then stor all gathered images in local folder. Afterwards, run the file '**Fashion Images Data Pre-processing.ipynb**' for fashion images data pre-processing. 
     Here, specify the local folder path where the collected fashion images of 'Trousers/Hose'.
     
     Here in this case, we uploaded all the fashion images data in Google Drive : https://drive.google.com/drive/folders/1BZn58-7iasLeLUMfQnW-OG4gw2UPUQmJ?usp=sharing
 3. Results: Processed Fashion Images data. (Duplicates Removal, File Format Change, Resized Images)
 4. Store these fashion images for Further process. 
    
 
## 3. Generation of Fashion Images with the help of DCGAN

1. We have to set-up Google Colab Pro in order to generate the fashion images. 
2. Go to Google Colab, set up account.
3. You have to mount the drive and upload the Processed fashion images data of 'Trousers/Hose' (for this use case) in the Google Drive.
4. Then run the file '**Fashion Images Generation.ipynb**' In this file, plases specify the fashion Images folder path ('Trousers/Hose' path).

** Also, you can specify learning rate and number of epochs in order to get better output results.**

