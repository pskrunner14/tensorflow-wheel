# TensorFlow Wheel

This is a custom TensorFlow wheel built from source, optimized for my machine, built on x64 linux (confirmed working on Ubuntu 18.04.1 LTS Bionic Beaver) with intel processor.

## Download Wheel

You can find the wheel in the [releases page](https://github.com/pskrunner14/tensorflow-wheel/releases).

### GPU:
* [**1.10.0, Python 3.6.\*, CUDA 9.2, cuDNN 7.2, AVX2**](https://github.com/pskrunner14/tensorflow-wheel/releases/tag/tf-1.10.0-gpu-avx2-v1.0) Built for modern Intel architecture (KabyLake) and Nvidia GPU (compute-capability 6.1)

### Installing via pip
```
pip install --no-cache-dir https://github.com/pskrunner14/tensorflow-wheel/releases/download/tf-1.10.0-gpu-avx2-v1.0/tensorflow-1.10.0-cp36-cp36m-linux_x86_64.whl
```
