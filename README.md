# potato-disease-classification
A React Native mobile application which is used to classify the potato disease by using convolutional neural networks and TensorFlow. This application also consists of ReactJs  application which runs on the web, gives the classification results based on the image uploaded by the user.



# Description 
The application is mainly built using react native, which is a cross platform javascript framework for mobile applications. The deep learning Model is created and operated using tensorflow and keras APIs . Python is used for building the model, training it and saving the model. FastAPI is used to serve the model on the server. It is deployed on google cloud platform to serve users from all over world. 

The react native application will make a request to the google cloud platform by using the bucket name and the request will be taken and the result is returned as JSON to the native application. Here the results are displayed to the users about the given input image.



# Working 
This application is very much useful for the farmers who will get a better idea about the yield in the potato field. 

It is a user friendly user interface, where the users have to just capture the picture of the potato leaf. The Deep learning model which is trained prior to classification, will be able to classify the given input image and give the class to which the potato leaf belongs to and the confidence for the prediction. 

Usually, Potato leaf will have three states, 1. Healthy, 2. Early Blight, 3. Late Blight. The classifier will provide the class mentioned above for each input image. The classes Early and Late blight will give less yield to the farmers as it is affected by some disease.


# ScreenShots
![Screenshot_2023_0130_175729](https://user-images.githubusercontent.com/66869443/215478159-2d153955-73de-429c-b982-c4b76cbb55d1.jpg) ![Screenshot_2023_0130_175748](https://user-images.githubusercontent.com/66869443/215478170-793eb1ed-325c-48bf-aab5-8e0079d8dac6.jpg)
![Screenshot_2023_0130_175813](https://user-images.githubusercontent.com/66869443/215478173-7e31bfe6-1623-48ad-8c80-ae5cc5b54a35.jpg)
![Screenshot_2023_0130_175846](https://user-images.githubusercontent.com/66869443/215478176-560305aa-3285-4252-afb3-5a7c8848cd5c.jpg)
