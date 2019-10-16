BootStrap: shub
From: shub://willgpaik/centos7_aci:latest


%post
yum -y install python36-devel \
        python36-pip
yum -y update

pip3.6 install --upgrade pip
pip3 install torch==1.3.0+cpu torchvision==0.4.1+cpu -f https://download.pytorch.org/whl/torch_stable.html
pip install torchvision \
        torchsummary \
        scipy \
        pandas \
        scikit-learn \
        jupyter \
        jupyterlab \
        spyder \
        ipython \
        matplotlib \
        seaborn \
        scikit-image \
        bokeh \
        plotly \
        pillow \
        opencv-python
