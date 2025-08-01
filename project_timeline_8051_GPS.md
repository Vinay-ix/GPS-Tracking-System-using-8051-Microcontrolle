
# 📅 Project Timeline – 8051 GPS Tracker

A detailed timeline of milestones and development phases for the **GPS Tracker using 8051 Microcontroller**.

---

## Week 1: 📚 Problem Understanding & Requirement Analysis
- Identified the problem: need for real-time location tracking
- Defined objective: display GPS coordinates on LCD using 8051
- Researched GPS NEO-6M module, NMEA sentences, and UART

---

## Week 2: 🧩 Component Selection & Hardware Design
- Selected components: AT89S52, NEO-6M GPS, 16x2 LCD, battery
- Designed the initial block diagram
- Planned interfacing logic between GPS and 8051

---

## Week 3: 🖥️ Software Development – UART & LCD Code
- Wrote 8051 assembly code for:
  - UART initialization (9600 baud)
  - Serial data reception from GPS
  - LCD interfacing routines

---

## Week 4: 🛠️ Hardware Assembly & Interfacing
- Assembled the circuit on breadboard/PCB
- Connected GPS TX to 8051 RX via level converter
- Wired LCD to 8051 data/control pins

---

## Week 5: 🔄 Testing & Debugging
- Verified serial data reception using terminal
- Parsed NMEA `$GPGGA` sentences
- Displayed coordinates on LCD
- Handled voltage mismatch issues and GPS power supply

---

## Week 6: 🧪 Proteus Simulation & Validation
- Created simulation in Proteus using VGPS module
- Observed LCD output and UART stream
- Validated end-to-end functionality

---

## Week 7: 📖 Documentation & Report Writing
- Compiled project report and abstract
- Annotated assembly code
- Included images, block diagram, and simulation output

---

## Week 8: 🎓 Final Presentation & Submission
- Recorded demo video for evaluation
- Presented working model and flow
- Submitted report, code, and documentation

---

🎯 **Outcome**: Successfully developed a reliable and efficient GPS tracking system using the 8051 microcontroller, demonstrating real-time coordinate display and UART communication.
