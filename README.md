# GenderDetectionForMasked-UnMaskedImages

![Image](https://github.com/DivyanshuSingh2000/GenderDetectionForMasked-UnMaskedImages/assets/67826413/58d03c73-d8ad-4b2a-a19d-398cfa5cd0c7)


The project aims to develop a real-time gender detection system capable of accurately determining the gender of individuals in images, even when they are wearing masks. To achieve this, we have created three distinct models: Face Mask Detection, Gender Classification without Face Mask, and Gender Classification with Face Mask.

The first model, Face Mask Detection, utilizes the VGG16 architecture combined with customized Dense layers. It determines whether a mask is present in the image. If a mask is detected, the system proceeds to use the Gender Classification with the Face Mask model; otherwise, it employs the Gender Classification without the Face Mask model.

The Gender Classification without Face Mask model utilizes a CNN architecture designed specifically for this purpose, followed by dense layers for classification.

The Gender Classification with Face Mask model incorporates a fusion of the XceptionNet and DenseNet121 models, which has shown superior performance compared to using only the DenseNet121 model. This model is also followed by customized Dense layers for accurate gender classification.

By combining these three models, our system can accurately detect masks and determine the gender of individuals in real-time images.
