# Lakhina Volume Implémentation

Ce notebook est une implémentation de la méthode Lakhina Volume extrait des papiers suivant [An empirical comparison of botnet detection methods. In Computers & Security, Vol. 45, Pages 100-123](https://www.researchgate.net/publication/262921640_An_Empirical_Comparison_of_Botnet_Detection_Methods) et [Diagnosing Network-Wide Traffic Anomalies](https://conferences.sigcomm.org/sigcomm/2004/papers/p405-lakhina111.pdf).  

Nous avons réalisé nos tests sur les datasets CTU-13 qui est un ensemble de données de trafic de botnet qui a été capturé à l'université CTU en République tchèque, en 2011. L'objectif de ce jeu de données était de capturer une grande quantité de trafic réel de botnet mélangé à du trafic normal et à du trafic de fond. Le jeu de données CTU-13 consiste en treize captures (appelées scénarios) de différents échantillons de botnet. Sur chaque scénario, les auteurs ont exécuté un malware spécifique, qui utilisait plusieurs protocoles et a effectué différentes actions.  
Le dataset est disponible ici : https://www.stratosphereips.org/datasets-ctu13  
Nous avons utilisé les datasets 0,1 et 9 pour nos résultats mais notre méthode peut-être étendu aux autres datasets.

Pour plus de détails d'implémentation, le notebook fournit des informations supplémentaires.
