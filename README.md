[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/L30CyvB9)
# Style transfer
Write here a short summary about your project. The text must include a short introduction and the targeted goals

Aquest projecte és un projecte de Transferència d'estils en imatges de deep learning. Té com a objectiu principal transferir estils en imatges de vista de carrer, combinant característiques textuals i visuals.

El que fa aquesta transferència d'estils és que pren una imatge de referència (anomenada "estil") i una altra imatge (anomenada "contingut"), i combina els aspectes visuals de l'estil amb el contingut de la imatge de manera que el resultat sembli que ha estat pintat amb l'estil de la imatge de referència. L'objectiu és aconseguir el millor resultat possible.

El projecte utilitza un conjunt de dades de 42.129 imatges proporcionades per 195 artistes, que es pot trobar al següent enllaç: https://paperswithcode.com/dataset/wikiart. Això proporciona una gran varietat d'estils visuals per entrenar el model.

Es oidebconsultar els enllaços proporcionats al projecte:

- https://github.com/HalbertCH/IEContraAST
- https://github.com/elleryqueenhomels/arbitrary_style_transfer/blob/master/README.md

Aquests enllaços et portaran als repositoris de GitHub relacionats amb el projecte. Potser hi trobaràs codi, documentació i altres recursos que t'ajudaran a entendre millor com es duu a terme la transferència d'estils en aquest context específic.

## Code structure
You must create as many folders as you consider. You can use the proposed structure or replace it by the one in the base code that you use as starting point. Do not forget to add Markdown files as needed to explain well the code and how to use it.

## Example Code
The given code is a simple CNN example training on the MNIST dataset. It shows how to set up the [Weights & Biases](https://wandb.ai/site)  package to monitor how your network is learning, or not.

Before running the code you have to create a local environment with conda and activate it. The provided [environment.yml](https://github.com/DCC-UAB/XNAP-Project/environment.yml) file has all the required dependencies. Run the following command: ``conda env create --file environment.yml `` to create a conda environment with all the required dependencies and then activate it:
```
conda activate xnap-example
```

To run the example code:
```
python main.py
```



## Contributors
Mireia Sempere, Maria Castellanos, Irene Castrillo

Xarxes Neuronals i Aprenentatge Profund
Grau d'Enginyeria de Dades, 
UAB, 2023
