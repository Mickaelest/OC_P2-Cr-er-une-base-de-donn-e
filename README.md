## Réunion de validation – Modification de la base de données

<img width="526" alt="laplaceimmo" src="https://github.com/Mickaelest/OC_P3-Creer-une-base-de-donnee/assets/166141412/cb6abf71-d293-48b5-8b31-b284bce5f1ff">

**De:** Clara  
**À:** Moi  
**Objet:** Réunion de validation – Modification de la base de données

Hello,

Afin d’avancer sur le projet DATAImmo, je prévois une première réunion pour valider la modification de la base de données.

Tu trouveras en pièce jointe un fichier zip avec les données suivantes :

- Des données extraites du site open data des Demandes de valeurs foncières (DVF)
- Des données de l’INSEE avec les résultats des recensements de la population
- Des données de data.gouv sur les régions, avec le référentiel géographique français, communes, unités urbaines, aires urbaines, départements, académies, régions.

D’ici la réunion, j’aurais besoin de 2 choses de ta part :

1. Il faut que tu prépares le dictionnaire des données en respectant le template en PJ pour répertorier et décrire les données importantes à stocker car nous avons omis de le faire. Il faut le remplir pour les trois fichiers de données.
2. Ensuite, peux-tu modifier le schéma relationnel en pièce-jointe pour qu’il prenne en compte les nouvelles données région et population ? Ça nous permettra de bien visualiser les différentes entités, associations et cardinalités de la base de données. Enfin, il faudra que tu me présentes ce nouveau schéma relationnel normalisé (Il doit suivre la norme 3NF) de la base de données qui donnera lieu à la création des nouvelles tables.

On validera tout ça ensemble lors de notre réunion de validation, pour que tu puisses avancer sur la création de la base.

Je reste à ta disposition en cas de besoin.

Bien à toi,

![2semainesplustard](https://github.com/Mickaelest/OC_P3-Creer-une-base-de-donnee/assets/166141412/2e4ab3e4-f5aa-4403-b5e0-da1025d1358a)

## Validation du schéma relationnel et suite du projet

**De:** Clara  
**À:** Moi  
**Objet:** Validation du schéma relationnel et suite du projet

Hello,

Félicitations pour cette première étape de conception ! Comme on en a parlé en réunion ce matin, on est bons pour partir sur la modification de la base de données. Il faut maintenant que tu implémentes les tables dans la base de données en respectant ce qu’on s’est dit ce matin (cf. compte rendu de réunion en pièce jointe).

On a échangé en interne, et on pense qu’un outil comme SQLite est pertinent pour ce type d’implémentation. Si tu es plus à l’aise, tu peux essayer d’implémenter un outil comme mySQL ou postgreSQL.

Une fois que tu auras fait ça, tu pourras faire les requêtes pour extraire les données dont nous avons besoin. Pour ça, envoie-moi un document PDF avec tous les résultats des requêtes ainsi que la requête associée. Utilise des alias pour que ça soit plus lisible. Tu trouveras toutes les demandes auxquelles il faudra répondre dans le CR de réunion.

Une fois que tu auras terminé, on regardera tout ça ensemble pour voir ce que tu as réussi à tirer comme données.

Bon courage !

Clara Daucourt  
CTO
