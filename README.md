# detection-des-lignes-des-voies
La notion de voiture autonome, désigne un véhicule capable d’aller d’un point A vers un point B sans conducteur sur une route. Et pour qu’on inclue une tel intelligence a un véhicule, sachant que la vue est prise depuis une caméra de notre voiture il faut une certaine connaissance au traitement d’image pour savoir extraire une route de l’image et détecter un véhicule proche du notre   
et j'ai opter pour la methode de la transformer de hough pour extraire ces lignes 
on auras besoin seulment de télecharger la bibiothèque open-cv de python et le tour est jouer 

les differentes etapes que j'ai suivie :
Après avoir apporté une image, le processus consiste en quelques étapes : rendre l’image en niveau de gris, puis on utilise un filtre gaussien pour éliminer le bruit de l’image et lui effectuer une extraction de contour en passant par l’algorithme de Canny, après cela ont défini une région d’intérêt, et enfin on lui applique la transformer de Hough.

