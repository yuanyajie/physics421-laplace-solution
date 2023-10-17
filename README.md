# Solving Laplace's Equation Using the Relaxation Method &mdash; the Solution

This is the solution to the homework problems described in <https://github.com/yuanyajie/physics421-laplace>. The solution can be found in the jupyter notebook `LaplaceEquation_hw_solution.ipynb`.

## How to Run the Jupyter Notebook

### Running on your own machine

You can download the jupyter notebook to your own computer and run it. In order to run the jupyter notebook, you need to have python3 installed. Additionally, numpy, matplotlib,Jupyterlab are needed. You can install these by running the following commands in your terminal:

    pip install numpy
    pip install matplotlib
    pip install jupyterlab

We use [K3D Jupyter](https://github.com/K3D-tools/K3D-jupyter) for 3D visualization. You can install it by running

    pip install k3d

After installing all the above dependendies, you can start jupyter lab interface from your terminal by the following command

    jupyter lab

This will open up a browser window with the jupyter lab interface.

Alternatively, you can open and run the jupyter notebook in [Visual Studio Code](https://code.visualstudio.com/).

### Other options to run the jupyter notebook

If you are unable to run the jupyter notebook on your own machine, you can use [binder](https://mybinder.org/). Just paste the url of this github repo (https://github.com/yuanyajie/physics421-laplace), and you can launch the jupyter notebook from there. The execution may be slower because this uses shared cloud computing resources.

[Google Colab](https://colab.google/) can let you run jupyter notebooks as well, and most of the calculations are fine. Hoever, my test showed that some features of k3d does not work on google colab. Unfortunately if you would like to use k3d for some interactive 3D visualizations, google colab may not be the best choice.