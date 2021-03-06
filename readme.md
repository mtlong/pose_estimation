# Template-Model Driven Pose Estimation



This repository contains the code for our works:
 1) **iSPA-NET**, accepted in ACM Multimedia Conference, 2018 (ACMMM18) - *Jogendra Nath Kundu, *Aditya Ganeshan, *Rahul MV, Aditya Prakash, R. Venkatesh Babu


![overview](misc/acmmm.png)

 2)  **Object Pose Estimation Using Multi-View Keypoint Correspondence**, accepted in Geometry Meets Deep Learning Workshop, at ECCV 2018. - *Jogendra Nath Kundu, *Rahul MV, *Aditya Ganeshan, R. Venkatesh Babu

![overview](/classifier_code/architecture_images/multi_view_arch.png)
###### \* = equal Contribution

This repository broadly consists of:

1) Data Creation : [data_creator](https://github.com/val-iisc/iSPA-Net/tree/master/data_creator)

2) Universal Correspondence Network Training Code : [ucn_code](https://github.com/val-iisc/iSPA-Net/tree/master/ucn_code)

3) iSPA-Net Training and Testing code : [classifier_code](https://github.com/val-iisc/iSPA-Net/tree/master/classifier_code)
	 - Refer to [classifier\_code/iSPA-Net.md](https://github.com/val-iisc/iSPA-Net/blob/master/classifier_code/iSPA-Net.md) for more details

4) Multi-View Keypoint based Pose Estimation - Training and Testing code : [classifier_code](https://github.com/val-iisc/iSPA-Net/tree/master/classifier_code)
	- Refer to [classifier\_code/Multi-View-Net.md](https://github.com/val-iisc/iSPA-Net/blob/master/classifier_code/Multi-View-Net.md) for more details


**Note:** For the Universal Correspondence Network, caffe code for which has to be requested from [NEC-Labs](http://www.nec-labs.com/~mas/UCN/).

iSPA-Net Link to Arxiv: [1808.01134](https://arxiv.org/pdf/1808.01134.pdf)

Object Pose Estimation Using Multi-View Keypoint Correspondence - [1809.00553](https://arxiv.org/pdf/1809.00553.pdf)

## Citation
```
#@article{ispanet-kundu-2018,
title={iSPA-Net: Iterative Semantic Pose Alignment Network},
author={Kundu, Jogendra Nath and Ganeshan, Aditya and MV, Rahul and Prakash, Aditya and Babu, R Venkatesh},
booktitle = {arXiv preprint arXiv: 1808.01134 },
year = {2018}
}

#@article{ispanet-kundu-2018,
title={Object Pose Estimation Using Multi-View Keypoint Correspondence},
author={Kundu, Jogendra Nath and MV, Rahul and Ganeshan, Aditya and Babu, R Venkatesh},
booktitle = {arXiv preprint arXiv: 1809.00553 },
year = {2018}
}
```

