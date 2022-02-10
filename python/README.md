## Create environment

`conda create --name=pplearn python=3.7`


## Activate environment

`conda activate pplearn`


## Install packages

```
conda install numpy=1.19.5
conda install matplotlib=3.2.2
conda install seaborn=0.11.1
conda install scikit-learn=0.24.1
conda install keras=2.3.1
conda install jupyter=1.0.0
```


## Register environment(kernel) to Jupyter

```
conda install ipykernel
python -m ipykernel install --user --name=pplearn --display-name "Programming Machine Learning"
```


## (Optional) Remove environment(kernel) from Jupyter

```
jupyter kernelspec list
jupyter kernelspec remove pplearn
```
