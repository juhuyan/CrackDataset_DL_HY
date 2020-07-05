Pavement surface crack datasets for DL based crack detection

###################################################################

CrackDataset_DL_HY

Ju Huyan (ju_huyan@outlook.com), University of Waterloo, Canada (https://www.linkedin.com/in/julia-huyan/)
Wei Li(grandy@chd.edu.cn), Chang' An University, China (http://it.chd.edu.cn/info/1024/9093.htm)

###################################################################

1.Introduction.

CrackDataset_DL_HY is an annotated road crack image database for both box-level and pixel-level crack detection. This crack image datasets includes road cracks of different types, including transverse cracks, longitudinal cracks, alligator cracks, and the sealed cracks.

If you use this crack image dataset, we appreciate it if you cite an appropriate subset of the following papers:

@article{huyancracku,

  title={CrackU-net: A novel deep convolutional neural network for pixelwise pavement crack detection},

  author={Huyan, Ju and Li, Wei and Tighe, Susan and Xu, Zhengchao and Zhai, Junzhi},

  journal={Structural Control and Health Monitoring},

  pages={e2551},

  publisher={Wiley Online Library}

}

@article{huyan2019detection,

  title={Detection of sealed and unsealed cracks with complex backgrounds using deep convolutional neural network},

  author={Huyan, Ju and Li, Wei and Tighe, Susan and Zhai, Junzhi and Xu, Zhengchao and Chen, Yao},

  journal={Automation in Construction},

  volume={107},

  pages={102946},

  year={2019},

  publisher={Elsevier}

}

##################################################################

2. Database Information.

2.1 This dataset contains to kinds of annotated datasets, which are seperated into two folders: Box-level_Dectetion and SematicSeg_Dataset

    -----Box-level_Dectetion folder:

         This folder contains the annotated crack images of the types transverse cracks, longitudinal cracks, alligator cracks, and sealed   

         cracks. Each type of crack files contains both original crack images and the .xml files that are the label information of the corresponding crack

         image. These can be used for box-level crack detection model training and test.

   -----SematicSeg_Dataset folder:

        This folder contains the original crack images and the corresponding pixel-level labels. Each label is a binary crack image that corresponds to the

        original crack image. These images can be used for pixel-level crack detection model training and test.

  2.2 These crack images are collected by automatic data collection vehicles of the size 1280(pixel)* 960(pixel). Detailed data collection methods can be find from the above papers.

###################################################################

3.License.

The dataset is made available for non-commercial research purposes only.

Copyright: Wei Li Research Team, School of Information Engineering @ Chang' An University, China

###################################################################

4.History.

Version 1.0 (2020/06/29)

    initial version

###################################################################
