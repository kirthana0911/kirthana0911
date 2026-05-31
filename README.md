<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0f1e,50:0d2137,100:0a1628&height=200&section=header&text=R.S.%20Kirthana&fontSize=52&fontColor=38bdf8&animation=fadeIn&fontAlignY=35&desc=ECE%20Engineer%20%7C%20VLSI%20%26%20Embedded%20Systems%20%7C%20IoT%20Developer&descAlignY=58&descSize=15&descColor=7dd3fc" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=800&lines=VLSI+%26+Digital+System+Design+%F0%9F%94%AC;Embedded+Systems+%7C+IoT+Developer+%F0%9F%94%A7;SoC+Physical+Implementation+%F0%9F%A7%AC;RF+%26+Antenna+Design+%F0%9F%93%A1;Building+Silicon+%26+Systems+%F0%9F%9A%80)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kirthanars-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kirthanars)
[![Gmail](https://img.shields.io/badge/Gmail-kirthanars5599%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kirthanars5599@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-kirthanars-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kirthanars)
[![Profile Views](https://komarev.com/ghpvc/?username=kirthanars&label=Profile+Views&color=38bdf8&style=for-the-badge)](https://github.com/kirthanars)

</div>

---

## `~/about_me` — Who Am I?

```verilog
// ============================================================
//  MODULE : engineer
//  AUTHOR : R.S. Kirthana
//  ROLE   : Electronics & Communication Engineer
// ============================================================

module kirthana (
  input  wire  curiosity,
  input  wire  challenges,
  output reg   innovations,
  output reg   solutions
);

  // === Identity ===
  parameter NAME      = "R.S. Kirthana";
  parameter LOCATION  = "Tamil Nadu, India";
  parameter DEGREE    = "B.E. – Electronics & Communication Engineering";
  parameter COLLEGE   = "K. Ramakrishnan College of Engineering";
  parameter CGPA      = 7.61;

  // === Core Stack ===
  parameter HARDWARE  = {"ESP32", "ESP8266", "Arduino", "STM32"};
  parameter HDL       = {"SystemVerilog", "VHDL"};
  parameter EDA_TOOLS = {"Xilinx Vivado", "KiCad", "Proteus"};
  parameter CLOUD     = {"AWS Lambda", "DynamoDB", "Amazon Lex", "S3"};

  // === Currently Learning ===
  parameter LEARNING  = {
    "VLSI Physical Design",
    "SoC Floorplanning & Timing",
    "ARM Cortex-M (STM32 + RTOS)",
    "AWS Serverless Architecture"
  };

  // === Fun Fact ===
  parameter FUN_FACT  = "Built a kart before building a circuit! 🏎️";

  always @(posedge curiosity) begin
    innovations <= challenges ? 1'b1 : 1'b0;
    solutions   <= 1'b1;  // Always outputs solutions
  end

  // Motto: Design. Simulate. Innovate. 🔌
endmodule
```

---

## `~/tech_stack` — Tools of the Trade

### 🖥️ Programming Languages

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FF6F00?style=for-the-badge&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-4B0082?style=for-the-badge&logoColor=white)

### ⚡ Hardware & Embedded Platforms

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878A?style=for-the-badge&logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Antenna Design](https://img.shields.io/badge/Antenna%20Design-607D8B?style=for-the-badge&logoColor=white)

### 🔬 EDA & Design Tools

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Xilinx](https://img.shields.io/badge/Xilinx%20Vivado-E01F27?style=for-the-badge&logo=amd&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-1565C0?style=for-the-badge&logoColor=white)
![Arduino IDE](https://img.shields.io/badge/Arduino%20IDE-00878A?style=for-the-badge&logo=arduino&logoColor=white)

### ☁️ Cloud — AWS

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![AWS S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Amazon Lex](https://img.shields.io/badge/Amazon%20Lex-232F3E?style=for-the-badge&logo=amazonalexa&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF4F8B?style=for-the-badge&logo=amazonapigateway&logoColor=white)

---

## `~/projects` — Featured Engineering Work

<table>
<tr>
<td width="50%" valign="top">

### 📡 Dual Band Microstrip Patch Antenna
**RF & Antenna Design**

Designed a dual-band microstrip patch antenna on FR4 substrate operating at **5.904 GHz** and **6.036 GHz** — targeting Wi-Fi 6 and wireless communication bands.

`KiCad` `FR4 Substrate` `RF Design` `Antenna Simulation`

</td>
<td width="50%" valign="top">

### ☣️ Toxic Gas Detection System
**Embedded IoT Safety System**

Real-time gas monitoring system for sewage workers using 3 sensors (MQ-2, MQ-6, MQ-135) with ESP32. Triggers immediate safety alerts on hazardous gas detection.

`ESP32` `MQ-2` `MQ-6` `MQ-135` `IoT` `Safety Alerts`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏨 Hotel Booking Chatbot
**Serverless AWS Application**

Fully serverless chatbot for hotel room booking and real-time availability tracking, integrating Amazon Lex NLP, Lambda functions, DynamoDB, and RDS via API Gateway.

`Amazon Lex` `AWS Lambda` `DynamoDB` `RDS` `API Gateway`

</td>
<td width="50%" valign="top">

### 📋 RFID Attendance System
**IoT Automation**

IoT-based automated attendance system using ESP8266 + RFID module. Records and wirelessly transmits attendance data over Wi-Fi in real time.

`ESP8266` `RFID` `Wi-Fi` `IoT` `Automation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌧️ Smart Window System
**Sensor-Driven Embedded Control**

Automated window blinds and fan control system that responds dynamically to sunlight intensity and ambient temperature using ESP32 and multiple sensors.

`ESP32` `Temperature Sensor` `Light Sensor` `Automation`

</td>
<td width="50%" valign="top">

### 🩸 Blood Donation Management System
**Database Engineering**

Full-featured database management system for blood banks — covering donor records, appointment scheduling, and blood inventory tracking with SQL.

`SQL` `Database Design` `Relational Modeling` `DBMS`

</td>
</tr>
</table>

---

## `~/achievements` — Milestones & Recognition

<div align="center">

### 🏎️ Motorsports Engineering

| | |
|:---:|:---|
| ![Badge](https://img.shields.io/badge/NATIONAL-IKR%202024-FF4500?style=for-the-badge&logoColor=white) | **Indian Karting Race (IKR) 2024** — Powertrain team member of **TN45 Motorsports**. Contributed to drivetrain design, integration, and on-track performance testing at national level. |
| ![Badge](https://img.shields.io/badge/NATIONAL-12th%20GKDC-FF6B00?style=for-the-badge&logoColor=white) | **Go Kart Design Challenge (GKDC)** — Competed in the **12th GKDC** at Kari Motor Speedway. Handled chassis integration and motorsports engineering under real race conditions. |

<br/>

### ☁️ Technical Certifications & Training

| | |
|:---:|:---|
| ![Badge](https://img.shields.io/badge/CERTIFIED-AWS%20Foundations-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) | **AWS Foundational Certification** — Completed AWS cloud training with Wipro covering core cloud services, architecture patterns, and serverless deployment. |
| ![Badge](https://img.shields.io/badge/WORKSHOP-SoC%20Physical%20Design-7C3AED?style=for-the-badge&logoColor=white) | **SoC Physical Implementation Workshop** — Hands-on training in floorplanning, placement, routing, and timing optimization in a sponsored SoC design environment. |

</div>

---

## `~/experience` — Internships & Training

<details>
<summary><b>🏭 NLC India Limited</b> — Intern · Telecom Division</summary>
<br/>

> `Telecom Network Switching` `Communication Infrastructure` `Industrial Systems`

- Completed internship in **Telecom Network Switching Systems** and industrial communication infrastructure
- Gained hands-on exposure to large-scale network architecture and switching topologies in a live industrial environment

</details>

<details>
<summary><b>☁️ Wipro</b> — Cloud Computing Training</summary>
<br/>

> `AWS` `Cloud Architecture` `Serverless` `S3` `Lambda`

- Completed industry-level training in **Cloud Computing and AWS architecture**
- Applied learning to real projects: static website hosting on S3 and serverless chatbot on Lambda + Lex

</details>

<details>
<summary><b>⚡ Edutantr</b> — VLSI Design Training</summary>
<br/>

> `VLSI` `Digital Circuits` `SystemVerilog` `VHDL` `Simulation`

- Trained in **VLSI design fundamentals** and RTL-level digital circuit design
- Worked with hardware description languages for synthesis and functional simulation

</details>

<details>
<summary><b>🖨️ Internshala</b> — PCB Design Training</summary>
<br/>

> `KiCad` `PCB Layout` `Schematic Design` `Fabrication`

- Trained in **schematic capture and PCB layout** using KiCad
- Covered component placement, trace routing, and manufacturing design rules

</details>

---

## `~/learning` — Currently On The Bench

```
╔══════════════════════════════════════════════════════════════╗
║                   ACTIVE LEARNING QUEUE                      ║
╠══════════════════════════════════════════════════════════════╣
║  🔲 VLSI Physical Design  →  SoC Floorplanning, Timing, CTS ║
║  ⚡ Embedded Systems      →  STM32, ARM Cortex-M, RTOS       ║
║  ☁️  AWS Cloud             →  Serverless, API Gateway, RDS    ║
║  🛠️  HDL & Verification    →  SystemVerilog, Simulation       ║
║  📡 Signal Processing     →  DSP, Noise Filtering, FFT       ║
║  🖨️  PCB Design            →  KiCad, DFM, High-Speed Layout  ║
╚══════════════════════════════════════════════════════════════╝
```

---

## `~/education`

<div align="center">

| Degree | Institution | Period | Result |
|--------|-------------|--------|--------|
| 🎓 **B.E. – Electronics & Communication Engineering** | K. Ramakrishnan College of Engineering | 2023 – Present | CGPA: **7.61 / 10** |
| 📘 Higher Secondary – XII | Jawahar Matriculation Hr. Sec. School | 2022 – 2023 | **79.33%** |
| 📗 SSLC – X | Jawahar Matriculation Hr. Sec. School | 2020 – 2021 | Passed |

</div>

---

## `~/languages`

<div align="center">

![Tamil](https://img.shields.io/badge/Tamil-Native-0ea5e9?style=for-the-badge)
![English](https://img.shields.io/badge/English-Fluent-22c55e?style=for-the-badge)
![German](https://img.shields.io/badge/German-Learning%20%F0%9F%93%96-f59e0b?style=for-the-badge)

</div>

---

<div align="center">

*"Design. Simulate. Innovate."* 🔌

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1628,50:0d2137,100:0a0f1e&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
