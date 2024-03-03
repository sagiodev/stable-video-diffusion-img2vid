# Stable Video Diffusion img2vid
## What it does
A Google Colab notebook that launches a GUI to use Stability AI's [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) (SVD) model.

The SVD model is an image-to-video model. It takes the input image as the first frame of the video and generates a short video clip using a motion prior learned from a large video dataset.

## How to use
1. Open the Colab Notebook. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sagiodev/stable-diffusion-img2vid/blob/main/stable_video_diffusion_img2vid.ipynb)
2. Review options. Run the notebook.
3. Wait for the gradio.live link to appear. Click the link to start the GUI.
4. In the GUI, upload an initial image for the video.
5. Adjust `crop offset` to get the desired crop.
6. Press `Run` to generate a video.

A full tutorial can be found [here](https://stable-diffusion-art.com/stable-video-diffusion-img2vid/).

![image](https://github.com/sagiodev/stable-video-diffusion-img2vid/assets/3319909/74d02aca-1bad-4d2d-93ca-cf521a38ee99)

## Colab runtime
It takes 9 mins on a T4 and 2 mins on a V100.

High RAM is not strictly necessary but helps to avoid crashes.

Works on free Colab.


## Advanced options
- Increase `motion bucket id` to increase the motion in the video.
- Increase `fps id` to increase the frame rate of the video.
- Fix the random as a positive integer to generate the same video.

## Known issues
The notebook may crash after a few generations when NOT using the high RAM setting. (Such as in the Free Colab runtime.)

## Credits
Thanks to these notebooks!

1. [Camenduru's SVD Colab notebook](https://github.com/camenduru/stable-video-diffusion-colab/)
2. [mkshing's SVD Colab notebook](https://colab.research.google.com/github/mkshing/notebooks/blob/main/stable_video_diffusion_img2vid.ipynb) 

## Examples


https://github.com/sagiodev/stable-video-diffusion-img2vid/assets/3319909/55f2d97a-70f1-48cd-9e3b-c3b9f924d0eb

https://github.com/sagiodev/stable-video-diffusion-img2vid/assets/3319909/854ec0b7-6cf5-4e65-ab2c-9f12c967bfdd

https://github.com/sagiodev/stable-video-diffusion-img2vid/assets/3319909/7f54c2a9-778e-47fc-a7e0-fe5f297b65c7

https://github.com/sagiodev/stable-video-diffusion-img2vid/assets/3319909/511cbcae-57e6-40a6-8b57-1d7ecbaacc4e

https://github.com/sagiodev/stable-video-diffusion-img2vid/assets/3319909/6e974023-d053-4a6c-a153-e191cdecd997



