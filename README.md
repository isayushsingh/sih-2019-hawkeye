# sih-2019-hawkeye

### Problem Statement​ 
Many residential society administrations in India face an impending problem of illegal vehicle parking inside their societies and theft of the vehicles. There are solutions that exist in the market for monitoring through cameras and software system but are expensive and the affordability comes into the question.

### Solution
​Hawk Eye is an affordable mobile application and camera system that uses image processing to identify and monitor vehicles entering and leaving a residential society passing through the entry/exit gate thereby ensuring the safety and well being of the users’ vehicles. Easy to use, this application keeps track of vehicular traffic through the surveyed area.

Whenever a vehicle enters/exits the premises, an LPR (​​License Plate Recognition​)​ CCTVcameraatthegatecapturesthevideoofthevehicle which is converted into frames followed by conversion to images. Then using standard image processing techniques, the license plate is extracted from the image followed by character segmentation and the license number is identified along with the color and model of the vehicle.

On authentication from the record stored in our database, the respective user is notified who needs to confirm whether the activity is authentic or not. If approved, the vehicle is allowed to enter/exit the premises. In case of any discrepancy, the user can raise an alarm which would notify the Guard who can take necessary steps.
