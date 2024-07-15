# Innovative Monitoring System for TeleICU Patients Using Video Processing and Deep Learning

## Overview

This project proposes a novel monitoring system for TeleICU units that leverages video processing and deep learning techniques. The system aims to enhance patient care by:

#### Automatic Person Identification: 
Utilizing deep learning algorithms to distinguish between patients, medical staff, and visitors within the ICU room.
#### Unusual Activity Detection: 
Analyzing patient movements through video to identify potentially concerning behaviors that might require intervention.
#### Real-time Decision Making: 
Based on the identified activity of the patient, the system can trigger alerts and notifications to the TeleICU control center for timely response.

## Key Topics:

* `YOLOv8`, a Deep learning model and architectures used for person identification and activity recognition.
* Video processing techniques like `OpenLabeling` for dataset creation with pre-processing and feature extraction.
* Real-time processing and alert generation mechanisms using `openCV-python`.

### Benefits:

#### Improved Patient Monitoring: 
Continuous, automated analysis of patient activity can aid in early detection of critical situations.
#### Increased Staff Efficiency: 
Automating routine monitoring tasks can free up staff time for more complex patient care needs.
#### Enhanced Proactive Care: 
Early identification of potential issues allows for preventative measures and improved patient outcomes.

### Further Development:

* Integrate with existing TeleICU infrastructure for seamless data flow and alert management.
* Conduct clinical trials to validate the system's effectiveness and safety in real-world ICU settings.
* An algorithm could be built such that YOLOv8 is used to identify patients, then activates motion alarms only when they're alone, for improved monitoring.
