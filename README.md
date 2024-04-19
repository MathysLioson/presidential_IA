# Application de Prédiction des Élections Présidentielles Françaises

Cette application analyse les résultats historiques des élections présidentielles françaises pour prédire les résultats des futures élections par circonscription. Utilisant les données de 1965 à 2022, l'application prépare et traite les données pour permettre des analyses détaillées et des prédictions basées sur des modèles statistiques ou de machine learning.

## Installation

Pour installer et exécuter ce projet, suivez les étapes ci-dessous :

1. **Cloner le dépôt :**
   git clone https://github.com/MathysLioson/presidential_IA.git

2. **Installer les dépendances :**

Assurez-vous que Python 3.x est installé sur votre système. Vous pouvez ensuite installer les dépendances nécessaires via pip :

pip install pandas

## Structure du Projet

- `data_brut/`: Dossier contenant les fichiers CSV des résultats électoraux par circonscription.
- `dataset/`: Dossier où les données traitées sont enregistrées.
- `script_principal.py`: Script principal qui exécute le traitement des données et la sauvegarde des résultats.

## Utilisation

Pour exécuter le script principal et traiter les données :

python script_principal.py

Cela générera deux fichiers dans le dossier `dataset/` :

- `montpellier_data.parquet`
- `montpellier_data.csv`

## Données

Les données comprennent les résultats des élections présidentielles françaises de chaque circonscription pour les années sélectionnées de 1965 à 2022. Chaque fichier est nommé selon l'année et le tour, par exemple `cdsp_presi1965t1_circ.csv`.

## Contribution

Les contributions à ce projet sont les bienvenues. Vous pouvez contribuer de plusieurs façons :

- En proposant de nouvelles fonctionnalités ou idées.
- En améliorant le code existant ou en suggérant des améliorations.
- En rapportant des bugs.

Pour contribuer, veuillez créer une issue ou soumettre une pull request.

## Contact

Pour toute question ou suggestion, veuillez contacter @MathysLioson.
