
# MicroEDS – Community Edition: Version 1.0.8



Real-Time Edge Anomaly Detection for Sensor Streams
MicroEDS is an Event Detection System (EDS) that uses unsupervised machine learning to detect anomalous events in real-time data.

Designed for edge environments, it runs on:

- Raspberry Pi & other SBCs  
- Windows  
- Linux  
- Any system with a Java Virtual Machine (JVM)

The Community Edition is distributed as a binary package.



# How MicroEDS may reduce IoT costs



MicroEDS runs anomaly detection directly on the edge device, next to the sensors. Instead of streaming massive volumes of raw data to the cloud, only meaningful events and summarised information are transmitted. This dramatically reduces bandwidth consumption, cloud storage costs, and processing expenses, while also enabling faster response times and continued operation even during network outages. By filtering noise locally and escalating only what matters, MicroEDS turns expensive, always-connected IoT architectures into efficient, scalable, and cost-controlled systems.



# Why MicroEDS

✔ Detect abnormal combinations  
✔ Detect sudden jumps & drifts  
✔ Learn normal behaviour automatically  
✔ Reduce false alarms  
✔ Works offline at the edge  
✔ Built-in dashboard, charts & reports  
✔ Integrates with external systems

 


# What Is an Event?

An event is an abnormal combination of sensor values which hints for pending problem. identified by the model.




=====================================
MicroEDS continuously:
=====================================


1. Reads raw data  
2. Applies rules  
3. Runs detectors  
4. Updates history  
5. Sends alerts if needed  


=====================================
Example Environments
=====================================

MicroEDS may be deployed on:

- Windows
- Ubuntu
- Raspberry Pi 5
- Raspberry Pi 4 (4GB+)  
- Radxa  
- Banana Pi  
- Intel NUC  
- BeagleY AI  
 

=====================================
Quick Start
=====================================

Step 1 – Download
Go to **Releases** and download the latest `microeds-ce.zip`.

Step 2 - Extract
Windows - Extract the content of the zip file into a directory c:\eds-sbc
Linox        - Create user named  eds-sbc
                    Extract the content of the zip file into a directory home/eds-sbc
                    Make the eds-sbc user the owner of the eds-sbc directory and all its sub-directories.


Step 3 – Run 
java -jar EDS-SBC.jar


Step 4 – Use Demo Database
The package includes a demo model so you can immediately see:
- dashboards  
- alarms  
- density  
- charts  


=====================================
Demo License
=====================================

The Community Edition runs with a demo license.

It is fully functional but has a limited runtime.  
Restarting the application re-enables the demo.
Follow the instructions in the user manual to get a full community license for free.

=====================================
Main Capabilities
=====================================

- Monitoring
- Real-time dashboard  
- Data table  
- Line/histogram / correlation charts  

Detection
- Abnormal combinations  
- Out-of-range values  
- Fixed values  
- Baseline changes  
- Communication failures  
- Trends

Analytics
- density tables  
- heat maps  
- similarity scoring  

Event Management
- pending/triggered  
- severity  
- duration  
- history  

Integration
- CSV  
- Modbus  
- TCP  
- MSMQ export  


Data Sources

MicroEDS can ingest data from:

- Non-pivoted CSV files  
- Modbus registers  
- TCP streams  

Only one input method may be active at a time.


Outputs

- Real-time alarms  
- Validation reports  
- Historical events  
- CSV export  
- MSMQ messages  


Model Components

A model contains:

- Variables  
- Detectors  
- Rules  
- Parameters  
- Versions  

Editing is done in **Pause** mode.



Typical Workflow

1. Run demo  
2. Understand variables  
3. Configure detectors  
4. Review alarms  
5. Adjust rules  
6. Import your own data  
7. Train model  
8. Move to production  


Safety Notice
Always test MicroEDS in a lab environment before using real operational data.


Minimum Hardware (SBC)

- Raspberry Pi 4  
- 4GB RAM  
- 32GB SD card  

More powerful hardware → better performance.


License

MicroEDS Community Edition is provided under a limited license.

You may:
✔ Evaluate  
✔ Test  
✔ Develop integrations  

You may not:
❌ reverse engineer  
❌ modify  
❌ redistribute  

For commercial deployment, a paid license is required.


Support

Community users can:

- open Issues  
- suggest improvements  
- request features  

Commercial customers receive SLA support.

Upgrade to Professional / Enterprise

Commercial editions provide:

- unlimited runtime  
- higher loads  
- multi-site management  
- advanced integrations  
- priority support  

Contact:  
admin@decisionmakers.biz**


For additional information contact

Decision Makers Ltd  
http://www.decisionmakersltd.com


If MicroEDS helps you, please star the repository.

