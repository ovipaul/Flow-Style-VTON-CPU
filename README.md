# Flow-Style-VTON-CPU
This repository is the CPU version of the [Flow-Style-VTON](https://github.com/SenHe/Flow-Style-VTON). Original repository does CUDA computation meanwhile this repository will do CPU computation. 

## Bad Result in Original Repository
The original repository is based on torch 1.1.0 with cuda. This creates an issue with RTX based GPUs. RTX based GPU cannot run torch 1.1.0 with CUDA, since in torch 1.1.0 supported version of CUDA is 10 and RTX GPUs need CUDA version of 11. There should be more efficient alternate solution. But for now this CPU version of the original repository can be used to tackle the bad result issue.

## Checkpoints & Dataset
Please refer to the original repository.

## Requirements
- python 3.6.13
- torch 1.1.0(CPU)
- torchvision 0.3.0
- tensorboardX
- opencv

## Test
Get inside the test of cloned repository.
```console
cd Flow-Style-VTON-CPU/test
```
Run the bash file to execute the test dataset.
```console
source test.sh
```
## Train
Coming Soon!

## Acknowledgements

The original repository is [Flow-Style-VTON](https://github.com/SenHe/Flow-Style-VTON). 
