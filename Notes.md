# Panama Papers - Investigation et Big Data - Notes

## Page 6

Complément d'information : http://www.lemonde.fr/panama-papers/article/2016/04/04/offshore-ce-qui-est-legal-ce-qui-ne-l-est-pas_4895041_4890278.html

## Page 8

Le **Süddeutsche Zeitung** (Journal de l'Allemagne du Sud) a rapidement réalisé qu'il ne serait pas en mesure de traiter seul cette masse d'information, et s'est adressé à l'**ICIJ**, qui avait démontré sa capacité à adresser ce type de problème avec les **Offshore Leaks**, les **Lux Leaks** ou les **Swiss Leaks**.

**ICIJ** = consortium permettant de mutualiser les forces de plusieurs médias pour produire des enquêtes de très grande ampleur. Fondé en 1997 par le [Center Public Integrity](https://publicintegrity.org/). L'ICIJ est devenu une structure indépendante le 24/02/2017.

## Page 12

Le faible nombre de sociétés américaines peut s'expliquer par la présence d'états paradis fiscaux, comme le **[Delaware](https://fr.wikipedia.org/wiki/Delaware)** (lois favorables aux entreprises, faibles taxes, avec plus de 50% des entreprises américaines cotées en bourse qui sont incorporées au Delaware).

- Surface web = accessible via les moteurs de recherche classiques (Google).
- Deep web = contenus non indexées par les moteurs de recherche (l'adresse doit-être connue).
- Dark web = réseaux privés (dont le plus populaire est TOR), acessibles via des outils dédiés.

## Page 14

Pour un CD (MP3) d'une taille moyenne de 150 Mo.

Pour un DVD d'une capacité de 4 Go.

http://filecatalyst.com/todays-media-file-sizes-whats-average/

665 DVDs = 10.64 Kg, pile de 9m31

Epaisseur d'un DVD = 14 mm

Poids d'un DVD = 16 grammes (https://fr.wikipedia.org/wiki/DVD)

## Page 16

Images = photocopies des passeports des actionnaires et des scans de contrats signés.

## Page 20

- Exemple 1 : données structurées peu changeantes pouvant être chargées dans une bases de données relationnelle, voire en mémoire.
- Exemple 2 : données remontées en flux continu, avec un besoin d'instantanéité, et une capacité qui va rapidement dépasser un stockage traditionnel.
- Exemple 3 : données de multiples sources (capteurs) et volumineuses (source : http://www.computerworlduk.com/data/boeing-787s-create-half-terabyte-of-data-per-flight-says-virgin-atlantic-3433595/).

Les technologies et solutions qui vont être évoquées proviennent essentiellement de l'écosystème Big Data.

## Page 21

Le premier challenge est de rendre cette information (essentiellement à base de documents) exploitable par les journalistes.

Métadonnées = données procurant des informations sur les données. Simplifie la classification, la recherche. Les métadonnées peuvent être créées manuellement ou automatiquement (catégorie, description, contextualisation, etc.).

Modèle ontologique **"W7"** des métadonnées : What, When, Where, Who, hoW, Which, Why (http://dataconomy.com/2016/12/metadata-important-data/).

Selon la jurisprudence du 21 décembre 2016 **"Tele2 Sverige"** de la **Cours de Justice de l'Union Européenne** (CJUE), la distinction métadonnées / contenu et secret des correspondances, est abolie.

> Prises dans leur ensemble, ces données sont susceptibles de permettre de tirer des conclusions très précises concernant la vie privée des personnes dont les données ont été conservées, telles que les habitudes de la vie quotidienne, les lieux de séjour permanents ou temporaires, les déplacements journaliers ou autres, les activités exercées, les relations sociales de ces personnes et les milieux sociaux fréquentés par celles-ci… En particulier, ces données fournissent les moyens d’établir, … le profil des personnes concernées, information tout aussi sensible, au regard du droit au respect de la vie privée, que le contenu même des communications.

Source : http://www.ledieu-avocats.fr/tempete-metadonnees-cjue-21-decembre-2016/

## Page 23

Exemple de [tarification OVH](https://www.ovh.com/fr/cloud/instances/tarifs.xml) :

- Serveur SP-30 (30 Go RAM, 2 CPU 2.4 GHz) = 35 € HT/mois. x 35 instances = **1225 €/mois**.
- Serveur EG-15 (15 Go RAM, 4 CPU 2.3 GHz) = 40 € HT/mois.

## Page 24

**Python** a aussi été utilisé pour le nettoyage de données et l'écriture de traitements uniques.

## Page 25

**Apache Tika** a été utilisé dans le projet **[Web Lab](http://weblab-project.org/)** (EADS) pour le traitement de données multimédia.

## Page 26

Stemming et lemmatization permettent la catégorisation, et une meilleure gestion des fautes d'orthographe.

Le Stemming, contrairement à la Lemmatisation, peut aboutir à des mots qui n'existent pas.

Les n-Gramme vont permettre une aide à la recherche (auto-completion).

## Page 28

http://www.analyticsvidhya.com/blog/2015/06/quick-guide-text-data-cleaning-python/

## Ecran 29

**Talend** a en particulier été utilisé pour l'alimentation de **Neo4j**.

## Ecran 30

**Apache Solr** permet la recherche à partir d'expression régulières.

## Ecran 33

Le stockage sous la forme de relations permet des recherches plus complexes et rapides qu'avec des bases de données standard.

Le premier exemple permettra la mise en place d'une action marketing de type cooptation afin d'inciter les personnes à acheter un véhicule PSA.

Utilisation : [Bank Fraud Detection](https://neo4j.com/graphgist/9d627127-003b-411a-b3ce-f8d3970c2afa) : "Find account holders who share more than one piece of legitimate contact information".

## Ecran 35

La recherche par facettes permet de filtrer une collection de données en choisissant un ou plusieurs critères (les facettes), organisés par axes (ex.: date de publication, type de document, langue, présence d'une entité/personne, etc.).

Le contenu de chaque facette est constitué à partir de la collection de données trouvée.

## Ecran 36

Le résultat de la recherche "transport" à droite peut-être découvert/filtré par catégories (facettes) à gauche.

A noter qu'Open Refine utilise aussi un système de facettes appliqué au processus de nettoyage des données.

## Ecran 38

Affichage du résultat d'une recherche par requête ou mots-clés. Un clic sur un noeud permet d'afficher des informations complémentaires, permettant de valider le résultat de la recherche, et/ou d'effectuer de nouvelles recherches.

## Ecran 39

Des filtres/styles peuvent-être appliqués si le résultat est trop complexe.

## Ecran 40

Utilisé dans le développement d'outils dédiés, lorsque des solutions clé en main comme Linkurious ne suffisent pas.

## Ecran 43

En France :

- Liste Challenges des 500 Français les plus riches (et son équivalent à l’international : la liste Forbes).
- Organigrammes des principaux partis politiques.
- Administrateurs du CAC 40.
- Personnalités préférées des Français.
- Joueurs de l’équipe de France de football.

Des temps de réponses faibles sont essentiels dans le processus de recherche itératif.

## Ecran 44

Quelques techniques permettant de mettre en oeuvre ces types de recherches.

## Ecran 45

Exemple avec l'IBAN de la Banque de France : https://regex101.com/r/Qwd2OZ/1

## Ecran 46

Le facteur humain reste essentiel dans la validation des recherches.

## Ecran 48

Le nom **"Panama Papers"** fait référence aux **"Pentagon Papers"**, document secret-défense émanant du département de la Défense à propos de l'implication politique et militaire des États-Unis dans la guerre du Viêt Nam de 1945 à 1971.

## Ecran 49

Essentiellement des journalistes anglophones ou d'Amérique du sud.

## Ecran 50

12 mois d'investigation pendant lesquels aucune information ne doit fuiter, même en interne. Différents outils ont été utilisés afin de garantir un maximum de confidentialité.

## Ecran 55

Ces 2 initiatives visent à faciliter les travail d'investigation des journalistes, par le biais d'une plateforme de collaboration et d'une mise à disposition de services de traitement de l'information.

