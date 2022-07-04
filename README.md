# 🧘 Yoga-Pose-Classification
Yoga Pose Detection and classification using deep learning
In this project we use pretrained model by google to generate keypoints predictions of our custom dataset and then store those predictions and apply **KNN** algorithm to classify new Images.

Here i have used Google's MLKit app to create a custom pose classifier on my desired dataset. To create an app like this for yoga poses or exercises that you want then you have to collect images for that poses and follow this [Mediapipe Colab](https://colab.research.google.com/drive/19txHpN8exWhstO6WVkfmYYVC6uug_oVR) tutorial to create ypur own app.

## Usage
Just start a new project in android studio using start a new project using git option. This will clone this repo on your desktop and then just build and run the app on your phone.

After installing the app select `LivePreviewActivity`  -> `Pose Detection` and the go to settings option and turn on `Run Classification` option to see your yoga poses being classified.

Screenshot from App installed on my phone

<div class="row">
  <div class="column">
    <img src="wedding.jpg">
    <img src="rocks.jpg">
    <img src="falls2.jpg">
    <img src="paris.jpg">
    <img src="nature.jpg">
    <img src="mist.jpg">
    <img src="paris.jpg">
  </div>
  <div class="column">
  </div>
</div>
