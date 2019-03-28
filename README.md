Commandes à faire :

```bash
git clone https://github.com/Nortalle/BBC_lab02.git
cd BBC_lab02
conda create --name BBC_lab02 python=3.7
conda activate BBC_lab02
pip install -r requirements.txt
jupyter notebook
```

Sauvegarder les requirements :

```bash
pip freeze > requirements.txt
```

Sauvegarder un environnement:

```bash
conda env export > environment.yml # et retirer la ligne : "prefix: " 
```

Importer un environnement:

```bash
conda env create -f environment.yml
```

Solution pour la page blanche :

```
pip uninstall notebook
pip install notebook==5.7.4
```

Solution au noyau qui ne démarre pas :

```bash
pip install "tornado<6"
```

