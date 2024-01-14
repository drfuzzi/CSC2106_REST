## **REpresentational State Transfer (REST)**

**Objective:** By the end of this session, participants will be able to set up their M5StickC Plus and develop a solution using REST API.

**Prerequisites:** 
- Computer / Laptop with Arduino IDE installed
- M5StickC Plus

## **Introduction**

REST (Representational State Transfer) is a software architectural style that defines a set of constraints and properties for building web-based systems. It is often used when building APIs (Application Programming Interfaces) that allow different systems to communicate with each other over the internet. It is essential in IoT (Internet of Things) because it provides a simple, standard way for devices to communicate with each other and with back-end servers over the internet.

One of the main benefits of using REST in IoT is that it allows devices to be connected and controlled remotely, which is essential for building distributed systems. REST also provides a uniform interface that can be used by various devices, regardless of their underlying hardware and software platforms. This makes it easy to build IoT systems that are flexible, scalable, and easy to maintain. Another important benefit of REST is that it is based on the HTTP protocol, which is widely supported and well-understood. This means that REST-based APIs (Application Programming Interfaces) can be easily accessed and used by many devices and software systems. This makes it easy to build IoT systems that are interoperable and can work with a variety of different devices and services.

Overall, REST is an essential technology in IoT because it provides a simple, standard way for devices to communicate with each other and with back-end servers. It is flexible, scalable, and easy to use, making it well-suited for building distributed systems and enabling interoperability in the IoT.

## **Applications of REST**

REST is used in various applications, including web services, mobile applications, and the Internet of Things (IoT). It is also a common choice for building APIs for cloud-based services, such as storage, computing, and data management. For IoT devices, REST is a good choice for building APIs that allow IoT devices to communicate with each other and with back-end servers. Typical IoT solutions incorporating REST include  smart home devices, wearable devices, industrial control systems and agricultural and environmental monitoring systems.

REST is particularly well-suited for use in the Internet of Things (IoT) because it provides a simple, standard way for devices to communicate with each other and with back-end servers. Generally, REST is an essential technology in IoT because it provides a simple, standard way for devices to communicate with each other and with back-end servers. It is flexible, scalable, and easy to use, making it well-suited for building distributed systems and enabling interoperability in the IoT. While REST is a widely used and well-understood technology that is well-suited for many different projects, there are some weaknesses to them. It underperforms where real-time communication or large data sets, such as online games or chat applications,  must be exchanged.  You should carefully consider your specific requirements and constraints when choosing a technology for building an API or a distributed system.

Overall, REST is a popular choice for building APIs in the IoT because it provides a simple, standard way for devices to communicate with each other and with back-end servers. It is flexible, scalable, and easy to use, making it well-suited for building distributed systems and enabling interoperability in the IoT.


![image](https://github.com/drfuzzi/CSC2106_REST/assets/108112390/b6617c95-3f77-47ec-a043-cad4ca0dcb7b)

Figure 1: Overview of REST API

## **M5StickC Plus**

The M5StickC is a compact device that has a built-in ESP32 microcontroller, a 0.96-inch color LCD display, and a variety of sensors and input/output options that includes a speaker, microphone, accelerometer, temperature sensor, and various input/output options, making it a versatile device for IoT projects. The device is powered by a rechargeable lithium-ion battery and can be charged via a USB-C connection. This small and portable device can connect to the Internet through a WiFi connection. This lab manual introduces the M5StickC Plus device and how to configure it for REST API access.



![image](https://github.com/drfuzzi/CSC2106_REST/assets/108112390/ff48eb65-2604-4ba9-8d51-90e5417688e6)

Figure 2: Interfaces for M5Stick-C Plus [1]

Step 1: Power the device by connecting the USB-C cable from the PC to the device.
Step 2: To connect the device to REST API, you must connect it to the internet via WiFi. To do this, you need to have a WiFi network available. Take note of the device’s IP address.
Step 3: To use the device with a REST API, you will need to configure the device and install the necessary libraries. Follow the instructions provided [here](https://docs.m5stack.com/en/quick_start/m5stickc_plus/arduino) [2].
Step 4: Now that you have the device configured for REST API access, you can test it by requesting the web-based service from any client (e.g. mobile phone, laptop, etc) that is within the same LAN.

By completing this lab, you have learned how to setup the M5StickC, connect it to WiFi, install the necessary libraries, and configure it for REST API access. You have also tested the M5StickC with a REST API, giving you a foundation for using it in your future projects.

## **Lab Assignment**

Extend your lab to incorporate both the functionality listed below:
1.   To extend the RESTful APIs into different URLs endpoints such as
  a.   /
  b.   /gyro/
  c.   /accel/
  d.   /temp/
2.   Besides obtaining data from the device, RESTful API can also trigger actuators. Extend the functionality of the lab to trigger any of the actuators in the device, i.e. LED, buzzer, LCD, etc.
  a.   /led/0 --> turn off the LED
  b.   /led/0 --> turn on the LED
  c.   /buzzer/0 --> turn off the buzzer
  d.   /buzzer/1 --> turn on the buzzer

Please upload the source file (.ino) to DropBox in xSITe. Remember to include your name and student ID. Lab assignments can be discussed with others but must each submittion must be unique and individual. 

## **Reference**
1. M5Stack Arduino Library, https://github.com/m5stack/M5StickC-Plus
2. Arduino IDE environment for M5StickC Plus, https://docs.m5stack.com/en/quick_start/m5stickc_plus/arduino
