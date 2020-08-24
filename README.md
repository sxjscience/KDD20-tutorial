# KDD20 Tutorial: Practical Automated Machine Learning with Tabular, Text, and Image Data

Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions with just a few lines of code. Rather than relying on human time/effort and manual experimentation, models can be improved by simply letting the AutoML system run for more time. 

In this hands-on tutorial, we demonstrate fundamental techniques that enable powerful AutoML. We consider standard supervised learning tasks on various types of data including tables, text, and images. Rather than technical descriptions of individual ML models, we emphasize how to best use models within an overall ML pipeline that takes in raw training data and outputs predictions for test data. A major focus of our tutorial is on automating deep learning, a class of powerful techniques that are cumbersome to manage manually. Each topic covered in the tutorial is accompanied by a hands-on Jupyter notebook that implements best practices. 

Most of this code is adopted from [AutoGluon](https://github.com/awslabs/autogluon/), a recent AutoML toolkit that makes it easy to translate your data into highly accurate models: [autogluon.mxnet.io](https://autogluon.mxnet.io)

## Information

**Tutors:** [Jonas Mueller](http://people.csail.mit.edu/jonasmueller/), [Xingjian Shi](https://sxjscience.github.io/), [Alex Smola](https://alex.smola.org/)  (Amazon Web Services)

**Contact:** [Jonas Mueller](mailto:jonasmue@amazon.com)

**Live Q&A:** August 24, 2020: 1-4pm (PST)

**Note:** Public links to video presentations will be posted shortly.

## Setup Instructions 

### Provided GPU machine

For the week of the KDD conference, we will provide access to cloud GPUs to run the hands-on tutorials. 
To access one of these machines (which will be available to you for 6 hours), please send an email to: `kdd20-autogluon@request-nb.mxnet.io`
and you will receive an automated reply with instructions on how to get started. Once you have access to one of these instances, all prerequisite packages will already be installed and all hands-on notebooks are already available to run on the instance.

### Your own machine

Before running the hands-on tutorials on your own machine, please [install AutoGluon](https://autogluon.mxnet.io/install.html). In the installation instructions, please select the **SOURCE** option under **VERSION** which will provide you with a command to install the most up-to-date AutoGluon code (needed for Tutorials #8-10). You can alternatively use the following installation command (which will install a recent pre-release version):

`python3 -m pip install autogluon==0.0.13b20200822`

You'll also need to install MXNet by following [this guide](https://sxjscience.github.io/KDD2020/). 
Tutorial #7 also requires you to first install [Pytorch](https://pytorch.org/).

A Linux machine with GPU is recommended, although you should be able to easily run the tabular data tutorials (#1-4) on a Mac laptop as well. All tutorials should be run in either Python 3.6 or 3.7. 


## Hands-on Tutorials

[1. AutoML with Tabular data - Using AutoGluon](https://github.com/jwmueller/KDD20-tutorial/blob/master/1.TabularData-UsingAutogluon.ipynb)

[2. AutoML with Tabular data - Data Processing](https://github.com/jwmueller/KDD20-tutorial/blob/master/2.TabularData-DataProcessing.ipynb)

[3. AutoML with Tabular data - Training Models & Ensembling](https://github.com/jwmueller/KDD20-tutorial/blob/master/3.TabularData-ModelsEnsembles.ipynb)

[4. AutoML with Tabular data - Inference](https://github.com/jwmueller/KDD20-tutorial/blob/master/4.TabularData-Inference.ipynb)

[5. AutoML with Image data - Using AutoGluon](https://github.com/jwmueller/KDD20-tutorial/blob/master/5.ImageData-UsingAutoGluon.ipynb)

[6. AutoML with Image data - Hyperparameter Optimization](https://github.com/jwmueller/KDD20-tutorial/blob/master/6.ImageData-HyperparameterOptimization.ipynb)

[7. Tuning your own models](https://github.com/jwmueller/KDD20-tutorial/blob/master/7.CustomModelHPO.ipynb)

[8. AutoML with Text data - Using AutoGluon](https://github.com/jwmueller/KDD20-tutorial/blob/master/8.TextData-UsingAutoGluon.ipynb)

[9. AutoML with Text data - Customize Search Space and HPO](https://github.com/jwmueller/KDD20-tutorial/blob/master/9.TextData-CustomizationHPO.ipynb)

[10. AutoML with Text data - Mixed Data Types](https://github.com/jwmueller/KDD20-tutorial/blob/master/10.TextData-MixedDataType.ipynb)
