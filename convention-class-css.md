## La convention de nomenclature des classes css

La convention BEM - Block Element Modifier vise à rendre réutilisable plus facilement nos styles
On va privilégier pour cela les classes car elles sont réutilisables et elles dissocient le fond de la forme
En plus ainsi on n'aura quasi exclusement des sélecteur de classes, ce sera très facile de connaitre le poids d'un selecteur et de le surcharger au besoin, puisque si tous mes selecteurs ont le même poids c'est le dernier qui surcharge l'autre

- On va avoir des block, c'est à dire des zones: par exemple : menu, heading, article, logo, comments, ...
  
- On va avoir des elements faisant partie d'un block : menu__links, menu__title, menu__subitlte, logo__title, ...
La convention est de mettre un double underscore __, ce n'est qu'une convention ça ne change rien au fonctionnement de html et css, il s'agit d'un nom de classe comme un autred

- On va avoir des modifiers, des alterations d'un block ou d'un element existant
par ex : logo--small, menu__title--dark