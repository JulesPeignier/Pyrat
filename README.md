# Pyrat
-----------

Small game on python proposed by [IMT Atlantique](https://formations.imt-atlantique.fr/pyrat/) :  
* A rat and a python are on opposite sides of a maze. 
* Cheeses are scattered throughout the maze. 
* The goal is to eat more pieces of cheese than your opponent. 
* The algorithm decides which path to take on a turn-by-turn basis.

# Algorithms 
-----------

AI name: Greedy Prep (preprocessing)
Description : Greedy Prep is a basic greedy where the path is calculated in the preprocessing


AI name : Greedy MR (Maze reduced)
Description : Greedy MR is an improved greedy 

*   -> the next cheese to take is determined in the turn
*   -> it changes direction if its target is eaten in the meantime
*   -> maze_map is reduced by removing dead ends that don't lead to a cheese (this greatly reduces the computation time)

AI name : PabloV2 (utilisé pour le tournoi) 
Description : PabloV2 est un greedy par zone de forte densité de fromage, il a deux états. 
*   -> Le premier où il va dans une zone de forte densité (selon la densité et la distance au joueur)
*   -> Le second où il se met en mode Greedy MR, le greedy amélioré
  
  
  

PS: Hi curious first years imt atlantique
