"# Demissions-d-un-organisme-bancaire: Projet efféctué au sein du ceri à l'Université d'avignon" 

Un établissement bancaire avait pour objectif de développer une méthode permettant d'identifier les membres de son institution qui étaient susceptibles de la quitter. L'objectif principal de l'établissement était de mettre en place une stratégie de gestion de la relation client visant à anticiper le départ des membres.

Pour élaborer cette méthode, nous avions accès à des données décrivant les membres, présentées sous la forme de deux tables distinctes. La première table (table1.csv) contenait des informations sur les membres qui avaient déjà quitté l'établissement par le passé, qualifiés de "démissionnaires". La seconde table (table2.csv) représentait un échantillon des clients actuels de l'établissement. Les membres étaient décrits en fonction de plusieurs caractéristiques, qui variaient partiellement d'une table à l'autre.

Une approche d'analyse prédictive a été utilisée pour modéliser la probabilité qu'un membre choisisse ou non de démissionner en se basant sur les valeurs des caractéristiques décrivant chaque membre. Ce processus générait un score, qui dans ce contexte, correspondait à la probabilité qu'un membre décide de démissionner. Naturellement, si le modèle était efficace, cette probabilité serait élevée pour les membres ayant déjà démissionné par le passé et faible pour les membres actuels.

Cependant, il pouvait également arriver que ce score soit élevé pour certains membres actuels (non démissionnaires). Dans de tels cas, on pouvait en déduire que le profil de ces membres était similaire à celui des démissionnaires, indiquant ainsi un risque potentiellement élevé de démission pour ces membres actuels.

