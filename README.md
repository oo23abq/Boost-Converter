# Boost-Converter-PCB
simple design of a boost converter PCB in kicad


```markdown
## Repository Structure

```text
├── docs/                               # General Documentation  
│   └── testreport.txt                  # Lab Test Report  
├── kicad/                              # KiCAD Project Files 
│   ├── Boost Converter.kicad_pcb       # PCB Board File
│   ├── Boost Converter.kicad_sch       # Schematic File 
│   ├── bom.csv                         # Bill of Materials
│   ├── gerbers/                        # Manufacturing Files 
│   │   └── boost.zip                   # Gerber and NC Drill Archives 
│   └── images/                         # 3D Renders 
│       ├── boostconverter_bottom.png   # Bottom Layer 
│       └── boostconverter_top.png      # Top Layer 
├── ltspice/                            # Analogue Simulation 
│   ├── schematic.asc                   # LTspice Schematic
│   └── waveform.asc                    # Plot pane waveform
├── testing/                            # Lab Testing
│   ├── oscilloscopeinput.png           # Input Voltage Waveform  
│   ├── oscilloscopeoutput.png          # Output Voltage Transient Response
│   └── testsetup.png                   # Bench test setup 
├── LICENSE                             # MIT License File 
└── README.md                           # Project Guidance / Info 
