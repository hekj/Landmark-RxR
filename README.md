## Landmark-RxR

**Landmark-RxR: Solving Vision-and-Language Navigation with Fine-Grained Alignment Supervision**<br>
__***Keji He***__, Yan Huang, Qi Wu, Jianhua Yang, Dong An, Shuanglin Sima, Liang Wang<br>
Conference on Neural Information Processing Systems (NeurIPS), 2021<br>

## Abstract
In Vision-and-Language Navigation (VLN) task, an agent is asked to navigate inside 3D indoor environments following given instructions. Cross-modal alignment is one of the most critical challenges in VLN because the predicted trajectory needs to match the given instruction accurately. In this paper, we address the cross-modal alignment challenge from a fine-grained perspective. Firstly, to alleviate weak cross-modal alignment supervision from coarse-grained data, we introduce a human-annotated fine-grained VLN dataset, namely Landmark-RxR. Secondly, to further enhance local cross-modal alignment under fine-grained supervision, we investigate the focal-oriented rewards with soft and hard forms, by
focusing on the critical points sampled from fine-grained Landmark-RxR. Moreover, to fully evaluate the navigation process, we also propose a re-initialization mechanism that makes metrics insensitive to difficult points, which can cause the agent to deviate from the correct trajectories. Experimental results show that our agent has superior navigation performance on Landmark-RxR, en-RxR and R2R.

[[Paper](https://proceedings.neurips.cc/paper/2021/file/0602940f23884f782058efac46f64b0f-Paper.pdf)] [[Supplemental](https://proceedings.neurips.cc/paper/2021/file/0602940f23884f782058efac46f64b0f-Supplemental.pdf)]

## Codes
Coming soon.

## Dataset Download

Our Landmark-RxR is built based on the English Guide split of RxR (en-RxR). It contains sub-instruction and sub-trajectory pairs split from instructions in en-RxR. Landmark-RxR has the largest scale of instructions and trajectories and the minimum granularity among current human-annotated VLN datasets. You can download this dataset [here](https://www.dropbox.com/sh/muwe42gzj4qxr4m/AABAGMvCL3odeRpDb_z_Ghu9a?dl=0).




## Citation
If you find this repository useful, please cite our paper:

```
@article{he2021landmark,
  title={Landmark-RxR: Solving Vision-and-Language Navigation with Fine-Grained Alignment Supervision},
  author={He, Keji and Huang, Yan and Wu, Qi and Yang, Jianhua and An, Dong and Sima, Shuanglin and Wang, Liang},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  year={2021}
}
