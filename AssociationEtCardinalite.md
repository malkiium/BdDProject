
Notre modèle comporte quatre associations principales :

Pilotes et Saisons : cette association permet de représenter les saisons remportées par les pilotes. Un pilote peut remporter une ou plusieurs saisons (1,n), et une saison ne peut être remportée que par un seul pilote (1,1).

Saisons et Écuries : cette association permet de représenter les écuries pour lesquelles les champions couraient durant chaque saison. Une saison est associée à une seule écurie (1,1), et une écurie peut être associée à une ou plusieurs saisons (1,n).

Pilotes et Pays : cette association permet de représenter la nationalité des pilotes. Un pilote possède une seule nationalité dans notre modèle (1,1), et un pays peut être associé à aucun, un ou plusieurs pilotes (0,n).

Écuries et Pays : cette association permet de représenter le pays dans lequel les écuries sont basées. Une écurie est basée dans un seul pays (1,1), et un pays peut accueillir aucune, une ou plusieurs écuries (0,n).
