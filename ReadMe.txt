# Facial Recognition Based Attendance System

The Facial Recognition Based Attendance System is a project developed to replace the current manual student attendance management system with an automated and efficient attendance tracking system. This system utilizes machine learning-based facial recognition technology to handle and track student attendance using a web application and deep learning algorithms/models.

## Components

Some of the main components of the system include:
- **Face Recognition:** Recognizing student faces for attendance marking.
- **Deep Learning Models:** Utilizing state-of-the-art deep learning models for image processing, particularly VGG-16 with transfer learning for face recognition.
- **Face Detection:** Employing MTCNN for face detection, capable of learning multiple tasks simultaneously, supporting the simultaneous detection of multiple faces.
- **Real-time Recognition:** A real-time face recognition system capable of identifying or verifying a student from a video frame.
- **Training Data:** Utilizing a dataset of 240 images of three classes or students, employing a 20-80 training approach with 20% of the images for model validation and 80% for training.

## Users

The system caters to four types of users:
- **System Admin**
- **Head of Department**
- **Academic Staff**
- **Student**

### System Admin

- Can log in and log out from the system.
- Can update their profile.
- Manages users’ information.
- Manages departments’ and colleges’ information.
- Assigns roles to users.
- Uploads students' images.
- Trains the model.
- Initializes the attendance system.
- Views the attendance status.

### Head of Department

- Can log in and log out from the system.
- Can update their profile.
- Views attendance status.
- Manages courses’ information.
- Registers students for specific courses.
- Manages instructor assignments.
- Sets up attendance rules for specific courses.
- Sets up schedules for specific courses.

### Instructor

- Can log in and log out from the system.
- Can update their profile.
- Configures basic attendance settings.
- Initiates attendance tracking.
- Ceases attendance tracking.
- Views attendance status.
- Handles special case attendance.

### Student

- Can log in and log out from the system.
- Can update their profile.
- Can view the attendance status.
- Can ask to leave and view leave status



## Contributors

- Abebayehu Alaro(https://www.linkedin.com/in/abebayehu-alaro)



## License

This project is licensed under the [MIT License](link-to-license-file).
