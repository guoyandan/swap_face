### [MobileFaceSwap: A Lightweight Framework for Video Face Swapping (AAAI 2022)](https://arxiv.org/abs/2201.03808)
--- 


**Dependencies**
- paddlepaddle==2.1.2
- insightface==0.2.1
- protobuf==3.20.1
- opencv
- numpy

**Getting Started**
1. The pretrained models can be downloaded from [Baidu Drive](https://pan.baidu.com/s/14mBadhwZbrj6n4ncS3Z-Ww 
提取码：lj4w) or [Google Drive](https://drive.google.com/file/d/1ZIzGLDB15GRAZAbkfNR0hNWdgQpxeA_r/view?usp=sharing).
2. 将checkpoints放到swap_face项目目录下
3. Run the codes as follows for image or video tests.

```
python image_test.py --target_img_path data/xxx.png --source_img_path data/xxx.png --output_path results --use_gpu True

python video_test.py --target_video_path data/test_video.mp4 --source_img_path data/head1.png --output_path results --use_gpu True
```
**Results**

![](docs/demo.png)

![](docs/video.gif)

**Citation**
```
@inproceedings{xu2022MobileFaceSwap,
  title={MobileFaceSwap: A Lightweight Framework for Video Face Swapping},
  author={Xu, Zhiliang and Hong, Zhibin and Ding, Changxing and Zhu, Zhen and Han, Junyu and Liu, Jingtuo and Ding, Errui},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  year={2022}
}
```
