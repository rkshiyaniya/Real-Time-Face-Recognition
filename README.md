# Face-Recognition
Face Recognition Using face_recognition and make real time using OpenCV

### Instruction :

1. First put all the images in 'img' folder with their name (for ex. rutvik.jpg)
2. Run main.py

### Workflow : 

1. First of all, it will load all images placed in 'img' folder
2. Find thier location & encondings and label name (classname) and put in respective array
3. Using opencv by your webcam it will detect your/unknown face, face location & enconding
4. Compare your real time encoding with the ones placed in 'img' folder
5. If it will find maximum matche with any image in 'img' folder, it will mark it labelname and show it
6. Else show 'Unknown'
