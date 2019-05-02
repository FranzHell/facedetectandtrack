# Face Detection and Tracking 


## Install

`pip install -r requirements.txt`

## Run


Green = Detected face 

Blue = Box from previous detection, updated via tracking. 

````
python face_tracking.py`
````

Use `-i` argument to set different detection intervals, in seconds. Default=6.
for example:

````
python face_tracking.py -i 3
````

To try different Haar Cascades replace the *.xml file in the face_tracking.py


