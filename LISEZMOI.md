# Mon site enseignant (MkDocs Material)

## Mettre le site en ligne (une seule fois)

1. Créez un compte sur https://github.com.
2. Créez un dépôt **public** nommé `votrepseudo.github.io`.
3. Dans le dépôt : *Add file → Upload files*, glissez **tout le contenu** de ce dossier
   (y compris le dossier caché `.github`), puis *Commit changes*.
4. Attendez 1 à 2 minutes (onglet *Actions* : la coche doit être verte).
5. *Settings → Pages* → Source : *Deploy from a branch* → branche **gh-pages**, dossier `/ (root)` → *Save*.
6. Votre site est en ligne : `https://votrepseudo.github.io`

## Personnaliser

- `mkdocs.yml` : votre nom, l'adresse du site, téléphone, e-mail, et le menu (`nav`).
- `docs/index.md` : page d'accueil (présentation + contact).
- `docs/assets/photo.svg` : remplacez par votre photo (ex. `photo.jpg`, et changez le nom dans `mkdocs.yml` et `index.md`).
- `docs/research/index.md` : recherche et publications.

## Ajouter une UE

1. Copiez le dossier `docs/units/ue-exemple` et renommez-le (ex. `ue-reseaux`).
2. Mettez vos PDF dans `cm/`, `td/`, `tp/` et listez-les dans le `index.md` de l'UE.
3. Ajoutez l'UE dans `nav` de `mkdocs.yml` et dans le tableau de `docs/units/index.md`.

Chaque modification envoyée sur GitHub republie le site automatiquement.

## Voir le site sur votre ordinateur (facultatif)

```bash
pip install mkdocs-material
mkdocs serve
```
puis ouvrez http://127.0.0.1:8000
