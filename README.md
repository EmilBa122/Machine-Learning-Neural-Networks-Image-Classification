# Machine Learning Neural Networks Image Classification

## Assignment Description
Classifying Paintings into Four Art Movements (Baroque, Impressionism, Cubism, Abstract Expressionism) with Neural Networks

## Dataset
The `wikiart_dataset.zip` file in this repository contains a subset of the wikiart dataset provided for this assignment.<br>
It includes 5,400 paintings (1,350 per class) from four art movements: Baroque, Impressionism, Cubism and Abstract Expressionism resized to 
32×32 images

List of dependencies:<br>
Libraries I use that are already pre-installed in Google Colab:<br>
numpy<br>
torch<br>
torchvision<br>
scikit-learn<br>
matplotlib<br>
pandas<br>
random<br>
os<br>
copy<br>
time<br>


Estimated running time = 1 hour and 25 minutes<br>

But the majority of this time (1 hour) is taken by the baseline CNN (no padding, no pooling, no activations) running on CPU, 
which was included deliberately to match the CPU/GPU comparison done for §2.2 and §2.3 in Section 2 (Convolutional Neural Network).
(so sorry about that)<br>
The remaining 25 minutes cover all other code in the notebook
