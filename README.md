# Portfolio de Mohamed Saidi

Portfolio en ligne : systèmes embarqués et électronique.

## Contenu du dossier

| Fichier | Rôle |
| --- | --- |
| `index.html` | La page du portfolio (tout le texte est ici) |
| `images/` | Toutes les photos et figures |
| `CV_Mohamed_Saidi.pdf` | Le CV ouvert par le bouton « Voir mon CV » |

## Modifier un texte

1. Clique sur `index.html`, puis sur l'icône crayon (✏️ « Edit this file »).
2. Cherche le texte à changer avec Ctrl+F.
3. Modifie uniquement le texte **entre** les balises, par exemple :
   `<li>Mon ancien texte</li>` devient `<li>Mon nouveau texte</li>`.
4. Clique sur **Commit changes…**, puis encore sur **Commit changes**.
5. Attends 1 à 2 minutes et recharge ton site.

Les sections sont repérées dans le fichier par des lignes comme
`<!-- ================= SECTION 02 : PROJETS ================= -->`.

## Ajouter ou supprimer une compétence

Une compétence = `<span class="chip">KiCad</span>`.
Copie-colle cette ligne pour en ajouter une, ou supprime-la pour l'enlever.

## Ajouter un projet

1. Dans `index.html`, repère la ligne `<!-- ----- PROJET : ... ----- -->` d'un projet existant.
2. Copie tout le bloc depuis cette ligne jusqu'au `</article>` qui le termine.
3. Colle-le juste après, puis change le titre, le texte, les puces et les photos.

## Ajouter ou remplacer une photo

1. Ouvre le dossier `images/`, puis **Add file → Upload files** et dépose ta photo (format .jpg de préférence, moins de 1 Mo).
2. Dans `index.html`, une photo de galerie ressemble à ceci :

```html
<figure><button type="button" data-full="images/ma-photo.jpg" data-cap="Légende longue"><img src="images/ma-photo.jpg" alt="Description" loading="lazy"></button><figcaption>Légende courte</figcaption></figure>
```

Remplace `ma-photo.jpg` (deux fois) par le nom exact de ton fichier, sans espace ni accent.

**Remplacer une photo sans toucher au code :** donne à la nouvelle photo exactement le même nom que l'ancienne et dépose-la dans `images/`.

## Supprimer une photo ou un projet

Supprime la ligne `<figure>…</figure>` de la photo, ou tout le bloc `<article>…</article>` du projet.

## Mettre à jour le CV

Dépose ton nouveau CV en le nommant exactement `CV_Mohamed_Saidi.pdf` : il remplace l'ancien.

## En cas d'erreur

Ouvre l'onglet **Commits**, choisis la dernière version qui marchait et restaure le fichier, ou demande de l'aide à Claude en collant le texte de `index.html`.
