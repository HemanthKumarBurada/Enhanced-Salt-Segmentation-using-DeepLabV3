# Enhanced-Salt-Segmentation-using-DeepLabV3

Salt segmentation in seismic images is an essential process in the field of geophysics,
particularly in the exploration and identification of subsurface resources like oil and gas. For
companies looking for oil and gas, finding where the salt is matters a lot. Moreover, lands
affected by salt become unsuitable for farming due to reduced plant absorption capacity,
impacting growth rates. Seismic images are derived from sound waves bounced off underground
structures, offer critical insights into the Earth's composition and the presence of valuable
resources. However, these images may often contain salt formations. To identify salt-affected
areas, seismic images are analysed at the pixel level to classify them as either salt or sediment.
TGS Salt Identification Challenge dataset is used which consists of images captured from
different underground spots randomly selected. Each image is 101 x 101 pixels and every pixel
in these images is labelled as either salt or sediment. In this proposed model deeplabv3, utilizes
ASPP, studies each tiny part of the picture, noticing textures and shapes to capture features at
multiple scales. To figure out the model performance, we utilize metrics like Dice Similarity
Coefficient, Intersection over Union (IOU).


