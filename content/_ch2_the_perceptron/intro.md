# The Perceptron
When discussing the perceptron, it is not always clear what exactly is meant by this term. While there is the original definition by @rosenblatt1958perceptron, there are certain parameters in an artificial neuron one can adjust for it to behave differently from the original perceptron. In this chapter, when I talk about the perceptron, I am talking about an artificial neuron with a weighted sum of an arbitrary number of inputs, uses the Heaviside step function and has precisely one binary output. We will discuss other versions of artificial neurons in a later chapter, but for now the basic perceptron is just what we want to get a good understanding of the fundamental concepts of neural networks.  



 ```{figure} images/perceptron_schematic.svg
---
name: Perceptron
alt: Perceptron
width: 80%
---
Perceptron 