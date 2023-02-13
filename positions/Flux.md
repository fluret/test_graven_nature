#Flux et position relative
Pour représenter le positionnement en flux normal, on peut imaginer le navigateur parcourant (logiquement) la page de code HTML du début à la fin et retranscrivant son contenu au fur et à mesure des balises rencontrées. Comme dans la lecture d'un texte, il procède verticalement, commençant en "haut" de l'écran pour aller jusqu'en "bas", et horizontalement de gauche à droite, sur la totalité de l'espace disponible et nécessaire en largeur comme en hauteur.
##Boîte de type bloc en flux normal

Par défaut, les boîtes de type bloc seront affichées dans une succession verticale. Prenons par exemple deux blocs différenciés par leur couleur :

En HTML :

<p class="jaune">Une boîte jaune</p>
<p class="verte">Une boîte verte</p>

En CSS :

.jaune {
  background-color: #ffff00;
}
.verte {
  background-color: #00ff00;
}

Le résultat, illustré par la figure ci-dessous, peut être observé également dans l'exemple 1 :