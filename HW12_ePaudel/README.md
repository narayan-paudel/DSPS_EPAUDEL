
# Reading: 

[The DeepDream release blogpost](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html)

[Understanding the Lomb-Scargle Periodogram](https://arxiv.org/abs/1703.09824) J. Vanderplas


# Assignment 1:

Finish the [Keras-Tensorflow lab](https://github.com/fedhere/DSPS/blob/master/HW12/KerasTensorflow.ipynb)

Note that I added a task (task 10):


task 1: print the shape of the train input and train labels

task 2: print the label of the 10th observation

task 3: what is the shape of train_input 1?

task 4: plot train_inpu 1

task 5: create a model with 3 layers: input layer and 2 fully connected layers with 128 and 10 neurons respectively

task 6: set a learning rate of 0.01, a loss function "sparse_categorical_crossentropy" and set the metric to "accuracy

task 7: test the model and declare the accuracy

task 8 plot the 10'th test observation and its label and prediction

task 9: find the first wrong prediction in the test set

task 10: create a more complex model by adding 3 fully connected layers (you choose the size). Test the accuracy of prediction and discuss if the model is overfitting




# Assignment 2:

Finish the [deepdream lab](https://github.com/fedhere/DSPS/blob/master/HW12/DSPS2019_deepdream.ipynb)

Follow the lab to load the modules and the model. 

Task 1: Create a random noise "image": an array of 300x300 pixels and 3 color channels (RGB). Fill it in with random noise but make sure the values are Unsigned integer 8bit type (np.unit8) and contained between 0 and 255. This is how a jpg image would be encoded in python and both pylab and this base code require this encoding for the image.  This can be achieved by generating random uniform noise (between 0 and 1) and convert it to 0-255 by multiplication, then convert the data type.

Task 2: start a deep dream on the random noise image: Adjust the sliders to change the strength of the deep dream, and how many scales it is applied over. until you obtain a "phsychadelic" result that you like

Task 3 pull each layer:  look at the bottom diagram that shows the architecture of the layer. Plot each relevant layer, the layers that start with "mixed"  

Task 4: Qalitatively describe, based on your reading, why the layers show different features and what it the "kind" of features extracted in the earler layers vs the later ones.

Task 5: Load your chosen image

Task 6: shrink it to 300 pixels along the x axis by subsampling

Task 7: Repeat step 4, DeepDream, with your image. Save the layer you like. Upload tha original and modified image to the readme file of your DSPS repo

Task 8: Answer: Are there "animals" in your image? why? (there should be)Task 4: Load your chosen image 


![img](https://github.com/fedhere/DSPS/blob/master/HW12/original.png)


![img](https://github.com/fedhere/DSPS/blob/master/HW12/dreamed.png)
