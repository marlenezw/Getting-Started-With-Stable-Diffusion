# Getting-Started-With-Stable-Diffusion

In this tutorial I walk you through how to set up and use Stable Diffusion locally on a Mac M1. We'll use Stable Diffusion, text to speech, to generate the image of the disney princess below. I use tensorflow and the keras_cv package to convert text to images.  If you do not have a GPU, follow along with this tutorial in this [colab notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb) after running the first few cells. Thanks to [Santiago](https://www.youtube.com/@underfitted) for a great tutorial from which I got a lot of inspiration for this video)

To ensure Tensforflow can access your GPU in your Mac follow the instialltion instructions [here](https://gist.github.com/svpino/31a16d236ca730336c54e3581f5c5b1b). You'll need to install most thing using the latest version of Miniconda. 

Requirements:

- keras_cv
- tensorflow-datasets
- Python 3.8.0 
- tensorflow-metal
- tensorflow-macos

Feel free to leave a comment if you have any issues! 

![generated disney princess](https://github.com/marlenezw/Getting-Started-With-Stable-Diffusion/blob/main/princess1.jpg)

