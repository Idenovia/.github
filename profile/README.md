<!-- trunk-ignore(markdownlint/MD041) -->
[![idenovia](https://github.com/Idenovia/.github/blob/main/assets/logo_header.png?raw=true)](https://www.idenovia.com)

![Qui sommes-nous?](https://github.com/Idenovia/.github/blob/main/assets/question.png?raw=true)

# Qu'est-ce qu'Idenovia ?

**Idenovia** est une petite société strasbourgeoise développant des services orientés vers le télésecrétariat et la prise de rendez-vous. Fondée en 2011, elle a développé et maintient encore à ce jour les logiciels _Serenovia_, _Wialo_ et _Calendovia_. Les deux services principaux, c'est-à-dire Serenovia et Calendovia, ont été sauvegardés en local via le SVN avant leur migration sur GitHub mi-2022 pour des raisons d'accès et de simplicité d'utilisation.

---

![Quels logiciels?](https://github.com/Idenovia/.github/blob/main/assets/code.png?raw=true)

# Quels sont les logiciels développés, et depuis quand ?

Logiciels à ce jour :
| Logiciel                      | Langage / Framework | Date de création | Fin de support | Note              |
| :---------------------------- | :------------------ | :--------------- | :------------- | :---------------- |
| **Serenovia Desktop** (v1-v3) | Java / Spring       | décembre 2012    | horizon 2023   |                   |
| **Calendovia** (v1-v2)        | Java / Spring       | avril 2015       | fin 2022       |                   |
| **Wialo** (v1)                | PHP, Java           | mars 2017        | fin 2022       |                   |
| **Serenovia Mobile** (v1)     | Java                | 2016             | 2019           | Code source perdu |

Logiciels en développement :
| Logiciel                   | Framework TypeScript | Note                               |
| :------------------------- | :------------------- | :--------------------------------- |
| **Serenovia Desktop** (v4) | Svelte               |
| **Calendovia** (v3)        | Svelte               |                                    |
| **Wialo** (v2)             | Svelte               |
| **Serenovia Mobile** (v2)  | Angular              |
| **API**                    | Express              |
| **Site & documentations**  | Docusaurus           | Certaines pages seront en Markdown |

---

![Pourquoi en closed source?](https://github.com/Idenovia/.github/blob/main/assets/lock.png?raw=true)

# Pourquoi le code n'est-il pas accessible hors de l'organisation ?

Le code d'Idenovia est actuellement en closed-source, ce qui veut dire que le code n'est accessible qu'aux membres de l'organisation. Cela est éventuellement justifié par le fait que les logiciels sont payants de base, à l'exception de Calendovia, et peuvent contenir des données sensibles exclusives à la société. Mais cela n'empêchera pas le fait que des repos (notamment le site et le frontend de Calendovia, si aucune donnée sensible n'est intégrée) deviendront probablement open-source une fois la refonte totale effectuée.
