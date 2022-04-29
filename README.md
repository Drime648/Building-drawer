# Building-drawer

This is an AI GAN model which can draw up buildings from a basic input image. It is actually a pair of two models: one model(the generator) will draw buildings, and another(the discriminator) will try and figure out if that drawing is a real building. Both models will compete with each other to become better than the other, so they will both improve together and become strong. This way, the main model, the generator, will be able to draw seemingly real buildings that can try to fool the discriminator.
