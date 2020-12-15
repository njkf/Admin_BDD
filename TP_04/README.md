# TP04

## Première partie 

Créez une image Docker qui contient tous les outils nécessaires pour mettre en place un système de backup automatique. Vous trouverez des ressources dans le TP 2 et 3 du cours de devops.
Vous pouvez créer votre image en local dans ce cas vous devez me faire parvenir le contenu de votre Dockerfile sinon vous pouvez vous créer un compte sur Docker Hub et uploader votre image dessus, dans ce cas veuillez me donner le lien publique vers votre image.

## Deuxième partie 

Mettez en place une stratégie de backups grâce à cron qui génère un dump de la base de données tous les lundis à 17h et génère un fichier compressé en format gzip contenant la date de création.


## Troisième partie 

Mettez en place une stratégie de backups avec logrotate qui réalise un dump journalier compressé en format bz2 et qui garde les 5 derniers dumps.

