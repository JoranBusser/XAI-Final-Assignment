# B-LRP and LIME Explanations

B-LRP and LIME are two explanation methods that can be used on image data. In these two notebooks, both explanation methods can be ran on the MNIST dataset and a folder including example images, respectively. Both folders have their own requirements.txt file.

All credit goes to the respective authors. Barely any changes were done by me.

The MNIST dataset can be found [here](http://yann.lecun.com/exdb/mnist/).

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all requirements from the requirements.txt files. If you want to do so inside of a notebook, prepend "!".

```bash
pip install -r requirements.txt
```

## Citations

Bykov, K., Höhne, M. M. C., Müller, K. R., Nakajima, S., & Kloft, M. (2020). How Much Can I Trust You?--Quantifying Uncertainties in Explaining Neural Networks. arXiv preprint arXiv:2006.09000.

Lapalap.GitHub - lapalap/B-LRP: B-LRP is the repository for the paper How Much Can I Trust You? — Quantifying Uncertainties in Explaining Neural Networks. GitHub. https://github.com/lapalap/B-LRP#

Zhao, X., Huang, W., Huang, X., Robu, V., & Flynn, D. (2021). Baylime: Bayesian local interpretable modelagnostic explanations. In C. de Campos, & M. H. Maathuis (Eds.), Uncertainty in Artificial Intelligence, 27-30 July 2021, Online (Vol. 161, pp. 887-896). (Proceedings of Machine Learning Research; Vol. 161). 

LeCun, Y., Cortes, C., & Burges, C. J. C. (2010). MNIST handwritten digit database. AT&T Labs. http://yann.lecun.com/exdb/mnist