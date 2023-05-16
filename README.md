# prodiapy
This module makes generation of image by Prodia API easier

### Installation 
```
pip install prodiapy==2.4
```
For using this script you need to get your Prodia api key, you can make it on https://app.prodia.com/api


### Example of txt2img usage
```python
import prodia

key = "your-prodia-key"

prodia.Client(api_key=key)

image = prodia.txt2img(prompt="kittens on cloud", model="dreamlike-diffusion-2.0.safetensors [fdcf65e7]")
print(image)
```
`image` variable will be a url of your image

Check Wiki for full documentation

Feel free to join out [Discord server](https://discord.gg/eAcrtqaE) and ask question!

![7eacddcb-3a45-4114-b731-3cd7af9522e1](https://user-images.githubusercontent.com/118455214/233359979-80274381-10dd-4ced-b7fa-d45437ef5bce.png)

