# Gradient-Samples
Samples for [Gradient](https://losttech.software/gradient.html), TensorFlow binding for .NET

**[Billion Songs](https://github.com/losttech/BillionSongs)** a separate repository with
deep learning-powered song lyrics generator in an ASP.NET Core web site.

See also:
[Writing billion songs with C# and Deep Learning](https://habr.com/post/453232/)

**BasicMath**- creates two constant tensors and performs simple algebraic operations on them

**CharRNN** - generates semi-sensical text in the style of input. For example (Shakespeare):
> LOST:
> What is your name beautiful princess?
>
> COMPUTER:
> Gradient your horn of exemity.
>
> GLOUCESTER:
> how one sick up scourish, thither place and thronds the grow for these bowing.
> 
> MARIANA:
> He shall speak not reverbering injurance.

**CSharpOrNot** - a mini-ResNet convolutional network, that guesses programming language,
given a rectangular text block from a code file. Has a cross-platform UI demo.
Get pretrained model here: https://github.com/losttech/Gradient-Samples/releases/tag/csharp-or-not%2Fv1

**GPT-2** - latest English [language model from OpenAI](https://blog.openai.com/better-language-models/)
(smaller version, pretrained). Added fine-tuning from https://github.com/nshepperd/gpt-2.

**FashionMnistClassification** - standard TensorFlow example, that classifies small pictures of clothes.

**LinearSVM** - incomplete port due to a bug with tf.flags

**ResNetBlock** - same as FashionMnistClassification above, but shows `Model` subclassing
to implement ResNet block.

**RL-MLAgents** - reinforcement learning agent, that learns to play Unity 3D based games
using Soft Actor-Critic algorithm, and Unity ML agents library. More details in
[the blog post](http://ml.blogs.losttech.software/Reinforcement-Learning-With-Unity-ML-Agents/).

**SimpleApproximation** - uses a simple 1 hidden layer neural network to approximate an arbitrary function.

All models **can be modified and trained**.

**LICENSE** - MIT, individual samples might have different licenses (clearing that up, see individual sample folders).
