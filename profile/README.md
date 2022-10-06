# Qu'est-ce qu'Idenovia ?

**Idenovia** est une petite société strasbourgeoise développant des services orientés vers le télésecrétariat et la prise de rendez-vous. Fondée en 2011, elle a développé et maintient encore à ce jour les logiciels *Serenovia*, *Wialo* et *Calendovia*. Les deux services principaux, c'est-à-dire Serenovia et Calendovia, ont été sauvegardés en local via le SVN avant leur migration sur GitHub mi-2022 pour des raisons d'accès et de simplicité d'utilisation.

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
