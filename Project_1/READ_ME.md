# LIST OF TOPICS - TARGET
1. How to communicate between Modbus Slave and Modbus Pool in the **same local host** (Depending on your system: Windows, Linux, MAC)
2. How to communicate between Modbus Slave and Modbus Pool in the **different machines** (1: Local host - 2: Virtual Machine)
3. How to build a **website** that can communicate with a **Modbus Slave** (which is located on your local host)
4. How to communicate between **SCADA on iFIX** and **Modbus Poll** (Modbus Slave --> Modbus Poll --> SCADA --> HMI)
5. How to communicate between **PLC SIEMENS** to **Modbus Poll** on simulation mode
6. How to communicate between **ESP32** and **Modbus Poll** on **IoT Gateway**
---
# CMD GUIDE
- ping (Example: ping 192.168.0.1) 
- ipconfig (Example: ipconfig)
- telnet (Example: telnet 192.168.0.1 302)
# ERRORS - SOLUTION
1. If you cannot connect the Modbus Poll and Modbus Slave using TCP/IP protocol
   1. Check the Windows Defender Firewall - Turn off the firewall
   2. Check if there is any client that connects on the same PORT or IP Address
---
## 1️⃣ FIRST TASK - Modbus (Poll <-> Slave) in the same local host
### Description

### Step-by-step
1. Open your operating system (you can choose a local host or a virtual machine) 
2. Install the Modbus tools (including Modbus Poll, Modbus Slave, Modbus Scan) - https://www.modbustools.com/download.html
3. Open and Run Modbus Poll and Modbus Slave in the same place
4. Check and configure the IP Address of Modbus Poll and Slave --> Make sure both Modbuses have the same IP Address
5. Write the data on the Modbus Poll and send to the Modbus Slave
--- 
## 2️⃣ SECOND TASK - Modbus (Poll <-> Slave) in the different machines
### Description

### Step-by-step
**Attention:** Where contain the Modbus Slave, we must use that IP Address

--- 
## 3️⃣ THIRD TASK - (Website <-> Slave) in the local host

--- 
## 4️⃣ FOURTH TASK - (iFIX SCADA <-> Poll) on iFIX workspace

--- 
## 5️⃣ FIFTH TASK - (PLC SIEMENS <-> Poll) on TIA PORTAL simulation
### References
- https://www.youtube.com/watch?v=YuRjIp0cipA

--- 
## 6️⃣ SIXTH TASK - (ESP32 <-> Poll) IoT Gateway

--- 
