# saxe_lab_tutorial_2024

1. First clone the repo with HTTPS:
```
git clone https://github.com/rodrigcd/saxe_lab_tutorial_2024
cd saxe_lab_tutorial_2024
```

or with SSH:
```
git clone git@github.com:rodrigcd/saxe_lab_tutorial_2024.git
cd saxe_lab_tutorial_2024
```

2. If you want you can create a virtual environment using conda:
```
conda create -n nndyn python>=3.11
conda activate nndyn
```

3. Then install the requirements:
```
python -m pip install -r requirements.txt
```

4. Finally install JAX:
```
conda install -c conda-forge jaxlib
conda install -c conda-forge jax
```

5. If you're using conda, you might need to run the following:
```
conda install ipykernel
ipython kernel install --user --name=my-nndyn
```

6. Open the jupyter notebook with your favorite editor or simply run:
```
jupyter notebook
```
