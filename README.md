<h1 align="center"> Chidori - Taser Glove </h1>

<p align="center">
  <img width="200" src="https://github.com/Shakthi-Dhar/Taser-Glove/blob/main/assets/Icon.png" alt="logo">
</p>

>__<h3>Why This Project?</h3>
Lot of fatalities occur simply because of delayed medical assistance because the individual affected wasn't in the physical state to notify hospitals or family about their medical emergency.__

<h3>What is Chidori?</h3>
A security glove that uses gestures to initiate tasing and automatically conveys an SOS message through our application. We use ESP8266 wifi module to form a connection with the cloud and a low voltage circuit as a tasing prototype and a MPU6050 accelerometer to act as a gesture sensor that initiates the tasing action and updates the data on the cloud through wifi module. When the data is being updated, we use cloud services to initiate an SOS message.

<p align="center">
  <img width="700" src="https://github.com/Shakthi-Dhar/Taser-Glove/blob/main/assets/flow%20chart.png" alt="Hardware">
</p>

<h3>Hardware Tech stack used</h3>
<h4>NodeMCU ESP8266</h4>
This device acts as the interface between the hardware and the backend. It constantly
reads the data from the MPU6050 sensor and once the condition for the gesture is
detected it sends an http Get request along with the message title and coordinates
obtained from a Geolocation API as a query parameter to our backend.

<h4>MPU6050</h4>
This module has an inbuilt gyroscope, accelerometer and temperature which we will be
calibrating to identify the gesture performed by the user.

<h3>This is how our prototype looks like</h3>
<p align="center">
  <img width="500" src="https://github.com/Shakthi-Dhar/Taser-Glove/blob/main/assets/circuit.png" alt="Hardware">
</p>

