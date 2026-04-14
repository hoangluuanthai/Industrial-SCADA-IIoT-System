# Industrial SCADA & IIoT Integration Project (Schneider Electric Ecosystem)

## 📝 Overview
This project focuses on the design and deployment of a comprehensive end-to-end SCADA system, integrating modern data management solutions. The system provides a seamless data synchronization pipeline from the **Field layer** (device level) up to the **Management layer** (Cloud/IIoT), ensuring real-time monitoring and historical data integrity.

## 🚀 Key Features
* **Industrial Control Logic:** Developed advanced process control logic using **Unity Pro (Schneider Electric)**, featuring **PID controllers** for system stability and setpoint tracking.
* **Advanced SCADA Interface:** Engineered a high-performance HMI/SCADA dashboard on **CitectSCADA 2016**. Utilized **Genies & SuperGenies** to optimize object management and ensure system scalability.
* **Seamless System Integration:** Implemented **KEPServerEX (OPC DA)** as a central gateway to bridge communication between the PLC Simulator and SCADA software.
* **Data Logging & IIoT Connectivity:** * Automated historical data logging via **SQL/ODBC** for performance analysis and auditing.
    * Integrated **MQTT protocol** to push operational telemetry to the Cloud, enabling secure remote monitoring and IIoT capabilities.

## 🛠 Technology Stack
* **PLC Software:** Schneider Electric Unity Pro (Control Expert).
* **SCADA Software:** CitectSCADA 2016.
* **Connectivity Tools:** KEPServerEX, MQTT Broker, MySQL/SQL Server.
* **Protocols:** Modbus TCP, OPC DA, MQTT.

## 📐 System Architecture
The system follows a multi-tier industrial architecture:
`Field Devices (PLC) <-> OPC Gateway (KEPServerEX) <-> SCADA (Citect) <-> Database (SQL) & Cloud (MQTT)`

* [View Detailed System Architecture](Technical_Report.pdf)

## 📺 Demo
* [Comprehensive Project Demo (Video/Documentation)](https://drive.google.com/drive/folders/1uu_BLxRKORHPv0vxZrhQaRKmCN2-QV4v?usp=drive_link)

---
**Author:** Hoang Luu An Thai  
**Field:** Automation & Control Engineering
