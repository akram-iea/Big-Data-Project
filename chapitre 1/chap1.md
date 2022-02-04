#Chapitre 1
##1.Quest-ce que les données liées(Linked Data)

Les données liées reposent sur l'utilisation du web dans la création des liens entre differents ***objets***. De la même manière que nous publions des informations textuelles non structurées sur le Web sous forme de ***documents*** HTML et que nous recherchons ces informations à l'aide de moteurs de recherche basés sur des mots clés, nous pouvons maintnant publier les données d'une facon plus structurée, ne se contentant plus de partager seulement des document en l'etendant a une notion d'objets liées entres elles par des liens qui sont eux meme des objets. En d'autres termes, les données liées refèrent aux données publiées dans le Web de facon qu'une machine puisse les comprendre.
Les technologies de données liées peuvent contribuer à accroître la flexibilité, l'adaptabilité et l'efficacité de la gestion de l'information dans les organisations, qu'il s'agisse d'entreprises, de gouvernements et d'administrations publiques ou de communautés en ligne. Pour les utilisateurs finaux et la société en général, le Web de données aidera à obtenir et à intégrer les informations nécessaires, et de gérer ainsi avec succès la transition vers une economie et une société basé sur l'information.
| Representation\degree of openness           | Internal use | Open             |
|---------------------------------------------|--------------|------------------|
| Structured data model  (XML, CSV, SQL, etc) | Data         | Open Data        |
| RDF data model                              | Linked Data  | Linked Open Data |

##2.Paradigme des donnés liées
Pour pouvoir publier et connecter la data en utilisant l'infrastucture Web en adherant a son architecture et son principe, on doit respecter 4 principes : 

1.	Utiliser des URIs comme nom des objets
2.	Faire des pages HTTP pour les URI pour que les utilisateurs puissent visualiser ces objets
3.	Lorsque quelqu'un consulte un URI, il faut fournir des informations utiles en utilisant les normes(RDF, SPARQL).
4.	Iclure des liens vers d'autres URI, afin qu'ils puissent découvrir d'autres choses.

Les données liées n'utilisent que les **HTTP URIs**(Uniform resource Identifier). Ces URIs constituent un moyen simple de créer des noms uniques au niveau mondial de manière décentralisée, puisque chaque deteneur d'un domaine peut créer des URIs. Non seulement ils servent de noms por nos objets mais ils permètent d'acceder à l'information qui les décrits.

Le modèle de données **RDF**(Resource Description Framework) représente les informations sous forme d'ensembles d'énoncés, qui peuvent être visualisés sous forme de graphes dirigés étiquetés par des nœuds et des arcs. Le modèle de données est conçu pour la représentation intégrée d'informations provenant de sources multiples, structurées de manière hétérogène et représentées à l'aide de schémas différents. En RDF, les informations sont représentées sous forme d'énoncés, appelés triples RDF. Les trois parties de chaque triple sont appelées sujet, prédicat et objet.Voici un exemple d'RDF:
http://jlow.me  foaf:name   "Johnny Lee Outlaw"




