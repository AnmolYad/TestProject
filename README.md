Chapter 1: Abstract 


The Internet of Things (IoT) is a rapidly growing technology that has the potential to revolutionize how we interact with the world around us. IoT devices are connected to the internet, allowing them to send and receive data, and enabling them to perform tasks without any human intervention. The use cases of IoT range from smart homes and wearables to industrial applications and self-driving cars. The proposed project aids towards making a Smart Home System with Google Home, and Amazon Alexa using NodeMCU ESP8266. It can control multiple devices and monitor real-time feedback of the relays in the Google Home and Alexa App from anywhere in the world. We can handle the relay module from the manual switches if no internet is available.



Chapter 2: Introduction


Smart homes are a type of home automation that uses the Internet of Things (IoT) technology to connect devices and appliances to the internet, allowing them to communicate with each other and be controlled remotely through a smartphone, tablet, or computer. IoT refers to the network of physical devices, vehicles, and other objects embedded with sensors, software, and connectivity that enables them to exchange data and interact with their environment.
In a smart home, devices like lights, thermostats, security systems, door locks, and appliances are all connected to the internet and can be controlled using a mobile app or voice commands. This allows homeowners to monitor and manage their home from anywhere, even when they're not physically present.
 
Smart homes offer several benefits, including increased energy efficiency, enhanced security, and improved convenience. For example, homeowners can remotely turn off lights or adjust the thermostat to save energy, receive alerts if there's an intruder or if a door is left unlocked, and automate routine tasks like turning on the coffee maker in the morning. To set up a smart home, homeowners will need to choose compatible devices and a smart home hub or platform to connect them. There are many different platforms available, including Amazon Alexa, Google Assistant, Apple HomeKit, Samsung SmartThings, and more.
One popular way to implement home automation is by using a microcontroller like the NodeMCU, which is based on the ESP8266 chip. The ESP8266 is a Wi-Fi enabled microcontroller that can connect to the internet and communicate with other devices. The NodeMCU is a development board that uses the ESP8266 chip and provides additional hardware features like USB connectivity, voltage regulators, and more. To get started with home automation using NodeMCU and ESP8266, you'll need to learn how to program the microcontroller using a language like Arduino or MicroPython. Once you have the programming skills, you can start building your own home automation system by connecting various sensors and devices to the NodeMCU.


Chapter 3: Problem Statement


With the advancement of technology and the increasing demand for automation, there is a growing need for smart home systems that can be easily controlled using voice commands and remote devices. The aim of this project is to develop a smart home system that can be controlled using both voice commands (via Google Assistant and Alexa) and manual inputs (via NodeMCU and ESP8266) for added convenience and flexibility.
The smart home system will be designed to control various household appliances such as lights, fans, ACs, and other electrical devices. The system will use NodeMCU and ESP8266 as the main microcontrollers, which will be connected to the home Wi-Fi network to receive commands from Google Assistant and Alexa. The system will also have manual switches that can be used to control the appliances directly.
The main objective of the project is to create a reliable and efficient smart home system that can be easily operated by the user. The system should be capable of receiving commands through voice inputs as well as manual inputs, and the response time for the commands should be fast enough to provide a seamless user experience. Additionally, the system should be designed in a way that ensures the security of the home network and prevents any unauthorized access to the system.
Overall, the project aims to develop a comprehensive and user-friendly smart home system that can enhance the comfort and convenience of the users by automating various household appliances and making them easily controllable using voice commands and manual inputs.



Chapter 4: Literature 


Manish Prakash Gupta (2018) have proposed “Home automation using voice via Google assistant. The spoken commands from google assistant sends message to micro-controller this micro-controller pass the message to relay which will switch On and Off the appliances. 

Aayush Agarwal, Anshul Sharma, Asim Saket Samad and S Babeetha (2018) “UJALA- Home Automation System Using Google Assistant” This project presents a design and prototype of Home Automation system that will use ESP8266 Wi-Fi module as a network provider in connecting with other appliances. Further we will connect the specific home to our database and it can be accessed from anywhere through a specific IP address or website. Also, an app would be developed which will allow the user to control their devices using the Google Assistant. 

Md Sarwar Kamal in (2017) “Efficient low-cost supervisory system for Internet of Things enabled smart home.” This paper proposes an efficient low-cost supervisory system for smart home automation that can be managed using IoT. The proposed system is based on Apriority algorithm and will help to monitor and control all the home appliances and electronic devices through a supervisory system in a most efficient and reliable manner. Both the consumers and the suppliers will get the opportunity to manage the power distribution by monitoring the electricity consumption. 

Nikhil Singh, Shambhu Shankar Bharti, Rupal Singh, Dushyant Kumar Singh (2014) “Remotely controlled home automation system”, Advances in Engineering and Technology Research (ICAETR) This paper describes an investigation into the potential for remote controlled operation of home automation systems. It considers problems with their implementation, discusses possible solutions through various network technologies and indicates how to optimize the use of such systems. The home is an eternal, heterogeneous, distributed computing environment (Greaves, 2002) which certainly requires a careful study before developing any suitable Home Automation System (HAS) that will accomplish its requirements. Nevertheless, the latest attempts at introducing Home Automation Systems in actual homes for all kinds of users are starting to be successful thanks to the continuous standardization process that is lowering the prices and making devices more useful and easier to use for the end user. Even so several important issues are always to be handled strictly before developing and installing a Home Automation System; factors like security, reliability, usefulness, robustness and price are critical to determine if the final product will accomplish the expected requirements.

