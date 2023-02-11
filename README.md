Please note that this repo does not attempt to breach or condone the breaching of the Stable Diffusion license, which may be read here: [https://huggingface.co/spaces/CompVis/stable-diffusion-license](https://huggingface.co/spaces/CompVis/stable-diffusion-license)

The original repo and readme may be found here: [https://github.com/CompVis/stable-diffusion/](https://github.com/CompVis/stable-diffusion/)

The only change made has been the removal of the safety classifier, and warnings pertaining to such. All other features are preserved.

Please also note that while HF has made it so that the safety checker can be disabled in the official diffusers by using `safety_checker=None`, this will also throw a long warning, repeated numerous times through normal use of Diffusers. Additionally, users may not want the safety classifier functionality present on their machines at all. Because of this, I will continue updating this repository occasionally with the latest changes from upstream for the forseeable future.


If you have the vanilla diffusers installed, first run:
```bash
pip uninstall diffusers
```

Then, to install:
```bash
pip install git+https://github.com/WAUthethird/diffusers-uncensored.git
```