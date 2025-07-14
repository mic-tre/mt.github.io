# Michael's TryHackMe Lab Tracker

Welcome to my technical journey. Below are my hands-on labs with notes, tools, and findings.

---

## 🧪 Lab 1: ACPI Troubleshooting  
**Goal**: Understand BIOS/UEFI power settings and ACPI tables  
**Steps**:  
- Accessed BIOS and reviewed power management settings  
- Ran `msinfo32` to locate ACPI table entries  
- Verified device states via Event Viewer  

**Findings**:  
Discovered that hybrid sleep mode was interfering with USB wake settings.

---

## 🔌 Lab 2: USB Controller Mapping  
**Goal**: Identify host controller-device connections  
**Tools Used**: USB Tree View, Device Manager  
**Steps**:  
- Mapped physical ports to controllers using USB Tree View  
- Verified high-speed transfers on specific USB 3.0 ports  
- Compared throughput using external SSD  

**Findings**:  
Confirmed which controller was used for max-speed ports and identified two legacy USB 2.0 ports.

---

## 🔐 Lab 3: Security Layering  
**Goal**: Strengthen endpoint protection  
**Tools Used**: Microsoft Defender, Malwarebytes  
**Steps**:  
- Configured real-time protection and scheduled scans  
- Ran sample EICAR tests  
- Set exclusions for system tools  

**Findings**:  
Achieved layered security with minimal system slowdown.

