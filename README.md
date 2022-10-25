<h1>This page is currently being updated</h1>


**USER GUIDE**

**Rapid non-destructive method to phenotype stomatal traits**

It is important to have good quality images to allow the machine-learning algorithm to recognise stomata.

Click on the link <https://drive.google.com/drive/folders/1Bta3MITvtJlY0yTmUauX1ayT2Wy3IWm2?usp=sharing>

If you cannot open the link using Chrome, open in another browser e.g. Microsoft Edge.

Copy the folder of the species of interest in your Google Drive.

Each species folder contains: 

- three folders: *Species*Images, *Species*AnalysedImages and *Species*SegmentedImages
- five files: three Google Colab scripts (detection, bounding box extraction and measurement), a detection mode and a measurement model.

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.001.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 001](https://user-images.githubusercontent.com/116483670/197895468-7c302653-4275-4890-ac51-274af9f22b88.png)

Stomata analysis process follows three steps:

- Stomata detection
- Bounding box extraction
- Stomata measurement

<h1>Stomata detection</h1>

Click on the start button of the first script 

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.002.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 002](https://user-images.githubusercontent.com/116483670/197895472-e853fd70-f217-4909-8681-65d18f702a0e.png)

Click on *Run anyway*

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.003.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 003](https://user-images.githubusercontent.com/116483670/197895772-96f0fb59-ec80-4436-8917-fa196f18af4f.png)

Click on the start button of the next script

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.005.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 005](https://user-images.githubusercontent.com/116483670/197895863-acd6bd38-83bc-495b-81ec-dad86b03f56f.png)

Click on the start button of the next script

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.006.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 006](https://user-images.githubusercontent.com/116483670/197895902-96e41ac6-c49f-41fa-8aa5-84cdef958b09.png)

Connect to Google Drive

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.007.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 007](https://user-images.githubusercontent.com/116483670/197895917-1d95fa0f-14d0-40af-b833-9a76da96ec21.png)

Sign in - Allow


Move images to be analysed to “*Species*Images” folder in your Google Drive.

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.008.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 008](https://user-images.githubusercontent.com/116483670/197895924-74a6341d-22ba-49fc-a5d3-d81c92143156.png)

In the next script, check that the path for stomatal detection model for the species of interest and the path for your images are correct.

Path for stomatal detection model

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.009.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 009](https://user-images.githubusercontent.com/116483670/197895931-d78ccba2-1e77-41b2-a3b3-2c3cc0e16ff6.png)

Path for *Species*images

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.010.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 010](https://user-images.githubusercontent.com/116483670/197895937-4dbee5ba-58f7-409b-91a8-204f3a3e3e89.png)

Click on the start button of the script

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.011.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 011](https://user-images.githubusercontent.com/116483670/197895946-d8fabb78-36b6-4e47-a012-1f44f715dece.png)

Click on the start button of the next script

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.012.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 012](https://user-images.githubusercontent.com/116483670/197895959-feed6237-416d-4099-9931-6a593bb08a92.png)

Download the folder below:

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.013.png) 
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 013](https://user-images.githubusercontent.com/116483670/197895966-ad7a1e37-996f-4bed-a847-77cadd1f8261.png)

This folder contains bounding box coordinates for each stomata in a txt file, and labelled images. 



Move txt files and labelled images to “*Species*AnalysedImages” folder in your Google Drive.

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.014.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 014](https://user-images.githubusercontent.com/116483670/197895976-33f9ec44-0bea-46fb-8bd4-387003d3b712.png)

