# CNN
convolution neural network ( deep learning )

*Image super-resolution is a software technique which let us enhance the image spatial resolution with existing hardware. In low resolution image-Pixel density with in an image is small, and in High resolution image- Pixel density with in an image is large.

<img width="852" alt="Screenshot 2021-11-17 at 11 16 27 PM" src="https://user-images.githubusercontent.com/72788390/142254653-b53f6e47-1686-48a2-8868-695c640b9c92.png">

As per image pro- cessing it suggest to perform Interpolation on low resolu- tion image , so researchers done different kind of interpo- lation such as Nearest-neighbour interpolation , Bi-linear interpolation , Bicubical interpolation.
In which Bicubical Interpolation produces noticeably sharper images than the previous two methods and balances processing time and output quality.
Convolutional neural network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, as- sign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classifica- tion algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics.
A ConvNet is able to successfully capture the Spatial and Temporal dependencies in an image through the applica- tion of relevant filters. The architecture performs a better fitting to the image dataset due to the reduction in the number of parameters involved and reusability of weights. In other words, the network can be trained to understand the sophistication of the image better.The role of the Con- vNet is to reduce the images into a form which is easier to process, without losing features which are critical for getting a good prediction.
it has several filter 
The objective of the Convolution Operation is to extract the high-level features such as edges, from the input im- age. ConvNets need not be limited to only one Con- volutional Layer. Conventionally, the first ConvLayer is responsible for capturing the Low-Level features such as edges, color, gradient orientation and many others. With added layers, the architecture adapts to the High-Level features as well, giving us a network which has the to- tally understanding of images in the dataset .let say f(i,j) is a i row and j column matrix and h(k,l) is a kernel , where i less than k and j less than l, otherwise we have to introduce zero padding in f(i,j) , and g is the convolu- tion of f and h, and The distance between two successive kernel positions is called a stride. Let the matrix rep- resenting the function f is A and the matrix representing the function h is B. For two matrices A and B of the same dimension, the array multiplication (or sweeping)
## some results :
![0](https://user-images.githubusercontent.com/72788390/142250491-f9be1aaa-6fc4-43d9-8f81-907cabdf2a27.png)
![2](https://user-images.githubusercontent.com/72788390/142250509-de9fc9d2-5ab3-4ebc-9235-c65028f0d430.png)
![3](https://user-images.githubusercontent.com/72788390/142250514-8f2812b0-9e4e-4b36-a753-bf142a996cf3.png)
