<h1 align="center">Land Cover Classification System - Satellite Image Processing</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/54114888/148724436-573a6b4f-3e03-4da2-aa9d-a16d7396c52c.png" width="180" height="180">
</p>

## 📜 Description:
Developed a and Cover Classification system using Satellite Image Processing with the help of Remote Sensing images. The system can classify between Forest land, Agricultural of Paddy fields nd Urban areas from a given Dataset. All the step by step procedure has been done and executed in the Jupyter notebook. The system can also clasify the Land cover into various other categories as well as shown in the Sample predicted results.

## 📽 Sample predicted results: (Also shown process in Jupyter notebook)
<p align="center">
<img src="https://user-images.githubusercontent.com/54114888/148724730-fef911e3-daa5-4f93-aa7a-244a468112e1.png" >
</p>

## 🏗 Benchmark datasets used:
- https://data.tpdc.ac.cn/en/data/1b2ebe66-8389-4c9f-9756-1b29d83f851f/
- https://x-ytong.github.io/project/GID.html
- https://www.sciencedirect.com/science/article/pii/S1877050918320386
- https://arxiv.org/pdf/1802.00631.pdf
- https://archives.palarch.nl/index.php/jae/article/download/6535/6361/12820
- http://madm.dfki.de/files/sentinel/EuroSAT.zip
- http://madm.dfki.de/downloads
- https://github.com/phelber/eurosat

## 🔭 Tabular Comparisons:
|  Settings  | Baseline | Baseline + A-Fan |
|:----------:|:--------:|:----------------:|
|  ResNet-50 |   75.21  |       76.33      |
| ResNet-101 |   77.10  |       78.14      |
| ResNet-152 |   78.31  |       78.69      |

Standard Testing accuracy (SA%) of ResNet-50/101/152 on EuroSAT dataset
<br>
<br>
|   Method   | top-1 err. | top-5 err. |
|:----------:|:----------:|:----------:|
|  VGG (v5)  |    24.4    |     7.1    |
|  ResNet-50 |    20.74   |    5.25    |
| ResNet-101 |    19.87   |    4.60    |
| ResNet-152 |    19.38   |    4.49    |

Fully Conv with Multiple Scale Results of ResNet-50/101/152 and VGG net
<br>
<br>
|   Network  | Year |    Salient Feature   | Accuracy | Parameters |  FLOP |
|:----------:|:----:|:--------------------:|:--------:|:----------:|:-----:|
|   AlexNet  | 2012 |        Deeper        |  84.70%  |     62M    |  1.5B |
|   VGGNet   | 2014 |  Fixed-size Kernels  |  92.30%  |    138M    | 19.6B |
| ResNet-152 | 2015 | Shortcut Connections |  95.52%  |    60.3M   |  11B  |

Accuracy obtained from ResNet-152, VGG Net and AlexNet on EuroSAT dataset
<br>
<br>
| EuroSAT        | ResNet-50 |       | ResNet-101 |       |
|:--------------:|:---------:|:-----:|:----------:|:-----:|
|                |  Baseline | A-FAN |  Baseline  | A-FAN |
|     AP (%)     |   33.20   | 33.85 |    36.21   | 37.05 |
|    AP50 (%)    |   53.92   | 54.73 |    56.90   | 57.31 |
|    AP75 (%)    |   35.83   | 36.54 |    39.40   | 40.22 |
|  Robust AP (%) |    0.00   |  0.50 |    0.20    |  0.66 |

Accuracy of detection on EuroSAT datasets with faster RCNN
<br>
<br>
|    Model   | top-1 err. | top-5 err. |
|:----------:|:----------:|:----------:|
|   VGG-16   |    28.07   |    9.33    |
|  ResNet-50 |    22.85   |    6.71    |
| ResNet-101 |    21.75   |    6.05    |
| ResNet-152 |    21.43   |    5.71    |

Error rates on EuroSAT dataset between VGG-16 and ResNet-50/101/152

## 📈 Graphical Observations/ Representation:

<p align="center">
<img src="https://user-images.githubusercontent.com/54114888/150593415-794c0187-006d-4328-a44e-48b03190b0e3.png" width="" height="300">
<p align="center">Comparison of Training and Testing Accuracy(%) of different models on EuroSAT dataset</p>  
</p>

<br>
<br>

<p align="center">
<img src="https://user-images.githubusercontent.com/54114888/150595312-1f371d4d-4b07-40af-98b0-515fb2235d32.png" width="" height="300">
<p align="center">Model accuracy and model loss of ResNet 152 on EuroSAT dataset</p>  
</p>

<br>
<br>

<p align="center">
<img src="https://www.mdpi.com/applsci/applsci-11-02723/article_deploy/html/images/applsci-11-02723-g021.png" width="" height="350">
<p align="center">Training Accuracy results of Classification models</p>  
</p>

## 💥 How to Contribute?

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) 

- Take a look at the Existing [Issues](https://github.com/Akash-Ramjyothi/Land-Cover-Classification-Satellite-Image-Processing/ssues) or create your own Issues!
- Wait for the Issue to be assigned to you after which you can start working on it.
- Fork the Repo and create a Branch for any Issue that you are working upon.
- Create a Pull Request which will be promptly reviewed and suggestions would be added to improve it.
- Add Screenshots to help me know what this Code is all about.

## 👦 Developed By:
<h2 align="center">Akash Ramjyothi</h2>
<p align="center">
  <a href="https://github.com/Akash-Ramjyothi"><img src="https://avatars.githubusercontent.com/u/54114888?v=4" width=150px height=150px /></a> 
    
<p align="center">
  <a target="_blank"href="https://www.linkedin.com/in/akash-ramjyothi/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="mailto:akash.ramjyothi@gmail.com?subject=Hello%20Akash,%20From%20Github"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.instagram.com/akash.ramjyothi/"><img src="https://img.shields.io/badge/instagram-%23D14836.svg?&style=for-the-badge&logo=instagram&logoColor=pink" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  ☎️ PH:+91 8939928002.
</p>

## 🌐 References Used:
[1] X. -Y. Tong, Q. Lu, G. -S. Xia and L. Zhang, "Large-Scale Land Cover Classification in Gaofen-2 Satellite Imagery," IGARSS 2018 - 2018 IEEE International Geoscience and Remote Sensing Symposium, 2018, pp. 3599-3602, doi: 10.1109/IGARSS.2018.8518389.

[2] J. Zhang, M. Fu, W. Qi, C. Yuan and D. Tian, "A Comparison of Land Cover Classification Methods Based on Remote Sensing and GIS Technologies," 2009 International Conference on Information Engineering and Computer Science, 2009, pp. 1-6, doi: 10.1109/ICIECS.2009.5367036.

[3] M. H. Nguyen et al., "Land Cover Classification at the Wildland Urban Interface using High-Resolution Satellite Imagery and Deep Learning," 2018 IEEE International Conference on Big Data (Big Data), 2018, pp. 1632-1638, doi: 10.1109/BigData.2018.8621883.

[4] T. Vignesh, K. K. Thyagharajan, R. B. Jeyavathana and K. V. Kanimozhi, "Land Use and Land Cover Classification Using Recurrent Neural Networks with Shared Layered Architecture," 2021 International Conference on Computer Communication and Informatics (ICCCI), 2021, pp. 1-6, doi: 10.1109/ICCCI50826.2021.9402638.

[5] H. Zhang, J. Zhang and F. Xu, "Land use and land cover classification base on image saliency map cooperated coding," 2015 IEEE International Conference on Image Processing (ICIP), 2015, pp. 2616-2620, doi: 10.1109/ICIP.2015.7351276.
