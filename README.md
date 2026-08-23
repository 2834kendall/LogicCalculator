# LogicCalculator

A modular **8-bit Function Calculator and Plotter** developed in **LogicCircuit** for the **EIF205 – Computer Architecture** course at Universidad Nacional, Brunca Regional Campus.

The project focuses on the design and implementation of digital circuits using combinational and sequential logic to evaluate and graph mathematical functions. The system follows a hierarchical modular architecture and is built without using prebuilt RAM or ROM components. :contentReference[oaicite:1]{index=1}

---

## Features

- 8-bit Arithmetic Logic Unit (ALU)
- Line function evaluation (`Y = mX + b`)
- Parabola evaluation (`Y = aX² + b`)
- Absolute value function evaluation (`Y = |X| + b`)
- Two's complement arithmetic
- Scalable LED display (8×8, 16×16, and 32×32)
- Automatic plotting sequencer
- Seven-segment display monitoring
- Out-of-range detection
- Modular and hierarchical circuit design :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4} :contentReference[oaicite:5]{index=5}

---

## Technologies

- LogicCircuit
- Digital Logic Design
- Combinational Circuits
- Sequential Circuits
- Flip-Flops
- Multiplexers
- Decoders
- Counters
- Finite State Machines

---

## Project Structure

```text
LogicCalculator/
├── docs/          # Project documentation
├── circuit     # LogicCircuit (.circ) file
└── README.md
```

---

## Git Workflow

```text
main
└── dev
    ├── feature/...
    ├── feature/...
    └── feature/...
```

Development is performed on `feature/*` branches, which are merged into `dev`. After testing and validation, `dev` is merged into `main`.

---

## Team Members

- Kendall Badilla
- Jordy Estrada
- Aaron Valverde

---

## Course Information

**Course:** EIF205 – Computer Architecture  
**Institution:** Universidad Nacional – Brunca Regional Campus  
**Academic Term:** II Semester 2026 :contentReference[oaicite:6]{index=6}
