5G - project

This project explores 5G network architecture, including the 5G Core (5GC), Service-Based Architecture (SBA), and key network functions. It provides an analysis of advanced 5G technologies such as Network Slicing, CUPS, and high-speed low-latency communication services.

 > Ubuntu 22.04 LTS :  Operating system used for development and execution.

 > Python 3.x :   Programming language used to implement the variable load ramp algorithm.

 > NumPy :   Numerical computing library for load calculations.

 > Matplotlib :  Plotting library used for visualizing load and rate graphs.

 > Pandas :  Data analysis and manipulation library.

 > Visual Studio Code (VS Code) :   Source code editor used for development.

 > Git :  Version control system for tracking project changes.

 > GitHub :   Platform used for source code management and project hosting.

 > Terminal (Bash) :   Used for executing scripts and managing the development environment.

ASSIGNMENT 1 :

This project implements a variable load ramp mechanism to gradually increase or decrease system load and monitor its behavior over time. It analyzes and visualizes the load rate using graphical plots, helping evaluate system performance under dynamic load conditions.

Features:

* 5G Core Network (5GC) Architecture Analysis
* Service-Based Architecture (SBA) Implementation Study
* Control and User Plane Separation (CUPS)
* Network Function Analysis (AMF, SMF, UPF, PCF, NRF)
* Network Slicing Concepts and Applications
* High-Speed Data Communication Support
* Low-Latency Communication Framework
* Enhanced Mobile Broadband (eMBB) Analysis
* Massive Machine-Type Communication (mMTC) Support
* Ultra-Reliable Low-Latency Communication (URLLC) Study
* Comparison between 4G EPC and 5G Core Network
* Performance and Scalability Evaluation

Inference:

The Variable Load Ramp Implementation and Rate Analysis project demonstrates the ability to control and monitor load variations in a systematic manner. The results show that the load follows the defined ramp profile accurately, enabling smooth transitions, stable system operation, and effective performance analysis through graphical visualization of load and rate characteristics.

ASSIGNMENT 2 :

To deploy the Open5GS User Plane Function (UPF) or the complete Open5GS Core Network using Docker containers on Ubuntu Linux and verify that all Network Functions (NFs) successfully register with the Network Repository Function (NRF). The objective is to understand containerized deployment of the 5G Core, monitor NF  registration, and ensure successful communication between the deployed network functions

Features:

*Containerized deployment of Open5GS 5G Core Network Functions using Docker.
*Independent UPF virtualization for flexible user-plane scaling.
*Support for complete 5G Core functions including NRF, AMF, SMF, UPF, UDM, and AUSF.
*Implementation of 3GPP Service-Based Architecture (SBA).
*Automatic Network Function registration with the NRF.
*Dynamic service discovery among Network Functions.
*One-command deployment using Docker Compose.
*Scalable and modular cloud-native architecture.
*Secure communication through Docker network isolation.
*Verification of NF registration using logs and API responses.
*Support for cloud and edge computing environments.
*Simplified maintenance, upgrades, and container management.

Inference:

The deployment of the Open5GS 5G Core as Docker containers successfully demonstrates a cloud-native approach to implementing 5G network functions. By containerizing components such as NRF, AMF, SMF, and UPF, the core network becomes more portable, scalable, and easier to manage compared to traditional deployments. Successful registration of network functions with the NRF confirms proper Service-Based Architecture (SBA) operation and enables dynamic service discovery among network functions. The project shows that containerization reduces deployment complexity, improves resource utilization, and supports flexible scaling, making it suitable for modern 5G and edge-cloud environments. Overall, the implementation validates the feasibility and effectiveness of running a complete 5G Core Network using Docker-based virtualization


