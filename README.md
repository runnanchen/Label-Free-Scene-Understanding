# CLIP2Scene: Towards Label-efficient 3D Scene Understanding by CLIP (CVPR 2023)

![Overview of the method](./assets/method.png)
CLIP2Scene leverages CLIP knowledge to pre-train a 3D point cloud segmentation network via semantic and spatial-temporal consistency regularization. It yields impressive performance on annotation-free 3D
semantic segmentation and significantly outperforms other self-supervised methods when fine-tuning on annotated data.

[[Preprint Paper]](https://arxiv.org/pdf/2306.03899.pdf) 

# Citation
If you use CLIP2Scene in your work, please cite
```
@article{chen2023clip2scene,
  title={CLIP2Scene: Towards Label-efficient 3D Scene Understanding by CLIP},
  author={Chen, Runnan and Liu, Youquan and Kong, Lingdong and Zhu, Xinge and Ma, Yuexin and Li, Yikang and Hou, Yuenan and Qiao, Yu and Wang, Wenping},
  journal={arXiv preprint arXiv:2301.04926},
  year={2023}
}
```
**Acknowledgement.** 

Part of the codebase has been adapted from [SLidR](https://github.com/valeoai/SLidR), [MaskCLIP](https://github.com/chongzhou96/MaskCLIP), [PCSeg](https://github.com/PJLab-ADG/PCSeg) and [OpenPCDet](https://github.com/open-mmlab/OpenPCDet).

# Contact
For questions about our paper or code, please contact [Runnan Chen](rnchen2@cs.hku.hk).
