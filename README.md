# face_recognition_msgs

ROS Face recognition messages and actions.

## face_recognition.msg

This message passes two arrays of faces recognised. One array conatins the subjects id's and the other the subjects names.

* `uint16[] ids_detected`:  
  The id's of the subjects identified
  
* `string[] names_detected`:  
  The names of the subjects identified
  
## scan_for_faces.action

This action will scan for known faces by moving the head/camera.

Goal
* none

Result  
* `face_recognition detected`:  
  The arrays of ID's and names recognised during the complete scan
  
Feedback  
* `float32 progress`:  
  The percentage of the action complete
* `face_recognition detected`:  
  The arrays of ID's and names recognised during the last individual scan
