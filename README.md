# BDM Feuille de temps

Application simple de feuille de temps (frontend statique).

Usage
- Ouvrir `index.html` dans un navigateur (ou servir le dossier avec un serveur HTTP).
- L'application sauvegarde les entrées automatiquement dans le stockage local (localStorage).
- Vous pouvez exporter les entrées en CSV via le bouton "Exporter CSV".

Développement local
- Servir le dossier racine via un serveur HTTP (recommandé) :
  - Python 3: `python -m http.server 8000`
  - Node (http-server): `npx http-server -c-1 .`

Structure proposée
- index.html        - interface
- src/app.js        - logique JS (persist, calcul, export)
- README.md         - instructions
- LICENSE           - MIT

Si vous voulez que j'ajoute un build (webpack/vite) ou des tests, dites-le et je propose une configuration.
