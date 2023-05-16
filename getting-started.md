---
title: "Getting started"
slug: "getting-started"
excerpt: "Start page of Docs"
hidden: false
createdAt: "2023-05-16T13:11:01.720Z"
updatedAt: "2023-05-16T13:48:23.113Z"
---
# Description

prodiapy is a module that makes usage of [Prodia Stable Diffusion API](https://docs.prodia.com/reference/getting-started) easier with Python

# Installation

To install `prodiapy` through pip run command

`pip install -U prodiapy`

# Examples

Here simplest example of prodiapy usage:

```python txt2img
import prodia

prodia.Client(api_key="put-your-prodia-key-here")

image = prodia.txt2img(prompt="kittens on cloud")
print(image) # prints url of image 
```



> 📘 
> 
> Note that you should put your Prodia api key in "" instead of `put-your-prodia-key-here`
> 
> How to find your Prodia API key: [link to prodia docs](https://docs.prodia.com/reference/getting-started-guide)