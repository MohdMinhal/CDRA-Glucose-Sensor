# Cylindrical Dielectric Resonator Antenna for Glucose Concentration
This repository contains the design and simulation of a Cylindrical Dielectric Resonator Antenna (CDRA) used for non-invasive glucose monitoring. The proposed antenna sensor detects glucose concentration by measuring the dielectric constant of blood through the placement of a thumb on the dielectric resonator.

## Table of Contents
- [Introduction](#introduction)
- [Antenna Design](#antenna-design)
- [Electromagnetic Modeling](#electromagnetic-modeling)
- [Simulation Results](#simulation-results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## Introduction
Diabetes mellitus is a chronic condition characterized by elevated blood glucose levels, which can lead to significant health risks. Monitoring blood glucose levels is crucial for effective management. Traditional methods involve invasive procedures that can be uncomfortable. This project introduces a non-invasive, cost-effective microwave resonator-based glucose sensor.

## Antenna Design
The proposed CDRA sensor consists of a cylindrical dielectric resonator made of alumina ceramic, fed by a 50Ω microstrip line. The sensor operates at a frequency of 4.155 GHz and has dimensions suitable for portable use.

**Antenna Parameters:**
- Substrate: Rogers RT/Duroid 5880
- Dielectric Resonator: Alumina ceramic
- Substrate Dimensions: 60 x 60 x 1.52 mm
- Resonator Dimensions: Height 10 mm, Radius 10 mm

## Electromagnetic Modeling
The human thumb model used for simulation is based on the Cole-Cole model, which accurately represents the complex permittivity of blood as a function of glucose concentration. The EM model was created using CST Microwave Studio.

## Simulation Results
Simulations show a shift in resonance frequency corresponding to different glucose concentrations. The results indicate approximately linear variation in resonant frequency with increasing glucose levels, demonstrating the sensor's potential for non-invasive glucose monitoring.

## Conclusion
The CDRA-based glucose sensor effectively detects changes in blood glucose concentration through non-invasive means, making it a promising tool for diabetes management.

## Usage
To use the design files and run simulations:
1. Clone the repository:
    ```sh
    git clone https://github.com/MohdMinhal/CDRA-Glucose-Sensor.git
    ```
2. Open the project files in CST Microwave Studio.
3. Run the simulations using the provided setup and parameters.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
