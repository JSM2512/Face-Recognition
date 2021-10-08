# Face-Recognition implementation using transfer learning method and harrcascade
#### Face recognition technology is a biometric technology, which is based on the identification of facial features of a person. People collect the face images, and the recognition equipment automatically processes the images.
### Data Collection : using harrcascade frontal face xml file
### Training using Transfer Learning method - VGG16 architecture
![vgg16-1-e1542731207177](https://user-images.githubusercontent.com/49087609/136613906-c8fb078a-f24c-4574-8e38-1d4496a42080.png)
VGG16 is a convolution neural net (CNN ) architecture which was used to win ILSVR(Imagenet) competition in 2014. It is considered to be one of the excellent vision model architecture till date. Most unique thing about VGG16 is that instead of having a large number of hyper-parameter they focused on having convolution layers of 3x3 filter with a stride 1 and always used same padding and maxpool layer of 2x2 filter of stride 2. It follows this arrangement of convolution and max pool layers consistently throughout the whole architecture. In the end it has 2 FC(fully connected layers) followed by a softmax for output. The 16 in VGG16 refers to it has 16 layers that have weights. This network is a pretty large network and it has about 138 million (approx) parameters.

### Face detection using Haar Cascade frontal face algorithm
Haar Cascade is an Object Detection Algorithm used to identify faces in an image or a real time video. The algorithm uses edge or line detection features proposed by Viola and Jones in their research paper “Rapid Object Detection using a Boosted Cascade of Simple Features” published in 2001. The algorithm is given a lot of positive images consisting of faces, and a lot of negative images not consisting of any face to train on them.
Research paper : https://ieeexplore.ieee.org/document/990517

### Result:
![Screenshot (449)](https://user-images.githubusercontent.com/49087609/136614860-e1b113ce-8d45-426b-987f-27a967468219.png)

