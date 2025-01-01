Face Recognition System Using PyTorch and OpenCV: 

This project demonstrates a real-time face recognition system using PyTorch, OpenCV, and the FaceNet model. The program leverages the MTCNN (Multi-task Cascaded Convolutional Networks) for face detection and InceptionResnetV1 (FaceNet) for face encoding and recognition.

Features
- Face Detection: Uses MTCNN to locate faces in images or video streams.
- Face Encoding: Generates 128-dimensional embeddings for detected faces using a pretrained FaceNet model.
- Face Recognition: Matches faces against a database of known encodings with customizable threshold settings.
- Real-Time Processing: Integrates with a webcam to perform live face detection and recognition.
- Customizable Database: Add your own known faces by providing images and names.
- 
How It Works
- Face Detection: Detects faces in the input frame using MTCNN.
- Face Encoding: Encodes detected faces into feature vectors using InceptionResnetV1.
- Known Face Database: Predefined faces and names are encoded for matching.
- Recognition: Compares live face encodings with known encodings using Euclidean distance to determine identity.
- Real-Time Display: Displays bounding boxes and names of recognized faces in a video stream.
