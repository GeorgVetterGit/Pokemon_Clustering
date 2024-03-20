# Name Clustering

## Overview


## Table of Content
1. [Installation](#install)
2. [Content](#content)
3. [Usage](#usage)
4. [Author](#author)

## 1. Installation {#install}

This algorithm was created in python v 3.12.

The following packages are used and must be installed beforehand:
#### pandas
```
pip install pandas==2.0.3
```
#### numpy
```
pip install numpy==1.23.5
```
#### thefuzz
```
pip install thefuzz==0.22.1
```
#### sklearn
```
pip install scikit-learn==1.3.0
```
#### MatplotLib
```
pip install matplotlib==3.8.3
```
#### Networkx
```
pip install networkx==3.2.1
```
#### Networkx
```
pip install gravis==0.1.0
```

## 2. Content {#content}

The following section contains a description of the files in this package.

### TypoCreator.py
Creates Typos for a given list of strings.

### pokemon.csv
A list of strings which should be varied by the TypoGenerator.py

### clustered_typos.csv
Output of the typo generator with the Pokemon strings

### Clustering.ipynb
The Cluster algorithm which clusters the varied strings fromt he file clustered_typos.csv

### /additional material
Visualisations and project report of this project

## 3. Usage {#usage}
Create you own list of strings and load it to the typo generator. The typo generator creates the clustered_typos.csv. This file can then be clustered via the Clustering.ipynb

## 4. Author {#author}
Georg Vetter

#### Contact
georg.vetter@westnetz.de