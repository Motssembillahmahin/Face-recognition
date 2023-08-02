# Face-recognition
Basically, this program so called application built for storage name according with the image. Assumming numerous images are stored in database and you’re one of them then it will detect you through webcam and storage your time in csv file. If you’re not part, then it will not detect you. Let’s see short notes for the following application. 

Step –1: 

Firstly, import all required modules to fulfill the program. Such as face – recognition, cv2, csv, OS or datetime and so on. Then use computer vision module (which is normally work for enabling computers to identify and understand objects and people in images and videos) to take input in other word through webcam. Note that there are multiple systems to take input whatever you need you can apply it.  

Step – 2: 

Afterwards, we compare the encode image and getting image which got from webcam by using face_compare() method, besides we use face_location method that use rgb image file which getting from webcam. 

Nevertheless, we argmin method from np module that used to produce minimal value according of x axis and y axis 

Step – 3: 

Not the last, We use csv module to storage data which are actually storaged in encoded image. Besides, we use datetime module that work for representing precise time of detecting. 

Step –4: 

Besides , we use time duration and motion detection for providing better service as if any image can’t appear 30s the webcam the program automatically off and motion part that can help to protect from motion effect . 

Finally, shut down the program through computer vision module
