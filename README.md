# CUDA-Q Hands-on Lab

Explore CUDA-Q through hands-on labs covering quantum computing fundamentals, quantum chemistry simulations, quantum error correction, and AI-powered quantum circuit synthesis. This session guides you from basic CUDA-Q programming to advanced applications in hybrid quantum-classical computing.

## Agenda

Navigate to the [**`cuda-q-academic`**](https://github.com/Squirtle007/cudaq-workshop-kisti/tree/main/cuda-q-academic) folder which contains 4 labs:

### Getting started with CUDA-Q
* [`quick-start-to-quantum/00_cudaq_basics.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/quick-start-to-quantum/00_cudaq_basics.ipynb)
* [`quick-start-to-quantum/01_quick_start_to_quantum.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/quick-start-to-quantum/01_quick_start_to_quantum.ipynb)
* [`quick-start-to-quantum/02_quick_start_to_quantum.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/quick-start-to-quantum/02_quick_start_to_quantum.ipynb)

### Advanced Applications with CUDA-Q - Quantum Chemistry
* [`chemistry-simulations/vqe_basics.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/chemistry-simulations/vqe_basics.ipynb)
* [`chemistry-simulations/adapt_vqe.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/chemistry-simulations/adapt_vqe.ipynb)

### Advanced Applications with CUDA-Q - Quantum Error Correction
* [`qec101/01_QEC_Intro.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/qec101/01_QEC_Intro.ipynb)
* [`qec101/02_QEC_Stabilizers.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/qec101/02_QEC_Stabilizers.ipynb)

### Advanced Applications with CUDA-Q - AI for Quantum
* [`ai-for-quantum/00_[simplified]compiling_unitaries_using_diffusion_models.ipynb`](https://github.com/Squirtle007/cudaq-workshop-kisti/blob/main/cuda-q-academic/ai-for-quantum/00_%5Bsimplified%5Dcompiling_unitaries_using_diffusion_models.ipynb)


# Docker Instructions

## Build the image
```bash
docker build -t cudaq-env:latest .
```

## Run the container
```bash
docker run -it --rm --gpus all -p 8888:8888 cudaq-env:latest
```

## Access JupyterLab

Once the container is running, open your browser and visit:
```
http://localhost:8888

```
