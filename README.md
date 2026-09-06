# NNSTARBARBERSHOP

Site web de **NNSTARBARBERSHOP** à Gatineau — coiffure mixte, rasage et soins de barbe.

## Aperçu local

Depuis la racine du projet :

```bash
python3 -m http.server 8080
```

Puis ouvrir [http://localhost:8080](http://localhost:8080).

## Pages

- **Accueil** — hero, services, espace salon
- **Services** — offre et galerie filtrable
- **Contact** — adresse, téléphone, heures, itinéraire

Walk-ins bienvenus. Téléphone / WhatsApp : **438 988 4828**

193 chemin de la Savane, Gatineau, QC J8T 1R2

## Déploiement Netlify (via GitHub)

Le site est un HTML statique. `netlify.toml` indique à Netlify de publier la racine du dépôt depuis la branche **main**.

1. Ouvrir [Importer nnstarcoiffure sur Netlify](https://app.netlify.com/start/deploy?repository=https://github.com/brad7768/nnstarcoiffure)
2. Autoriser GitHub, choisir le dépôt `brad7768/nnstarcoiffure`
3. Branche de production : **main** (le dossier de publication est déjà défini dans `netlify.toml`)
4. Lancer le déploiement

Après cette connexion, chaque `git push` sur `main` republie le site automatiquement.
