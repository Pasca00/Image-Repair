# Image-Repair

Small GAN model trained to repair "damaged" images (damage is simply simulated with a few straight, white lines).

Generator is a U-Net 256x256 architecture, with a PatchGAN discirminator.

Due to the nature of the dataset, the model was not able to learn how to repair actual damaged images, but it does perform decently on images with the same type of "damage".
