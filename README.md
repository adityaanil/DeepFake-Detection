# DeepFake-Detection

*Face swapping* refers to the process of transferring one person’s face from a source image to another person in a target image, while maintaining photo-realism.

It has a number of applications in cinematic entertainment and gaming. However, it could be used for malicious purposes as well. For example, "Deep Fake" is one such project that uses GANS  or *generative adversial networks* to produce videos showing people doing or saying something that they haven't done before. While most uses of such technology are harmless some terrible cases do exist. One such where this was used to create compromising images of celebraties by face swapping. 
A detection system could have prevented this type of harassment before it caused public harm.

Common Steps:

1. A face detctor is applied to narrow down the facial region (ROI).
2. The head position and the facial landmarks are used to build a perspective model.
3. Adjustments are made to fit the new image in the ROI.
4. Blending that fuses the source face into the target area.




