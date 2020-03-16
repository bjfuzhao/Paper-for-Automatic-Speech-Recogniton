1. Patterns in Self-Supervised Learning   https://towardsdatascience.com/self-supervised-learning-78bdd989c88b

Self Supervision: To encode an object, you try to set up learning tasks between parts of it or different views of it(the self).

Given an part(intput) of the object, can you predict or generate the other part(output) of the objdect?

Changing the object's view by data augmentation and predict the same label.

You are simply playing around with the object, these are free-lunch tasks - no external labels needed.

Now we have plenty of auto-generated input-output examples, we're back in the game, and resorting to tools used for supervised learning
to learn a great representation for the object from these examples.


2. Self-Supervised Learning and the Quest for Reducing Labeled Data in Deep Learning
https://towardsdatascience.com/self-supervised-learning-and-the-quest-for-reducing-labeled-data-in-deep-learning-db59a563e25b

What made the ImageNet so hard was actually the secret ingradient to deep learning so effective, the abundance of data.

Self-supervised learning concerns learning semantically meaningful features from unlabeld data. For self-supervised training,
the pseudo-labels are soly derived from data attributes alone.

The main difference between self and supervised learning lies in the source of lables. The pesudo-labels are automatically generated
from the data itself, and used as the training targets. With self-supervised training, we can pre-train models on incredibly large
databased without worrying about human labels.

In pure classification, the network learns representations with the goal of separating the classes in the feature space; In self-supervised
learning, pretext tasks usually chanllenge the network to learn more general concepts.

By Solving the pretext task, the network will learn semantically meaningful features that can be easily transfered to learn new problems. 
In other words, the goal is to learn useful representations from unlabels data before going supervised.

3. Deep InfoMax:

4. https://self-supervised-sp.github.io/Interspeech2020-Special-Session


