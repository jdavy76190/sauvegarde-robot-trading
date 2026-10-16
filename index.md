# Sauvegarde Robot Trading

## Présentation

Sauvegarde Robot Trading est une application privée de sauvegarde automatique de données hébergées sur un serveur VPS.

Elle utilise rclone et Restic pour transférer des sauvegardes chiffrées vers le compte Google Drive personnel de son propriétaire.

## Fonctionnement

- Sauvegarde automatique des bases de données et configurations du serveur.
- Compression et déduplication des sauvegardes.
- Chiffrement des données avant leur transfert.
- Conservation de plusieurs versions.
- Possibilité de restaurer les fichiers en cas de panne.

## Utilisation de Google Drive

L'application demande l'autorisation d'accéder à Google Drive uniquement pour gérer les fichiers nécessaires aux sauvegardes.

Elle n'est pas destinée à un usage public ou commercial.

## Confidentialité

Consultez notre [politique de confidentialité](confidentialite.html).
