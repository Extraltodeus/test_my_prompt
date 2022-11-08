Made as a script for the [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) repository.
# Test my prompt!

Have you ever used a very long prompt full of words that you are not sure have any actual impact on your image? Did you lose the courage to try to remove them one by one to test if their effects are worthy of your pwescious GPU?

WELL now you don't need any courage as this script has been MADE FOR YOU!

It generate as many images as there are words in your prompt (you can select the separator of course).


![image](https://user-images.githubusercontent.com/15731540/200430459-88ed61b7-fead-40d6-b339-ab65bbaae685.png)


<sub>*A most exquisite menu*</sub>

💥Note : the separator must be the same as the one you use. The default is ", " including the space. So make sure that each and every description in your prompt is separated the same way or they will be tested together. 💥 

## Installation

Copy this file in your /scripts folder.

## Examples

Here the prompt is simply : **"banana, on fire, snow"** and so as you can see it has generated each image without each description in it.

![grid-0020-2554476-Euler a-24-12-81761151-20221107152306](https://user-images.githubusercontent.com/15731540/200349119-e45d3cfb-39f0-4999-a8f0-4671a6393824.png)
<sub>See how sad things are with no banana</sub>

Of course you can do it with more parameters.

"big titties goth gf, dress, swimsuit, beach, sunset, cloudy weather, iso100"

neg : "ugly, lowres, black and white, grascale, low quality, missing limbs, hands, painting, anime, 3d render, (wide angle:1.2), (naked:0.8)"

![grid-0012-2847822-Euler a-32-7 5-ac3abe1d-20221106213735](https://user-images.githubusercontent.com/15731540/200350301-58ef3664-7062-4ad4-b43b-bb1d9adaeab8.png)
<sub>It seems obvious that "dress" and "sunset" have a negative effect on that prompt.</sub>

You can also test your negative prompt :

![grid-0013-2847822 0-Euler a-32-7 5-ac3abe1d-20221106213903](https://user-images.githubusercontent.com/15731540/200350376-83f25611-1648-451f-8316-0ef3f2cc5fd1.png)

Another example :

![grid-0023-3893916328 0-Euler a-32-7 5-ac3abe1d-20221106223202](https://user-images.githubusercontent.com/15731540/200350566-c2b548c4-c66f-4e4a-a2c1-7e75a6400092.png)

Something very curious : removing "AUTOMATIC1111" simply removes the Gigachad from the picture.
![grid-0002-4184123397 0-Euler a-42-12 5-ac3abe1d-20221107150635](https://user-images.githubusercontent.com/15731540/200350663-13fe236d-c81f-4e0b-a009-35c229c0b8a5.png)
<sub>This may or may not have been edited.</sub>
