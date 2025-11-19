# Emertxe-PIC16F877A-Washing-Machine
#**Emertxe internship project – Embedded C and PIC16F877A (PICSimLab) washing machine simulation**

---

This is one of the **Embedded Internship Projects** completed during the internship at **EMERTXE Information Technologies Pvt. Ltd.**

---

## **📝 Introduction**

This project implements a **washing machine controller** that can perform **washing**, **rinsing**, and **dry spinning** operations.
The intelligence of the machine is driven by the **PIC16F877A microcontroller**, which executes a sequence of instructions based on the washing mode selected.

A washing machine is an electromechanical system designed to wash clothes such as shirts, towels, curtains, and bed sheets.
Traditional washing requires water as the primary cleaning medium, unlike dry cleaning machines which use special chemicals.

In this project, the PIC microcontroller controls every step of the machine—from **power-on**, **door detection**, **water level sensing**, **wash cycle**, **rinse cycle**, and **spin cycle**—simulated using **PICSimLab**.

---

## **🛠 Installation Requirements**

To run this project, you will need:


*[ **MPLAB X IDE** ](https://www.microchip.com/en-us/development-tools-tools-and-software/mplab-x-ide?gclid=Cj0KCQjwtrSLBhCLARIsACh6Rmj98yI7_Y5H--lwe8m4DN3FVB0o-k4u7y-e0-T-w_9Cct4qIL2pq20aAkIFEALw_wcB#tabs)
* [**MPLAB XC8 Compiler**](https://www.microchip.com/en-us/development-tools-tools-and-software/mplab-xc-compilers?gclid=Cj0KCQjwtrSLBhCLARIsACh6Rmj-KmEgeZLWYdpD2qr2bs3wJx5kiOpLbDUEuGerZoyp6GZ4tR-WrMQaAltBEALw_wcB)
* [**PICSimLab**](https://sourceforge.net/projects/picsim/) (Simulator)

---

## **🖼 Screenshots**

Include your screenshots here after uploading them to GitHub.
Suggested screenshot labels:

* **POWER ON Screen**
  <img width="1048" height="758" alt="image" src="https://github.com/user-attachments/assets/73dfa2d2-0c48-4da2-8484-1459c5ce61e1" />

* **DOOR OPEN Display**
  <img width="1048" height="758" alt="image" src="https://github.com/user-attachments/assets/df7e8465-9f5f-42b9-b8c0-91b590c6a937" />

* **WATER LEVEL – Screen 1**
  <img width="1048" height="758" alt="image" src="https://github.com/user-attachments/assets/27624597-3229-4616-b892-e4cf0d9c62e7" />

* **WATER LEVEL – Screen 2**
  <img width="1048" height="758" alt="image" src="https://github.com/user-attachments/assets/66c4c19d-2a6e-4b14-bf2d-1ac1f8599402" />

* **START/STOP Screen**
  <img width="1048" height="758" alt="image" src="https://github.com/user-attachments/assets/ce316eda-72d3-4b44-b825-b6951ca6d70b" />


---

## **▶️ Steps to Run the Project**

Follow these steps to build and simulate the project:

1. **Download** or clone the project ZIP.
2. **Extract** all files.
3. Open **MPLAB X IDE → File → Open Project → Select extracted folder → Open Project**.
4. Once opened, right-click the project → **Batch Build** to compile.
5. After successful build, a **HEX file** will be generated in the project directory.
6. Open **PICSimLab**, select:

   * **Board:** PICGenios
   * **Microcontroller:** PIC16F877A
7. In PICSimLab, open **File → Load HEX** → browse and load the generated HEX file.
8. Use the defined switches in PICSimLab to observe different washing machine program states on the LCD.

---

## **🎬 Demo Video**

Watch the complete working demo on YouTube:
👉  https://youtu.be/TPzTH5Z35Sc?si=T4yJVCx_e3F_Q1I2

---

## **📚 Documentation**

Useful documentation related to this project:

* PICSimLab Docs (PICGenios Board)
  [https://lcgamboa.github.io/picsimlab_docs/0.8.9/PICGenios.html](https://lcgamboa.github.io/picsimlab_docs/0.8.9/PICGenios.html)

* PICSimLab Boards Overview
  [https://lcgamboa.github.io/picsimlab_docs/0.8.9/Boards.html#x17-160004](https://lcgamboa.github.io/picsimlab_docs/0.8.9/Boards.html#x17-160004)

* LCD Datasheet (HD44780)
  [https://www.sparkfun.com/datasheets/LCD/HD44780.pdf](https://www.sparkfun.com/datasheets/LCD/HD44780.pdf)

* PIC16F877A Microchip Datasheet
  [https://ww1.microchip.com/downloads/en/devicedoc/39582b.pdf](https://ww1.microchip.com/downloads/en/devicedoc/39582b.pdf)

---

## **🌍 Environment Variables**

To run this project in MPLAB, ensure required **plugins** and **toolchains** are correctly installed from MPLAB's Tools → Options menu.

---

## **📩 Feedback**

If you have any questions, improvements, or issues, feel free to reach out:

📧 [puttugurusai@gmail.com](mailto:puttugurusai@gmail.com)

---
 
Just tell me — I’ll prepare everything.
