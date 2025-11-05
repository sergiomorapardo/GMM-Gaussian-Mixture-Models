# GMM: Gaussian Mixture Models

Instructor: _Sergio Alberto Mora Pardo_
* email: [sergiomora823@gmail.com](mailto:sergiomora823@gmail.com)
* LinkedIn: [sergiomorapardo](https://www.linkedin.com/in/sergiomorapardo/)
* github: [sergiomorapardo](https://github.com/sergiomorapardo)

### Overview

This is the code for Siraj Raval as part of The Math of Intelligence series. 
This is a lesson on Gaussian Mixture Models, they are probability distributions that consist of multiple Gaussian distributions.
This is useful for modeling more complex data, that has multiple peaks. Sometimes one bell curve isn't enough. We can optimize
this model for clustering so that we can classify the data into the discovered classes using the Expectation Maximization
algorithm. 

## Notebook

|Date|Description|Path|
|----|-----------|----|
| 01-08-2020 |Intro to GMM|[intro_to_gmm_em.ipynb](https://nbviewer.jupyter.org/github/sergiomorapardo/Gaussian_Mixture_Models/blob/master/intro_to_gmm_%26_em.ipynb)|
| 01-08-2020 |GMM covariances|[plot_gmm_covariances.ipynb](https://nbviewer.jupyter.org/github/sergiomorapardo/GMM-Gaussian-Mixture-Models/blob/master/plot_gmm_covariances.ipynb)|
| 15-08-2020 |Example GMM|[gmm_restaurant.ipynb](https://nbviewer.jupyter.org/github/conorosully/medium-articles/blob/master/src/gmm_restaurant.ipynb)|
| 15-08-2020 |data GMM|[datos_gmm](https://github.com/ajpelaezr/datos_gmm)|
| 15-08-2020 |Aplicación GMM|[15082020.ipynb](https://nbviewer.jupyter.org/github/sergiomorapardo/GMM-Gaussian-Mixture-Models/blob/master/15082020.ipynb)|

## Aditional (Bonus)

|Date|Description|Path|
|----|-----------|----|
| 15-08-2020 | Density Estimation for a Gaussian mixture |[plot_gmm_pdf.ipynb](https://nbviewer.jupyter.org/github/sergiomorapardo/GMM-Gaussian-Mixture-Models/blob/master/plot_gmm_pdf.ipynb)|
| 15-08-2020 |  Gaussian Mixture Model Selection  |[plot_gmm_selection.ipynb](https://nbviewer.jupyter.org/github/sergiomorapardo/GMM-Gaussian-Mixture-Models/blob/master/plot_gmm_selection.ipynb)|

## Dependencies

* numpy 
* matplotlib
* scipy
* seaborn

Install missing dependencies with [pip](https://pip.pypa.io/en/stable/)

## Usage

Just run `jupyter notebook` in terminal and the code will pop up in your browser

Install jupyter [here](http://jupyter.readthedocs.io/en/latest/install.html).

## Credits

The credits for this code go to [bspiering](https://github.com/brianspiering). Ive merely created a wrapper to get people started

## Sklearn
[GaussianMixture](https://scikit-learn.org/stable/modules/generated/sklearn.mixture.GaussianMixture.html#sklearn.mixture.GaussianMixture)

