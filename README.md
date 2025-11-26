# Évaluation Développement Web

Bonjour,

Pour ce rendu, j'ai décidé de m'amuser un peu en imitant le style d'organisation et le design graphique de Wikipédia. J'ai donc simplement décidé d'imiter le plus possible la page originale de Grace Hopper. 

Le langage de design de Wikipédia étant relativement rigide, j'ai tordu quelques règles afin que cela soit plus ressemblant. Par exemple, la biographie encadrée de Wikipédia ne suit pas l'utilisateur. J'ai donc décidé d'aller à l'encontre de la consigne et de le laisser fixé en haut de la page. J'ai cependant transformé mon élément de navigation en un élément qui suit l'utilisateur, car j'aimerais que Wikipédia implémente cette fonctionnalité.

J'ai utilisé des pseudo-liens pour la plupart des liens de la page, car il y a beaucoup d'hyperliens dans une page Wikipédia et je ne voulais pas y passer trop de temps non plus. Les liens de notes et de bibliographie sont de véritables URLs. 

Mon texte principal est contenu dans l'élément main et l'encadre dans l'élément aside. Les deux sont organisés dans une flex-box dans l'élément container. Arrivé à une limite de 800 pixels de large, la barre de navigation disparait et la flexbox passe de row à column. 

La plupart du temps, je refuse d'utiliser des ia génératives, mais j'avais raté l'information selon laquelle la média query devait être placée à la fin du css et non au début. Et je me suis arraché les cheveux sur la question jusqu'au moment ou j'ai, pour le coup, utilisé un LLM pour débuguer.

Comme un fichier css est plus aéré qu'un fichier HTML, j'ai décidé de ne commenter que le css pour améliorer la lisibilité. J'ai également essayé d'utiliser des variables pour toutes les couleurs utilisées plusieurs fois.
