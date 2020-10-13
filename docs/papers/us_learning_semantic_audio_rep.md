# Unsupervised Learning of Semantic Audio Representations

Papers We Love Chennai #4

**Location**: TBD

**Date and Time**: Saturday, 19 May 2018 3pm to 4.30pm (tentative)

Read the [paper](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46665.pdf)

### Abstract
Even in the absence of any explicit semantic annotation, vast collections of audio recordings provide valuable information for learning the categorical structure of sounds. We consider several class agnostic semantic constraints that apply to unlabeled nonspeech audio: (i) noise and translations in time do not change the underlying sound category, (ii) a mixture of two sound events inherits the categories of the constituents, and (iii) the categories of events in close temporal proximity are likely to be the same or related. Without labels to ground them, these constraints are incompatible with classification loss functions. However, they may still be leveraged to identify geometric inequalities needed for triplet loss-based training of convolutional neural networks. The result is low-dimensional embeddings of the input spectrograms that recover 41% and 84% of the performance of their fully-supervised counterparts when applied to downstream query-by-example sound retrieval and sound event classification tasks, respectively. Moreover, in limited-supervision settings, our unsupervised embeddings double the state-of-the-art classification performance.


**Related work**: triplet loss learning (FaceNet paper, Colin Raffel's pairwise sequence embedding for matching MIDIs with MP3s, etc.). AudioSet dataset and construction of VGGish model. DCASE 2018 competition tracks for audio machine learning.

