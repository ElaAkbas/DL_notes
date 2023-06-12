# Adversarial Training 

Adversarial Training is the technique of taking a model which is already good. Then you add some noise and then you find that the model doesn't work anymore. To make a model which can deal with noise you train it further on noisy images. 

Now you can also use a model to generate this noise which loss is a function of the inverse of the loss of your classifier. This model is then the adversarial network of your classifier. The one model tries to generate noise which will fool the other model. Then you tell the adversarial model why it failed and retrain it. 


![Adversarial Training](images/Pasted%20image%2020220611155505.png)

This basically an advanced form of [data Augmentation](Data%20Augmentation.md) where you generate noise with another network.