Smart Proctoring System 🎓🔍

This repository houses the Smart Proctoring System, a lightweight yet powerful solution designed to enhance the integrity of online tests by detecting suspicious behavior through video and audio inputs. Leveraging OpenCV, MediaPipe, and advanced machine learning algorithms, this system ensures accurate and continuous monitoring, making it an ideal tool for modern digital education environments.

🛠 Features

Video-Based Behavior Detection: 
Utilizes OpenCV and MediaPipe to monitor and analyze head movements, identifying potential cheating behaviors.

Audio Surveillance: 
Incorporates sound device libraries to detect unauthorized speech or noise, providing an additional layer of monitoring.

Head Pose Recognition: 
Employs ML algorithms to accurately track and analyze head poses, ensuring that the examinee remains focused on the test.

Continuous Monitoring: 
The system operates seamlessly throughout the test, offering real-time detection and alerts for any suspicious activity.

Lightweight & Efficient: 
Designed to be lightweight, ensuring it runs smoothly even on low-resource systems.

🚀 Technologies Used

OpenCV: 
For video capture and image processing to detect and analyze head movements.

MediaPipe: 
To enhance the accuracy of face and head pose detection.

Sounddevice:
For capturing and analyzing audio inputs to monitor speech and ambient sounds.

Python: 

Core language used for developing and integrating the system components.

Machine Learning Algorithms: 

Deployed for head pose estimation and speech recognition to ensure robust and accurate monitoring.
📊 Performance

Accuracy: 

High accuracy in detecting head movements and speech.

Efficiency:

Optimized to run in real-time with minimal resource usage.

Scalability: 

Can be adapted and scaled to handle a variety of online proctoring scenarios.

🧠 How It Works

The Smart Proctoring System operates by continuously monitoring the video and audio feed of the test-taker.
OpenCV captures the video input, where MediaPipe processes the frames to detect and track the examinee's head movements.
Simultaneously, the audio input is analyzed using the sounddevice library to detect any unauthorized speech or ambient noise. 
Machine learning algorithms enhance the system's accuracy by providing reliable head pose estimation and speech recognition.
