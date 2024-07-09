## Docker
- docker search ***
- docker pull ***
- docker run -it --name fanc -v /disk2/fanc:/app --gpus all --network host ubuntu:latest /bin/bash (--gpus load nvidia, --network host use host network)
- docker save --output=/path/to/directory/myimage.tar myimage:latest
- docker load < tar-file
- docker images

## Linux
- CUDA_VISIBLE_DEVICES=0 python train.py

## URL
-清华源 https://pypi.tuna.tsinghua.edu.cn/simple
