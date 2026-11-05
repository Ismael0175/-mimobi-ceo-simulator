# MimoBi CEO Simulator — PWA solo, gratuite

Application web progressive (PWA) en français, pensée pour un usage personnel sur iPhone.

## Coût et architecture
- 0 € : aucun abonnement, achat intégré, publicité ou service backend.
- Aucun compte, aucune connexion e-mail, aucun Supabase.
- Sauvegarde automatique locale dans le navigateur / stockage de l'application sur cet appareil.
- Export et import manuels d'une sauvegarde JSON pour garder une copie de sécurité.
- Mise en cache pour jouer hors ligne après le premier chargement réussi.

## Installer sur iPhone
Une PWA installable doit être servie depuis une adresse HTTPS (ou localhost pour les tests). Le moyen gratuit simple est GitHub Pages :
1. Créer un dépôt GitHub gratuit et y déposer tous les fichiers de ce dossier.
2. Dans le dépôt : Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
3. Ouvrir l'adresse HTTPS publiée dans Safari sur l'iPhone.
4. Toucher Partager → Sur l'écran d'accueil → Ajouter.

L'hébergement GitHub Pages est gratuit pour un dépôt public. Le code de l'application sera donc accessible publiquement à toute personne qui connaît l'adresse ; cela ne donne pas accès à ta sauvegarde, qui reste enregistrée localement sur ton iPhone.

## Sauvegarde : à savoir
- La progression est stockée sur cet appareil uniquement ; elle ne se synchronise pas avec d'autres appareils.
- Évite d'effacer les données du site dans Safari, car cela peut supprimer la sauvegarde locale.
- Utilise régulièrement « Exporter ma sauvegarde » et conserve le fichier JSON dans Fichiers / iCloud Drive.
- Si tu changes d'iPhone, utilise « Importer une sauvegarde » pour récupérer ta partie.

## Test local sur ordinateur
Depuis ce dossier, lance `python3 -m http.server 8000`, puis ouvre `http://localhost:8000`.

## Scénario
La partie démarre en août 2029, après la clôture de juillet 2029, avec les données de départ du scénario MimoBi. Toutes les données économiques sont fictives et servent uniquement au gameplay.
