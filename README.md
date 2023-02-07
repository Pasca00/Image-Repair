# Image-Repair

Small GAN model trained to repair "damaged" images (damage is simply simulated with a few straight, white lines).

Generator is a U-Net 256x256 architecture, with a PatchGAN discirminator.

Due to the nature of the dataset, the model was not able to learn how to repair actual damaged images, but it does perform decently on images with the same type of "damage".

## Results
Example of image repair on an image from the training dataset:

 * "Damaged" image:
<p align="left">
  <img src="https://github.com/Pasca00/Image-Repair/blob/master/images/train_input.png?raw=true">
</p>

 * Expected output:
<p align="left">
  <img src="https://github.com/Pasca00/Image-Repair/blob/master/images/train_target.png?raw=true">
</p>

* Actual output:
<p align="left">
  <img src="https://github.com/Pasca00/Image-Repair/blob/master/images/train_result.png?raw=true">
</p>

Example of image repair on a previously unseen image:

 * "Damaged" image:
<p align="left">
  <img src="https://github.com/Pasca00/Image-Repair/blob/master/images/test_input.png?raw=true">
</p>

 * Output:
<p align="left">
  <img src="https://github.com/Pasca00/Image-Repair/blob/master/images/test_result.png?raw=true">
</p>
