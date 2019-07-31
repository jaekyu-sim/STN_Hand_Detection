# STN_Hand_Detection

I tried capturing roi of hand in person image.(Single person image)

To make roi of hand, I use Spatial Transform Networks and add condition vector that 1 when hand is left and 0 when hand is right.

The network I made is here.

![Network_Shape](/Image_for_Github/Network.PNG)

The Input data is gray scale image. So, I've done preprocessing to make image gray scale.

The network concatnate condition vector and input image. And the others is same with STN.

Here is the output.
The upper one is success case of my network. And the bottom one is failure case of my network.
But, Success case is more frequent than failure case.

![Output_S](/Image_for_Github/output_success.PNG)

![Output_F](/Image_for_Github/output_fail.PNG)
