# MSCN

This is the official code of "Multi-Sensor Collaboration Network for Video Compression Based on Wavelet Decomposition", pubished in TCSVT 2022
paper: [Multi-Sensor Collaboration Network for Video Compression Based on Wavelet Decomposition](https://ieeexplore.ieee.org/document/9866775)

# Description

images: 

structure (Entire framework of the proposed multi-sensor collaboration network (MSCN) for video compression.)
netwrok (Network architecture of CDSR in sampling factor 1.)     
BD-rate (RD curves on 7 test sequences by 3D-HEVC anchor and MSCN.)

models:

f1net.py: network of CDSR in sampling factor 1.
f2net.py: network of CDSR in sampling factor 2.
f4net.py: network of CDSR in sampling factor 4.

![structure](https://user-images.githubusercontent.com/55533905/226543568-f8f0dfc5-839b-4e56-abc6-1ba1b711dfd3.png)
Entire framework of the proposed multi-sensor collaboration network (MSCN) for video compression. CDSR: Color guided depth super-resolution.

![network](https://user-images.githubusercontent.com/55533905/226543635-d3e3a8ad-c706-424e-9506-2662719ef2f6.png)
 Network architecture of CDSR in sampling factor 1. The sampling factor 1 means that depth frame has the same size as color frame.
 
#Dependencies
network training: pytorch 1.8.0
training dataset compressed by HM16.16
testing dataset compressed by 3D-HEVC

If you find our work useful in your research or publication, please cite our work:

[1] H. Lan, Z. Ji, C. Jung, D. Zou and M. Li, "Multisensor Collaboration Network for Video Compression Based on Wavelet Decomposition," in IEEE Transactions on Circuits and Systems for Video Technology, vol. 33, no. 1, pp. 434-444, Jan. 2023, doi: 10.1109/TCSVT.2022.3201697.

@ARTICLE{9866775,
  author={Lan, Hui and Ji, Zhe and Jung, Cheolkon and Zou, Dan and Li, Ming},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={Multisensor Collaboration Network for Video Compression Based on Wavelet Decomposition}, 
  year={2023},
  volume={33},
  number={1},
  pages={434-444},
  doi={10.1109/TCSVT.2022.3201697}}
