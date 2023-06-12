# Attention 
With attention, you have a model learn which part of the input is the most important. What to pay attention to. For instance, with natural language processing you do this to reason 

Basically you have the network learn which are of the important parts of your input so that it can reason about the input with respect to the important parts. So to focucs more on the imporant parts and less on the less important part. 



OHHH so you first have a network which learns which part of the input is the most important. Then you put this before the input to your neural network, so the neural network can focus on the most essential part. 

So the attention is a layer which you first learn. This layer then learns what to focus on in the input. When this layer is trained you use it to tell another neural network what to focus on. 

With NLP, you have a sentence and the attention layer will tell you wich are the most important tokens from this sentence.

![Attention aritecture the face of the dog is the most important](images/Pasted%20image%2020220610231714.png)

So you have two neural networks. You use one nn first to extract the features (abstract representation of the input through convolution) and then you have an attention layer on these features wich will learn which of the features are the most important. This is an attention mask with for instance values lower for features more important and higher for features of higher importance.

![Attention example](images/Pasted%20image%2020220610231917.png)

In the example 1x1 convolution is used to combine multiple channels.