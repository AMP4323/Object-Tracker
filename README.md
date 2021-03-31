# Object-Tracker
Tracking using your andriod device camera. 
1) IP Camera application, you can download it from playstore/appstore.
2) Start the server in the application and note the IP address and PORT number written at the bottom.
3) In the code, while capturing video frames, i.e. cv2.videocapture('') with cv2.VideoCapture('rtsp://IP:PORT/h264_ulaw.sdp'), replace IP and PORT with mentioned IP and PORT on the IPcamera application.

What's the use of this?
Because if you don't have a webcam or if you are performing on Raspberry Pi then Rpi Cam, then you can use your cell's camera for testing the model or code while capturing live frames. 
