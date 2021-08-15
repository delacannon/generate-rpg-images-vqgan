Hey! Here is a brief guide on how AI generated the images of above using VQGAN+CLIP. It's very straightforward.

Generating an image can take between 5 and 10 minutes, sometimes even before 2' you can capture a sketch in some iteration that inspires you. 

Far from being perfect, the generated images can help you to create atmospheres, landscapes or terrifying amorphous beings  that I personally find match very well with the settings for MoSh adventures.

**Tools:**
 - Must read https://learn.adafruit.com/generating-ai-art-with-vqgan-clip
 - Gmail acount needed
 - [Colab Research VQGAN+CLIP (z+quantize method)](https://colab.research.google.com/drive/1BGPem6Vuv47MMtgzR98bvodKDFKXM3Rb) (generator)
 - [PhotoMosh](https://photomosh.com/) (post-production)

**My workflow for Mothership images:**

Let's make a monster, a **CRONOJELLY**. *When the monster hits a character with the tentacles, Body Save or target ages 2d10 years and suffers Stress equal to the result / 2* 

- Open Colab Research VQGAN+CLIP [link](https://colab.research.google.com/drive/1BGPem6Vuv47MMtgzR98bvodKDFKXM3Rb) - the first time go to *File/Save a copy in Drive*.
- Run each cell in order from top to bottom. In cell *Selección de modelos a descargar / Selection of models to download* select **wikiart_16384**:
  - Using this model I find that it generates images with better results.
- *Parámetros/Parameters* example: 
  ![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/jelly-example.png)
  

*textos/prompt* In this field is where you define the image you want to generate and the output style. The options are endless.

**image_inicial/initial_image**

*jelly4.png*

![Initial image](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/jelly4.png)

**Result:**

*original output*

![Cronojelly1](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/cronoj.png)

*post-production* 

![Cronojelly1](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/cronojelly1.png)

*CRONOJELLY post-production*

I hope this little guide will help you to experiment and generate images that will inspire you.

**Some random images I generated before with diferent styles:**

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/arrival.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/black_market.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/astrozombi.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/fortress.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/zombie-teamsters.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/arch.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/jaws.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/thing.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/bear-cyborg.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/vamp.png)

![Foo](https://raw.githubusercontent.com/delacannon/generate-rpg-images-vqgan/main/images/tatooine-corben.png)


