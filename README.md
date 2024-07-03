# Awesome-AMD-solutions-for-AI
AMD ROCm, PyTorch, etc on Ubuntu 22.04

For convenience, configure sudo to never ask for your password.

`sudo visudo`

In the bottom of the file, add the following line:

$USER ALL=(ALL) NOPASSWD: ALL

Where $USER is your username on your system. 

https://github.com/Samiii777/AMD_MachineLearning/tree/main/linux
provides shell scripts. Code after line 34 in install.sh installs python packages and can be commented out.

Another guide is at https://phazertech.com/tutorials/rocm.html

sudo apt install "linux-headers-$(uname -r)" "linux-modules-extra-$(uname -r)"

sudo usermod -a -G render,video $LOGNAME

wget https://repo.radeon.com/amdgpu-install/6.0.2/ubuntu/jammy/amdgpu-install_6.0.60002-1_all.deb

sudo apt install ./amdgpu-install_6.0.60002-1_all.deb

sudo apt update

sudo apt install amdgpu-dkms

sudo apt install rocm

vi ~/.bash_profile

Add the following line

export HIP_VISIBLE_DEVICES=0

Restart your computer before continuing.

## SAM from YOLO
https://docs.ultralytics.com/models/sam/#how-to-use-sam-versatility-and-power-in-image-segmentation

## alpaca lora
bnb issue needs to be resolved first.
https://github.com/TimDettmers/bitsandbytes/issues/47


https://github.com/tloen/alpaca-lora
