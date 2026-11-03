# Academic Coursework & Technical Presentations
### Master of Technology in Industrial Intelligent Systems (2020 – 2022)
**Department of Electrical & Electronics Engineering | Amrita Vishwa Vidyapeetham, Coimbatore**  
**Author:** Charitha B.V. (Roll No: `CB.EN.P2IIS20012`)

---

## Overview

This directory archives the technical presentations, seminar slide decks, and project defense materials delivered during the **M.Tech in Industrial Intelligent Systems** program. The presentations represent independent investigations, term projects, end-semester capstone reviews, and the Master's dissertation defense.

Each project addresses practical challenges in industrial intelligence—spanning predictive maintenance, distributed cloud computing, cyber-physical automation, fault-tolerant control, and cybersecurity.

---

## Coursework Index

| # | Topic / Presentation Title | Academic Course / Context | Core Methodologies & Technologies | Document Link |
|:---:|---|---|---|:---:|
| 1 | **Thermal Imaging-Based Motor Fault Detection** | 20IS799 M.Tech Dissertation | Infrared Thermography (FLIR), Spatial Profiling, ML Classifiers | [View Presentation](Thermal-Imaging-Motor-Fault-Detection.pptx) |
| 2 | **Silica Concentrate Prediction in Mining** | 19AI716 Cloud & Big Data Analytics | PySpark, Spark Streaming, Google Cloud Dataproc, BigQuery | [View Presentation](BigData-Mining-Silica-Prediction.pptx) |
| 3 | **Cyber-Physical Agents for Irrigation** | Architecture of Intelligent Systems | Multi-Agent Systems, Logic Agents, FAO AquaCrop Simulation | [View Presentation](Cyber-Physical-Irrigation-Agents.pptx) |
| 4 | **Three-Tank Process Control & Monitoring** | Fault Detection & Diagnosis / Process Control | Hybrid Nonlinear Dynamics, State Estimation, Sensor Faults | [View Presentation](Three-Tank-Process-Fault-Diagnosis.pptx) |
| 5 | **Neuro-Fuzzy Actuator FDI** | Fault Detection & Diagnosis Systems | Hybrid Neuro-Fuzzy Systems, ANFIS, Electro-Pneumatic Actuators | [View Presentation](Neuro-Fuzzy-Actuator-FDI.pptx) |
| 6 | **Smart Greenhouse IoT Automation** | Embedded Systems Design | Embedded IoT Gateway, Multi-threaded RTOS, Python Edge AI | [View Presentation](Smart-Greenhouse-IoT-Automation.pptx) |
| 7 | **IoMT Security & Privacy in Smart Healthcare** | Ubiquitous Computing & IoT Security | IoMT Firmware Analysis, WRECK Vulnerabilities, Cryptography | [View Presentation](IoMT-Security-Smart-Healthcare.pptx) |
| 8 | **RFID-Based Parking Slot Allocation** | 20RM600 Research Methodology | RFID Transceivers, HT12E/HT12D RF Encoding, IR Proximity | [View Presentation](RFID-Smart-Parking-Allocation.pptx) |
| 9 | **Music Genre Classification with ML** | Machine Learning | Audio Feature Extraction, MFCCs, Multiclass Classification | [View Presentation](Music-Genre-Classification-ML.pptx) |

---

## Project Summaries & Technical Details

### 1. Thermal Imaging-Based Fault Detection in an Induction Motor
* **Course / Context:** 20IS799 M.Tech Dissertation (Defense Date: 17-June-2022)
* **Faculty Advisor:** Dr. T. Ananthan (Assistant Professor, Dept. of EEE)
* **File:** [`Thermal-Imaging-Motor-Fault-Detection.pptx`](Thermal-Imaging-Motor-Fault-Detection.pptx)
* **Description:**  
  Presents the complete research methodology and experimental validation for non-invasive condition monitoring of industrial three-phase induction motors. Utilizing Forward-Looking Infrared (FLIR) radiometric thermal cameras, spatial temperature distributions were analyzed across baseline and fault-induced conditions (bearing faults, unbalanced supply, and stator overheating). Evaluated machine learning classifiers for automated fault categorization without requiring mechanical sensor placement. This work formed the basis of the IEEE ICESC 2022 publication.

---

### 2. Silica Concentrate Prediction in Industrial Mining Process
* **Course:** 19AI716 Cloud and Big Data Analytics (End-Semester Capstone)
* **File:** [`BigData-Mining-Silica-Prediction.pptx`](BigData-Mining-Silica-Prediction.pptx)
* **Description:**  
  Constructed an end-to-end distributed big data analytics pipeline predicting silica impurity levels in iron ore froth flotation processes. Implemented data preprocessing, feature engineering via VectorAssembler/VectorIndexer, and regression models in Apache Spark (PySpark ML and Spark Streaming). Leveraged Google Cloud Platform services including Dataproc clusters, BigQuery data warehousing, Cloud Pub/Sub messaging, and Vertex AutoML for model benchmarking.

