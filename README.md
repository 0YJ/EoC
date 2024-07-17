## Welcome to EoC Project 

<p align="center">
  <img src="IMG/ceres.jpg" alt="avatar">
</p>

To eliminate biases from the observer in the conventional phenotyping progress, we present an artificial intelligence-based solution to predict the growth status and detect the fine-grained elements of tomato plants (Solanum lycopersicum) in greenhouse environments. We have generated a comprehensive manually labeled augmented dataset consisting of 68,077 images classified into 26 classes. This dataset was created using a unique multi-pose multi-angle camera system, to collect high-quality digital images for fast and accurate monitoring of tomato plants across different life stages. Our distributed model structure first uses 7 classes to locate regions of interest, followed by pixel-wise semantic segmentation into 19 find-grained sub-classes. The detection results achieved using YOLO-EOD (an enhanced version of YOLO8 incorporating Squeeze-and-Excitation block), are validated through metrics like accuracy, mean average precision (mAP), and recall. Both qualitative and quantitative results ensure the presented solution is robust for our task. In addition, we want to enhance performance through a distributed model structure across various edge devices (such as drones, robotics, and embedded systems) based on the artificial intelligence of things (AIoT) strategy. 


EoC Dataset
---------------
Please clone our [repository](https://github.com/0YJ/MPTSTD) for downloading. We suggest reading [README](https://github.com/0YJ/MPTSTD/blob/main/README.md) before using the dataset.

Citation
--------------

Please cite the [MPTSP paper](https://www.ph.com/placeholder.pdf) if it helps your research:
```bibtex
@online{dah2024,
  author = {Yujie, Sven},
  publisher = {DaAnHort},
  title = {EoC},
  date = {2024-04-24},
  url = {https://github.com/0YJ/MPTSTD/},
  note = {Presented at the KIDA Conference 2023 in Quedlinburg},
  langid = {en}
}
```
