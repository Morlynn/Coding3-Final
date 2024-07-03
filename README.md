# Coding3-Final
Donghao Liu  
Student ID：23014662
## Motivation
Neural Style Transfer (NST) is an extremely interesting and versatile technique based on PyTorch that brings many innovative applications and possibilities in the artistic and creative fields. Through this project, I aim to expand my knowledge in computer vision and deep learning by learning and understanding the principles and implementation of the algorithm in depth.  
## How to use
The notebooks I use follow these steps:  
  
1.Load images: Load the content image and the style image.  
2.Preprocess images: Preprocess the images.  
3.Build the model: Use a pre-trained convolutional neural network (VGG19) to extract image features.  
4.Define the loss function: Include content loss and style loss.  
5.Optimize: Transform the content image into a new image with the style image features through the optimization process.  
  
**The content image I used:**  
  
![sculpture](https://github.com/Morlynn/Coding3-Final/assets/163441891/ee22d71c-06ca-4c0f-b2ee-b7eb351b16b0)  
[sculpture](https://www.pinterest.com/pin/323696291967075044/)
  
**The style image I used:**  
  
![cyberpuck2](https://github.com/Morlynn/Coding3-Final/assets/163441891/0d047df8-e381-42a5-a802-c8a933d672de)  
[Sky scrapers](https://in.pinterest.com/pin/316518680075673642/)


## Learning process
In this project, I conducted two experiments to explore and understand the capabilities of Neural Style Transfer.  
### Analyzing the effects of VGG19 Layer changes on Style Transfer Result
Firstly, I attempted to modify different layers of the VGG19 model to compare the impact of each layer on the style transfer results.

In **2.Compare _low-level detailed features.ipynb** and **2.Compare _high-level global features.ipynb**, I extracted lower-level detail features (such as fine details and textures) and higher-level global features (such as shapes and structures) respectively, and compared the results.

<img width="320" alt="b40370b9a7ae146cc7f53b683ec13f4" src="https://github.com/Morlynn/Coding3-Final/assets/163441891/4a154d95-6641-4173-9e30-bd4c8eb0a577">
<img width="261" alt="dca5f9884d3d1cf72dae11c672bd937" src="https://github.com/Morlynn/Coding3-Final/assets/163441891/32a6d828-0eb2-41eb-8f98-aaba602bcb77"> <br>
<img width="317" alt="1c99c5ceadbce4e92bb0a90180fcb9c" src="https://github.com/Morlynn/Coding3-Final/assets/163441891/ff7ccebc-1982-4ac7-8857-e1c375420dd7">
<img width="261" alt="fec221c4ea06add7f921f571d0ebda9" src="https://github.com/Morlynn/Coding3-Final/assets/163441891/bb20bd07-c98b-40d1-9ffe-2253b9de2712">  
  
**Detail Feature Image：**  
![low](https://github.com/Morlynn/Coding3-Final/assets/163441891/a66dd125-1a01-473a-b433-2bcdcf4891ca)  
· Rich in details, retaining more texture and edge information from the original image.  
· Overall color and details are complex, showcasing more subtle elements of the artistic style.

