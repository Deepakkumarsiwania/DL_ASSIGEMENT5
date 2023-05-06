# DL_ASSIGEMENT5
Train a DCGAN to generate images from noise. Use the EMNIST(Extended MNIST)
database to learn the GAN
Discriminator in DCGAN:-
i. if roll no. % 2 == 0: use VGG11 as a discriminator.
Answer:

1.Imported all required library 
2. We import the eminest dataset loaded into the  data loader.
3.we create the generator network  and discriminator network
4. As my roll number 004 i taken the VGG11 as network
5.then we train the GAN network  for ten epoch=10,optimizer =adam. Lr=.0002,beta =0.5,0.970
6 batch_size = 64
image_size = 64
7.loss_D and loss _G
1.we git clone the style Gan
2. Provide the see from the generation of image seed 0-5
3.Then we get the random images

Part2:
nowTake your face image and 5 different face images of your friends (One image per friend).
Perform feature disentanglement and linear interpolation between your face and your
friend's face.
1.first we taken image source and  target image of five friends
2.we preprocess the image for the best out put in in styleGan
3.plot the images  source and target images
4.convert target to a GAN and source to GAN
5.create the video and divide it into the frames.
Image are:
