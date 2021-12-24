# Driver-Drowsiness-Detection-And-Speech-Recognition </br>
When the driver's eyes remain closed for a certain time, an alarm is triggered. The driver must open his eyes and say a word generated randomly by the system to stop the alarm after ensuring the driver's awareness and vigilance.</br>
We have used :</br>
- dlib to detect some points of the eyes (landmarks) to compute a ratio (EAR: Eye Aspect Ratio) which allows to know if the eyes are closed </br>
- OpenCV to manipulate the videos </br>
- SpeechRecognition for voice recognition and transforming voice into text </br>
- the Concurrent.future module to ensure asynchronous execution of the alarm and voice recognition </br>

Demo Link: https://www.linkedin.com/posts/ghaylen-triki-926a7a199_computerabrvision-speechrecognition-senti-activity-6880146456011915264-mx2q </br>

