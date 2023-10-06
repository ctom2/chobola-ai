# A Feature-Driven Richardson-Lucy Deconvolution Network

![Light-sheet microscopy image deconvolution](https://github.com/ctom2/dx43/blob/main/content/static/images/lucyd.gif?raw=true)

*Example of light-sheet microscopy deconvolution with background subtraction.*

\[[arXiv](https://arxiv.org/abs/2307.07998)\] \[[GitHub](https://github.com/ctom2/lucyd-deconvolution)\] \[[MICCAI 23 poster](https://drive.google.com/file/d/17YhWWuLn86sBEK3tf-nIuQJORnhj3eaj/view?usp=sharing)\]

----

👨‍🔧 LUCYD is now available for testing in a Colab notebook: [run here](https://colab.research.google.com/drive/1KG0Iv1bEcE2Hx7AYRBxk8I-mKRP5vKbw?usp=sharing)

----


### Contributions
1. A lightweight deconvolution model that embeds the Richardson-Lucy image formation formula into a deep neural network
2. The synergy between deep learning and classic formula for image formation reduces the necessity of having large amounts of training data 


### Abstract

> The process of acquiring microscopic images in life sciences often results in image degradation and corruption, characterised by the presence of noise and blur, which poses significant challenges in accurately analysing and interpreting the obtained data. This paper proposes LUCYD, a novel method for the restoration of volumetric microscopy images that combines the Richardson-Lucy deconvolution formula and the fusion of deep features obtained by a fully convolutional network. By integrating the image formation process into a feature-driven restoration model, the proposed approach aims to enhance the quality of the restored images whilst reducing computational costs and maintaining a high degree of interpretability. Our results demonstrate that LUCYD outperforms the state-of-the-art methods in both synthetic and real microscopy images, achieving superior performance in terms of image quality and generalisability. We show that the model can handle various microscopy modalities and different imaging conditions by evaluating it on two different microscopy datasets, including volumetric widefield and light-sheet microscopy. Our experiments indicate that LUCYD can significantly improve resolution, contrast, and overall quality of microscopy images. Therefore, it can be a valuable tool for microscopy image restoration and can facilitate further research in various microscopy applications. 


Please cite our work if you find it useful to your research.
```
@InProceedings{10.1007/978-3-031-43993-3_63,
  author="Chobola, Tom{\'a}{\v{s}}
  and M{\"u}ller, Gesine
  and Dausmann, Veit
  and Theileis, Anton
  and Taucher, Jan
  and Huisken, Jan
  and Peng, Tingying",
  title="LUCYD: A Feature-Driven Richardson-Lucy Deconvolution Network",
  booktitle="Medical Image Computing and Computer Assisted Intervention -- MICCAI 2023",
  year="2023",
  publisher="Springer Nature Switzerland",
  pages="656--665",
  isbn="978-3-031-43993-3"
}
```
