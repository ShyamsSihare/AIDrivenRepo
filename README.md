├── data/
│ ├── public/ # Public benchmark datasets (download links provided)
│ ├── pilot/ # Controlled-access pilot data (metadata only)
│ └── processed/ # Preprocessed and feature-engineered datasets
├── src/
│ ├── preprocessing/ # Data cleaning and normalization scripts
│ ├── models/ # Model architectures and training routines
│ ├── evaluation/ # Metrics, statistical tests, and bias analysis
│ └── visualization/ # Figure and table generation scripts
├── experiments/
│ ├── config/ # Experiment configuration files
│ └── run_experiments.py # Main experiment runner
├── results/
│ ├── tables/ # Generated LaTeX tables
│ └── figures/ # Publication-ready figures
├── requirements.txt
└── README.md


## System Requirements

- Python ≥ 3.9  
- CUDA 11.x (optional, for GPU acceleration)  
- Operating Systems: Linux, macOS, or Windows  

Recommended hardware: ≥16 GB RAM, GPU with ≥8 GB VRAM (optional).

## Installation

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
# venv\Scripts\activate    # Windows






