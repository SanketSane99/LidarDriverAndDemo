# GarminLidarLitev4LED Driver And Demo
Adapted preexisting Arduino library to interface with the LidarLite_v4LED sensor using Mbed.


![image](https://user-images.githubusercontent.com/85893093/145903958-eeffc936-7194-41f8-ade3-3e680ac312af.png)
Garmin LIDAR-Lite v4 LED


The Garmin LIDAR-Lite v4 LED is a lidar sensor that is primarily interfaced with using the I2C or ANT interfaced. It is also configurable for SPI with user applications.
This library and Demo use I2C.


The following image shows the pin layout of the Lidar. Note that most of the pins are circular, except the first, which is rectangular and is the 5V input power source.

![image](https://user-images.githubusercontent.com/85893093/145903079-3c0971f5-d54d-42a2-804c-5f9ab2103091.png)

The next image shows the connections that should be made with the sensor.
![image](https://user-images.githubusercontent.com/85893093/146111138-a7fa52d2-737d-4dfc-9e08-10cb54852b0d.png)





For this demo, the Bluefruit module is used. The following pin connections were used.
![image](https://user-images.githubusercontent.com/85893093/146111282-6f196e60-5779-4743-865a-af83b05e7789.png)


For more info on the bluefruit module, see the following link:
https://os.mbed.com/users/4180_1/notebook/adafruit-bluefruit-le-uart-friend---bluetooth-low-/.

![20211214_140043](https://user-images.githubusercontent.com/96154246/146110832-fac30f29-b3b2-4923-818b-799e658c0059.jpg)
![20211214_140051](https://user-images.githubusercontent.com/96154246/146110845-8cee6e5d-3926-4794-9781-892a70a266c0.jpg)
![20211214_140102](https://user-images.githubusercontent.com/96154246/146110857-9edaa65c-3c5e-4c54-9b3a-7b175a00f593.jpg)

Video demo: https://www.youtube.com/watch?v=OlzsVd41I5I
