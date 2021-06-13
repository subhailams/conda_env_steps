## 1. Install Anaconda https://www.anaconda.com/products/individual

### Open command prompt and follow below steps

Step1 : Create conda environment

```
conda create -n ids python=3.8
```

```
conda activate ids
```

```
conda install -c anaconda ipykernel
```

```
python -m ipykernel install --user --name=ids
```

Step 2 : Install starter dependencies

```
pip install pandas
```
```
pip install numpy
```
```
pip install seaborn
```

Step 3: Download or git clone repository https://github.com/dineshh912/IoT-botnet-attack-detection

```
cd IoT-botnet-attack-detection
```

```
jupyter notebook
```

Step 4: Make sure to change the kernel of the notebook to "ids" environment to be able to import the installed packages. Open any .ipynb file and Goto Kernel -> Change Kernel -> ids

