# EE22005 Engineering Practice and Design (Year 2)

Coursework portfolio from my second year of BEng Integrated Mechanical and Electrical Engineering at the University of Bath (2025-26). It collects evidence of technical and professional engineering skills across electronics, programming, machine learning and sustainability.

## Highlights

### Machine learning: breast tumour classification
Classification of malignant versus benign tumours on the Breast Cancer Wisconsin (Diagnostic) dataset (569 samples, 30 features) with a feedforward neural network.
- Trained with stochastic gradient descent with momentum and a cross-entropy loss, for 200 epochs on an 80/20 split.
- Hyperparameters chosen by grid search: 10 hidden units, learning rate 0.01, batch size 32.
- Reported results: 97.4% accuracy, precision 0.98, recall 0.96, F1-score 0.97, with 5 misclassifications out of 114 test samples.
- Discussion of improvements: dropout or L2 regularisation, feature selection or PCA, ensemble methods, and more diverse patient data.
- Files: `ml_code_screenshot_1.png`, `ml_code_screenshot_2.png`

### Software design, test and validation (Python)
A program that reads temperature data from a CSV file, stores each reading as an object, converts between Celsius, Fahrenheit and Kelvin, and calculates minimum, maximum, mean and standard deviation over a chosen time range, with error handling. Designed with UML and flowcharts and tested against a test plan.
- File: `software_design_test_validation.pdf`

### PCB design and signal integrity
Improvements to a PCB layout for signal integrity: decoupling capacitors close to the microcontroller power pins, wider spacing between traces, no sharp right-angle traces, and a ground plane. Designed in OrCAD.
- Files: `pcb_layout_1.png`, `pcb_layout_2.png`, `pcb_design_screenshot.png`

### Computational simulation and signals
- Circuit simulation of a single-phase full-bridge inverter (50 Hz square wave output, triangular inductor current): `circuit_simulation.png`
- Spectrum analysis (FFT) of laboratory signals and FIR filter design.

### Personal project: energy-efficient LED lighting system
Design and evaluation of a high-efficiency switch-mode LED driver, with measurements of efficiency, power consumption and driver losses, and a regenerative design and sustainability analysis.
- Files: `led_lighting_system_report.docx`, `regenerative_design_led_project.pdf`, `sustainable_energy_management.docx`, `executive_summary_led_project.docx`

### Other evidence in the portfolio
Circular economy design (life-cycle CO2 and cost analysis of a robotic arm and a mouse robot), sustainable materials management, feasibility studies, ethics, risk, quality and project management, market analysis, product costing, standards and referencing.

## AI use
As declared in the portfolio pages, AI was used for grammar correction only.

Yassin Elhady, University of Bath
