# Face-recognition
Teaching machine to recognise face.



Using library face_recognition, we can teach machine to identify the persons. We can use it to make security camera for own house.
download the face_recognition library.


OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. 




Why using ML / DL for face recognition?
* Deep learning led to huge advances(human level performance)
* Large amount of data can be processed by it.
* Compution powers( GPUs, TPUs)


FACE RECOGNITION:
* The ability of machine to recognise a person’s face in an image.
* Teach computers how to detect and recognise a face.

FACE DETECTION VS FACE RECOGNITION:

In face detection we find out no. of faces and where the faces are located in an image.
In face recognition we find out WHO that person is in the image.

APPLICATIONS OF FACE RECOGNITION:
* Digital photography: face detection
* Dynamic range enhancement
* Digital photography surveiilance
* Emotion and expressions identification


TOOLS FOR FACE RECOGNITION:
* COMMERCIAL(requires sharing the data with cloud)

            -     Amazon Rekognition API
                        - available for face detection, emotion detection and motion tracking

            -     Microsoft Azure face API
                        - available for face detection, gender age and face similarity

* Open source(can be used offline)
            - OpenFace
            -Dlib:  Face_recognition



SLIDING WINDOW CLASSIFIER:
In big picture, a window slides through the image and detect the face location in the image.


COMMON FACE DETECTOR ALGORITHMS
* Viola jones
            Traditional machine learning based approach
            Uses decision trees
            Very fast
            Large true positives
            For low resource devices

* Feature based
            HOG based features    
            Gradient from light to dark regions
            Slower but accurate
            Other feature based:
            Haar cascade

* Neural networks
            Convolutional neural networks
            Highly accurate
            Needs very large amount of data for training
            For computers with dedicated GPUs
            
            
