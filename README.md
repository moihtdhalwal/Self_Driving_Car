# Self_Driving_Car

 Steering wheel angle prediction model

# Task/Objective
 Our aim is to predict the steering angle of a car from its dashboard camera video feed.
 The proposed model , predicts the angle frame by frame.
 
# Dataset Used
 The dataset used consists of consecutive frames of the dashcam feed.
 The dataset can be found in this link : [Dataset](https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view)
 
# Model Structure
 1. The model was a Convolutional Neural Network(CNN). 
 2. MaxPooling2D and BatchNormalisation layers were stacked after the every single CNN layer to improve the stability and precision of the model.
 3. After CNN layers some dense layers were added.
 4. RELU activation function was used for all the layers except the last layer where 'tanh' was used as it suited this task more than other functions.
 5. The predictions were in radians which were then converted into degrees and OpenCV was used to visualise the end result.
 
# Training and Testing
 Training of the model was done on Google Colab(with GPU support) for smaller training time.
 Testing of the model was done on a local machine after importing the weights of model.
 
# Result

