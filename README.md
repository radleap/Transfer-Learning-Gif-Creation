[//]: # (Image References)

[image1]: ./static/images/sailing_formula.JPG "Transfer Learning"
[image2]: ./static/images/funsail.gif "sailing gif"

## Transfer Learning: Using Convolutional Layers to Give Style to an Image

![Transfer Learning][image1]

## General Project Details

This project is a fun application of neural networks to "transfer" learned styles to a different image's content.
The feature mapped layers that are created in convultions can be used in combination to find "correlations" that represent style. A VGG-16 model, and layers are used.
An optimization function is applied to iteratively "transfer" the style. This is computationally expensive, so using a platform like heroku to operationalize would prove difficult.
However, scaled computing on AWS is a potential option to operationalize.

![sailing gif][image2]

## Data
See static for the input images. 

## Outputs
See TransferLearningGifCreate.ipynb.

## Motivation
This is a fun application of neural networks, and an interesting concept. In the right business, this could provide an interesting value proposition as seen in popular app or photography software.

## Requirements
Use Google Colab, requirements are already provided in that environment.

## License
### The MIT License (MIT)
### Copyright (c) 2020 Ben Jacobson
```
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
