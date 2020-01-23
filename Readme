README

1. Install all the packages present in requirements.txt using the command
	pip install -r requirements.txt
	
2. Collect the data, crop the images for only faces and store the data in the given structure

	├── dataset
	│   ├── Person1
	│   │   ├── 1.jpg
	│   │   ├── 2.jpg
	│   │   ├── 3.jpg
	│   │   ├── ...
	│   └──Person2
	│       ├── 1.jpg
	│       ├── 2.jpg
	│       ├── 3.jpg
	│       ├── ...
	├── encode_faces.py
	├── encodings.pickle
	├── haarcascade_frontalface_default.xml
	└── pi_face_recognition.py
 
3. Run this command to generate the encodings for all the images. A pickle file will be generated.
	$ python encode_faces.py --dataset dataset --encodings encodings.pickle --detection-method hog	 
 	
4. Run the excecutable.py


source: https://www.pyimagesearch.com/2018/06/25/raspberry-pi-face-recognition/