# Régression Linéaire Multiple avec Python


Dans ce projet, le but est de construire un modèle de régression linéaire multiple qui sera utilisé pour la prédiction des prix des maisons.

Un agent immobilier souhaite obtenir de l'aide pour prévoir les prix des maisons dans les régions des États-Unis. Ce serait formidable si vous pouviez en quelque sorte créer un modèle qui peut lui permettre d'intégrer quelques caractéristiques d'une maison et de renvoyer une estimation du prix de la maison.
L’agent immobilier vous a demandé si vous pouviez l'aider avec vos nouvelles compétences en science des données. Vous dites oui et décidez que la régression linéaire pourrait être un bon moyen de résoudre ce problème !
Pour cela, l’argent immobilier vous donne des informations sur un échantillon de 5000 maisons dans des régions des États-Unis. Ces informations se trouvent da la table de données : **"Maisons.csv"**.

## Cette table de données contient les caractéristiques suivantes :

*	'__Revenu_moyen__' : Le revenu moyen des résidents de la ville où se trouve la maison.
*	'__Age_moyen__': L’âge moyen des maisons de la ville où se trouve la maison.
*	'__Nb_moyen_pieces__': Nombre moyen de pièces dans les maisons de la ville où se trouve la maison.
*	'__Nb_moyen_chambres__' : Nombre moyen de chambres à coucher dans les maisons de la ville où se trouve la maison.
*	'__Population__' : La population de la ville où se trouve la maison.
*	'__Prix__' : Le prix avec lequel la maison s’est vendue
*	'__Adresse__' : Adresse de la maison.

## Objectif : Appliquer la technique d'apprentissage supervisé par régression linéaire pour prédire le prix d'une nouvelle maison dont on dispose de ces caractériques.

Pour y arriver, voici les étapes effectuées pour mettre en place ce modèle de régresion:
## Etape 1: Une analyse Statistique des données comprenant 
- des Analyses desciptives 
- des Tests statistiques de normalité, linéarité, etc...
- des analyses graphiqes (boxplot, nuage de points, hsitogramme, etc...)
- matrice de corrélations

## Etape 2: Mise en oeuvre du modèle avec la bibliothèque statsmodels.api
- Splittage des données en données d'entrainnement et de test
- Normalisation des données en utilisant StandardScaler de Sklearn.preprocessing
- Model de régression avec OLS

## Etape 3: Vérification des hypothèses de la régresion linéraire
*  La linéarité des variables indépendantes avec la variable cible
*  Absence d'Auto-corrélation ou Indépendance des erreurs
*  Homoscédasticité des erreurs
*  Absence de multicolinéarité des variables explicatives
* Nullité des espérences des erreurs
* Normalité des résidus

## Etape 4: Détection et traitement de points influents/ aberants sur le modèle
- Points le Levier
- Distance de Cook
- Impact des points influents le modèle.


### Vous pouvez trouver tous les détails de ces étapes expliquées clairement dans le notebok python **Regression_Lineaire**.


##### <center> TRES BONNE LECTURE ! </center>
