# Card Model

### Credentials

- id [AUTO-INCREMENT] : identifiant principal de l'entreprise
- idcompany_id [COMPANY] : contenu de l'entreprise qui a créé le modèle de carte
- name [VARCHAR] : nom du modèle de la carte
- items [JSON ARRAY] : tableau des items possible de la carte
    - {
    "itemx" => {
        "name" => "x",
        "img_link" => "link"
        }
    }
- background_link [VARCHAR] : lien relatif du background d'image de la carte

### Functions