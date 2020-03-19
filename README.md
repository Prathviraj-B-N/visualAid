# visualAid
Detects face and helps visually impaired to recognize people in advance

## Create your dataset
> Create a folder in dataset directory for each face want to recognize and name it after them.
> Add some pictures
> train your model

## Train your model
```bash
python encode_faces.py --dataset dataset --encodings encodings.pickle --detection-method hog
```

## Run code
```bash
python pi_face_recognition.py --cascade haarcascade_frontalface_default.xml --encodings encodings.pickle
```
