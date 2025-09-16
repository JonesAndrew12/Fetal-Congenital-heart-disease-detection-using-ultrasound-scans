Fetal congenital heart disease prediction using ultrasound scans is the technical project name. So basically what is does is it captures the ultrasound heart image of the baby in the mothers fetus and predicts any 
abnormalities in the heart, for example VSD(ventricular septal defect) is a disease that causes a hole in the  heart which can cause further complications. There are chances that the human eyes can miss the 
error making it fatal for the baby and the mother, The sooner the diagnosis the best the doctors can save the baby.I got the heart images from a website called roboflow and manually annotated the data with the 
help of my mom who said where the fault was.I used Yolo V8 object detection algorithm to classify the images based on the disease. If there is a defect in the heart then a box will be displayed around the predicted 
defect and the doctors can check it out and prepare for neccessary actions.The model had an accuracy of 82% with a train test ratio of 80:20.
   
I used yolo v8 model because it is specifically designed for detecting objects and localizing the pattern in a given image.It is the best algorithm that is out there with the highest average accuracy above 60%.
It also used Convolutional neural network to map the features of an image and predict the necessary outputs.
