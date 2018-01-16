# Neural Style Transfer

This notebook implements deep CNN based image style transfer algorithm from "Image Style Transfer Using Convolutional Neural Networks" (Gatys et al., CVPR 2016).

The proposed technique takes two images as input, i.e. a content image (generally a photograph) and a style image (generally an artwork painting). Then, it produces an output image such that the content(objects in the image) resembles the "content image" whereas the style i.e. the texture is similar to the "style image". In order words, it re-draws the "content image" using the artistic style of the "style image".