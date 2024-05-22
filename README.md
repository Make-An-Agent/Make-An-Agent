## Make-An-Agent: A Generalizable Policy Network Generator with Behavior-Prompted Diffusion

This repository is the PyTorch implementation of **Make-An-Agent**, which is a conditional diffusion-based policy generator.

## Code Usage

Training the autoencoder:
~~~
cd encoder
python train.py
~~~

Training behavior embeddings:
~~~
cd embedding
python train.py
~~~

Training diffusion generator:
~~~
cd PolicyGenerator
python train.py
~~~