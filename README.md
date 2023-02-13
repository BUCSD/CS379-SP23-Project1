# CS379-SP23-Project1
Face recognition based attendance system.


## Objective:
The objective of this lab is to develop a Python project that simulates a facial recognition-based attendance system. The students will implement two key features: enroll and record attendance.

## Requirements:

### Enroll Feature:
The enroll feature should capture the images of a new person using the device's camera.
Request the person's name and create a folder with the person's name inside the "Templates" folder.
All the images of that person should be stored in the newly created folder.
Retrain the face recognition model for every new enrollment.

### Record Attendance Feature:
The record attendance feature should run indefinitely unless someone stops it using a stop button.
The feature should capture an image using the device's camera and supply the image to the trained model to generate the person's name.
The person's name, date, and time should be recorded in the "attendance.csv" file.
If the "attendance.csv" file does not exist, the project should create it automatically.
The captured images should be saved in the matching folder in the "Templates" folder.
Model Update Feature:

Implement a model update feature that updates the model using all the images available in each of the folders in the "Templates" folder.

## Design

You solution must follow object-oriented design. 

### Evaluation Criteria:
Functionality: All required features should work as expected.

Accuracy: The model should generate the correct person's name.

Error rate: The error rate should be minimized.

Description/Report: A report of the process the students went through in developing the project should be provided.

### Team Work:

Students are allowed to work in a team of a maximum of three people.
Individual and team project evaluation criteria will be the same.

Note:
It is recommended to work in a team but working alone is also allowed.

### Use of ChatGPT or online sources
You are allowed to use any resource you can find to complete the project. Just make sure you complete the requirements with the features requested. 
