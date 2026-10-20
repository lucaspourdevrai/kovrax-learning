# KOVRAX Learning

Application Windows Electron pour apprendre Lua et GLua (Garry's Mod), avec cours progressifs, exercices et suivi de progression.

## État actuel

Le dépôt est initialisé, mais **les sources complètes de la version 2.2 ne sont pas encore importées**. Aucun installateur Windows n'est disponible à ce stade.

## Sécurité

Ne jamais publier de mot de passe MySQL, de chaîne de connexion, de jeton ou de fichier `.env`.

La version 2.2 de travail utilise une connexion MySQL locale depuis Electron et est réservée à un usage privé. Elle ne doit pas être distribuée comme solution multiutilisateur sécurisée. Le chiffrement des identifiants locaux ne remplace pas un contrôle d'accès côté serveur.

## Suite

Importer le contenu de l'archive source `KOVRAX-Learning-v2.2-MySQL-Local-GitHub.zip`, vérifier l'application et configurer GitHub Actions pour compiler l'installateur Windows.
