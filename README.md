# Tri de photos (projet de famille)

Page statique permettant d'ordonner une série de photos et de renvoyer sa proposition
sous forme de lien.

Les images sont chiffrées côté client (AES-GCM 256, clé dérivée par PBKDF2-SHA256).
Sans le mot de passe, ce dépôt ne contient rien de lisible : seuls des blocs chiffrés
et la page qui les déchiffre dans le navigateur.
