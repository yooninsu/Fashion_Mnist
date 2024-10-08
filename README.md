﻿# Fashion_Mnist

 1. ResNet-18:
Architecture: You have imported ResNet-18 from the torchvision.models module. ResNet (Residual Network) is known for its skip connections that help prevent the vanishing gradient problem by allowing gradients to flow more easily through the network.
Use Case: ResNet is suitable for image classification tasks like Fashion MNIST because it enables deep network training without performance degradation. It seems you have configured it to work with the Fashion MNIST dataset, which consists of grayscale images.


  3. Wide Residual Networks (WRN-28):
Architecture: The WRN-28 (Wide Residual Network) is a variation of ResNet that increases the width of layers instead of depth. Wider networks generally perform better on some tasks as they can learn more complex features with fewer layers.

Use Case: WRN-28 is commonly used when there’s a need for powerful feature extraction with fewer layers but wider convolutions, making it suitable for datasets like Fashion MNIST.

Unfortunately, the WRN model's implementation code was not clearly visible in the snippet provided. However, it’s common to import this architecture from pre-built libraries like torchvision or from custom WRN modules.

