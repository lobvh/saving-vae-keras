# saving-vae-keras

I've looked through the Internet to find a way to save VAE (Variational Auto Encoder) model which is made in Keras, but nothing worked. Then came the idea to export weights, and encoder/decoder architecture from the instantiated VAE model itself! That worked.  

For this code to work you'll need to impelement a VAE class. I've used the original one found here: https://keras.io/examples/generative/vae/.
