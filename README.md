# CNN--SDC-Simulator

Building and training a convolutional neural network(Nvidia model) for end-to-end driving of a car in a simulator(Udacity) using TensorFlow and Keras

####attempt_x.ipynb
  - shows my attempts to train the cnn model. After verifying the end-to-end driving in the simulator, using Image augmentation and Image data generation improved the model performance to generalise to new testing track. 

####final.ipynb 
  - is the final model.

####IMG 
- folder contains all the dataset images collected

####driving_log.csv 
- is the log containing steering angles, throttle, speed values for the images in IMG folder

####drive.py 
- is the python code which connects our model trained and the simulator(- install the required libraries imported in the code, - run the codefile in terminal, - and open the simulator in autonomous mode to connect)
