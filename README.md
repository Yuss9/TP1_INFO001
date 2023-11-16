# TP1_INFO001
 TP1 sécurité des applications.
 
[Lien github ici](https://github.com/Yuss9/TP1_INFO001)

## IMPORTANT
Tous fonctionne.

Pour faire fonctionner le projet il faut avoir trois fichiers dans le projet au même endroit que le serveur.py et client.py : voici les noms des trois fichiers : 
- serveur_http.cert.pem
- serveur_http.pem
- root_ca.cert.pem

Voici les coordonnées du serveur de nous deux : 
```bash
ssh etudiant@192.168.170.156 
```
mdp yurtseven

```bash
ssh etudiant@192.168.170.112
```
mdp fernandez

## Authors
 - [@Yuss9](https://github.com/Yuss9) Huseyin YURTSEVEN
 - [@Ygdrazil](https://github.com/Ygdrazil) Volodia FERNANDEZ 

## LANCEMENT



```bash
sudo dnf install python3-pip
```


```bash
pip install cryptography
```

Dans la VM :

```bash
ssh etudiant@192.168.170.156 
```
mdp yurtseven

```bash
ssh etudiant@192.168.170.112
```
mdp fernandez

Dans deux terminaux.

```bash
python3 serveur.py
```

```bash
python3 client.py
```

## Tech Stack

**Server:** Python


![Logo](https://images.ctfassets.net/mrop88jh71hl/55rrbZfwMaURHZKAUc5oOW/9e5fe805eb03135b82e962e92169ce6d/python-programming-language.png)
