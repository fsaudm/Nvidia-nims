# LLMs with NIMs

This is a first look into Nvidia's NIMs, and how "easy" it becomes to run big deep learning models, including Reasoning: LLMs and the newlly released Llama 3.1, Vision, Speech, among others. 

<br>

I have included a Jupyter notebook `llama3_1.ipynb` with sample code for _**LLM reasoning**_, and on how to call and run inference on Llama 3.1: the smaller yet very powerful 8B version, as well as the massive 405B version. In this notebook, I wrapped the nomdels in simple python functions that one can call by simply running:

`llama3_1_8b("quante lingue parli?")`

(to which Llama 3.1 said: "Parlo l'italiano, l'inglese, il francese e il tedesco."...)

<br>

If you are interested in _**text-to-image generation**_, and/or _**Diffusion models**_, I have also included a Jupyter notebook with sample code to use stabilityai's Stable-Diffusion-xl, wrapped in an easy-to-use python function. I asked the model to generate a `gen_image_diffusion("A very handsome Maine Coon, sharp focus, 4k")`, and this is what I got back!


<img src="generated_image.png" alt="maine_coon" width="400"/>


<br>

**Note**: You will need an API key, which you can obtain by following the instructions on Nvidias [API catalog](https://build.nvidia.com/explore/discover). You will very likely have to install certain python libraries, which would depend on the model you want to run. To run Llama 3.1, you may want to install:
- python-dotenv
- openai
