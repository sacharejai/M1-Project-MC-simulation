# M1-Project-MC-simulation
The project consists of setting up your own simulation based on Monte-Carlo methods. A simulation of the experiment SiTrInEO will be implemented, as well as particle-matter interactions within detectors.

Le programme est juste à compiler sous  python3, une fois compiler lors de l’exécution il faut entré le nombre de particule que le système de détection va étudier et les résultats sont sortis sous forme de fichier txt, et de courbe pour l’histogramme de l’influence des petits angles et les impulsions avec leurs barre d’erreur associé.

Le code peut etudier l'influence d'un angle sur les detecteurs et donc l'influence sur la distribution angulaire de theta et phi.

Le code peut etudier le taux de comptage en fonction de la distance entre les detecteurs

Pour l'affichage en 3 dimensions il faut choisir quel trajectoire a aller recuperer en changeant le numero de la particule a tracer. Il faut verifier au prealable que la particule ne sort pas du systeme puisque la data ne garde que les hit des particules qui ne sortent pas.

Le code fait un simulation d'un spectrometre d'impulsion d'electrons cosmique, les impulsions sont garde dans un fichier data de sortie avec leurs inceritudes associé.
