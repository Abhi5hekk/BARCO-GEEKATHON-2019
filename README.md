# BARCO-GEEKATHON-2019

## Idea Description:

As we see nowadays tech is all around us. And it's utility can be seen in the field of security and privacy too. As we see surveillance cameras nowadays are installed everywhere to monitor anomalous activities. But it is very tedious to look at all the cameras or to catch every single detail. Here comes our approach to rescues.
Our approach can resolve all these problems by using Computer Vision and IoT. Our model will identify if there is any violence related activity in the
video obtained from the cameras and will send this data to the server where the respective centers will be alerted about the issue and also an automatic call will be generated for the nearest hospitals and police station of the area. 


## Technical Description of The Solution:

As mentioned earlier this project is mainly based on Computer Vision.
The video feed will be made to pass through CNN+LSTM architecture where it will generate labels for the different degree of violence. This label generation will be done on cloud and the obtained labels will be sent to the respective centers wherein the backend the values of the level of violence in the images will be updated. 
Depending on the degree of violence different actions will be performed if violence level if between 0.4-0.6, only a notification at the center will be created. If the degree of violence will exceed 0.6 then automatically a call will be generated at the nearest hospital and at the police station of the area.
