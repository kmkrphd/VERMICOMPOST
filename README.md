# VERMICOMPOST
Quality Prediction
The VERMICOMPOST Dataset represents a technically structured and statistically consistent dataset collected to simulate real-world vermicomposting environments. It integrates multi-modal sensor readings, spectral and image-derived features, and computed compost quality indicators — specifically, Maturity Index (MI), Contamination Risk (CR), and Nutrient Score (NS). Each of the 10,000 samples corresponds to a unique vermicomposting state derived from varied feedstock sources such as crop residues, manures, agro-industrial byproducts, food waste, horticultural waste, and paper residues.

The dataset encompasses realistic environmental conditions — including temperature (25–70 °C), moisture (25–85%), pH (5.0–8.5), and electrical conductivity (0.2–6 dS/m) — as well as spectral reflectance (NIR) and visual texture parameters (entropy, color variance). These variables are synthetically correlated to mimic the nonlinear progression of composting processes like humification, microbial activity, and nutrient transformation. The embedded dependencies among modalities enable the dataset to simulate sensor fusion and domain variability, essential for multi-modal learning models such as VERMI-QualNet.

Dataset Characteristics

Multi-Modal Integration: Combines low-cost environmental sensors, spectral indices, and visual features to emulate real compost bin data.

Cross-Feedstock Variability: Includes six distinct feedstock types to represent diverse chemical and biological composting behaviors.

Realistic Correlations: Built-in dependencies between environmental and target indicators (e.g., temperature decay → higher maturity) simulate true biophysical patterns.

Continuous and Categorical Features: Enables both regression and classification modeling approaches.

Noise and Range Constraints: Uses realistic bounds and statistical noise to replicate natural measurement fluctuations.
