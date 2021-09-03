# Image-Captions-and-Generating-Images
Searching and Generating Images by Using Sentences

In this projects,I am trying to training two model which are pseudo siamese network and GAN.

**Targets** :
1. Searching twenty relatively images which are described by five specific sentences.
2. Generating one similarly image by using the previous five specific sentences.

**Inputs** :
1. Five sentences in english which describe : <br>
  1.1 What's kinds of fabrics <br>
  1.2 What's the color series  <br> 
  1.3 Visualization patterns of fabric <br>
  1.4 More details of pattern descriptions  <br>
  1.5 Handfeel of fabric

**Model_Used** : 
1. (pseudo siamese network)  <br>
  1.1 pretrained_Bert <br>
    1.1.1 Ref : https://huggingface.co/bert-base-uncased
  1.2 CNN model <br>
2. GAN-GP
