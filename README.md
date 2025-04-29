This project aims to predict Parkinson’s Disease using voice measurements and machine learning. Parkinson’s Disease is a progressive disorder that affects movement and speech. People with Parkinson’s often show changes in their voice such as reduced loudness, monotone pitch, or hoarseness.

We use the UCI Parkinson’s dataset, which contains voice recordings from healthy individuals and Parkinson’s patients. From these recordings, features like jitter, shimmer, and harmonic-to-noise ratio (HNR) are extracted and analyzed.

To improve prediction, we apply several feature selection algorithms to find the most important voice features. These include:

Genetic Algorithm (GA)

Particle Swarm Optimization (PSO)

Grey Wolf Optimizer (GWO)

Simulated Annealing (SA)

Cuckoo Search Algorithm (CSA)

Ant Colony Optimization (ACO)

Wolf Search Algorithm (WSA)

Harris Hawks Optimization (HHO)

Hybrid Methods (e.g., HHO+ACO, WSA+SHAP)

After selecting the best features, we train models like Random Forest and XGBoost to predict whether a person has Parkinson’s.
