# Wiki(data)gouv

> Créer des liens entre wikidata et datagouv.

- Notes : https://etherpad.wikimedia.org/p/wiki-data-gouv

## Objectifs 

- Importer des données de data.gouv.fr vers wikidata
- Construire des requêtes SparQL utiles aux utilisateurs de data.gouv.fr

## Format 

Le tout au format « barcamp » : on définit ensemble ce qui nous
intéresse et on le fait.

## Logistique

- Le 12 juin de 9h30 à 18h30
- À la DINSIC, au 20 avenue de Ségur
- Salle 5.728 pour une vingtaine de personnes
- Inscription gratuite et obligatoire, par email à `bastien.guerry@data.gouv.fr`

## Déroulé

### 9-30-10h30 : accueil et introductions rapides

- Accueil et tour de table
- Point juridique
- Présentation de Data.gouv et du SPD
- Introduction à wikidata (?)
- Présentation de SparQL (?)

### 10h30-11h : préparation des groupes de travail

- Réflexion collective pour la préparation du barcamp

### 11h-13h : Travail en petits groupes thématiques

### 13-14h : PAUSE déjeuner

### 14h-14h30 : Restitution rapide de ce qui a été fait

### 14h30-17h30 : Travail en petits groupes thématiques

### 17h30-18h30 : Restitution finale

## Ressources et outils

- [Mix N Match](https://tools.wmflabs.org/mix-n-match/#/)
- [wikidata-cli](https://github.com/maxlath/wikidata-cli)
- [Wikidata reconciliation for OpenRefine](https://tools.wmflabs.org/openrefine-wikidata)
- [Créer un robot dans wikidata](https://www.wikidata.org/wiki/Wikidata:Creating_a_bot/fr)

## Point juridique
Dans la licence ouverte, l'obligation de citer la source et la date ne porte que sur le primo-réutilisateur. La license ouverte n'est pas contaminante. Elle n'est pas un droit d'auteur au sens propre (donc pas de problème avec un éventuel renoncement au droit d'auteur au sens de la CC0) puisque l'État n'a pas de droit sur les données. La licence porte de toute façon sur la donnée (non protégeable individuellement par le droit d'auteur) et non sur le jeu de données. 

Wikidata permet cela sans problème, puisque chaque élément de donnée peut avoir une référence, et que nous avons déjà les propriétés pour l'URL de référence, la date de production de la donnée et la date d'import.

## Idées de contenus à travailler

- Axe géographique :
  - Vérifier la cohérence entre les communes sur Wikidata et les différentes versions du COG.
  - Mettre en conformité les données de Wikidata à l'aide de la base officielle des codes postaux

- Axe culture :
  - Bases Palissy et Mérimée
  
- Axe entreprises et associations : 
  - "Sireniser" des données de Wikidata (puis Wikipédia) ?
  - Créer un pywikibot pour importer des infos (adresse, date de création, etc) dans Wikidata à partir d'un SIRET
  - Tourisme (base [datatourisme](https://www.data.gouv.fr/fr/datasets/donnees-touristiques-de-la-base-datatourisme/))

- Axe annuaire des administrations
  - Comment wikidater le référentiel des organisations de Wikidata
    pour récupérer les alias sur datagouv et améliorer le search ?
  - Comment faire le lien entre les admnistrations sur Wikidata et
    l'annuaire du service public ?

- Axe biologie
  - Botanique
  - Diversité et répartition des espèces (exemples : [herbiers](https://www.data.gouv.fr/fr/datasets/les-herbiers-de-zosteres-de-la-region-bretagne-inventaire-2007-des-sites/), [fonds meubles](https://www.data.gouv.fr/fr/datasets/carte-biosedimentaire-des-fonds-meubles-des-pertuis-charentais-source-hily-c-1976-echelle-1-100-000/), [hamster](https://www.data.gouv.fr/fr/datasets/hamster-reconquete-en-alsace/))

- Axe lexicologie
  - Wikidata propose maintenant l’extension `Lexeme` en production
    mais les imports automatisés sont pour le moment découragés. Il
    serait néanmoins intéressant de faire un tour d’horizon des
    données disponibles sous licence libre, compatibles avec CC-0
    (Wikidata) ou CC-by-sa-3.0-unported (Wiktionnaire).
	
   - https://www.data.gouv.fr/fr/organizations/rennes-language-center/#dashboard
   - https://www.uantwerpen.be/en/research-groups/clips/projects-and-publica/datasets/

- Axe anthropologie/sociologie
  - cultes
  - démographie
  - langues

- Axe éducation
  - liste des établissements
  - organigrammes
    - https://www.data.gouv.fr/fr/datasets/ontologies-descriptives-du-systeme-et-des-programmes-scolaires-francais/
  - liste des domaines de recherche universitaire
    - https://www.data.gouv.fr/fr/datasets/domaines-scientifiques-et-structures-de-recherche-de-luniversite/
- Axe médecine
- Axe géologie
- Axe environnement (données de [qualité de l'air](https://www.data.gouv.fr/fr/datasets/mise-a-disposition-de-donnees-de-qualite-de-lair-sur-la-france-www-prevair-org-1/))
- Axe astronomie

