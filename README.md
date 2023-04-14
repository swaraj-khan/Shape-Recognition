# Shape-Recognition

This project allows the user to name three different shapes of their choosing and trains a machine learning model to identify those shapes based on an image drawn by the user.

The application uses SKLEARN and a CV2 to train a convolutional neural network (CNN) on a dataset of hand-drawn shapes. The trained model can then predict the user-drawn shape based on its features, such as the number of edges and angles.

The user interface is designed using the Tkinter library and provides an intuitive drawing canvas where the user can draw their shape using the mouse or touchpad. Once the drawing is complete, the user can submit the image to the model for prediction, and the application will display the name of the recognized shape.

This project is a great way to explore the world of deep learning and computer vision, and can be easily extended to recognize more shapes or even other types of images. So go ahead, give it a try and see if the model can recognize your shapes accurately!


Given below is the process flow :

Step 1: Enter the name of classifier

![1](https://user-images.githubusercontent.com/94361805/232049362-5aaf76e4-d070-4b10-a048-102e439501ef.PNG)

Step 2: Enter the names of 3 shapes 

![2](https://user-images.githubusercontent.com/94361805/232049555-f59c5ce8-c109-48a4-8603-bebf720aaf2d.PNG)

Step 4: Draw shapes with the brush. ( you can also increase or decrease the thickness of the brush + clear the canvas with the "clear" button if you are not happy ) and then press the button that has the name of the shape

![3](https://user-images.githubusercontent.com/94361805/232049899-77b884b4-11d9-46c5-b814-4e6a84919f4b.PNG)
![4](https://user-images.githubusercontent.com/94361805/232049903-3ab59198-e4c4-477d-ad78-c5fc8b6ba6fc.PNG)

Step 5: Once you are done with drawing shapes, press the "Train Model" button

![5](https://user-images.githubusercontent.com/94361805/232050145-4f36a367-7e34-4cf9-b091-713bc6b0c329.PNG)


Step 6: Now simply draw any shape and then press the "Predict" button to see which shape you have drawn

![6](https://user-images.githubusercontent.com/94361805/232050318-b5070ad8-f36e-4eb8-a606-75402214bdb9.PNG)


