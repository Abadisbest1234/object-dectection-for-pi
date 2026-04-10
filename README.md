# object-dectection-for-pi
This software uses a ESP32-cam connected to a rasberry-pi to detect diffrent objects

# How to connect the esp32CAM to any rasberry-pi:

1. the pre-installed code on the esp32 is good enough.
2. connect the rasbeery pi to its wifi.
3. in the code replace the "cap = cv2.VideoCapture(0)" to "cap = cv2.VideoCapture(http://192.168.0.000:00/stream) # example address".
4. upload the python script to the pi and install the libaires over the main internet.


