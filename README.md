## *Symmetric Parallax Attention for Stereo Image Super-Resolution, arXiv 2020.* [**[*pdf*]**](https://arxiv.org/pdf/2011.03802.pdf), [**[*demo*]**](https://wyqdatabase.s3-us-west-1.amazonaws.com/iPASSR_visual_comparison.mp4).
***<center><a href="https://yingqianwang.github.io" target="_blank">Yingqian Wang</a>&emsp;&emsp; Xinyi Ying&emsp;&emsp; Longguang Wang&emsp;&emsp; Jungang Yang&emsp;&emsp; Wei An&emsp;&emsp; <a href="http://yulanguo.me/" target="_blank">Yulan Guo</a></center>*** <br>
 <br><br>

### Download the Results
**We share the quantitative and qualitative results achieved by our iPASSR on all the test sets for both 2xSR and 4xSR. Then, researchers can compare their algorithms to our method without performing inference. Results are available at [Baidu Drive](https://pan.baidu.com/s/1w8RtQau2RoY89jsFvMCStw) (Key: NUDT).**
<br><br>

### PyTorch Implementation

#### Requirement
* **PyTorch 1.3.0, torchvision 0.4.1. The code is tested with python=3.7, cuda=9.0.**
* **Matlab (For training/test data generation and performance evaluation)**

#### Train
* **Download the training sets from [Baidu Drive](https://pan.baidu.com/s/173UGmmN0rtOUghIT40oy8w) (Key: NUDT) and unzip them to `./data/train/`.** 
* **Run `./data/train/GenerateTrainingPatches.m` to generate training patches.**
* **Run `train.py` to perform training. Checkpoint will be saved to  `./log/`.**

#### Test
* **Download the test sets and unzip them to `./data`. Here, we provide the full test sets used in our paper on [Baidu Drive](https://pan.baidu.com/s/1SIYGcMBEDDZ0wYrkxL9bnQ) (Key: NUDT).** 
* **Run `test.py` to perform a demo inference. Results (`.png` files) will be saved to `./results`.**
* **Run `evaluation.m` to calculate PSNR and SSIM scores.**
<br>

### Citiation
```
@article{iPASSR,
  author    = {Wang, Yingqian and Ying, Xinyi and Wang, Longguang and Yang, Jungang and An, Wei and Guo, Yulan},
  title     = {Symmetric Parallax Attention for Stereo Image Super-Resolution},
  journal   = {arXiv Preprint: 2011.03802},
  year      = {2020},
}
```
<br>

### Contact
**Any question regarding this work can be addressed to [wangyingqian16@nudt.edu.cn](wangyingqian16@nudt.edu.cn).**
