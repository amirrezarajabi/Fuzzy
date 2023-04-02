# Fuzzy Edge Detection

I implement an edge detector using fuzzy logic

## Logic
i choose `3*3` kernel

![](./kernel.png)

after that we have to set mean to zero and by normalizing pixel value and fuzzifying pixels by this chart

![](./fuzzyset.png)
![](./BlackorWhite.png)

Then we have to choose fuzzy logic for decide that one pixel is edge or not. this is my rules :

![](./rules.png)

## Results
Image             |  Edge-Etected Image
:-------------------------:|:-------------------------:
![](./coin.jpg)  |  ![](./EDGE-coin.jpg)
![](./nature.png)| ![](./EDGE-nature.png)
![](./face-random-persom-from-dataset.jpg)| ![](./EDGE-face-random-persom-from-dataset.jpg)
![](./pic1.jpg) | ![](./EDGE-pic1.jpg)
![](./pic2.png) | ![](./EDGE-pic2.png)
