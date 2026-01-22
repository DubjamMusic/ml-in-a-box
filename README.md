# 🛠️ HustleCodex ML Toolkit

Automated setup scripts that transform bare Ubuntu Paperspace instances into production-ready ML environments with PyTorch, TensorFlow, CUDA, and 40+ data science packages.

### Quick Start

1. Provision a Paperspace Core machine with Ubuntu 20.04 or 22.04
2. Clone this repository
3. Run `bash ubuntu-XX/ml_in_a_box.sh` (replace XX with your Ubuntu version)
4. Wait 15-30 minutes for installation to complete

### Hardware Compatibility

| Ubuntu Version | Recommended Hardware | Driver/CUDA |
|----------------|---------------------|-------------|
| 22.04 | H100 (required), A100 (recommended) | Driver 535.x, CUDA 12.1 |
| 20.04 | A6000, RTX series, older GPUs | Driver 515.x, CUDA 11.7 |

Driver requirements are determined by Nvidia hardware generation support.

## What's Included

**Core ML Frameworks**: PyTorch 1.12/2.1, TensorFlow 2.9/2.15, JAX  
**Hugging Face Stack**: Transformers, Datasets, Accelerate, Diffusers, PEFT  
**Data Science**: NumPy, Pandas, SciPy, Matplotlib, scikit-learn, XGBoost  
**NLP**: spaCy, NLTK, sentence-transformers  
**Development**: JupyterLab, Python 3.9/3.11, Node.js 20.x, Git  
**GPU Acceleration**: CUDA 11.7/12.1, cuDNN 8.5/8.9, Nvidia drivers

See `ubuntu-XX/README.md` for complete package lists with versions and licenses.

## Repository Structure

```
ai-toolkit-ml-box/
├── ubuntu-20/          # Ubuntu 20.04 setup (CUDA 11.7, Python 3.9)
│   ├── ml_in_a_box.sh  # Installation script
│   └── README.md       # Detailed package list
└── ubuntu-22/          # Ubuntu 22.04 setup (CUDA 12.1, Python 3.11)
    ├── ml_in_a_box.sh  # Installation script
    └── README.md       # Detailed package list
```

## GitHub Copilot Integration

See [COPILOT_CAPABILITIES.md](COPILOT_CAPABILITIES.md) for how GitHub Copilot can help maintain this repository.
