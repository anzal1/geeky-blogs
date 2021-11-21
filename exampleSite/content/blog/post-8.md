---
title: "Drone Software and Development"
description: "meta description"
image: "images/post/post-8.png"
date: 2021-11-17T18:19:25+06:00
categories: ["drone"]
type: "regular" # available types: [featured/regular]
draft: false
---

Drones allow opening previously unavailable opportunities – to see the invisible and reach the unreachable – not only in the air but also on the ground and underwater. Drawing on our 32-year experience in software development, we discover drone software architecture, discuss a basic and extended set of features for modern drone apps, and give an overview of trends that are likely to shape the future of drone software development.



> “Our greatest power as nations and individuals is not the ability to employ assault weapons, suicide bombers, and drones to destroy each other. The greater more creative powers with which we may arm ourselves are grace and compassion sufficient enough to love and save each other.” ― Aberjhani, Splendid Literarium: A Treasury of Stories, Aphorisms, Poems, and Essays

#### Industries where drones are used
Modern drones are not only about thrilling aerial footages. Drones are gaining popularity across all kinds of markets. By the year 2022, the commercial drone market is expected to reach $10,738 million. According to Goldman Sachs, the fastest adopters of drone techs will be such industries as:

{{< image title="" w="" h="" o="webp q1" p="center" c="rounded" src="images/post/drone.jpg" alt="alter-text" >}}

###### Construction: 
Surveying buildings; creating contour maps; building roads and railways; counting construction supplies.

###### Agriculture: 
Monitoring plants and livestock; monitoring water use; spraying crops.

###### Insurance:
Damage inspection; risk assessment; fraud monitoring.

###### Oil & gas:
Laying and monitoring oils & gas pipelines.

##### Drones are also actively conquering such spheres as:

###### Scientific surveillance:
Exploring the ground of archaeological sites, radiation zones, and the deep sea; monitoring wildlife; terrain modeling.

###### Disaster management: 
Monitoring areas affected by natural disasters. Informing search and rescue teams about the damage; supplying blood, emergency aids and equipment; fighting fire.

###### Logistics: 
Checking inventory; delivering packages (works in combination with barcode scanning).

###### Energy: 
Inspecting solar farms and power lines.

###### Security: 
Monitoring state boundaries; ensuring security during public events.

##### Overview of a sample drone software architecture
drone software architecture

Drone software includes several parts: system software, user software, and a cloud-based control platform.

###### System software encompasses the following components:

Embedded software operates as CPU – manages hardware, tracks drone telemetry and partially analyzes the data received from drone sensors (GPS, thermal sensors, infrared and lidar cameras, ultrasonic and vision sensors and more).
OS allows users to operate the firmware part.
Web and cloud interfaces allow accessing the OS from remote drone control systems (user applications and cloud control stations) and streaming gathered data from embedded software to the cloud or mobile devices.
A cloud-based drone control platform is used for data processing, storage and analysis. It also enables a drone’s autonomous response actions. The cloud part is a must when it comes to complex processes as in, say, 3D maps creation, computer vision, pattern recognition.

###### The cloud-based control platform hosts:

Streaming data processor.
Data lake and big data warehouse.
Data analytics and machine learning.
Drone control module.
Interfaces to communicate with the drone.
User software covers front- and back-end parts of web and mobile user applications. They help users to plan and conduct flights, as well as display data from a drone to users. User software also includes interfaces for communication with the cloud and the drone.

To communicate with each other, the three parts use special protocols, for example, MAVlink and ROSlink.

Highlights in modern-day drone application development
To make a successful and long-lasting drone application, we suggest paying attention to the following development aspects:

Features for safe and convenient work
The basic feature set of drone applications should include:

Simulating training flights and controlling real flights.
Checking weather conditions and forecasting weather in the flying region.
Planning routes (taking into consideration ‘no-fly’ maps and info about critical infrastructure, transport and pedestrian ways, privacy zones).
Transmitting to the smartphone what a drone sees or the already processed data from the cloud (audio/video streaming).
User applications can offer extended functionality depending on what the drone is used for. Among the most utilized capabilities of modern drone user apps are:

Professional photography and film editing.
Video and image sharing.
Chat capabilities.
Alerts on the drone condition, route modifications, obstacles in the way.
3D modeling and exporting into the needed format.
Other important considerations
Software certification
Drone software is subject to such standards as DO-178C and ISO 14508, so the software architecture, requirements gathering, coding and integration processes, reviews and testing, configuration management should be organized accordingly.

###### Exceptional data security
Drones are often a target of hacker attacks. Thus, exceptional attention should be given to ensuring data security, especially when it comes to drones’ usage for government or military purposes. The required level of protection for the software part can be provided through such measures as ensuring a safe connection between software parts, isolating confidential parts at the architectural level, strong encryption and authentication.

###### Continuous enhancements
If you want to keep up with the rapidly evolving innovations in the drone industry, enhancements should happen frequently and not hinder the system’s stability. One of the latest and most popular approaches to assert the software quality in the context of fast development is to use the continuous development, delivery and deployment approach. The approach implies the usage of containers, shared code repository, infrastructure-as-code (IaC) approach and other DevOps practices, automation in test (unit, API, UI) preparation and execution, sound versioning and more.

###### Design that allows for scalability
To stay competitive, drone software should be ready for both increasing the number of users and data, and new features and deep customizations. A good way to address these needs is organizing the drone applications’ architecture in a modular pattern (for example, based on the service-oriented model or microservices).

Integration with other systems
Enterprise drone applications should be able to integrate with enterprise systems, depending on their task – for example, with logistics management systems for delivery services, maintenance systems for pipeline surveying and so on.

###### Simple UI in user apps
UI should make drone controlling easy for people from different spheres and of different roles. It means that a user app should be intuitive in guiding a drone operator through the flying process and accurate in conveying the analytics results.

What does the market expect from drones in the near future
The main efforts in drone software development will be focused on the enablement of more advanced autonomous capabilities. They will derive from:

Ability to perform AI-driven route planning and mid-course corrections (in case of weather or wind changes). It will require refinement of AI algorithms for better autonomous trajectory creation. To safely navigate around obstacles and avoid collisions, algorithms for both co-piloting and fully autonomous flights of drones have already been developed. But they still require further improvement.
Real-time monitoring and coordination. The use of real-time operating systems (RTOS) is gaining popularity as a way to make drones capable of quicker data processing and accurate responding. RTOS multi-threading allows a drone to promptly combine and process real-time data about people, buildings, other drones, manned aircrafts that are in close proximity. In addition, it enables RTOS to accurately trigger follow-up actions, quickly assess the priority of tasks and schedule actions accordingly.
In addition, priority will be given to improving data collection and analysis. Users require more and more sophisticated pattern recognition for enhanced 3D modelling, image processing and analysis, deep learning and other intelligent capabilities that are in direct correlation with modern enterprise drone usages.

