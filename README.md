
## Skin-Lesion-Analyzer

Live Web App: https://skin-disease-final-five.netlify.app/index.html
<br>

<img src="http://skin.test.woza.work/assets/app_pic.png" width="350"></img>

<br>

This is a prototype for a freely available online tool that can tell doctors and lab technologists the three highest probability diagnoses for a given skin lesion. It could help them quickly identify high risk patients and speed up their workflow. The app will produce a result in less than 3 seconds. To ensure privacy, user submitted images are pre-processed and analyzed locally and are never uploaded to an external server. 

This app is powered by Artifical Intelligence. My goal for this project was to build an end to end solution - starting with model creation and ending with a live web app. Users are able to submit a picture of a skin lesion and get an instant prediction. 

The app is able to classify 7 types of skin lesions as described in this paper:

The HAM10000 Dataset: A Large Collection of Multi-Source Dermatoscopic Images of Common Pigmented Skin Lesions<br>
https://arxiv.org/abs/1803.10417


The python code to build and train the model is included in the Jupyter notebook. All the javascript, css and html files are also freely available here. The trained model is also available.


