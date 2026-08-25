# Awesome Neural Art with stars

*Update, May 2026:* I started this repo in 2018. Since then, neural art has come a very long way. I'm keeping this page around as a time capsule of the early days of neural art.

Creating art and manipulating images using deep neural networks.

## Contents

* [Colorization](#colorization)
* [Style Transfer](#style-transfer)
* [Super Resolution](#super-resolution)
* [Patching](#patching)
* [Background subtraction](#background-subtraction)
* [Deep Dream](#deep-dream)
* [Interactive art](#interactive-art)
* [Multiple categories](#multiple-categories)
* [Lectures](#lectures)

## Colorization

See also: [Awesome Image Colorization](https://github.com/MarkMoHR/Awesome-Image-Colorization) ⭐ 1,163 | 🐛 6 | 📅 2026-08-21 and the [colorization subreddit](https://www.reddit.com/r/Colorization) where people do this manually.

* [Interactive Deep Colorization](https://github.com/junyanz/interactive-deep-colorization) ⭐ 2,692 | 🐛 32 | 🌐 Python | 📅 2022-07-29

<img src='https://github.com/junyanz/interactive-deep-colorization/blob/master/imgs/demo.gif' width=600>  

<img src='https://richzhang.github.io/ideepcolor/index_files/imagenet_showcase_small.jpg' width=800>

* [colornet](https://github.com/pavelgonchar/colornet) ⭐ 3,552 | 🐛 14 | 🌐 Python | 📅 2020-04-21

<img src='https://raw.githubusercontent.com/pavelgonchar/colornet/master/summary/209000_0.png' width=600>  

* [Colorful Image Colorization](https://github.com/richzhang/colorization) ⭐ 3,461 | 🐛 59 | 🌐 Python | 📅 2023-11-27

<img src='https://camo.githubusercontent.com/0f54d76e1561911ef2c423251c386a9368551365/687474703a2f2f726963687a68616e672e6769746875622e696f2f636f6c6f72697a6174696f6e2f7265736f75726365732f696d616765732f746561736572342e6a7067' width=600>  

## Style Transfer

* [neural-style](https://github.com/jcjohnson/neural-style) ⭐ 18,285 | 🐛 316 | 🌐 Lua | 📅 2018-02-23 - Torch implementation of neural style algorithm.

<img src='https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/starry_stanford_bigger.png' width=600>  

* [fast-style-transfer](https://github.com/lengstrom/fast-style-transfer#image-stylization) ⭐ 10,963 | 🐛 112 | 🌐 Python | 📅 2023-07-16 - TensorFlow CNN for fast style transfer with larger scale style features in transformations.
* [deep-photo-styletransfer](https://github.com/luanfujun/deep-photo-styletransfer) ⭐ 9,989 | 🐛 34 | 🌐 Matlab | 📅 2021-08-02 - Code and data for ["Deep Photo Style Transfer"](https://arxiv.org/abs/1703.07511).
* [AdaIN-style](https://github.com/xunhuang1995/AdaIN-style) ⭐ 1,567 | 🐛 15 | 🌐 Lua | 📅 2017-10-30 - Code for [Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization](https://arxiv.org/abs/1703.06868). Contains neat features such as transfering style without color, style interpolation, and spatial control.
* [texture\_nets](https://github.com/DmitryUlyanov/texture_nets) ⭐ 1,225 | 🐛 42 | 🌐 Lua | 📅 2018-01-07 - Code for "Texture Networks: Feed-forward Synthesis of Textures and Stylized Images".
* [adaptive-style-transfer](https://github.com/tensorlayer/adaptive-style-transfer) ⭐ 114 | 🐛 6 | 🌐 Python | 📅 2021-12-03 - Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization.

<img src='https://raw.githubusercontent.com/xunhuang1995/AdaIN-style/master/examples/style_interp.jpg' width=600>  
<img src='https://raw.githubusercontent.com/xunhuang1995/AdaIN-style/master/examples/spatial_control.jpg' width=600>  

* [Bicycle GAN](https://github.com/junyanz/BicycleGAN) ⭐ 1,514 | 🐛 21 | 🌐 Python | 📅 2020-08-05 - NIPS 2017 Toward Multimodal Image-to-Image Translation, PyTorch implementation. Given the same night image, model is able to synthesize possible day images with different types of lighting, sky and clouds.

<img src='https://github.com/junyanz/BicycleGAN/blob/master/imgs/results_matrix.jpg' width=820>  

* [Deep Painterly Harmonization](https://github.com/luanfujun/deep-painterly-harmonization) ⭐ 6,041 | 🐛 34 | 🌐 Cuda | 📅 2021-08-02 - Photoshopping an object into a painting, and then neural network changes the style (pallete, strokes, luminosity, etc) of the object to match the painting style. [See paper](https://arxiv.org/abs/1804.03189).
* [Neural Style Transfer](https://github.com/titu1994/Neural-Style-Transfer) ⭐ 2,288 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2023-02-13 - Keras Implementation of Neural Style Transfer from the paper ["A Neural Algorithm of Artistic Style"](http://arxiv.org/abs/1508.06576) in Keras 2.0+.

## Super Resolution

* [waifu2x](https://github.com/nagadomi/waifu2x) ⭐ 28,211 | 🐛 154 | 🌐 Lua | 📅 2023-05-04 - Image Super-Resolution for Anime-Style Art.

<img src='https://raw.githubusercontent.com/nagadomi/waifu2x/master/images/slide.png' width=820>  

* [srgan](https://github.com/tensorlayer/srgan) ⭐ 3,467 | 🐛 153 | 🌐 Python | 📅 2024-02-22 - Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network.

<img src='https://raw.githubusercontent.com/tensorlayer/srgan/master/img/SRGAN_Result3.png' width=820>  

* [fft-descreen](https://github.com/6o6o/fft-descreen) ⭐ 82 | 🐛 4 | 🌐 Python | 📅 2020-03-06 - Clean up deconvolution checkerboard artifacts found in style transferred images.

## Patching

AKA in-painting

* [DeepFill V1](https://github.com/JiahuiYu/generative_inpainting) ⭐ 3,466 | 🐛 76 | 🌐 Python | 📅 2024-06-27 - Generative Image Inpainting with Contextual Attention.
* [EdgeConnect](https://github.com/knazeri/edge-connect) ⭐ 2,620 | 🐛 108 | 🌐 Python | 📅 2024-02-03 - a two-stage adversarial model that comprises of an edge generator followed by an image completion network.
  <img src='https://user-images.githubusercontent.com/1743048/50673917-aac15080-0faf-11e9-9100-ef10864087c8.png' width=820>
* [Deep Image Completion](https://github.com/adamstseng/general-deep-image-completion) ⭐ 75 | 🐛 4 | 🌐 Python | 📅 2018-05-07 - Contains face-completion and general image completion models. Each can complete images with differnet types of corrupted masks like scribbles, lines, dots and texts.
  <img src='https://raw.githubusercontent.com/adamstseng/general-deep-image-completion/master/general-completion.jpg' width=820>

## Background subtraction

AKA image matting. See also: [Awesome Background Subtraction](https://github.com/murari023/awesome-background-subtraction) ⭐ 531 | 🐛 4 | 📅 2021-09-25

* [DeepLab V3+](https://github.com/jfzhang95/pytorch-deeplab-xception) ⭐ 3,000 | 🐛 134 | 🌐 Python | 📅 2024-08-04 - Implementations of an encoder-decoder Modified Aligned Xception and ResNet as backbone [(paper)](https://arxiv.org/pdf/1802.02611.pdf).

* [Salient Object Detection](https://github.com/Joker316701882/Salient-Object-Detection) ⭐ 444 | 🐛 25 | 🌐 Python | 📅 2021-12-24 - Tensorflow implementation for cvpr2017 paper ["Deeply Supervised Salient Object Detection with Short Connections"](https://arxiv.org/abs/1611.04849) (not peer reviewed). Same author as original Deep Image Matting author.

* [AlphaGAN](https://github.com/CDOTAD/AlphaGAN-Matting) ⭐ 154 | 🐛 12 | 🌐 Python | 📅 2020-07-19 - Unofficial implementation of [AlphaGAN: Generative adversarial networks for natural image matting](https://arxiv.org/pdf/1807.10088.pdf). Uses a GAN as the name suggests.

* Deep Image Matting - Implementations of the [Deep Image Matting paper](https://sites.google.com/view/deepimagematting).
  * [PyTorch implementation](https://github.com/foamliu/Deep-Image-Matting-v2) ⭐ 831 | 🐛 4 | 🌐 Python | 📅 2020-01-09 - Same author as [Keras implementation](https://github.com/foamliu/Deep-Image-Matting) ⭐ 990 | 🐛 6 | 🌐 Python | 📅 2019-08-20, but this is their improved (and maintained) codebase.
  * [Tensorflow implementation](https://github.com/Joker316701882/Deep-Image-Matting) ⭐ 624 | 🐛 39 | 🌐 Python | 📅 2018-09-21 - Original paper author.
  * [Another PyTorch implementation](https://github.com/huochaitiantang/pytorch-deep-image-matting) ⭐ 297 | 🐛 32 | 🌐 Python | 📅 2022-11-22
  * [Dataset generator](https://github.com/hector-sab/DIM_DataCreation) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2017-09-25 - Generates training data for the Deep Image Matting paper.

## Deep Dream

* [deepdream](https://github.com/google/deepdream) ⚠️ Archived - The original Google implementation.

## Interactive art

* [neural-doodle](https://github.com/alexjc/neural-doodle) ⚠️ Archived -
  Turn your two-bit doodles into fine artworks with deep neural networks, generate seamless textures from photos, transfer style from one image to another, perform example-based upscaling, but wait... there's more! (An implementation of Semantic Style Transfer.)

<img src='https://github.com/alexjc/neural-doodle/blob/master/docs/Workflow.gif' width=820>  

* [iGAN](https://github.com/junyanz/iGAN) ⭐ 4,005 | 🐛 14 | 🌐 Python | 📅 2020-08-05 - iGAN: Interactive Image Generation via Generative Adversarial Networks.

<img src='https://raw.githubusercontent.com/junyanz/iGAN/master/pics/demo.gif' width=820>  

* [style2paints](https://github.com/lllyasviel/style2paints/) ⭐ 18,179 | 🐛 54 | 🌐 JavaScript | 📅 2023-08-01 - An AI-driven interactive line art colorization tool. Backend is a Residual U-net and Auxiliary Classifier GAN.

## Multiple categories

* [deep-image-prior](https://github.com/DmitryUlyanov/deep-image-prior) ⭐ 8,088 | 🐛 70 | 🌐 Jupyter Notebook | 📅 2023-04-27 -  Image restoration with neural networks but without learning. Does artifact removal, inpainting, super-resolution, denoising.

## Lectures

* [Neural Style Transfer Review](https://github.com/ycjing/Neural-Style-Transfer-Papers) ⭐ 1,638 | 🐛 4 | 📅 2022-02-21 - Repo for the [Neural Style Transfer review article](https://arxiv.org/abs/1705.04058).
* [The Neural Aesthetic @ ITP-NYU, Fall 2018](https://ml4a.github.io/classes/itp-F18/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Richard Decal](https://www.richarddecal.com) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
