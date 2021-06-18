# CS-439 Mini-Project : Lookahead performance for GANs training

We used for this project the GAN architectures and training code from : original gan architectures and training codes from https://github.com/lyeoni/pytorch-mnist-GAN
The code to build the Lookahead optimizers is taken from the official lookahead's paper implementation https://github.com/michaelrzhang/lookahead
We also make use of the implementation of Fréchet Inception Distance for PyTorch : https://github.com/mseitzer/pytorch-fid

Pictures generated every 20 epochs in our run are available in the "generated_pictures" folder, including the one used in our report : MNIST_SGD_epoch_200_run_3.png, MNIST_Lookahead SGD_epoch_200_run_3.png, MNIST_batch1.png, MNIST_Adam_epoch_200_run_2.png, MNIST_Adam_epoch_200_run_3.png, MNIST_Lookahead Adam_epoch_200_run_1.png.
Running the jupyter notebook reproduces our results and saves randomly generated pictures at the same level as the notebook. To run it, simply run all the cells in order. The plot used in the report as well as additional ones are displayed in the notebook.

The notebook is prerunned and shows our results.

The folder "FID_data" contains the MNIST test data as well as a folder where we store pictures generated every time we want to compute the FID.

MNIST data is present in the  "mnist_data" folder.
