# cranberry ##################
##############################
##############################
##############################

# Repository Description 
It is the docker container of nvidia server computer in the department of Anesthiology & pain medicine of SNUH. It is created based on the docker image from [nvidia cuda](https://hub.docker.com/r/nvidia/cuda/). Download appropriate version of the docker image considering your ubunutu version. For me, it was the [latest version](https://gitlab.com/nvidia/container-images/cuda/blob/master/dist/11.1/ubuntu18.04-x86_64/runtime/cudnn8/Dockerfile) in October, 2020 on ubuntu 18.04.
The purpose of this container is the medical research for 2nd grade of Medicine Course in SNU Medicine(2020).

# contents
This container contains the whole process of data preprocessing and running CNN model using raw vital data(ECG, PPG).

# Required modules
The python code is written on the following verions.

- tensorflow-gpu 2.3.1
- cuda 11.1, cudnn 8.4.0
- other modules(pandas, matplotlib...) was the lastest version since 20.11.25.

