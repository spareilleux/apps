# apps

Applications web installables, publiées sur https://spareilleux.github.io/apps/.

- **IxForge** (`ixforge/`) : des listes et des compteurs gardés dans le navigateur, hors ligne, sans compte. IA facultative avec la propre clé API Claude de la personne (la clé reste sur son appareil ; les requêtes partent directement du navigateur vers `api.anthropic.com`).

- **Observatory** : lien vers https://spareilleux.github.io/learn/demos/observatory/ (publié par le dépôt `learn`), une scène 3D installable.

`ixforge/` est généré, ne pas le modifier à la main : `go run ./cmd/ixforge-site -app -out <dossier>` depuis `go/ixctl` du dépôt ix (licences des bibliothèques incluses dans `ixforge/vendor/`).
