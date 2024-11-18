
# Projet de page de connexion

## Description
Ce projet est une page de connexion moderne et réactive construite avec React et stylisée avec Tailwind CSS. Il fournit une interface utilisateur élégante pour l'authentification de l'utilisateur, avec des options de connexion par email/mot de passe et d'authentification Google.

## Caractéristiques
- Interface utilisateur propre et intuitive
- Champs de saisie d'email et de mot de passe
- checkbox « Se souvenir de moi
- lien « mot de passe oublié
- Bouton de connexion par courriel/mot de passe
- Bouton de connexion avec Google
- Possibilité de créer un nouveau compte
- Conception réactive

## Technologies utilisées
- React
- Tailwind CSS

## Installation
1. Clonez le dépôt :
   ```
   git clone https://github.com/EvansNzati007/LoginFormWithReact-TailwindCss.git
   ```
2. Naviguez vers le répertoire du projet :
   ```
   cd LoginPageProject
   ```
3. Installez les dépendances :
   ```
   npm install
   ```

## Utilisation
Pour lancer le serveur de développement :
```
npm run dev
```
L'application sera disponible à `http://localhost:3000`.

## Structure du projet
- `src/composants/Form.jsx` : Contient le composant principal du formulaire de connexion
- `src/app.jsx` : contient le composant principal du formulaire  

## Personnalisation
Le formulaire de connexion peut être facilement personnalisé en modifiant les classes CSS de Tailwind dans le fichier `Form.jsx`. Vous pouvez ajuster les couleurs, l'espacement et d'autres styles pour répondre aux exigences de conception de votre projet.

## Améliorations futures
- Implémenter la validation des formulaires
- Ajouter des fonctionnalités aux boutons de connexion et d'authentification Google
- Intégrer un backend avec NodeJs , Php ou avec SpringBoot 