# Auto-face-pixelating
Giving a very simple face pixelating model. Basically it is a face detector with a pixelating function.

This demo used a Haar Feature-based Cascade Classifier provide by OpenCV `Python: cv2.CascadeClassifier.detectMultiScale(image, ...) → objects`. This classifier is far from good compared to todays deep learning based classifier. I have a SOTA performance face detector but there's some copyright problems and I couldn't use it here. I'll replace this detector with a deep learning model later.

Actually the pixelating is very time & labor consuming work. It is very odd that we have not see any automatic programs working on this. Usually they just put a big mosaic square in a specific position in order to reduce the time-consuming. However, in some conditions(eg. R18) the accurateness is pretty import, the big mosaic square will impair the user experience. And the fixed position can not deal with the huge range movement. So the detection based auto pixelating is a faster, cheaper and safer solution.
