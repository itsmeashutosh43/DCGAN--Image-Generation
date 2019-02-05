Learning features of huge unlabelled data and preserving those features to create new set of data has a great scope in fashion, art and machine learning("Understanding Generative Adversarial Networks (GANs)", 2019). Here we present a machine learning model which generates images based on the feature provided by the training images. For our objective adversarial networks can learn good representations of images for supervised learning and generative modeling (Radford, Metz & Chintala, 2016).

Generative Adversarial Networks(GAN) belong to the set of generative models(Goodfellow,et al.,2014). The GAN model consists of two network
A generative network G(.) that takes in random input z and returns x_g=G(z) that should follow the targeted probability distribution.
A discriminator network D(.) that takes image vector x_image and classifies whether the generated image is real or generated.

The generator needs to learn how to create data in a way that discriminator isn’t able to distinguish as fake. The discriminator network has the task to determine if the image is real or fake. An intuitive way to understand GAN  is to imagine a forger trying to create a fake
Picasso painting (Chollet, n.d.). At first, the forger(generator) is pretty bad at this task. As times goes on, the forger becomes increasingly competent at imitating the style of Picasso, and the art dealer becomes increasingly expert at spotting fakes.In the end, they have on their hands some excellent fake Picassos. That’s what a GAN is: a forger network and an expert network, each being trained to best the other.

We have used a Deep Convolutional GAN (DCGAN) which is very similar to GAN, but specifically focuses on using Deep Convolutional networks in place of those fully-connected networks. Convolutional networks in general find areas of correlation within an image.


Results


