# Image-Captions-and-Generating-Images
Searching and Generating Images by Using Sentences

In this projects,I am trying to training two model which are pseudo siamese network and GAN.
Besides, I am trying to use the pretrained Speech2Text model which released by facebook's team.

**Targets** :
1. Searching twenty relatively images which are described by five specific sentences.
2. Generating one similarly image by using the previous five specific sentences.
3. Convert speech files(.wav) to text.

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
    1.1.1 Ref : https://huggingface.co/bert-base-uncased <br>
  1.2 CNN model <br>
2. GAN-GP <br>
3. facebook/hubert-large-ls960-ft model <br>
  3.1 Ref : https://huggingface.co/facebook/hubert-large-ls960-ft <br>

# Result
![result](https://user-images.githubusercontent.com/55430748/135552868-091092d9-9891-4b5a-a3d6-bceb52a6f568.png)
