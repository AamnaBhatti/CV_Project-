Urdu is a complex language as it is an amalgam of many South Asian and East Asian languages; hence character recognition of Urdu is a huge and difficult task. We have systematically studied a recognition problem of handwritten Urdu digits. 
Our contribution is as follows:
1)  Firstly  we  visualize  our  dataset  using  PCA,  t-SNE  anda combination of PCA+t-SNE
![tsne](https://user-images.githubusercontent.com/74530146/107235825-e8262100-6a46-11eb-8ae6-0d7fe9591023.png)
2)  We apply 3 different architecture combinations namely:
* ResNet version 1 and version 2
* ResNet   version   1   with   Squeeze   and   Excitation block,  ResNet  version  2  with  Squeeze  and  Exci-tation block
* ResNet  version  1  with  Convolutional  Block  Atten-tion  Module,  ResNet  version  2  with  ConvolutionalBlock Attention Module3)  
![ResultsReadme](https://user-images.githubusercontent.com/74530146/107240364-a5b31300-6a4b-11eb-9093-c753c997bec2.png)
3) Lastly we visualized feature maps to understand what islearned in them
![89](https://user-images.githubusercontent.com/74530146/107236529-9c27ac00-6a47-11eb-8442-e32fc0420b5c.png)


Links to explore:<br>
* [Dataset](https://github.com/AamnaBhatti/CV_Project-AamnaBhatti-and-AmeeraArif/tree/main/Dataset)
* [Code](https://github.com/AamnaBhatti/CV_Project-AamnaBhatti-and-AmeeraArif/tree/main/Code)
* [CheckPoints](https://github.com/AamnaBhatti/CV_Project-AamnaBhatti-and-AmeeraArif/tree/main/CheckPoints)
* [Results](https://github.com/AamnaBhatti/CV_Project-AamnaBhatti-and-AmeeraArif/tree/main/Results)


Result:

| Attempt | Base Model | SE | CBAM |
| :-: | :-: | :-:| :-: |
| ResNetV1 |  97.76% | 98.3% | 98.68% |
| ResNetV2  |  98.1 | 98.5% | 99.2% |<br>



