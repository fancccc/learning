## Docker
- docker search ***
- docker pull ***
- docker run -it --shm-size=2048m --name fanc -v /disk2/fanc:/app --gpus all --network host ubuntu:latest /bin/bash (--gpus load nvidia, --network host use host network)
- docker commit [容器ID或名称] [新镜像名称]
- docker save --output=/path/to/directory/myimage.tar myimage:latest
- docker load < tar-file
- docker images
- docker ps -a #查看所有容器
- docker start fanc
- docker attach fanc

## Linux
- CUDA_VISIBLE_DEVICES=0 python train.py
- rm model-{1..300}.pt (remove model-1.pt - model-300.pt)
- 解压：tar zxvf FileName.tar.gz
- 压缩：tar zcvf FileName.tar.gz DirName

## URL
-清华源 https://pypi.tuna.tsinghua.edu.cn/simple

## Git
 - git reset --soft origin 重置本地commit\add 
