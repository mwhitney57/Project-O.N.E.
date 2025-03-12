# Project-O.N.E.
My first major personal project: Project O.N.E. (Operation Nexus Equilibrium). A custom-engineered door lock solution with biometric identity verification, full remote control, two-way communication, and more, all contained within 3D-printed housings.

View all of the individual parts of Project O.N.E. at their respective repositories:
- [System](https://github.com/mwhitney57/Project-O.N.E.-System)
  - Run on the Raspberry Pi -- controls the electromagnetic solenoid that locks the door. Communicates with the server to handle remote commands sent from the CLI or Controller application.
- [Server](https://github.com/mwhitney57/Project-O.N.E.-Server)
  - Handles communication between the server and all other clients, including connections from the CLI and Controller application.
- [CLI](https://github.com/mwhitney57/Project-O.N.E.-CLI)
  - A web command-line interface (CLI) for controlling the system from anywhere, on any device with a browser.
- [Controller](https://github.com/mwhitney57/Project-O.N.E.-Controller)
  - A Java-based application for Windows computers with a user-friendly interface for quick and easy control of the system.
