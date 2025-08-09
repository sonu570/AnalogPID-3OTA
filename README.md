# AnalogPID-3OTA

This project was carried out as part of my research work under the guidance of a professor Dr. Ajisek Raj in the Department of Electrical Engineering. The goal was to design and implement the cheapest possible PID controller using Operational Transconductance Amplifiers (OTAs), achieving high performance while keeping component costs minimal.

The work was conducted in two parts:

CMOS-based PID Controller

Implemented a custom CMOS design of the PID controller in Cadence.

Developed the complete circuit code for simulation.

Performed optimization to minimize peak overshoot, rise time, and steady-state error (ESS).

LM13700-based PID Controller

Built a hardware implementation using the LM13700 OTA IC.

The plant utilized 3 OTAs, while the controller consisted of 4 OTAs.

Tuned the design for optimal transient performance by reducing overshoot, improving rise time, and minimizing ESS.

This research was an enriching experience, allowing me to practically implement concepts from a research paper, optimize them, and verify results both in simulation (Cadence) and hardware (LM13700).
