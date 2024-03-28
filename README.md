# Awesome-AMD-solutions-for-AI
AMD ROCm, PyTorch, etc on Ubuntu 22.04
inspired by https://phazertech.com/tutorials/rocm.html

sudo apt install "linux-headers-$(uname -r)" "linux-modules-extra-$(uname -r)"

sudo usermod -a -G render,video $LOGNAME

Enter one of the following lines depending on your version of Ubuntu:

Ubuntu 22.04: wget https://repo.radeon.com/amdgpu-install/6.0.2/ubuntu/jammy/amdgpu-install_6.0.60002-1_all.deb

sudo apt install ./amdgpu-install_6.0.60002-1_all.deb

sudo apt update

sudo apt install amdgpu-dkms

sudo apt install rocm

vi ~/.bash_profile

Add the following line

export HIP_VISIBLE_DEVICES=0

## SAM from YOLO
https://docs.ultralytics.com/models/sam/#how-to-use-sam-versatility-and-power-in-image-segmentation
