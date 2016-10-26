In this repository, we host two notebooks. Both notebooks aim at analyzing job logs from our schedulers, and answer the question: 

 - How much of our users' workload requires X, or less than X of resource Y ?
 
To do so, we first used Pandas to analyze our logs. We however hit a roadblock when the time came to scale the analysis to larger log files. We then switched from Pandas to Apache Spark. You will find both notebooks in this repository.

Authors: Maxime Boissonneault and Félix-Antoine Fortin

---

Dans ce dépôt, nous hébergeons deux notebook. Les deux visent à analyser les logs de tâche de nos ordonnanceurs, et à répondre à la question: 

 - Quelle proportion du temps de calcul de nos usagers nécessitent une quantité X - ou moins de X - de la ressource Y ?
 
Pour ce faire, nous avons d'abord utilisé Pandas pour analyser nos logs. Nous avons cependant frappé un mur lorsque nous avons tenté d'analyser des logs plus gros. Nous avons alors converti notre notebook pour utiliser Apache Spark. Vous trouverez les deux notebooks dans ce dépôt.

Auteurs: Maxime Boissonneault et Félix-Antoine Fortin
