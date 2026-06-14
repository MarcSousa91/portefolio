# Portfolio de Marc Sousa

Site portfolio scolaire pour Marc Sousa, étudiant en troisième année de BUT Informatique.

## Pages

- `index.html`: accueil et présentation générale.
- `projets.html`: projets Unity, web, données.
- `stages.html`: stages et missions professionnelles.
- `competences.html`: compétences techniques et référentiel BUT.
- `cv.html`: CV web imprimable et emplacement PDF.
- `contact.html`: liens et coordonnées.

## Ajouter le CV PDF

Place le fichier PDF dans:

```text
assets/media/cv-marc-sousa.pdf
```

La page `cv.html` l'affichera dans le lecteur PDF intégré et gardera aussi une version HTML imprimable.

## Lancer localement

Le site est statique. Il peut être ouvert directement avec `index.html`.

Pour un aperçu avec un serveur local:

```bash
python -m http.server 5173
```

Puis ouvrir `http://localhost:5173`.
