<h1>Rapid non-destructive method to phenotype stomata</h1>


**USER GUIDE**

It is important to have good quality images to allow the machine-learning algorithm to recognise stomata.

Click on the link (Google Drive shared folder)

<https://drive.google.com/drive/folders/1Bta3MITvtJlY0yTmUauX1ayT2Wy3IWm2?usp=sharing>

Copy the folder of the species of interest in your Google Drive.

Each species folder contains: 

- three folders: *Species*Images, *Species*AnalysedImages and *Species*SegmentedImages
- five files: three Google Colab scripts (detection, bounding box extraction and measurement), a detection model and a measurement model.

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.001.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 001](https://user-images.githubusercontent.com/116483670/200269749-34db9b98-ef24-443b-a82d-b3ee7a135049.png)

Stomata analysis process follows three steps:

- Stomata detection
- Bounding box extraction
- Stomata measurement

<h1>Stomata detection</h1>

Open *Species* Detection file

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.000.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 000](https://user-images.githubusercontent.com/116483670/200269793-2bf6bec9-72ba-4582-ba77-db2b1f6304df.png)

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

- Path for stomatal detection model

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.009.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 009](https://user-images.githubusercontent.com/116483670/197895931-d78ccba2-1e77-41b2-a3b3-2c3cc0e16ff6.png)

- Path for *Species*images

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

Move txt files and original images to “*Species*AnalysedImages” folder in your Google Drive.

![](Aspose.Words.8a2c643e-8098-4838-ba52-e7a69dcb9864.014.png)
![Aspose Words 8a2c643e-8098-4838-ba52-e7a69dcb9864 014](https://user-images.githubusercontent.com/116483670/197895976-33f9ec44-0bea-46fb-8bd4-387003d3b712.png)

<h1>Bounding box extraction</h1>

Open Bounding box extraction file

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.000.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 000](https://user-images.githubusercontent.com/116483670/200271250-59268aa3-3073-4f50-a384-9ffbcf047334.png)

Click on the start button of the first script

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.001.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 001](https://user-images.githubusercontent.com/116483670/197896379-e430cc4d-62e6-46ff-be8e-a87a470ac7b1.png)

Click on the start button of the next script

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.002.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 002](https://user-images.githubusercontent.com/116483670/197896385-61a574c4-2fd2-450b-9669-fa969b54ac45.png)

Click on the start button of the next script

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.003.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 003](https://user-images.githubusercontent.com/116483670/197896387-a2d442b7-8c32-45ad-917b-494c72e00571.png)

Click on the start button of the next script

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.004.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 004](https://user-images.githubusercontent.com/116483670/197896395-d9afc875-0003-4ef0-a0cb-4c548d918221.png)

Click on the start button of the next script

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.005.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 005](https://user-images.githubusercontent.com/116483670/197896399-278a02d9-dbb0-4633-b887-197dfc296c1f.png)

Connect to Google Drive 

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.006.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 006](https://user-images.githubusercontent.com/116483670/197896408-7f040cff-609c-43d9-aec1-d01685a08640.png)

Sign in - Allow

In the next script, check that the path for the folder that contains txt files and labelled images is correct.

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.007.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 007](https://user-images.githubusercontent.com/116483670/197896432-dbe0658f-1609-4748-a17f-9b60c1aea180.png)

Click on the start button of the script

Click on the start button of the next script

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.008.png) 
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 008](https://user-images.githubusercontent.com/116483670/197896444-49062b7d-27b6-4ff2-b988-36f787757651.png)

Download the folder below:

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.009.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 009](https://user-images.githubusercontent.com/116483670/197896452-9160e484-5e64-46bc-ad8c-f4b2e288eed8.png)

This folder contains images of individual stomata.

Check the quality of images before proceeding to the next step. Delete images where stomata are not clear to exclude it from analysis.

Move individual stomata images to “*Species*SegmentedImages” folder in your Google Drive.

![](Aspose.Words.4a686a76-6697-4bd5-a1a5-d36983812772.010.png)
![Aspose Words 4a686a76-6697-4bd5-a1a5-d36983812772 010](https://user-images.githubusercontent.com/116483670/197896456-6a01a15a-413a-4178-bed2-fd116e93414e.png)

<h1>Stomata measurement</h1>

Open *Species* Measurement file

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.000.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 000](https://user-images.githubusercontent.com/116483670/200271786-0f94c29d-e242-4967-910e-fa89d128c117.png)

Click on the start button of the first script

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.001.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 001](https://user-images.githubusercontent.com/116483670/197896885-353fbed9-4938-4e5b-95ec-483e6d9d221c.png)

Click on the start button of the next script

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.002.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 002](https://user-images.githubusercontent.com/116483670/197896889-566ac0f5-bee1-4327-a8c6-da0599453f61.png)

In the next script, check that the paths for the folder that contains individual stomata images and measurement model are correct.

- Path for *Species*Segmentedimages

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.003.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 003](https://user-images.githubusercontent.com/116483670/197896895-61d32853-7c9c-40b5-a2c1-5e188d82b47e.png)

- Path for stomatal detection model

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.004.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 004](https://user-images.githubusercontent.com/116483670/197896902-d234cf20-ad5d-4fed-b1f5-c0bbc20a1c1d.png)

Click on the start button of the script

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.005.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 005](https://user-images.githubusercontent.com/116483670/197896907-a949e6e9-407d-4d7f-8baf-5b3243dafcac.png)

In the next script, check that the paths for the folder that contains individual stomata images is correct.

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.006.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 006](https://user-images.githubusercontent.com/116483670/197896916-57d969c8-1f3b-48b8-9f29-c6e975a0b0e6.png)

Click on the start button of the script

Click on the start button of the next script

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.007.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 007](https://user-images.githubusercontent.com/116483670/197896921-38470953-ca2e-443a-b42d-a050c6c6bace.png)

Download the folder below:

![](Aspose.Words.c92e0bb2-a880-43fe-9a54-8074a5ddde47.008.png)
![Aspose Words c92e0bb2-a880-43fe-9a54-8074a5ddde47 008](https://user-images.githubusercontent.com/116483670/197896938-a24f3e7f-1ee5-42c8-9a7e-b86e3ecbd4cf.png)

This folder contains data on stomatal size and aperture if applicable.