---

### 3. Cyber-Physical Intelligent Agents for Irrigation Scheduling
* **Course:** Architecture of Intelligent Systems (AIS)
* **File:** [`Cyber-Physical-Irrigation-Agents.pptx`](Cyber-Physical-Irrigation-Agents.pptx)
* **Description:**  
  Investigates cyber-physical multi-agent architectures for precision agricultural irrigation. Formulated an Agent Central Station (ACS) using logic-based decision engines coupled with the Food and Agriculture Organization (FAO) AquaCrop simulation engine. Demonstrated closed-loop soil moisture and evapotranspiration monitoring for dynamic, water-conserving irrigation control.

---

### 4. Process Control & Monitoring of Three-Tank Benchmark System
* **Course:** Fault Detection & Diagnosis / Process Control
* **File:** [`Three-Tank-Process-Fault-Diagnosis.pptx`](Three-Tank-Process-Fault-Diagnosis.pptx)
* **Description:**  
  Investigates hybrid dynamical modeling and automated fault detection on the classical DTS200 Three-Tank Benchmark System. Analyzed coupled nonlinear fluid dynamics governed by mixed continuous and discrete-event states. Formulated fault detection routines capable of distinguishing sensor biases, actuator failures, and inter-tank fluid leaks under varying continuous flow setpoints.

---

### 5. Hybrid Neuro-Fuzzy Systems for Fault Detection & Isolation (FDI)
* **Course:** Fault Detection and Diagnosis Systems (FDS)
* **File:** [`Neuro-Fuzzy-Actuator-FDI.pptx`](Neuro-Fuzzy-Actuator-FDI.pptx)
* **Description:**  
  Examines theoretical foundations and practical implementations of hybrid neuro-fuzzy inference systems (ANFIS) for complex industrial fault diagnosis. Presents classification and continuous regression architectures for symptom-to-fault mapping. Includes an in-depth case study evaluating fault detection and isolation on an industrial electro-pneumatic control valve actuator.

---

### 6. Smart Greenhouse Automation using Industrial IoT
* **Course:** Embedded Systems Design (ESD)
* **File:** [`Smart-Greenhouse-IoT-Automation.pptx`](Smart-Greenhouse-IoT-Automation.pptx)
* **Description:**  
  Presents the hardware and firmware architecture of an embedded IoT gateway for automated greenhouse microclimate regulation. Implemented multi-sensor acquisition (soil moisture, temperature, relative humidity, luminous flux) interfacing with a multi-threaded Python runtime. Outlines scheduled hourly climate setpoint controllers driving ventilation, shading, and irrigation actuators.

---

### 7. Security and Privacy of IoT Devices in Smart Healthcare
* **Course:** Ubiquitous Computing & IoT Security (701-UC)
* **File:** [`IoMT-Security-Smart-Healthcare.pptx`](IoMT-Security-Smart-Healthcare.pptx)
* **Description:**  
  Comprehensive survey and cybersecurity risk appraisal of the Internet of Medical Things (IoMT). Evaluates firmware vulnerability attack vectors (such as WRECK bugs in embedded network stacks), device tampering, patient data eavesdropping, and interoperability friction. Synthesizes risk mitigation frameworks aligned with healthcare regulatory standards.

---

### 8. Automated Parking Slot Allocation using RFID Technology
* **Course:** 20RM600 Research Methodology
* **File:** [`RFID-Smart-Parking-Allocation.pptx`](RFID-Smart-Parking-Allocation.pptx)
* **Description:**  
  Explores research methodology principles applied to intelligent transportation systems. Designed and simulated an automated multi-lane parking allocation system combining RFID identification, infrared entry/exit sensing, and HT12E/HT12D RF telemetry. Evaluates throughput improvements and latency reductions over conventional manual ticketing systems.

---

### 9. Music Genre Classification using Machine Learning
* **Course:** Machine Learning
* **File:** [`Music-Genre-Classification-ML.pptx`](Music-Genre-Classification-ML.pptx)
* **Description:**  
  Delivered an end-to-end supervised machine learning pipeline for automated acoustic categorization on standard audio datasets (e.g., GTZAN). Extracted acoustic spectral features, including Mel-Frequency Cepstral Coefficients (MFCCs), spectral centroid, and roll-off, followed by classification and cross-validation across multiple musical genre categories.
