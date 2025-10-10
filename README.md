Monopole Antenna (3.3 GHz)

Project Overview

This repository contains the design and simulation files for a monopole antenna operating at 3.3 GHz.  
The project was carried out using ANSYS HFSS, focusing on geometry design, solver setup, and performance analysis.

---

🛠 Tools Used
- ANSYS HFSS – for design and electromagnetic simulation  
- CSV/Excel – for post-processing results  

---

📂 Repository Contents
- monopole.aedt → HFSS project file  
- monopole_geometry.step → exported 3D geometry  
- solver_settings.txt → solver setup (frequency range, boundary conditions, mesh, etc.)  
- s11_plot.png` → return loss plot (S11 vs frequency)  
- s11_data.csv → exported S11 data  
- radiation_pattern.png → far-field radiation pattern  
- README.md` → project documentation  

---

📈 Results
- The antenna was designed for 3.3 GHz operation.  
- Simulation results include return loss (S11) and radiation patterns.  
- Geometry and settings are provided so others can reproduce the design.

---

Notes
- Results may vary depending on mesh settings and boundary conditions.  
- Contributions and suggestions are welcome.

I constructed a monopole antenna in order to investigate its performance and radiation properties for wireless communication applications. For frequencies like 3.3 GHz, which are frequently utilised in contemporary telecom systems, the monopole design is straightforward, economical, and effective.  Additionally, it offers an omnidirectional emission pattern, which qualifies it for use in mobile communication systems and base stations.  Building it helped me understand antenna design principles, impedance matching, and simulation analysis using HFSS.
