# Requirement.txt
An automated PyTorch machine learning pipeline designed to optimize ex vivo microfluidic caging boundaries and execute downstream genomic error correction for label-free circulating tumor cell (CTC) isolation.
text
# --- Project CELL-CAGE Core Dependency Manifest ---

# Core Data Science & Numerical Simulation
numpy>=1.24.0
pandas>=2.0.0
scikit-learn>=1.2.0
scipy>=1.10.0

# Stage 1: Response Surface & Bayesian Optimization
scikit-optimize>=0.9.0

# Stage 2: Deep Learning Bioinformatic Subtraction
torch>=2.0.0
torchvision>=0.15.0

# Data Visualization & Reporting
matplotlib>=3.7.0
seaborn>=0.12.0
