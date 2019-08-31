# Users

### Credentials

- id [AUTO-INCREMENT] : identifiant principal de l'utilisateur
- email [VARCHAR] : identifiant de connexion et de contact de l'utilisateur
- password [VARCHAR]: password de l'utilisateur crypté via symfony
- roles [JSON ARRAY] : tableau des rôles de l'utilisateur
     - {"ROLE_NAME"}
- username [VARCHAR] : identité de l'utilisateur (format : Prenom NOM)

### Functions


