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
