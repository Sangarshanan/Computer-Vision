# Computer-Vision

Computer vision is a field that deals with how computers can be made for gaining high-level understanding from digital images or videos. From the perspective of engineering, it seeks to automate tasks that a human can do.

### 1) Face verification using siamese networks

In face recognition systems, we want to be able to recognize a person’s identity by just feeding one picture of that person’s face to the system. And, in case, it fails to recognize the picture, it means that this person’s image is not stored in the system’s database.

To solve this problem, we cannot use only a convolutional neural network for two reasons: 

1) CNN doesn’t work on a small training set. 

2) It is not convenient to retrain the model every time we add a picture of a new person to the system. However, we can use Siamese neural network for face recognition.

I am using the triplet loss function....Triplet because it used THREE vectors 

- Vector of the image we feed I

- Vector of positive image P

- Vector of Negative image N

It tries to reduce the distance between I-P while increasing the distance between I-N

### 2) Playing Dino run using python 

Dino run is an offline game available in chrome
The main libraries used are Pyautogui and Pillow 







