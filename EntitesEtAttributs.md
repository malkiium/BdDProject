
Notre modèle comporte quatre entités principales :

PILOTE : cette entité permet de représenter les pilotes ayant remporté au moins un championnat du monde.

PILOTE(PRIMARY KEY pil_id int, pil_nom varchar(100), pil_prenom varchar(100), pil_date_naissance date)

pil_id : identifiant unique du pilote, utilisé comme clé primaire.
pil_nom : nom du pilote.
pil_prenom : prénom du pilote.
pil_date_naissance : date de naissance du pilote.

SAISON : cette entité permet de représenter les différentes saisons du championnat ainsi que les résultats du champion.

SAISON(PRIMARY KEY sai_annee int, sai_nb_gp int, sai_points_champion decimal(6,2), sai_victoires_champion int)

sai_annee : année de la saison, utilisée comme clé primaire.
sai_nb_gp : nombre de Grands Prix durant la saison.
sai_points_champion : nombre de points obtenus par le champion durant la saison.
sai_victoires_champion : nombre de victoires obtenues par le champion durant la saison.

ECURIE : cette entité permet de représenter les écuries pour lesquelles les champions ont couru.

ECURIE(PRIMARY KEY eco_id int, eco_nom varchar(100))

eco_id : identifiant unique de l'écurie, utilisé comme clé primaire.
eco_nom : nom de l'écurie.

PAYS : cette entité permet de représenter les pays associés aux pilotes et aux écuries.

PAYS(PRIMARY KEY pay_id int, pay_nom varchar(100))

pay_id : identifiant unique du pays, utilisé comme clé primaire.
pay_nom : nom du pays.
