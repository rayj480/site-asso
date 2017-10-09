# Spécifications du site 

## Besoin 

Besoin d'un site pour l'association de maman qui permttrait aux visiteurs. 

### Besoins fonctionnels

1. afficher les informations de l'association 
2. afficher les coordonnées du site
3. permettre aux visiteurs de partager leur expériences
4. permettre aux visiteurs d'adhérer à l'association 

### Besoins non fonctionnels

1. un site accessible


## Eléments technique 

* Framework : react 
* Base de données : mongo-db 

## Base de données 


`site_settings : {
    key: string, 
    value, string
}`

`users : {
    login : string, 
    mdp, string, 
    last_conn : date, 
    nom : string, 
    prenom: string, 
    email: string[regex], 
    adresse: string, 
    code_postal: string, 
    ville: string, 
    status: ["active", "inactive"], 
    type: ["admin", "user"]
}`

`comments : {
    titre: string, 
    body: string, 
    user_id
}`

`responses: {
    body: string, 
    user_id, 
    comment_id
}`

## Pages 

#### Accueil 

Message de bienvenue

Bonjour et Bienvenue sur le site de l'association "Action SEP Solidaire". Ce site est destiné à faire connaître la schélrose en plaque du point de vue des malades, mais avant tout, de permettre aux personnes de s'exprimer, de s'entraider, et ainsi de progresser tous ensemble dans la vie et la compréhension de la maladie. Nous sommes ravis de vous compter parmi nos visteurs. Ce site n'est pas seulement fait pour accueillir les malades de la SEP mais également tous les proches des malades, car il est possible que tous ceux qui se trouve dans l'entourage du malade se retrouve toucher physiquement ou d'une autre façon. 


#### Nous contacter

Description de l'association 

Formulaire de contact 

A.SEP.ACTION
Adresse
CODEPOSTAL Ville

Google Maps


#### S'incrire 


#### Paratger mon expérience

input["text"]

Fil d'actualité 

Fil d'actu Facebook