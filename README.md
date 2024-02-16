# Denoising-images-using-GAN
GANs consist of a generator and a discriminator trained simultaneously by an adversarial process. A generator learns to create images that look real, while a discriminator learns to tell real images apart from fakes. Over time, during the training process, the generator becomes better at creating denoised samples, and the discriminator becomes better at distinguishing between clean and noisy samples. The discriminator is a CNN-based image classifier. 

![image](https://github.com/Adamo-afk/Denoising-images-using-GAN/assets/77570313/ca98dfcf-9f70-4a2b-94bc-f3357203c789)

For training the Generative Adversarial Network the SIDD dataset will be used. The GAN, if trained for a small number of epochs, gets good results in denoising the images, but the color palette of the output images is heavily affected and the image washes off over time. To get rid of this effect, the final 3x3 filter that gets generated can be normalized for better results.

![](https://github.com/Adamo-afk/Denoising-images-using-GAN/assets/77570313/9f29e9b9-98fb-4cae-ba79-332618f7b955)

