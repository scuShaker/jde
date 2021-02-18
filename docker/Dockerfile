FROM  pytorch/pytorch:1.3-cuda10.1-cudnn7-devel

RUN apt update && apt install -y ffmpeg libsm6 libxrender-dev
RUN pip install Cython -i https://pypi.tuna.tsinghua.edu.cn/simple
RUN pip install -i https://pypi.tuna.tsinghua.edu.cn/simple opencv-python cython_bbox motmetrics numba matplotlib sklearn

