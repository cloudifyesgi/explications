# La structure du projet

Nous avons réaliser un projet en module, c'est à dire que nous avons séparé les différents tâches du projet au maximum.
  
  ![Structure globale du projet](https://zupimages.net/up/19/32/hakl.png)
  
## Logiciels et versions utilisées

### API Rest

Nous avons opté pour du NodeJS avec du javascript bien qu'avec notre recule actuel nous aurions préféré partir sur du NodeJS en Typescript. Pour l'ORM nous avons utilisé mongoose qui nous permet de facilement exploiter notre base de donnée sous MongoDB.
L'API Rest doit s'occuper de tous les traitements complexe ainsi que de toutes les communications avec la base de données.

### FRONT WEB

Pour le front web nous avons utilisé Angular qui est optimal avec une API sous NodeJS. Cela nous permet de faire des requêtes à l'API de manière fluide et sans rechargement de page. Nous avons utilisé le Template CoreUI mais Angular Material suffit amplement.
