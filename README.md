# Bayesian Data Analysis Python Demos

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/avehtari/bda_py_demos) to interactively run the IPython Notebooks in the browser.

This repository contains some Python demos for the book [Bayesian Data
Analysis, 3rd ed by Gelman, Carlin, Stern, Dunson, Vehtari, and Rubin (BDA3)](http://www.stat.columbia.edu/~gelman/book/). See also [Bayesian Data Analysis course material](https://github.com/avehtari/BDA_course_Aalto).

Currently there are demos for BDA3 Chapters 2, 3, 4, 5, 6, 10 and 11. Furthermore, [cmdstanpy](https://mc-stan.org/cmdstanpy/) is also demoed.

Demos are in jupyter notebook (.ipynb) format. These can be directly previewed in GitHub without need to install or run anything.

Corresponding demos were originally written for [Matlab/Octave](https://github.com/avehtari/BDA_m_demos) by [Aki Vehtari](http://users.aalto.fi/~ave/) and translated to Python by Tuomas Sivula. Some improvements were contributed by Pellervo Ruponen and Lassi Meronen. There are also corresponding [R demos](https://github.com/avehtari/BDA_R_demos).


## Installation

This project uses [pixi](https://pixi.sh/) to manage dependencies.

1. **Install pixi:** If you don't have pixi installed, you can find the installation instructions [here](https://pixi.sh/latest/#installation).

2. **Install dependencies:** Open a terminal and navigate to the project's root directory. Then, run the following command to install all the necessary packages:

   ```bash
   pixi install
   ```

3. **Run Jupyter:** With the dependencies installed, you can start Jupyter Notebook to run the demos:

   ```bash
   pixi run jupyter notebook
   ``` 