Sean Dieter Tebje Kelly, Nagender Kumar Suryadevara, Subhas Chandra Mukhopadhyay (2013) “Towards the Implementation of IoT for Environmental Condition Monitoring in Homes” In this paper, we have reported an effective implementation for Internet of Things used for monitoring regular domestic conditions by means of low-cost ubiquitous sensing system. The description about the integrated network architecture and the interconnecting mechanisms for the reliable measurement of parameters by smart sensors and transmission of data via internet is being presented. The longitudinal learning system was able to provide a self-control mechanism for better operation of the devices in monitoring stage. The framework of the monitoring system is based on a combination of pervasive distributed sensing units, information system for data aggregation, and reasoning and context awareness. Results are encouraging as the reliability of sensing information transmission through the proposed integrated network architecture is 97%. The prototype was tested to generate real-time graphical information rather than a test bed scenario. 

Jawarkar, Ahmed, Ladhake, and Thakare (2008) “Micro-controller based Remote Monitoring using Mobile through Spoken Commands” propose remote monitoring through mobile phone involving the use of spoken commands. The spoken commands are generated and sent in the form of text SMS to the control system and then the microcontroller on the basis of SMS takes a decision of a particular task. 

Potamitis, Georgila, Fakotakis, and Kokkinoss, G. (2003) suggested the use of speech to interact remotely with the home appliances to perform a particular action on behalf of the user. The approach is inclined for people with disability to perform real-life operations at home by directing appliances through speech. Voice separation strategy is selected to take appropriate decision by speech recognition. 

Tan, Lee and Soh (2002) proposed the development of an Internet-based system to allow monitoring of important process variables from a distributed control system (DCS). It proposes hardware and software design considerations which enable the user to access the process variables on the DCS, remotely and effectively rent designations. 

Prof. Era Johri in (2001) have successfully completed the project on “Remote Controlled Home Automation”.



Chapter 5: Objective 


The objective of your IoT project is to create a smart home system that can be controlled both manually and through voice commands using two of the most popular voice assistants, Google assistant, and Alexa. The system will be powered by NodeMCU ESP8266, an inexpensive and versatile microcontroller board that can be programmed using the Arduino IDE. 

1.	Establish a connection among IoT devices such as NodeMCU ESP8266 and 4-way relay module.
2.	Program NodeMCU using Arduino IDE.
3.	Integrate Google Assistant and Amazon Alexa apps.
4.	The connected device should be enabled for manual + voice control.



Chapter 6: Methodology 


1.	Installation of the relay module onto the PCB and interconnection of all the components
Attach the relay module to the PCB, a printed circuit board, and connect all electronic parts together. This will ensure that the circuit works as intended and the electronic components are communicating with each other efficiently.
2.	Setting up and customizing a Sinric Pro account.
To use Sinric Pro, create an account and customize it to our needs. This includes choosing our preferred language and setting up our smart home devices, adding new devices, and customizing their settings. We can also integrate other services, such as Alexa, for even more functionality.
3.	Addition and configuration of room and device information in the Sinric Pro app.
In the Sinric Pro app, input and customize details about the room and devices we want to control. This includes providing names and settings for each device, which can then be accessed remotely through the app, allowing us to control them with ease.
4.	Customization of device details, notifications, timers, and additional settings.
The customization of device details, notifications, timers, and additional settings enables users to personalize the way they interact with their smart devices. This includes setting specific schedules for devices, receiving alerts for important events, and adjusting device settings such as brightness or temperature to meet individual preferences.
5.	Programming NodeMCU.
Programming NodeMCU involves using software tools to write code that is uploaded to the NodeMCU board. This code can then be used to control various electronics and devices. NodeMCU supports the use of a variety of programming languages, including C++ and Python, to create custom applications for IoT projects.
6.	Incorporation of app-keys from Sinric Pro into the NodeMCU program.
To enable the NodeMCU board to communicate with the Sinric Pro app, the app-keys need to be incorporated into the NodeMCU program. This is typically done by copying and pasting the keys into the appropriate sections of the code, allowing the NodeMCU board to authenticate with the Sinric Pro servers and establish a connection.
7.	Configuration of the Amazon Alexa app to connect it with Sinric Pro.
To connect the Amazon Alexa app with Sinric Pro, it is necessary to configure the Alexa app settings. This involves linking the Alexa app with the Sinric Pro account, enabling the appropriate skill, and then discovering and configuring the devices connected to the account. Once configured, users can control their smart home devices using voice commands with Alexa.
8.	Establishing a Wi-Fi connection with the Node MCU and linking it with the Amazon Alexa app.
To link Node MCU with Amazon Alexa, it is necessary to first establish a Wi-Fi connection with the board. This involves connecting the Node MCU board to a Wi-Fi network, then configuring the Amazon Alexa app to connect with the board. Once the connection is established, users can control their devices using voice commands with Amazon Alexa.

 
 ![image](https://github.com/AnmolYadav1/SmartHomeAutomation/assets/89251630/4f59224f-477f-4cc5-a546-29fcbd1f5201)

 

