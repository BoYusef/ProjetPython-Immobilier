## Motivation, Justification et Objectifs du projet

En France, comme dans la plupart des pays du monde, les acheteurs de maison effectuent une recherche en 
ligne et on recourt au site de vente en ligne dans le processus de recherche d'une propriété. De même, les propriétaires
 de bien immobilier et en particulier de maison, dans le but de vente leur maison dans un processus rapide et valoriser leur 
 bien on recourt aux sociétés de vente en ligne. Cela à favoriser l'avènement massif des **sociétés de bases de données immobilières**. 
 Avec le développement rapide de l’informatique et de l’avènement de nouvelles technologies de structurations des données, 
 le secteur immobilier est devenu de plus en plus numérique au cours de la dernière décennie. Les propriétaires de bien immobilier 
 répertorient leurs propriétés dans des bases de données en ligne comme [bienici](https://www.bienici.com), [pap](https://www.pap.fr/), 
 [seloger](https://www.seloger.com/) et [immo logement](https://www.logic-immo.com).  Ils fournissent des informations sur des caractéristiques
 qui se rapporte à **la localisation** du bien immobilier (Adresse géographique, Région, le département etc.…), 
 ses **caractéristiques intrinsèques** (Superficie, Nombre de pièce, Nombre de chambre, parking etc…) et ses **caractéristiques environnementales** 
 (Proximité des transports, attractivités de la ville etc…).

Les acheteurs, les propriétaires, les agents immobiliers et les évaluateurs ont tous besoin d'une méthode pour déterminer la valeur marchande des maisons. 
Les sites Web immobiliers comme [bienici](https://www.bienici.com) ont une méthode d'évaluation automatisée qui estime la valeur d'une maison en fonction 
des informations soumises par l'utilisateur (**Situation géographique**, **état général**, **son environnement**), des dernières ventes réalisées dans le 
quartier et des métadonnées s’appuyant sur les fichiers de l’**Institut National de la Statistique** ([INSEE](https://www.insee.fr/fr/accueil)), complétés 
d’éléments fournis par des organismes spécialisés. Cependant, ces méthodes reposent pour la plupart sur des règles de décision et non sur des 
methodes avancées de **Machine Learning** ou du **Deep Learning** qui pouront leur permettre d'ameliorer la precision de leur estimation.
 Egalement, [bienici](https://www.bienici.com) ne considèrent l'impact de l'apparence du logement dans leurs méthodes d'évaluation automatisées. 

C'est ainsi que, nous avons juger bon de se pencher sur le theme institulé << **Prediction du prix d'un bien immobilier à l'aide de modèle de Machime learning et du Deep Learning** >> et dont l'objectif generale est d'appliquer les methodes de **Machine Learning** et du **Deep Learning** pour predit le prix d'une maison. Comme objectifs specifique il s'agira principalement de :
 - **<font color= red>Collecter des donnees de differents sources et pertinentes pour l'analyse</font>** 
 - **<font color= red>Faire la description des maisons a partir de differents caracteristiques</font>**
 - **<font color= red>Proposer differentes methodes d'estimer et faire des comparaisons rigoureuses entre elles</font>**
 

Pour atteindre notre objectif general et les objectifs specifique fixes nous divons se travaille en trois grandes parties.
 la première partie sera consacree a la collecte des donnnees, leur nettoyage(**preprocesing**) et mise en forme pour l'analyse. 
 Quant a la deuxième partie elle sera consacree aux statistiques descriptives et mutivaries ansi qu'a la visualisation des donnees.
 La derniere partie de ce notebook concernera la modelisation avec en vue une deux sous-partie dont la premiere sera dediee a la prediction 
 avec les donnees numeriques/categorielles uniquement et une deuxieme concernant la prediction en utilisant les images de la maison(Apparence 
 interieur et exterieur).