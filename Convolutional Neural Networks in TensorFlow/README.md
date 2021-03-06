# Convolutional Neural Networks in TensorFlow  

## Exercise 1: Cats vs. Dogs  
A CNN model was used to classify images as being either a cat or a dog.  Two folders containg images of either cats or dogs were divided into training and validation subfolders.   
- [Using more sophisticated images with Convolutional Neural Networks](https://github.com/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%202%20-%20Lesson%202%20-%20Notebook.ipynb)  
## Exercise 2: Cats vs. Dogs Using Augmentation  
Data augmentation was used in the ImageDataGenerator function to essentially create a larger training set in order to avoid overfitting the training set.  This improved validation losses.  
- [Cats vs. Dogs Augmentation](https://github.com/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%204%20-%20Lesson%202%20-%20Notebook%20(Cats%20v%20Dogs%20Augmentation).ipynb)  
- [Horses vs. Humans Augmentation](https://github.com/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%204%20-%20Lesson%204%20-%20Notebook.ipynb)  
## Exercise 3: Horses vs. Humans using Transfer Learning  
The Inception V3 model was used in a transfer learning application.  The pretrained model was left untrained and a trainable layers were added at the output of the second to last convolutional layer.  Dropout was also applied to the trainable layers to avoid overfitting and also made the validation accuracy higher thant the training accuracy.  
- [Cats vs. Dogs using Transfer Learning](https://github.com/lmoroney/dlaicourse/blob/master/Course%202%20-%20Part%206%20-%20Lesson%203%20-%20Notebook.ipynb)  
- [Transfer learning and fine-tuning](https://www.tensorflow.org/tutorials/images/transfer_learning)
## Exercise 4: Multi-Class Classifier Sign Language MNIST  
A CNN model was used to identify the 26 signs of the alphabet using sign language.  The dataset is a csv file provided by Kaggle.  Key features of this notebook are loading a csv file instead of having data sorted in folders.  The training and test datasets were loaded into image arrays and label arrays for four numpy arrays total to train and test the model.  
- [Sign Language MNIST](https://www.kaggle.com/datamunge/sign-language-mnist)  
- [Rock Paper Scissors Classifier](https://github.com/lmoroney/dlaicourse/blob/master/Course%201%20-%20Part%208%20-%20Lesson%202%20-%20Notebook.ipynb)
