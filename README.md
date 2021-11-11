# DocDenoiser
### Document denoiser using Pytorch Autoencoder

### Autoencoder
An autoencoder is a type of artificial neural network used to learn efficient data codings in an unsupervised manner. The aim of an autoencoder is to learn a representation (encoding) for a set of data, typically for dimensionality reduction, by training the network to ignore signal - in this case 'noise'. Along with the reduction side, a reconstructing side is learnt, where the autoencoder tries to generate from the reduced encoding a representation as close as possible to its original input, hence its name.

### Basic information:
- Dataset - Kaggle dataset ["Denoising Dirty Documents"](https://www.kaggle.com/c/denoising-dirty-documents).
- Training was done using [Google Colab](https://colab.research.google.com/) (basic) and took approximately 30 min for 100 epochs.
- Architecture:
Input shape (1, 540 , 420) 
- ![architecture](https://user-images.githubusercontent.com/74296883/141296168-85d1d901-ada8-4245-9e7c-5bce11e9d2be.jpg)

### Results
| Image with noise  | Denoised image |
| ------------- | ------------- |
|  ![images-with-noise-0099](https://user-images.githubusercontent.com/74296883/141296995-12175e4f-f4e4-4319-893e-5fb19e60650b.png)| ![denoised-images-0099](https://user-images.githubusercontent.com/74296883/141297149-ef787594-2123-4d3d-9ba6-13016d1112f0.png)|
