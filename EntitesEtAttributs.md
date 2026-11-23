
Notre modèle comporte quatre entités principales :

PILOTE : cette entité permet de représenter les pilotes ayant remporté au moins un championnat du monde.

pil_id (INT) : identifiant unique du pilote, utilisé comme clé primaire.
pil_nom (VARCHAR(100)) : nom du pilote.
pil_prenom (VARCHAR(100)) : prénom du pilote.
pil_date_naissance (DATE) : date de naissance du pilote.

SAISON : cette entité permet de représenter les différentes saisons du championnat ainsi que les résultats du champion.

sai_annee (INT) : année de la saison, utilisée comme clé primaire.
sai_nb_gp (INT) : nombre de Grands Prix durant la saison.
sai_points_champion (DECIMAL(6,2)) : nombre de points obtenus par le champion durant la saison.
sai_victoires_champion (INT) : nombre de victoires obtenues par le champion durant la saison.

ECURIE : cette entité permet de représenter les écuries pour lesquelles les champions ont couru.

eco_id (INT) : identifiant unique de l'écurie, utilisé comme clé primaire.
eco_nom (VARCHAR(100)) : nom de l'écurie.

PAYS : cette entité permet de représenter les pays associés aux pilotes et aux écuries.

pay_id (INT) : identifiant unique du pays, utilisé comme clé primaire.
pay_nom (VARCHAR(100)) : nom du pays.
