# Autonomous-RC-Car-
A scale down version of a self driving car system achieved by using OpenCV and Python. This helps the RC car to perform basic autonomous functions such as start and stop by the help of sensors and Raspberry Pi.
# Functionality
The RC car can stop by recognising the traffic sign and a stop sign using image recognition by the help of OpenCv. 
It does not move when there is a object infront of the remote controlled car.

# Prerequisite
  Hardware:<br/>
   1)Raspberry Pi<br/>
   2)Ultra Sonic Sensor<br/>
   3)Camera Module<br/>
   4)Remote Controlled Car (The cars remote should be insulated with wires on the buttons so that the pi could control the car.<br/>
  Software:<br/>
   1)Python<br/>
   2)OpenCv library<br/>
# Training
  To train your own dataset for OpenCv just rent a server and train it, Since it will take ages to train on your local machine. Datasets can be obtained through [ImageNet](http://image-net.org/index).<br/> Although I would recommend TensorFlow instead of OpenCV for training with good accuracy and detection.
  
# Screenshots
![trafficlight](https://user-images.githubusercontent.com/12658863/37247759-5f19c3a4-2475-11e8-92d4-6c9a4e2a640d.JPG) ![stopsign](https://user-images.githubusercontent.com/12658863/37247765-79ee5ce4-2475-11e8-96f2-88cfdc45348a.JPG) ![code](https://user-images.githubusercontent.com/12658863/37247771-934c2f72-2475-11e8-977c-d1b9dd06e912.JPG)
