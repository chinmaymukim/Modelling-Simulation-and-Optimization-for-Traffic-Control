🚦 Traffic Control Simulation using Modelling, Simulation & Optimization

Author: Chinmay Mukim
Student ID: x21145024
Institution: National College of Ireland
Module: Modelling, Simulation, and Optimization

📌 Project Overview

This project focuses on designing, simulating, and evaluating a traffic control mechanism for a real-world inspired road crossing scenario. The goal was to model vehicle behavior, analyze traffic flow, and optimize crossing safety and efficiency using simulation techniques.

The scenario represents a busy national road intersecting a school–village crossroad, where traffic congestion and unsafe crossings are common during morning rush hours. Through baseline and multiple simulation studies, this project investigates how vehicle speed, arrival rates, and driving parameters impact safety, waiting time, and travel time.

🛣️ Problem Scenario

A National Road (North–South) with continuous traffic flow
A Crossroad (East–West) connecting a village and a school
Peak rush hour: 8:30 AM – 9:00 AM
Around 50 cars crossing during school hours
No traffic lights — crossing decisions depend on vehicle behavior and timing
The challenge was to enable safe and efficient crossings without stopping national road traffic.

🎯 Objectives

✔ Build a baseline traffic simulation under fixed assumptions
✔ Model vehicle arrival using probabilistic distributions
✔ Analyze travel time, waiting time, and traffic flow
✔ Conduct multiple simulation studies to test robustness
✔ Evaluate statistical significance of speed and flow changes
✔ Identify an optimal traffic configuration without collisions

🧠 Methodology

The project was executed in three structured phases:

1️⃣ Baseline Simulation

Simulation duration: 30 minutes (1800 seconds)
Vehicle arrivals modeled using Exponential Distribution
Assumed:
National road speed: 100 km/h
Crossroad speed: 50 km/h
Random seed fixed to ensure reproducibility
Vehicle dynamics tuned to avoid unrealistic crashes

📊 Outcome:

Average travel time ≈ 2.75 minutes
Average waiting time ≈ 3.1–3.2 minutes
Smooth traffic flow achieved

2️⃣ Simulation Studies (Comparative Analysis)

Three independent simulation models were implemented, each running for 30 minutes:

🔹 Simulation Study 1

Increased traffic flow
Modified speed and braking assumptions
Result: ❌ Vehicle collisions at crossroad

🔹 Simulation Study 2

Reduced crossroad speed
Adjusted acceleration/deceleration
Result: ❌ Crossroad instability remained

🔹 Simulation Study 3 (Final Model ✅)

Optimized:
Inter-arrival times
Vehicle speeds
Acceleration & deceleration parameters
Result: ✅ Collision-free, stable, and efficient traffic flow

📈 This model demonstrated the best balance between safety and efficiency.

🛠️ Tools & Technologies Used

Python
Jupyter Notebook
Probabilistic Modeling
Exponential Distribution
Inverse Transform Sampling
Traffic Flow Simulation Framework
Data Visualization
Traffic density plots
Flow and behavior graphs
Statistical Analysis
Average travel time
Waiting time comparison
Traffic throughput

📂 Project Structure
📁 Traffic-Control-Simulation
│
├── baseline_simulation.ipynb
├── simulation_study1.ipynb
├── simulation_study2.ipynb
├── simulation_study3.ipynb
├── report.pdf
└── README.md

📊 Key Results
Simulation Model	Avg Travel Time	Avg Waiting Time	Outcome
Baseline	~165 s	~190 s	✅ Stable
Study 1	258 s	567 s	❌ Crash
Study 2	388 s	927 s	❌ Crash
Study 3	207 s	360 s	✅ Optimal

🔍 Insights & Learnings

Speed alone does not guarantee safety
Proper inter-arrival timing is critical
Over-aggressive braking and acceleration lead to instability
Multiple simulation runs are essential for reliable conclusions
Small parameter changes can drastically affect system behavior

🚀 Future Enhancements

Introduce multi-lane roads
Add traffic signals or pedestrian crossings
Model evening traffic scenarios
Include stochastic driver behavior
Scale simulation to urban intersections

📚 References

Key academic and module resources were used, including:
Lecture notes from NCI
Peer-reviewed research on traffic flow modeling
Microscopic traffic simulation frameworks
(See full reference list in the project report)

⭐ Final Note

This project demonstrates a complete simulation lifecycle from assumptions and modeling to validation and optimization reflecting both technical rigor and analytical thinking.

If you found this project insightful, feel free to ⭐ the repository!
