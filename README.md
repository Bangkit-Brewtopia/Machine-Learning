# Machine Learning
This is the development repository of machine learning  in the **Brewtopia** app. 
## Coffee Beans Quality Classification ✔
### Tech: Python, Tensorflow, Keras, Matplotlib
This is a machine learning model that builds for the quality check of the coffee beans. With this model, you can detect the coffee beans that have defects, so they can be quickly sorted out to create a good quality of coffee.

The model was trained by **5650 image data** with a split of **80% training data** and **20% test data**. The model was built with Sequential API that contains 4 convolutional layers, 4 max-pool layers, and 4 Dense layers to train the model. Our model has pretty good accuracy on train data and test data, with the result of the training data is **95%** on training data and **91%** on the test data. 

- Classes: **Normal**, **Defect**
- Location: https://github.com/Bangkit-Brewtopia/Machine-Learning/tree/coffee-quality


## Chatbot ✔
### Tech: Python, Tensorflow, NLTK, Numpy, Json
We build a chatbot called **BrewChat** that can be used by users for getting more information about coffee. We build it using TensorFlow and Natural Language Processing (NLP) to make the computer understand the messages from the user and the responses of it.

The model was trained by 80 data objects of patterns and responses that classify into nine classes. When the user sends the messages, the model will encode them and then classify them based on the classes that are already defined. After it, the model will give the responses of it based on the data from the response object.

- Classes: **greeting**,**goodbye**,**thanks**,**introduction**,**types**,**brewing**,**flavors**,**caffeine**,**brands**
- File location: https://github.com/Bangkit-Brewtopia/Machine-Learning/tree/chatbot






