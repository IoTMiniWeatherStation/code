# Smart Agricultural Weather Stations
Smart agriculture allows farmers to maximize yields using minimal resources such as water, fertilizer, and seeds by deploying sensors which helps farmers to understand their crops at a micro scale. Weather Stations can be placed at various locations throughout growing fields. These stations have a combination of sensors appropriate for the local crops and climate. Information such as air temperature, relative humidity and atmospheric pressure are measured and recorded at different intervals. Portability, decreased prices and the increased efficiency make weather stations attractive for farms of all scales. The potential users of this system is to small farms at home and it can globally increase our capacity to feed the world. 
We used NodeMcu board ESP8266 programmed with Arduino IDE. We streamed the data obtained from sensors to a Thingspeak channel. For getting the temperature and humidity we used the DHT11 and for pressure we used BMP180 and LDR for light intensity. We have used a Arduino based C language and the server used is Thingspeak as stated above.
#### AM.EN.U4CSE16014   Arya Nimmy Raju :
*	Responsible for interfacing the sensor DHT11 with ESP8266 using Arduino IDE.
* After going through sample codes, understood how to interface a sensor to an microcontroller device(ESP8266).
#### AM.EN.U4CSE16037  Lakshmi Anand :
*	Responsible for interfacing the sensor BMP180 with ESP8266 using Arduino IDE.
*	Responsible for assembling the bmp180 sensor.
*Learnt about the different libraries that BMP180 uses and understood how to interface a sensor with the ESP8266.
#### AM.EN.U4CSE160148  Pillai Ritika Mohan:
* Initially was responsible to create a client server model(sensor network) using three ESP8266. But it was a complicated procedure for us to do within the time constrain due to our minimal knowledge in networking. 
*	Responsible for connecting an LDR with the ESP8266 in order to find the light intensity. 
*	Learnt how to interface an analog device to a microcontroller device using libraires
* Learnt about client server model(sensor network) and how to connect two microcontrollers.
#### AM.EN.U4CSE16008   Amruda Kandoth :
*	Responsible for sending data collected from the three sensors to a channel created in Thingspeak.
*	Connected an led which lights up when data is sent to the server.
*	Learnt what is Thingspeak and it’s various applications.
*	Learnt how to send data from the processor to the channel in Thingspeak.
## Challenges faced:
As stated above initially our goal was to use three ESP8266 with each other and create a client server model. We learned about client server model and tried to implement it in our program but we were finding difficulties to transmit data from two clients to the third one, which was acting as both server and client.



