# ASCII Webcam

Explication de l'erreur : 

En Python, l'indentation (les espaces au début de chaque ligne) ne sont pas juste une question de lisibilité — c'est une règle syntaxique stricte. Python l'utilise pour comprendre la structure du code (ce qui est dans une fonction, dans une boucle, etc.). Le problème est qu'il existe deux façons d'indenter : avec la touche Tab ou avec des espaces. Ces deux caractères sont invisibles dans la plupart des éditeurs, ils semblent identiques à l'œil nu. Mais pour Python, ce sont des caractères complètement différents, et les mélanger dans un même fichier provoque une TabError. 

Affiche votre webcam en ASCII dans votre terminal !  

## INFO

> Affiche votre webcam en ASCII dans votre terminal !  
> Utilisé dans la vidéo : [https://youtu.be/DBnStqiLB-Q](https://youtu.be/DBnStqiLB-Q)  
> Ce projet a été inspiré par : https://github.com/uvipen/ASCII-generator

## Installation

Clonage du dépôt :

```sh
git clone https://github.com/micodeyt/ascii-webcam
cd ascii-webcam
```

Installation des dépendances :

```sh
pip install -r requirements.txt
```

## Utilisation

Commande de lancement : (dans le répertoire)

```sh
py cam.py
```

Appuyez sur `Echap` pour quiter le programme.
