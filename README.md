# WasteWise

<!--- 
add the WasteWise logo and align it to the center, adjust size using "width"
--->
<p align = "center">
<img src = "UX/logo-color.png" width = "250">
</p>

## Brainstorm 

Hey @all! 

In this "Brainstorm" section, I just added some info collection about the requirements of the README as well as some suggestions. We need to delete this "Brainstorm" section before final hand in.

Obviously, feel free to change and beautify stuff! This is just a suggestion and just a first version.

### How to fill individual sections:

- Summary: Short project description of not more than 130 words to add to the certificate.
- How to run the demo: Explain what needs to be done for anyone to try the demo. Navigate to the corresponding WD directory, npm install, then npm run dev and so on, but explained in a better way.
- Contributors: Everyone who participated needs to add their name here. If you like, also provide a link to your GitHub profile.

## Summary 

WasteWise is an app that helps its users to conveniently dispose of their waste. Based on a photo of the respective object, it recommends the correct way of disposal to help our environment clean and green. This feature relies on a fine-tuned residual neural network image classifier coupled with a function providing the recommendations for each class.

## How to run the demo

### Minimal Waste Image Classifier App in Huggingface Spaces

To quickly get an impression of the waste recognition and disposal recommendation feature, follow this link and enable your webcam: https://huggingface.co/spaces/fabianjkrueger/WasteWise

<p align = "center">
<img src = "images_blog/gradio_hgfs_demo.GIF">

__Steps:__

1. Take a photo of your waste. Make sure to present only one object at a time and that your background is neutral.
2. Start inference by pressing "Submit". After a few seconds, you can see the results.
3. If you want to see an interpretation, click "Interpret" and wait a few seconds. This will show you which parts of the image were most important for the model to classify the image.
4. To repeat, hit "Clear" and take a new photo.

__Disclaimer:__ At the time this is written, the model can classify 20 classes with an accuracy of about 90%. Due to data mismatch (trained on downloaded stock photos, queried on your realistic user images), it will still make lots of mistakes and is likely to misclassify many images. In the future, provided we are able to get more and better data, this might be improved.

### Fully Assembled App


## Contributors

<!--- all tracks and names of members are sorted alphabetically --->

### Artificial Intelligence: 
[Andrea Torcianti](https://github.com/trc729)\
[Fabian Janosch Krüger](https://github.com/fabianjkrueger)

### Data Science
[Juliana Quiroga](https://github.com/julianabquiroga)\
[Marina Zaitseva](https://github.com/zaitsevam)

### User Experience Design
 [Oluwayinka ojo](https://github.com/ojoflorence) 

### Web Development
[Andreas](https://github.com/crftwrks)
