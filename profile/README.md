# Qu'est-ce qu'Idenovia ?

**Idenovia** est une petite société strasbourgeoise développant des services orientés vers le télésecrétariat et la prise de rendez-vous. Fondée en 2011, elle a développé et maintient encore à ce jour les logiciels *Serenovia*, *Wialo* et *Calendovia*. Les deux services principaux, c'est-à-dire Serenovia et Calendovia, ont été sauvegardés en local via le SVN avant leur migration sur GitHub mi-2022 pour des raisons d'accès et de simplicité d'utilisation.

# Quels sont les logiciels développés, et depuis quand ?

Logiciels à ce jour :
| Logiciel | Nom de code | Langage / Framework | Date de création | Note |
|:-:|:-:|:-:|:-:|:-:|
| **Serenovia Desktop** (v1-v3) | | Java / Spring | fin 2012 | |
| **Calendovia** (v1-v2) | | Java / Spring | 2013 | |
| **Wialo** (v1) | | PHP, Java | | |
| **Serenovia Mobile** (v1) | | Java | 2016 | Perdu en 2019 |
| **Serenovia API** | | Java / Spring Boot | 2022 | Sera bientôt inclus dans le kernel |

Logiciels en développement :
| Logiciel | Nom de code | Langage / Framework | Note |
|:-:|:-:|:-:|:-:|
| **Template partagé** | Sphere | Angular |
| **Serenovia Desktop** (v4) | Nurse | Angular |
| **Calendovia** (v3) | N/A | Angular | 2013 |
| **Wialo** (v2) | N/A | Angular |
| **Serenovia Mobile** (v2) | Dine | Angular |
| **Kernel partagé** | Cosmos | Java / Spring Boot | Sera sous forme d'API |
| **Authentificateur unifié** | Orochi | Angular |

# Pourquoi le code n'est-il pas accessible hors de l'organisation ?

Le code d'Idenovia est actuellement en closed-source, ce qui veut dire que le code n'est accessible qu'aux membres de l'organisation. Cela est éventuellement justifié par le fait que les logiciels sont payants de base. Mais cela n'empêchera pas le fait que quelques uns des composants intégrés dans ces services pourront bientôt devenir open-source une fois la refonte totale effectuée.

# Quelle refonte ?

Une refonte est en cours sur les logiciels, avec pour objectifs:
- l'unification du noyau, 
- une meilleure clarté du code,
- de meilleures relations entre les bases,
- une meilleure sécurité,
- une harmonie entre les services,
- des logiciels plus stables et une meilleure prévention en cas de problèmes rencontrés,
- une veille technologique constante menant à un maintien conséquent des services,
- moins de fonctionnalités inutiles,
- une meilleure intuitivité quelque soit la cible.

Pour cela, un passage de Spring + JSP à Spring Boot pour le noyau + Angular pour les frontends est envisagé.
