# Analyse des avis de produits Amazon

Ce script Python permet d'analyser les avis de produits Amazon en extrayant les avis à partir de l'URL d'un produit spécifique, puis en effectuant une analyse de sentiment sur ces avis.

## Prérequis

Avant d'exécuter le script, assurez-vous d'avoir les éléments suivants installés :
- Python 3.x
- Les packages Python répertoriés dans le fichier `requirements.txt`. Vous pouvez les installer en exécutant la commande suivante dans votre terminal :

```bash
pip install -r requirements.txt
```

## Exécution du script

Une fois que vous avez installé les packages requis, vous pouvez exécuter le script en utilisant Streamlit, un framework de développement web pour les applications de science des données en Python. Pour lancer l'application, exécutez la commande suivante dans votre terminal :

```bash
streamlit run streamlit_app.py
```

Cela lancera l'application Streamlit où vous pourrez fournir l'URL d'un produit Amazon et obtenir une analyse des avis associés.

Assurez-vous d'avoir une connexion Internet active pendant l'exécution du script, car il extrait les avis en temps réel depuis le site Amazon.

## URL de produits prêts à être testés

Si vous cherchez des URL de produits à utiliser pour tester le script, vous pouvez consulter le fichier `urlProduct.txt` où vous trouverez des URL de produits préparées à cet effet.



