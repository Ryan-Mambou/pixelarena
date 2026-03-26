# CP3 — La Résurrection

## Contexte

Bienvenue chez **PixelArena** ! Vous venez d'etre embauche comme developpeur frontend.

Le developpeur precedent a quitte l'entreprise precipitamment. Son code... disons qu'il a ses particularites.

Votre manager vous demande une modification "simple" :

> "Change la couleur du bouton JOIN dans le Lobby. Le bleu ne va pas avec notre nouvelle charte graphique. Mets-le en **vert** (#10b981). Ca devrait prendre 5 minutes."

## Installation

```bash
# Terminal 1
cd mfe-header && npm install && npm start   # → localhost:3001

# Terminal 2
cd shell && npm install && npm start        # → localhost:3000
```

L'application demarre sur http://localhost:3000

## Votre Mission

### Objectif

Changer la couleur du bouton "JOIN" dans le Lobby de **bleu** (#3b82f6) vers **vert** (#10b981).

### Fichier a modifier

`src/components/Lobby.css`

### Ce que vous devez faire

1. Ouvrir `src/components/Lobby.css`
2. Trouver la classe `.button`
3. Changer `background: #3b82f6` en `background: #10b981`
4. Sauvegarder

### Resultat attendu

Seul le bouton "JOIN" du Lobby devrait devenir vert.

---

## Validation du Checkpoint

<<<<<<< Updated upstream
Apres avoir fait la modification, repondez a ces questions :

1. Le bouton "JOIN" est-il devenu vert ?
2. Les autres boutons ont-ils change de couleur aussi ?
3. Si oui, pourquoi selon vous ?

---

## Structure du projet

````
pixelarena-checkpoint1/
├── src/
│   ├── index.js
│   ├── App.jsx
│   ├── App.css
│   └── components/
│       ├── Navbar.jsx
│       ├── Navbar.css      <- Equipe Navbar
│       ├── Lobby.jsx
│       ├── Lobby.css       <- Equipe Lobby (MODIFIER ICI)
│       ├── Leaderboard.jsx
│       └── Leaderboard.css <- Equipe Leaderboard
├── public/
│   └── index.html
├── package.json
└── webpack.config.js
=======
### mfe-header/webpack.config.js — 4 TODOs

```js
name: 'mfeHeader',
filename: 'remoteEntry.js',
exposes: { './Navbar': './src/components/Navbar' },
shared: { react: { singleton: true }, 'react-dom': { singleton: true } },
````

### shell/webpack.config.js — 1 TODO

```js
remotes: {
  mfeHeader: 'mfeHeader@http://localhost:3001/remoteEntry.js',
},
>>>>>>> Stashed changes
```

---

<<<<<<< Updated upstream
Bonne chance !

# pixelarena

=======

## Validation

- http://localhost:3000 affiche le Header chargé depuis le port 3001
- Push ta branche
  > > > > > > > Stashed changes
