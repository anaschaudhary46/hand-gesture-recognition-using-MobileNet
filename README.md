Overview:

   In this project, we aim to create a real-time communication tool for individuals with hearing and speech
impairments. The tool combines hand gesture recognition and voice conversion to enable deaf and mute individuals
to express themselves more effectively. The system captures hand gestures through a camera, processes them using
a MobileNet based model, and converts the recognized gestures into spoken words. 


Model Training:

The model is trained using transfer learning with MobileNet model for image classification. The model includes a dense layer with 1024 neurons and a softmax output layer. The MobileNet base layers are frozen, and the model is compiled using the Adam optimizer and categorical crossentropy loss. Data augmentation during training includes rotation, shift, shear, zoom, and horizontal flip. The model is trained for 30 epochs with a batch size of 32 on the training set. After training, the model is evaluated on the test set, yielding a test loss and accuracy. The model achieved accuracy of 97% percent.

Getting Started:

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
Make sure you have Python installed on your machine.

Installation:
1. Clone the repository using
git clone https://github.com/anaschaudhary46/hand-gesture-recognition-using-MobileNet

2. Open the terminal/cmd and navigate to the project folder.
cd hand-gesture-recognition-using-MobileNet

3. Install the requirments.txt using
pip install requirments.txt
Requirments.txt will install all the required dependancies.

4. Usage
Now run the main.py using
python main.py

Conclusion:

In conclusion, the development and implementation of the Hand Gesture Recognition and Voice
 Conversion system represent a significant technological advancement with the potential to
 positively impact the lives of individuals with hearing and speech impairments. The project
 successfully achieved its primary goal of recognizing hand gestures and converting them into
 audible speech, providing a means of communication for the deaf and dumb community.
 Throughout the development process, key milestones were accomplished, including the
 integration of a reliable hand detection algorithm, an accurate gesture classification model, and
 an efficient voice conversion system. The system's real-time processing capabilities, user-
 friendly interface, and integration of accessibility features contribute to its usability and
 accessibility for a diverse user base.
 
 The incorporation of both manual and automated testing methodologies ensured the system's
 robustness and reliability. Manual testing facilitated a comprehensive examination of user
 interactions, while automated testing enhanced efficiency by systematically validating various
 system functionalities. 
