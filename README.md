# face_recognition_msgs

ROS Face recognition action.
 
## scan_for_faces.action

This action will scan the last camera image for known faces

Goal
* none

Result  
* `uint16[] ids_detected`:  
  The id's of the subjects identified
  
* `string[] names_detected`:  
  The names of the subjects identified
  
Feedback  
* `none`
