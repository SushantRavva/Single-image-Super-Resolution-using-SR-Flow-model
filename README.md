# Single-image-Super-Resolution-using-SR-Flow-model
Used SR-FLOW model, which is a flow based model to enhance the quality of images by increasing the resolution.

# Flow-Based Methods
The normalizing flow was first introduced
to learn an exact mapping from data distribution to a latent
distribution by using the tractability of exact log-likelihood.
Unlike GAN which learns an implicit density, the normalizing flow explicitly computes the probability density.
For the SR task, a conditional normalizing flow method with
affine coupling layers was employed in. However, the
scale factor was limited to ×2 SR task. Recently, SRFlow applied a similar approach for ×4 and ×8 SR tasks
and successfully generated diverse SR results.

# Wgat is SR-Flow and how does it work?
SRFlow: a normalizing flow based super-resolution method capable of learning the 
conditional distribution of the output given the low-resolution input. 
Our model is trained in a principled manner using a single loss, namely the negative log-likelihood.

SRFlow maps HR images to a latent space thanks to the tractable loss function of the normalizing 
flow, and generates diverse HR images from an input random variable sampled from the latent space with the con- ditional LR image.
