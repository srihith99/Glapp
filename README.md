# Glapp
A Glucose Monitoring and Diabetes diagnosis app that provides realtime glucose metrics (of a person) in a completely non invasive manner (i.e without actually taking subject's blood). The app also conveys the risk of diabetes based on existing medical records and the past readings of the user.

Using the app : ( Refer to the video file as well )
1) Insert the finger of the subject into the sensor slot
2) Wait for 30 seconds
3) Get the glucose readings and diagnosis on the app
5) Should the glucose level be critically high or low , an alert message shall be sent to the emergency contact( preferably the family doctor ).

Principal:
We used 940 nm NIR leds and photo detectors to check the variation in glucose concentration.We trained our model using regression to map the glucose levels of live subjects from hospitals to the output voltage received from the photo diode.We took care of many parameters such as skin colour,thickness,angles of leds.Our area of testing is finger.
Our final accuracy is 86%.
Our algorithm is designed in such a way that it keeps evolving.Its keeps getting better as we collect more data points.So we are planning to collaborate with some hospitals around us and request doctor to test the subjects with our project too, hence we end up getting good accuracy.
