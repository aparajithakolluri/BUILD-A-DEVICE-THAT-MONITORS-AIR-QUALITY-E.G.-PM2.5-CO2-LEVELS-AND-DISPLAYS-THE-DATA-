# BUILD-A-DEVICE-THAT-MONITORS-AIR-QUALITY-E.G.-PM2.5-CO2-LEVELS-AND-DISPLAYS-THE-DATA-
# COMPANY # : CODTECH IT SOLUTIONS
# NAME #: K V S L J APARAJITHA
# intern id# :CT08KWF
# domain # : IOT
# batch duration #: January 10th, 2025 to February 10th, 2025
# name of mentor #:neelam harish
The Air Quality Monitoring System operates by utilizing sensors to detect environmental parameters like gas levels, temperature, and humidity. Specifically, analog readings from the gas sensor, connected to an Arduino's analog pin, provide data on the air quality. These readings are mapped to predefined thresholds, categorizing the air quality as "Good," "Poor," "Very Bad," or "Toxic." Simultaneously, a DHT11 sensor measures humidity and temperature. The collected data is displayed in real-time on an OLED screen using the Adafruit libraries. By continuously monitoring these parameters, the system offers a snapshot of air quality conditions, enabling users to assess and respond to changes in their environment.
Components Required for this Project are:
Arduino board
MQ135 gas sensor for detecting various gases.
DHT11 temperature and humidity sensor
OLED display for visual output
Breadboard and jumper wires
Platform Selection: Consider platforms like ThingSpeak, Adafruit IO, or AWS IoT Core, which offer features like data logging, visualization, and alerts.   
Data Transmission: The microcontroller will transmit the sensor data to the chosen cloud platform using Wi-Fi.
Data Storage: The cloud platform will store the historical data for analysis and visualization.
Dashboard Creation: Create a custom dashboard on the platform to visualize the real-time and historical air quality data (PM2.5 and CO2 levels) using charts and graphs.
Alerts: Configure alerts to notify users via email or SMS when specific thresholds for PM2.5 or CO2 are exceeded.
Software Development:
Microcontroller Programming: Write code for the microcontroller to:
Read sensor data.
Connect to Wi-Fi.
Format data for transmission.
Transmit data to the cloud platform.
Handle potential communication errors.
Dashboard Customization: Customize the dashboard on the cloud platform to include:
Real-time data displays for PM2.5 and CO2.
Historical data visualizations (line graphs, bar charts).
Geographic mapping (if applicable) to display air quality data across different locations.
User-defined thresholds for alerts.
Deployment and Maintenance:
Device Placement: Strategically place the device in a location that accurately represents the local air quality.
Calibration: Regularly calibrate the sensors to ensure accurate readings.
Power Management: Monitor battery levels and ensure timely recharging.
Cloud Platform Management: Regularly review the cloud platform for data integrity and to adjust alert thresholds as needed.
Software Updates: Update the microcontroller code and dashboard as necessary to improve functionality or address issues.
This project provides a framework for building a basic air quality monitoring system. Further enhancements could include:
Integration with weather data to provide a more comprehensive understanding of air quality.
Adding features like remote device configuration and firmware updates.
Developing a mobile app for real-time data access and alerts.
Expanding the system to monitor other air pollutants, such as ozone and nitrogen dioxide.
By combining readily available hardware, software, and cloud services, this project can be a valuable tool for individuals, communities, and researchers to monitor and understand local air quality.
# output :https://github.com/aparajithakolluri/BUILD-A-DEVICE-THAT-MONITORS-AIR-QUALITY-E.G.-PM2.5-CO2-LEVELS-AND-DISPLAYS-THE-DATA-/issues/1#issue-2811355633
