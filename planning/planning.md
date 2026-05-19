# Detailed Project Planning

## Week 1 – Project Research and Circuit Selection

During the first week, research was conducted on possible electronic clock designs using TTL logic ICs. Different existing projects and clock implementations were analyzed to determine feasibility, complexity and required components. The TTL Clock project by Sergey Kiselev was selected as the main reference design because of its modular structure and use of classic 74xx TTL integrated circuits.

Project goals were defined during this phase, including the design of a working TTL digital clock, development of a custom PCB using Altium Designer, creation of technical documentation, design of a custom enclosure in Fusion 360 and publishing all project files on GitHub. The initial project scope, estimated budget and overall planning were also established.

---

## Week 2 – Datasheet Analysis and Component Research

During week 2, all required components were researched and analyzed using manufacturer datasheets. Components such as the SN74LS90 decade counters, SN74LS47 display drivers, SN74LS00 NAND gates, resistor arrays, 7-segment displays, capacitors and oscillator components were studied in detail.

Special attention was given to electrical specifications, package dimensions, compatibility with TTL logic, through-hole footprints and component availability at DigiKey. Delivery times and pricing were also compared to optimize the project budget.

---

## Week 3 – Altium Libraries and Footprints

During this week, all necessary libraries and PCB footprints were prepared in Altium Designer. Component footprints were manually verified using datasheets to ensure correct pin spacing, package dimensions and soldering reliability.

Several custom schematic symbols and footprints were created where necessary. The Altium project structure was organized and optimized to simplify future schematic modifications and PCB routing.

---

## Week 4 – Schematic Design

The electronic schematic of the TTL clock was created in Altium Designer. The schematic includes the oscillator section, frequency divider stages, counter circuits, display drivers, power supply connections and reset logic.

All electrical connections were carefully verified to prevent routing and logic errors during the PCB design stage. Preliminary Electrical Rule Checks (ERC) were performed to validate the design and identify possible issues.

---

## Week 5 – PCB Design Start

The PCB design phase started during week 5. The initial PCB dimensions were defined and the first component placement was completed.

Special attention was given to routing simplicity, signal flow, display alignment, accessibility of components and through-hole soldering convenience. Multiple placement iterations were performed to improve the overall layout and optimize the mechanical organization of the board.

---

## Week 6 – PCB Routing and Optimization

During this week, the PCB routing process was finalized. Connections between all TTL ICs and display drivers were completed while maintaining a clean routing structure, reliable power distribution and proper spacing between traces.

Additional optimization tasks included adjusting track widths, improving ground connections, reorganizing signal traces and correcting final footprint issues. A complete Design Rule Check (DRC) was performed to validate the PCB before production.

---

## Week 7 – PCB Finalization and Gerber Generation

The PCB design was finalized and prepared for manufacturing. Final PCB inspections were carried out, including verification of silkscreen labels, component placement and mounting holes.

Gerber manufacturing files were generated and carefully reviewed before submission to PCBWay for production.

---

## Week 8 – Ordering PCB and Components

The PCB was ordered through PCBWay while all electronic components were ordered from DigiKey. The complete Bill of Materials (BOM) was finalized, including manufacturer information, DigiKey part numbers, component quantities and pricing.

Shipping costs and estimated delivery times were also analyzed and documented as part of the project planning.

---

## Week 9 – PCB and Component Delivery

The manufactured PCB and all ordered components were delivered and inspected carefully. All received parts were checked for correct quantities, package types, physical condition and compatibility with the PCB design.

The PCB itself was visually inspected for manufacturing defects, broken traces, incorrect drilling or alignment issues before assembly started.

---

## Week 10 – Assembly and Soldering

The assembly phase started during week 10. Through-hole components were soldered onto the PCB while following the schematic and PCB documentation carefully.

Special attention was given to IC socket placement, display alignment, power supply soldering and connector installation. The assembly process was documented with photographs for the GitHub repository.

---

## Week 11 – Testing and Debugging

The assembled clock was tested extensively for functionality. Testing included power verification, oscillator operation, counter functionality, display operation and reset logic testing.

Detected issues were analyzed and corrected through systematic debugging procedures using signal measurements and visual inspection techniques.

---

## Week 12 – Final Optimization and Documentation

During the final stage of the project, the hardware and documentation were optimized and finalized. Final corrections and improvements were applied to the PCB assembly while the GitHub repository structure was fully organized.

The README documentation was written entirely in English and expanded with technical specifications, project planning, cost estimation, PCB information, component selection and testing information.

Additional screenshots, PCB renders, schematics, STL files, datasheets and project documentation were uploaded to GitHub. The project was then fully prepared for final submission.
