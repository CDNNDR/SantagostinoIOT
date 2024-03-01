AltAirX
Start Up
22.02.2024 rev.0


















Product Description

AltAir is an IoT sensor characterized by a PCB board containing CO2, temperature, relative humidity, and illumination sensors. The board has a microcontroller that features Wi-Fi and BLE connectivity and is powered via a USB type C port or a single-cell Li-Po battery. AltAir is equipped with two unused but available I2C ports for potential expansions, which are not exposed outside of the case. The case consists of a main structure, a sliding structure that acts as a closure, and two buttons, RESET and BOOT.



fig.1 - scheme reset e boot buttons




fig.2 - chiusura a slitta



Configurazione

Ensure that AltAir is charged by pressing the RESET button once. 

If the sensor is charged, a green LED will light up inside the cloud.



If the sensor is not charged, connect it to a 5V max 2A USB power adapter, using a USB Type C cable.

After charging the sensor, press the RESET button and check that the green LED inside the cloud lights up.

The AltAir board is configured for data transmission and connection to a Wi-Fi network through a captive portal. Below, we will see the steps for the configuration.


press RESET

press BOOT









Use your smartphone, tablet, or computer with Wi-Fi connection.


Search for the Wi-Fi network named "AltAir Configuration Portal."
















From this moment, a captive portal for the configuration of AltAir will be activated on the chosen device, be it a smartphone, tablet, or computer.

If the portal does not automatically appear after selecting the "AltAir Configuration Portal" Wi-Fi network, open your web browser (Google Chrome, Safari, Opera, etc.), and the portal will appear within your web browser.




J. WiFi SSID field of the portal > Enter the name of the Wi-Fi network you want to connect the sensor to.

K. PASSWORD field of the portal > Enter the password of the Wi-Fi network you want to connect the sensor to.

The Dashboard TOKEN Field can be found, scanned, and copied from the QRCode inside the sensor's box. The TOKEN has a format similar to this:

 altair_beta_kit/11f0a4fb-5b45-4cc0-b644-da21d6039a18 

(don’t copy this is an example)







M. Once all the data has been entered, select from the dropdown menu at the bottom the sampling frequency, that is, how many minutes the sensor should send the data. It is recommended to use 15 minutes for optimized use of the 2000mah battery.







N. After completing step M, press SUBMIT, and if you see the blue LED light up, the configuration has been successful. If the LED is red, it will be necessary to repeat the operation.





In case you want to reset the sensor to change its password and Wi-Fi, it will be possible at any time to perform the procedure from point A to point N and reconfigure the board with a new SSID, Wi-Fi network name, and PASSWORD, Wi-Fi network password.


Power Supply

AltAir must not be exposed to open flames or direct heat sources. The sensor requires 4 hours for a full charge and it is advised that it be connected exclusively to USB power adapters of 5V 0.5-2A. It can operate continuously while connected to the power cable.



































Welcome to Your Sensor Data Platform
video tutorial: https://www.loom.com/share/e3f239bb10a141cab6b6681b857279da?sid=a5fd96dd-21a1-4d42-82ff-dda5b811d398 


Follow these simple steps to get started with monitoring and customizing your sensor data dashboard:
Step 1: Account Setup
Check Your Email: Look for an email from us with setup instructions.


Create Your Account: you'll need to enter details such as your name and password. Use this link to access the platform 

www.app.santagostinoiot.com 

or use the link provided with the email
Step 2: Navigate the Platform
Log In: Once your account is set up, log into your account to access the platform and your workspace
Step 3: View Sensor Data
Device session: Initially, your data might be limited as the sensors have only been installed for a short period. As time goes on, you'll see more comprehensive data from your sensors.
Step 4: Customize Your Dashboard
Configure Sensor Settings: You can change the name of your devices, add tags, or update the device image in the configuration section.


Create and Modify Dashboards: Tailor your dashboard to your needs. Add, modify, or copy sections to include widgets like graphs. These can display various sensor data, such as CO2 levels, with options to customize colors, connections, and axes.
Step 5: Access and Share on Mobile
The platform offers a mobile version for on-the-go access. You can edit and share your dashboards using a shareable link, making it easy to collaborate with others.






Step 6: Reporting and Alerts
Generate Reports: Create reports for specific time periods in formats like CSV. This helps in analyzing data over time.


Set Up Rules for Notifications: Establish rules to receive alerts based on specific data thresholds or averages, ensuring you're informed of critical changes promptly.
Final Steps:
Explore the platform to familiarize yourself with its full range of features. Your dashboards are fully customizable, allowing for a personalized monitoring experience.
Should you wish to create a new dashboard, the process is straightforward and allows for extensive customization.
Conclusion
You're all set! Dive into the platform and start playing with the various features at your disposal. If you have any questions or need further assistance, don't hesitate to contact our support team.



Milan
01.03.2024
Rev. 0


