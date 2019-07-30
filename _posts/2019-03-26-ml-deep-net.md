---
title: "ML: Neural Network and Deep learning"
date: 2019-03-26
permalink: /posts/2019/03/deep-net/
tags:
  - adavanced
  - machine learning
  - python
---

_Machine Learning: An article explores neural network/._
The goal of a feedforward network is to approximate some functionf∗. For example,for a classiﬁer,y=f∗(x) maps an inputxto a categoryy. A feedforward networkdeﬁnes a mappingy=f(x;θ) and learns the value of the parametersθthat resultin the best function approximation.

These models are calledfeedforwardbecause information ﬂows through thefunction being evaluated fromx, through the intermediate computations used todeﬁnef, and ﬁnally to the outputy. There are nofeedbackconnections in whichoutputs of the model are fed back into itself. When feedforward neural networksare extended to include feedback connections, they are calledrecurrent neuralnetworks

Feedforward neural networks are callednetworksbecause they are typicallyrepresented by composing together many diﬀerent functions. The model is asso-ciated with a directed acyclic graph describing how the functions are composedtogether. For example, we might have three functionsf(1),f(2), andf(3)connectedin a chain, to formf(x) =f(3)(f(2)(f(1)(x))). These chain structures are themost commonly used structures of neural networks. In this case,f(1)is calledtheﬁrst layerof the network,f(2)is called thesecond layer, and so on. The overall length of the chain gives thedepthof the model. The name “deep learning”arose from this terminology. The ﬁnal layer of a feedforward network is called theoutput layer.

During neural network training, we drivef(x) to matchf∗(x).The training data provides us with noisy, approximate examples off∗(x) evaluatedat diﬀerent training points. Each examplexis accompanied by a labely ≈ f∗(x).The training examples specify directly what the output layer must do at each pointx; it must produce a value that is close to y. The behavior of the other layers isnot directly speciﬁed by the training data. The learning algorithm must decidehow to use those layers to produce the desired output, but the training data donot say what each individual layer should do. Instead, the learning algorithm mustdecide how to use these layers to best implement an approximation of f∗. Becausethe training data does not show the desired output for each of these layers, theyare called hidden layers.

Each hidden layer of the network is typically vector valued. Thedimensionality of these hidden layers determines thewidthof the model. Eachelement of the vector may be interpreted as playing a role analogous to a neuron. Each unit resembles a neuron inthe sense that it receives input from many other units and computes its ownactivation value. 

It is best to think offeedforward networks as function approximation machines that are designed toachieve statistical generalization, occasionally drawing some insights from what weknow about the brain, rather than as models of brain function.

References:
Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep learning. MIT press.