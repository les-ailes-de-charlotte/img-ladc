# img-ladc — images publiques des mails LADC

Servi par GitHub Pages sur **https://img.lesailesdecharlotte.com** (enregistrement CNAME chez Cloudflare, en « DNS only »).

Adresse d'une image : `https://img.lesailesdecharlotte.com/signatures/<fichier>.png`

## Ajouter une image

1. Ouvrir le dossier `signatures/` du dépôt, puis **Add file › Upload files**.
2. Glisser la ou les images.
3. En bas, laisser cochée **« Create a new branch for this commit and start a pull request »**, écrire une ligne de description, puis **Propose changes** et **Create pull request**.
4. Attendre la coche verte du contrôle « verification » (environ 30 secondes), puis **Merge pull request** et **Confirm merge**.
5. L'image est en ligne en une à deux minutes. Tester l'adresse en navigation privée.

Le contrôle refuse la proposition si elle modifie, renomme ou supprime un fichier déjà publié, si un nom contient une majuscule, un accent ou un espace, ou si une image dépasse 500 Ko. Le message d'erreur dit quoi corriger.

## Règles

- **Ne jamais remplacer ni supprimer un fichier publié.** Il est appelé par des mails déjà envoyés, et Gmail comme Outlook gardent les images en cache.
- **Nouvelle version = nouveau nom** (`olivier-v2.png`) ; l'ancienne reste en ligne. Il faut ensuite régénérer et recoller les signatures qui l'utilisent.
- Images à la taille exacte d'affichage, en PNG ; nom en minuscules, sans accent ni espace.
- Que des images publiques : logos, icônes, et portraits dont la personne a donné son autorisation écrite.
- Un dossier par usage : `signatures/` pour les signatures mail ; un autre usage (newsletter…) = un nouveau dossier.

Mis en place le 24/11/2026 (Jérémy). Pendant GAF : `img-gaf` → img.grandamourfestival.fr.
