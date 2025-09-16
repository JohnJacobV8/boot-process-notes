# Boot Process and Startup of a Computer

This document summarizes the learning from my **Software Engineering Fundamentals certification at Platzi**, about how a computer starts when the power button is pressed.  
The process is fundamental because it determines whether the system can start correctly and do so securely.  

---

## Main Stages

### 1. BIOS (Basic Input/Output System)  
- Initializes and tests basic hardware components.  
- Enables communication between the operating system and devices.  

### 2. POST (Power-On Self Test)  
- Verifies that memory, keyboard, video, and other components function correctly.  
- If an error occurs, it shows messages or beep codes.  

### 3. Bootloader  
- Program that transfers control to the operating system.  
- Examples: GRUB (Linux), Windows Boot Manager.  

---

## Default Process Flow  

1. The user presses the power button.  
2. The electrical signal travels from the power source through the circuits, starting the automatic process.  
3. BIOS is executed and runs the POST.  
4. If POST is successful, the bootloader loads the operating system into memory.  
5. The OS takes control and enables user interaction.  

---

## Cybersecurity Relevance  

Understanding this process helps identify points of vulnerability:  

- Malware in the boot sector (MBR, bootkits).  
- Manipulation of the BIOS/UEFI.  
- Security in startup settings like TPM and Secure Boot.  

---

## Conclusion  

The boot process of a computer is much more than just a black screen with text:  
It is the foundation that allows the entire system to function. Knowing it is essential to understand how our devices work and how to ensure their integrity in the context of **cybersecurity**.  

---

👉 [Visit my GitHub profile](https://github.com/JohnJacobV8)  
👉 [Connect with me on LinkedIn](https://www.linkedin.com/in/johnjacobv8)  
🌐 Languages: Spanish (native), English C1 (advanced professional)  

![rjywryjhwr](https://github.com/user-attachments/assets/f64c613e-7bb6-4270-910a-7aed2128e9cf)
