# Waste-Predictor
The User uploads an image in the webapp and ultimately it can classify it in two categories 'compostable' and 'Recyclable' by finding the accuracy from the model that we have created.
We can use the result of the model and make the prediction for real time. So a general use of this model can be that the model being deployed in the camera and it is guarded near the dustbin so any user came to dump garbage can easily get to know in which of the dustbin he has to throw whether it should be recyclable or compostable.
## How I built it
Firstly made the model by using Auto ML vision Image Classifier supported by google cloud. Then I set the confidence threshold appropriately to give maximum accuracy. At last, wrapped our model in the desired UI and then deployed the result in our Web App using the API tensorflow.js.
