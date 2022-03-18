# ThesisProject
An instance of degradation problem, common in deep networks, is shown. In this toy example the usefulness of residual connections is exposed.
Tensorflow/Keras framework is used to implement the models. More on the thesis below:

## Towards advertisement clustering: two approaches based on Neural Networks
#### Abstract
The advertisement aired by radio broadcasters is one of their major incomes. The
provider, i.e. the company which owns the radio station, and the customer, i.e.
whichever subject interested in advertising a product, sign a contract in which
some aspects of the advertisement campaign are specified.
Therefore it is evident the usefulness of an automatic system which is capable
of assess the compliance with the contractual terms. A primary requirement for
such a system is to be able to univocally and as accurately as possible identify a
specific commercial break.
In this Thesis we analyze two Neural Networks approaches to carry out
the first step of the identification, i.e. the generic recognition of advertisement
segments among all the other audio contents. The first model consists of a deep
convolutional network which, taking an audio excerpt as input, it is capable of
responding with its probability of being an advertisement. The second model is
based on the TCN (Temporal Convolutional Network) architecture employed to
extract from the audio input the music and speech energies.
Moreover, to accomplish the training of these two Neural Networks, we collected
advertising, music and speech audio samples from some italian radio broadcasts,
then gathered in MUSPAD (MUsic, SPeech and ADvertisement) dataset.
The first model outperformed the second one in all the experimental results.
These noteworthy performances let us think that such a model might be employed,
within the advertisement identification system, in an industrial context.

Keywords:
Neural Networks, advertisement, clustering, classification
