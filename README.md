# CellProfiler
Installation guide of the CellProfiler on Linux Mint 21.1 with python > 3.9 and conda 4.12.0.

conda create -n py39 python=3.9
conda activate py39
sudo apt update
sudo apt -y upgrade
sudo apt install -y make gcc build-essential libgtk-3-dev
sudo apt-get install -y python3-pip openjdk-11-jdk-headless default-libmysqlclient-dev libnotify-dev libsdl2-dev
sudo apt-get install -y \
                freeglut3 \
                freeglut3-dev \
                libgl1-mesa-dev \
                libglu1-mesa-dev \
                libgstreamer-plugins-base1.0-dev \
                libgtk-3-dev \
                libjpeg-dev \
                libnotify-dev \
                libsdl2-dev \
                libsm-dev \
                libtiff-dev \
                libwebkit2gtk-4.0-dev \
                libxtst-dev
pip install CellProfiler
