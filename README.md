# Flask Data Processing App

Cette application Flask traite et affiche les données envoyées par des modules et des passerelles. Elle permet de :
- Recevoir des données via une requête POST.
- Traiter les informations comme la température, l'humidité, la pression, etc.
- Afficher les dernières données reçues via une requête GET.

## 🚀 Fonctionnalités
- Calcul du niveau de batterie et de la durée de vie de la batterie.
- Prédictions basées sur les données du capteur (placeholder pour `bme_prediction`).
- Calcul de l'accélération et de la vitesse angulaire pour déterminer la stabilité.
- (Optionnel) Analyse des informations IP à partir d'une adresse IP (désactivé par défaut).
