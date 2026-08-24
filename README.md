# Signal — État des réseaux sociaux

Tableau de bord en temps réel pour suivre les pannes et rétablissements des principaux réseaux sociaux, directement dans le navigateur.

## Fonctionnement

- **Suivi automatique** : Discord, Slack, Reddit et Spotify sont interrogés via leur API de statut officielle (Atlassian Statuspage), gratuite et publique.
- **Suivi manuel** : Instagram, Facebook, WhatsApp, X, TikTok et Snapchat ne publient pas de statut machine-readable. Un lien direct vers leur page Downdetector est fourni pour vérification rapide.
- Bouton **Actualiser** pour une vérification à la demande, ou interrupteur **auto 60s** pour un rafraîchissement continu.

## Utilisation

Ouvrir `index.html` dans un navigateur, ou consulter la version en ligne :
`https://svperman.github.io/signal-reseaux-sociaux/`

## Stack

HTML / CSS / JavaScript pur, aucune dépendance, aucune clé API requise.
