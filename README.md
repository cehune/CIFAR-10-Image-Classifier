# CIFAR-10-Image-Classifier
The CIFAR (Canadian Institute For Advanced Research) 10 database is a set of 60,000 32 x 32 pixel images. I trained a Convolution Neural Network model to 
achieve an accuracy rate of 70%. 

Within this project, I used PyTorch, Numpy, and a small amount of pandas, seaborn, and scikit learn. 

The dataset has 50,000 training images, and 10,000 testing images. Each image has one of ten classes describing what the iamge is (frogs, cats, etc.). 

Training the model over 10 iterations, I was able to achieve this prediction - to - actual heatmap. The x-axis represents the actual classes of each image. The
y-axis represents the distribution of the computers guesses for each class. Since each square shows the percentage of times the robot guessed a certain value when the 
actual class was a certain value, the rows each add up to 1.0. The squares along the main diagonal show the percentage of times that the robot guessed correctly. 

![image](https://user-images.githubusercontent.com/71574223/208555534-2c3db583-f975-49e0-8285-5a7e0ff14419.png)

You can see that the model struggled for images where the subject is similar to another. 

## Statistics
The model was most accurate predicting automobiles, getting an accuracy rate of 90%.
The model was least accurate guessing birds, having an accuracy of only 43%. 
The most common incorrect guess was guessing dogs as cats. 
