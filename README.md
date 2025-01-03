# CasDyF-Net: Image Dehazing via Cascaded Dynamic Filters
  
**Authors**: Yinglong Wang, Bin He

**Paper link**(arxiv): [Link of paper](https://arxiv.org/abs/2409.08510)

## Installation
The project is built with **Python 3.8**, **PyTorch 1.10.0**, **CUDA 11.3**,

For installing, follow these instructions:
~~~
pip install -r requirements.txt
~~~
If you're having problems with your version, you can try installing each package one by one using pip alone
## Training and Evaluation
To Train ,you can run this cmd in your terminal:
~~~
python main.py --mode train --dataset yourpath --batch_size 8
~~~
You can also change the parameters in the main.py file.Saving your changes and running main.py will have the same effect
## Results 
You can download the pre-trained **models** from this link:

[Download the pre-trained models](https://drive.google.com/drive/folders/10zPlf5OPEz-VCO7HiAnbCNGgp29K2hOC?usp=drive_link)

If you just need the output images of the models, you can download the **images** from this link:

[Download the images](https://drive.google.com/drive/folders/1jbgU3fwJ3gZfprJcsyuCToPcD6eReDK4?usp=drive_link)

|Dataset|PSNR|SSIM|
|------|-----|----|
|SOTS-Indoor|43.21|0.997|
|SOTS-Outdoor|38.86|0.995|
|Dense-Haze|17.56|0.658|
|O-HAZE|25.44|0.936|
|Haze4K|35.73|0.99|

## Citation
## Contact

e-mail: wangyinglong2023@gmail.com

wechat: dauing2023
