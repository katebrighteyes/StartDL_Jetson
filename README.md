# StartDL_Jetson 

Jetpack 4.X =<

# recommend pwm fan on always

sudo sh -c 'echo 50 > /sys/devices/pwm-fan/target_pwm'

# git clone

git clone https://github.com/katebrighteyes/StartDL_Jetson

cd StartDL_Jetson

sudo chmod 777 *.sh

# 1. Python Dev

sudo apt-get install libpython3-dev python3-numpy

2~3 minutes


# 2. PyTorch

./install-pytorch.sh

about 40 minutes


# 3. G-Streamer 

./install_gstreamer.sh

# torch to trt

./install_torch2trt.sh


* gtk err

sudo apt install libcanberra-gtk-module libcanberra-gtk3-module
