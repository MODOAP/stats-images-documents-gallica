ModOAP - Statistiques sur les images contenues dans un ou plusieurs documents Gallica

Ce script permet de calculer des statistiques sur les images contenues dans un ou plusieurs documents Gallica.

Calculs effectués :

   - Nombre d'images par document et par position dans le document (1er tiers, 2nd tiers, 3e tiers)
   - Nombre d'images par document et par position dans la page (moitié haut, moitié bas, moitié gauche, moitié droite)
   - Taux d'images par page par document
   - Taille moyenne des images par document (exprimée en pixels)
   - Pourcentage moyen de couverture de la page par document
   - Taux d'images par page par année du corpus total

Fonctionnement :

   1. Récupérer les blocs images d'un ou plusieurs documents (au format structuré JSON) en spécifiant les liens ARK des documents hébergés sur Gallica.
   2. Lancer le calcul statistique. Les résultats sont présentés sous forme de graphiques dans un fichier html de visualisation, généré par ce script.

