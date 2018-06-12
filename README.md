# face_recognition_msgs
ROS message package containing the following:
## face_recognition.msg
Message that sends an array of faces recognised
- uint16[] ids_detected
- string[] names_detected
## scan_for_faces.action
This action scans by moving the head/camera for faces that are recognised
---
face_recognition detected
---
float32 progress
face_recognition detected
