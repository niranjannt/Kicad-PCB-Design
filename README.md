# Analog Signal Generator PCB - ECE 445L Project
This project involved designing a PCB for an analog signal generator using a **TM4C123GH6PM microcontroller**, an **AD5061BRJZ-1500RL7 SPI DAC**, and an **AD822ARZ op-amp** in unity gain configuration. The system allows users to generate various waveforms and adjust amplitude and frequency via a potentiometer and mode selection button.

---

## Features

- **Analog Signal Output:** Generate multiple waveforms through the DAC and op-amp while monitoring values on a TFT display.  
- **Debugging Tools:** Integrated test points, logic analyzer connections, and status LEDs for easier system verification.  
- **Power Regulation:** Linear voltage regulation with an **LP2950-33 low-dropout regulator** to convert a 3.7V battery to a stable 3.3V supply.  
- **PCB Trace Design:** Trace widths calculated based on current to ensure proper power delivery and minimal voltage drop.  
- **Component Placement:** Careful layout to minimize trace lengths and maintain signal integrity.  

---

## Design Considerations

- PCB fits into a **SERPEC 151 enclosure**, including battery mounting.  
- Full schematic and PCB layout generated after thorough review of component datasheets.  
- Bill of Materials (BoM) created to estimate cost for scaled production.  
- Electrical Rules Check (ERC) performed in KiCad to ensure proper connections and correct component specifications. Unnecessary warnings (e.g., button with no value) were approved when appropriate.  
- KiCad ensures common mistakes, such as near-missed connections, are caught before fabrication.  

---

## Skills Developed

- Embedded systems programming and interfacing  
- Analog-to-digital signal handling  
- PCB design and layout  
- Power supply design and regulation  
- Practical trace planning and signal integrity  
- BOM creation and cost estimation  

---

## Screenshot / Diagram
<img width="1322" height="947" alt="image" src="https://github.com/user-attachments/assets/a1ce2376-a20f-49a4-bd64-565442dfc9bb" />
<img width="1426" height="902" alt="image" src="https://github.com/user-attachments/assets/fcdeb751-8a66-4b84-b384-72d6f4fb9f3d" />
![Analog Signal Generator PCB](images/1764009235149.png)



---

