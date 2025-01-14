# KDFuse
This is official Pytorch implementation of "KDFuse: A High-Level Vision Task-driven Infrared and Visible Image Fusion Method Based on Cross-Domain Knowledge Distillation"

# Framework
![](https://github.com/Chenjia-Yang/KDFuse/blob/main/image/framework.png)

# Pre-trained SegFormer Checkpoint preparation
Downloading the pre-trained fusion model from the [link](https://pan.baidu.com/s/1SLkqxvxINBkgCE4Lv2_qIQ?pwd=ha7y) and putting it into `'./pretrained/'`.

# To Test
1. Download the pre-trained fusion model from [fusion_model](https://pan.baidu.com/s/1LDIAqVsEkHrqc1nMadF8lw?pwd=eyhv) and put it into `'./models/'`.
2. Place the paired test images in the folder './image/'.
3. The result data_root are put in `'./Results/'`.
   
Then run `test.py`.
