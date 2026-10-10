# Qiskit Fall Fest 2026 at IISER Kolkata

Welcome to the repository for **Qiskit Fall Fest 2026**, hosted by IISER Kolkata and supported by IBM Quantum.

This event is an immersive, hands-on introduction to quantum information and quantum computing. Participants will build and run quantum circuits with [Qiskit](https://www.ibm.com/quantum/qiskit), explore quantum foundations, and work through practical labs.

## Event Highlights

- IBM Quantum industry expert talk and faculty panel discussion
- Hands-on workshops covering Qiskit and quantum computing
- Labs on quantum teleportation, the Stern-Gerlach experiment, VQE, QKD, QFT, and phase estimation
- Surprise challenge with official Qiskit swag
- Digital certificates and IBM Quantum learning material

## Schedule

| Day | Date | Time | Venue | Sessions |
| --- | --- | --- | --- | --- |
| Day 0 | Saturday, October 10 | 9:00 PM onwards | MN Saha Auditorium | Kick-off, Why Quantum?, and environment setup |
| Day 1 | Sunday, October 11 | 10:00 AM-12:00 PM and 2:00-5:00 PM | MN Saha Auditorium | Quantum foundations, Qiskit 101, and hands-on labs |
| Day 2 | Monday, October 12 | 9:00 PM-12:00 AM | MN Saha Auditorium | VQE and Qiskit MCP |
| Day 3 | Tuesday, October 13 | 6:30-8:30 PM | G06 | IBM industry expert talk and faculty panel |
| Day 4 | Wednesday, October 14 | 7:15 PM-11:30 AM | MN Saha Auditorium | QKD, QFT, and phase estimation |

See the [full detailed schedule](https://slashdot-iiserk.github.io/qiskit_fallfest/?utm_source=readme#schedule).

## Repository Contents

```text
.
├── Day_0/
│   └── QFF_2026_Day0.ipynb       
└── Day_1/
    ├── Qiskit_101/               # Qiskit fundamentals
    ├── quantum_teleportation/    # Quantum teleportation lab
    └── stern_gerlach/            # Stern-Gerlach experiment lab
```

More workshop material will be added as the event progresses.

## Prerequisites

- Basic Python knowledge
- No prior quantum mechanics experience is required
- A laptop and an extension cable for the interactive notebook sessions

All examples in the Day 0 setup check run on a local simulator, so an IBM Quantum account is not required to get started.

## Getting Started

1. Clone or download this repository.
2. Install Python 3.10 or later (python.org) if you don't have it.
3. Open a terminal (Command Prompt or PowerShell on Windows) and create a virtual environment:
   python -m venv qiskit-env
4. Activate it:
   Windows: qiskit-env\Scripts\activate
   Mac/Linux: source qiskit-env/bin/activate
4. Install the packages:
   pip install 'qiskit>=2.1.0' 'qiskit-ibm-runtime>=0.40.1' 'qiskit-aer>=0.17.0' 'numpy' 'pylatexenc' matplotlib jupyter 
2. Open `Day_0/QFF_2026_Day0.ipynb` in Jupyter notebook or VS Code.
3. Run the notebook from top to bottom.
4. Restart the kernel when prompted after installing the packages.
5. Continue with the Day 1 notebooks once the environment check passes.

The setup notebook installs the required packages, including Qiskit, Qiskit Aer, and Matplotlib. Python 3.10 or later is recommended.

## Registration

Participation is free for IISER Kolkata students, including BS-MS, MS, iPhD, PhD, and research scholars.

[Register for Qiskit Fall Fest 2026](https://slashdot-iiserk.github.io/qiskit_fallfest/register.html?utm_source=readme)

## Organisers

Hosted by IISER Kolkata and organised by the **Slashdot Coding and Design Club**, with support from IBM Quantum.