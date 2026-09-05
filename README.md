# Portfolio — Salma Essaoud

Portfolio professionnel, thème cybersécurité (Red Team / Blue Team), en HTML/CSS/JS pur — sans dépendance ni build.

## Aperçu en local

```bash
cd portfolio
python3 -m http.server 8765
# puis ouvrir http://localhost:8765
```

## Ajouter le CV en PDF

Le bouton "CV (PDF)" du hero pointe vers `assets/CV_Salma_Essaoud.pdf`.
Placez votre CV compilé à cet emplacement exact (même nom de fichier) pour que le bouton fonctionne.

## Déploiement sur GitHub Pages

1. Créez un nouveau dépôt sur GitHub (public), par exemple `portfolio` ou `salma-essaoud.github.io`.
2. Depuis ce dossier :
   ```bash
   git remote add origin https://github.com/SALMA-ESSAOUD/<nom-du-repo>.git
   git branch -M main
   git push -u origin main
   ```
3. Sur GitHub : **Settings → Pages → Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
4. Le site sera disponible sous quelques minutes à :
   - `https://salma-essaoud.github.io/<nom-du-repo>/` (nom de repo classique)
   - ou `https://salma-essaoud.github.io/` directement si le repo s'appelle `salma-essaoud.github.io`.

## Structure

```
portfolio/
├── index.html
├── css/styles.css
├── js/script.js
└── assets/         # CV PDF, favicon custom, images de projets, etc.
```
