# Face Recognition Sign-In/Sign-Out Application

This application uses face recognition to manage sign-ins and sign-outs. It is implemented in Python and utilizes various AWS services, OpenCV (cv2), Tkinter for the GUI, Chalice for local development, Boto3 for AWS SDK, and Dlib for face recognition.

## Installation

1. Clone the repository.
2. Install the necessary packages mentioned in the `requirements.txt` file.

## Usage

1. Run the application locally using Chalice: `chalice local`.
2. The application GUI built with Tkinter will appear.
3. Use the "Sign In" and "Sign Out" buttons to manage user sessions.

## Features

- **Face Recognition**: The application uses Dlib's face recognition capabilities to identify users.
- **AWS Integration**: Utilizes several AWS services for various functionalities:
  - **Lambda Function**: Executes the core logic of the application, including face recognition and session management.
  - **S3**: Stores user images and other resources securely.
  - **DynamoDB**: Manages user data and maintains session records.
  - **AWS Rekognition**: Augments face recognition capabilities by providing additional image analysis features.
- **Local Development**: The application can be run locally using Chalice, facilitating development and testing.
- **GUI**: Features a user-friendly GUI built with Tkinter for easy usage.

## Contributing

Contributions are welcome. Please open an issue to discuss your ideas or initiate a Pull Request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

![Architecture](architecture.png)
