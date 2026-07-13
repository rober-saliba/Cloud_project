# 🤖 Robotics Lab Monitoring Platform

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
</p>

## 📌 Project Overview
The **Robotics Lab Monitoring Platform** is a data-driven system designed to monitor the environment of the ** Robotics Lab** at Braude Academic College. The project leverages **Apache Spark** for distributed data processing and **Firebase** as a Realtime Database to manage and analyze sensor data (Temperature, Humidity, Motion, and Distance).

## 📢 Features

**✅ Real-Time IoT Data Integration**
* Synchronizes live sensor data from a Raspberry Pi to a **Firebase Realtime Database**.
* Implemented a **Gemini AI ChatBot** interface for natural language querying of current lab metrics.

**✅ Big Data Analytics with Apache Spark**
* Utilizes **PySpark** to process large-scale sensor logs and user comments.
* Implemented **MapReduce** algorithms to identify key patterns and frequently reported issues in the lab.

**✅ Anomaly Detection & Visualization**
* Automated detection of environmental anomalies (e.g., temperature spikes or high humidity).
* Interactive dashboards created in **Databricks** for historical trend analysis.

**✅ Advanced Management Dashboard**
* Role-based user management (Manager/Engineer) to control system access and lab oversight.

## 🛠 Tech Stack

**⚙️ Data Engineering & Cloud**
* **Apache Spark (PySpark):** Core framework for distributed processing and text analysis.
* **Firebase:** Real-time NoSQL database for hardware-software synchronization.
* **Databricks:** Unified analytics platform for collaborative data engineering.

**🖥 Hardware & Communication**
* **Python:** Scripting for sensor data collection and MQTT/Firebase integration.
* **MQTT:** Protocol used for lightweight sensor messaging between devices.

## 📐 System Flow



## 📂 Repository Structure
* `scripts/`: Python scripts for sensor integration and data uploading.
* `pyspark_notebooks/`: Spark-based notebooks for MapReduce analysis and anomaly detection.
* `docs/`: Technical reports and project documentation.

## 💻 How to Run (Quick Start via Google Colab)

The easiest way to run and test this project is directly through Google Colab—no local cloning or environment setup required!

1. **Firebase Configuration:** Ensure you have your Firebase `serviceAccountKey.json` and `databaseURL` ready, as you will need them to connect the database.
2. **Open the Notebook:** Click the button below to open the project directly in your browser:
   
   <a href="https://colab.research.google.com/drive/1zAiCCOvGcj_66eqPqtVkCJGDet_Redfr?usp=sharing" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

3. **Configure Setup:** Once inside the notebook, make sure to **set the run setup to `True`**.
4. **Run the Project:** Execute the cells in the notebook. Colab will automatically handle the installation of necessary dependencies (like `pyspark`, `firebase-admin`, and `paho-mqtt`) and run the project!
