# ER-Drill-Simulator
An AI-powered emergency room operational simulator designed to train healthcare staff by generating chaotic clinical crises based on real-time shift circumstances.

## Live Demo
**Link:** er-drill-simulator.vercel.app



## Project Overview
Hospital emergency departments constantly face severe overcrowding, dangerous patient surges, and unpredictable staffing shortages. While clinical training focus heavily on textbook medical procedures and accurate diagnoses, healthcare providers rarely practice how to behave under the chaos of managing an understaffed floor during a multi-patient crisis. This can deverely impact the quality of care the patients receive in times of critical need. This project was made in hopes of fixing this issue and allowing trainees to receive more practice so they are better prepared for situations. 

**ERDS** addresses this gap. It is an on-demand operational simulator for ER charge nurses and senior residents. Instead of presenting predictable, pre-scripted scenarios, the application takes into account the live staffing variables (available nurses, attending physicians, and current floor volume) to generate chaotic, high-fidelity crisis scenarios. It then utilizes an AI-assisted evaluation engine to score the user's response and how well they delegate the resources given.



## Key Features
- **Dynamic Variable Integration:** Alters and shapes clinical crises directly to the structural limitations of the current shift.
- **Realistic Crisis Generator:** Simulates sudden patient crashes, overlapping emergencies, and personnel constraints using advanced language modeling.
- **AI-Assisted Grading Engine:** Evaluates user responses on a rigid clinical scorecard, grading Triage Logic, Resource Delegation, and Speed.
- **Zero-Footprint Deployment:** Lightweight web interface designed for instant deployment and usage on any desktop or mobile clinical workstation.



## Technical Architecture & Stack
This project was constructed using a modern, decoupled web architecture to maximize performance, deployment speed, and maintenance visibility.
- **Frontend Framework:** React + Vite (structured for responsive and clean UI/UX components).
- **Styling:** Tailwind CSS (configured with high-contrast, alert-driven design patterns).
- **Core Logic & AI Orchestration:** Built using an AI-assisted engineering workflow. The application features manual code refactoring to integrate client-side text parsing, custom validation logic, and automated state management.
- **Hosting & Deployment:** Automated continuous integration (CI/CD) hosted globally on **Vercel** with version control managed entirely via **GitHub**.



## License
Distributed under the MIT License. See `LICENSE` for more information. This project is intended strictly for educational, research, and simulation purposes.
