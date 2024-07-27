# Face-Detection
Face Detection, Face + Blurring, Face + Eye Detection, and Saving. Using haarcascade xml files.


## About the files

- **Face Detection** - face_detection.ipynb
- **Face + Blurring** - blur_face.ipynb
- **Face + Eye Detection** - face_and_eye.ipynb
- **Saving the Faces** - save_faces.ipynb


## Other xml files

There are also other Haarcascade Frontalface files such as,

- haarcascade_frontalface_alt.xml
- haarcascade_frontalface_alt2.xml

I have used default one here, you can try different files and select which suites best. Difference is that they use different data structures.

According to my research / experiments default file gave better results. However, depening on the use case and camera do try different xml and see which results suite you the most.


## Link to other Haarcascade files

https://github.com/opencv/opencv/tree/master/data/haarcascades


You can explore and see there are also other files which can detect `Full Body`, `Lower Body`, `Upper Body`, `Smile`, etc.
