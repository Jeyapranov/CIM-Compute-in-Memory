# Reconfigurable 10T SRAM 2x2 Array for In-Memory Computing

## 📜 Abstract
This project presents the design of a **10T Compute-in-Memory (CIM) SRAM cell** and a 2x2 array implemented in **90nm technology**. The design addresses the memory-processor bottleneck in von Neumann architectures by enabling logical operations (AND) directly within the memory array.

The proposed topology features fully decoupled read/write paths and uses high-threshold NMOS transistors to reduce leakage, making it highly suitable for low-power AI and edge computing applications.

## 🚀 Key Features
- **Technology:** 90nm CMOS (Cadence Virtuoso)
- **Topology:** 10-Transistor (10T) Bitcell with decoupled paths
- **Operations:**
  - Standard SRAM Storage (Read/Write)
  - In-Memory Computation (Bit-wise AND operation)
- **Efficiency:** ~22% power saving compared to standard CIM designs

## 📊 Performance Metrics
| Parameter | Single Cell Value | 2x2 Array Value |
| :--- | :--- | :--- |
| **Power Consumption** | 17.06 µW | 80 µW |
| **Read Access Time** | 20 ps | 40 ps |
| **Write Access Time** | 63 ps | 83 ps |
| **Read SNM** | 439 mV | - |
| **Hold SNM** | 508 mV | - |

## 🛠️ Tools Used
- **Design:** Cadence Virtuoso (Schematic & Layout)
- **Simulation:** Spectre
- **Waveform Viewing:** Cadence ViVA

## 📸 Results
### 10T SRAM Cell Schematic
*(Place your schematic screenshot in the Images folder and name it 'schematic.png', then uncomment the line below)*
### CIM Operation Waveforms
*(Place your waveform screenshot in the Images folder and name it 'waveform.png', then uncomment the line below)*
## 👥 Team
- **Jeyapranov R**
- Abirami S
- Magesh Kumar E
- Narmatha B
- **Guide:** Dr. P. Deepa (Associate Professor, ECE, GCT Coimbatore)