<h1>This page is currently being updated</h1>


**USER GUIDE** 

**Rapid non-destructive method to phenotype stomatal traits** 

It  is  important  to have good  quality  images  to  allow  the  machine-learning  algorithm to recognise stomata. 

Click on the link  (shared Google Drive folder) [https://drive.google.com/drive/folders/1Bta3MITvtJlY0yTmUauX1ayT2Wy3IWm2?usp=shari ng ](https://drive.google.com/drive/folders/1Bta3MITvtJlY0yTmUauX1ayT2Wy3IWm2?usp=sharing)

Copy the folder of the species of interest in your Google Drive. 

Each species folder contains:  

- three folders: *Species*Images, *Species*AnalysedImages and *Species*SegmentedImages 
- five files: three Google Colab scripts (detection, bounding box extraction and measurement), a detection mode and a measurement model. 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.001.jpeg)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 001](https://user-images.githubusercontent.com/116483670/197507867-5ef08c50-a4e8-41e8-99d4-c22d0f4113da.jpeg)

Stomata analysis process follows three steps: 

- Stomata detection 
- Bounding box extraction 
- Stomata measurement 

<h1>Stomata detection</h1> 

Click on the start button of the first script 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.002.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 002](https://user-images.githubusercontent.com/116483670/197507879-907bfb64-3f6a-4d91-a431-7b96210f14d9.png)

Click on *Run anyway* 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.003.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 003](https://user-images.githubusercontent.com/116483670/197507886-49584c62-680d-4b63-be01-680562a464e4.png)

Click on the start button of the next script 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.004.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 004](https://user-images.githubusercontent.com/116483670/197507897-3dc3f358-42a3-42ae-9964-691be8a953bc.png)


Connect to Google Drive

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.005.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 005](https://user-images.githubusercontent.com/116483670/197507917-3fe0573f-c431-452f-8b8f-c88d7ef7a05b.png)

Sign in - Allow 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.006.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 006](https://user-images.githubusercontent.com/116483670/197507937-c2c0766c-b020-45fb-aa34-c1ed12895b4f.png)




Move images to be analysed to “*Species*Images” folder in your Google Drive. 

In the next script, check that the path for stomatal detection model for the species of interest and the path for your images are correct. 

- Path for stomatal detection model 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.007.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 007](https://user-images.githubusercontent.com/116483670/197507952-422d7404-f684-44a9-9a35-3b8595658779.png)

- Path for *Species*images 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.008.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 008](https://user-images.githubusercontent.com/116483670/197507962-75146be5-f0d0-4a09-a0d1-255048322dfc.png)

Click on the start button of the next script 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.009.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 009](https://user-images.githubusercontent.com/116483670/197507968-1062962f-c447-4923-9cd5-9f2165582334.png)

Click on the start button of the next script 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.010.png)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 010](https://user-images.githubusercontent.com/116483670/197507978-3e95276d-0ca4-41e2-b3b3-228b15f60476.png)

Download the folder below: 

![](Aspose.Words.437e4a0d-31d9-490f-b3dd-afd6af6a9983.011.jpeg)
![Aspose Words 437e4a0d-31d9-490f-b3dd-afd6af6a9983 011](https://user-images.githubusercontent.com/116483670/197507983-db1fdd0a-ad19-4128-9706-b04d70a745aa.jpeg)

This folder contains bounding box coordinates for each stomata in a txt file, and labelled images.  
