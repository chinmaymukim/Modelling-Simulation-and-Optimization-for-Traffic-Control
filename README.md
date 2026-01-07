# 🚦 Traffic Control Simulation
Modelling, Simulation & Optimization

Author: Chinmay Mukim
🎓 National College of Ireland | Modelling, Simulation & Optimization
🧠 Python • Simulation • Probabilistic Modeling

🔍 Overview

A traffic flow simulation project that models and optimizes vehicle movement at a school–village crossroad intersecting a busy national road during morning rush hours.

The project explores how vehicle speed, arrival rates, and driving behavior affect:

Safety (collision avoidance)

Waiting time

Travel efficiency

All conclusions are backed by multiple simulation studies and statistical analysis.

🛣️ Scenario

National Road: North–South (continuous traffic, no stopping)

Crossroad: East–West (village ↔ school)

Rush Hour: 8:30 – 9:00 AM

Traffic Volume: ~50 vehicles crossing

Traffic Lights: ❌ None

🎯 Goal:
Enable safe and efficient crossings without interrupting national road traffic.

🎯 Project Goals

Build a baseline traffic simulation

Model vehicle arrivals using probability distributions

Measure travel time, waiting time & traffic flow

Run multiple simulations to validate results

Identify a collision-free optimal configuration

⚙️ How It Works
🧠 Modeling Approach

Vehicle arrivals generated using Exponential Distribution

Randomness handled via Inverse Transform Sampling

Fixed random seed for reproducibility

Realistic vehicle dynamics (speed, braking, acceleration)

🧪 Simulation Phases
1️⃣ Baseline Simulation

⏱ Duration: 30 minutes (1800 seconds)

🚗 National road speed: 100 km/h

🚙 Crossroad speed: 50 km/h

Result

Avg travel time: ~2.75 min

Avg waiting time: ~3.1 min

✅ Stable, collision-free traffic

2️⃣ Comparative Simulation Studies
Study	Key Change	Result
Simulation 1	Higher flow & aggressive braking	❌ Collisions
Simulation 2	Reduced crossroad speed	❌ Instability
Simulation 3	Optimized speed & arrival rates	✅ Optimal

✔ Simulation Study 3 achieved safe, efficient crossings
✔ Best balance of flow, safety, and waiting time

📊 Key Results
Model	Avg Travel Time	Avg Waiting Time	Status
Baseline	~165 s	~190 s	✅ Stable
Study 1	258 s	567 s	❌ Failed
Study 2	388 s	927 s	❌ Failed
Study 3	207 s	360 s	✅ Optimal
🛠️ Tech Stack

Python

Jupyter Notebook

Simulation Modeling

Probabilistic Systems

Statistical Analysis

Data Visualization

Traffic density plots

Flow & behavior graphs

📂 Repository Structure
Traffic-Control-Simulation/
│
├── baseline_simulation.ipynb
├── simulation_study1.ipynb
├── simulation_study2.ipynb
├── simulation_study3.ipynb
├── report.pdf
└── README.md

💡 Key Takeaways

Speed alone does not guarantee safety

Inter-arrival timing is critical in crossings

Small parameter changes can cause system failure

Multiple simulations are essential for validation

🚀 Future Improvements

Multi-lane road modeling

Traffic signals & pedestrian crossings

Evening traffic scenarios

Stochastic driver behavior

Urban-scale intersection simulations

⭐ Why This Project Matters

This project demonstrates:

End-to-end simulation design

Strong analytical and optimization thinking

Real-world application of probability & modeling

📌 Relevant for roles in Data Science, Simulation, Operations Research, and Optimization.

⭐ If you like this project, consider starring the repository!
