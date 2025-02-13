# installCaffeJTX2
Install Caffe on the NVIDIA Jetson Nano Development Kit.

Caffe: a fast open framework for deep learning. http://caffe.berkeleyvision.org/
Caffe source code is here: https://github.com/BVLC/caffe

Scripts to install Caffe and dependencies on the NVIDIA Jetson Nano Development Kit.
This script is for L4T 27.1, an Ubuntu 16.04 variant. 

To maximize the performance of the Jetson Nano, you can use the jetson_clocks.sh script which enables all CPU cores, and maximizes clock speeds on the CPUs and GPU. JetPack 4 installs jetson_clocks.sh in the home directory.

For best results on the Jetson Nano install:

<ul>
<li>L4T 27.1 (Ubuntu 16.04)</li>
<li>OpenCV4Tegra</li>
<li>CUDA 10.0</li>
<li>cuDNN v5.1</li>
</ul>

These can all be installed with JetPack 3.

To install, run the installCaffe.sh script:

$ ./installCaffe.sh


Last tested with last Github Caffe commit: 317d162acbe420c4b2d1faa77b5c18a3841c444c

