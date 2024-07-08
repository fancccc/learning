## Docker
- docker search ***
- docker pull ***
- docker run -it --name fanc -v /disk2/fanc:/app --gpus all --network host ubuntu /bin/bash (--gpus load nvidia, --network host use host network)

## Linux
- CUDA_VISIBLE_DEVICES=0 python train.py
