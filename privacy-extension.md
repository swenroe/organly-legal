# Politique de confidentialité — Extension Chrome Organly (BETA)

## Résumé
L’extension Organly permet de capturer et annoter une capture d’écran, puis de créer une tâche Organly avec la capture en pièce jointe. Elle propose aussi un module de saisie de temps.

## Données traitées
L’extension peut traiter uniquement les données suivantes :
- **Captures d’écran** : uniquement lorsque l’utilisateur déclenche une capture.
- **Données saisies par l’utilisateur** : titre, description, tags, échéance optionnelle, saisie de temps.
- **Données d’authentification** : jeton OAuth (access token) pour appeler l’API Organly.

## Stockage
- **Localement dans le navigateur** (`chrome.storage.local`) : jeton OAuth, préférences, état du timer et brouillons.
- Aucune base externe de tracking n’est utilisée.

## Partage et transfert
- Les données (tâches, captures, entrées de temps) sont envoyées **uniquement à Organly** et **uniquement après validation** par l’utilisateur.
- **Aucune vente de données**, aucun partage à des tiers à des fins publicitaires.

## Analytics / Tracking
- **Aucun**.

## Sécurité
- L’extension utilise OAuth (Authorization Code + PKCE) pour se connecter à Organly.
- Aucun mot de passe Organly n’est stocké par l’extension.

## Contact
Pour toute question : **support@organly.io**
