# propagation d'une maladie
les membres de groupe:
Ji Yinzhe
Zhao Zixuan
Liu Yuhao
Lu Zhaojie

Introduction:
 On utilise 4 nombres pour presenter 4 états dans ce phenomene d’infectation ,
- 0: les personnes sains
- 1: mort
- 0.25: les personnes dans la periode d’incubation
- 0.5: les personnes infectees

Ensuite, pour les variables, on considere de mettre:
-	  I: le taux d’etre infecte
-	  M: le taux de mortalite
-	  U: la duree de la periode d’incubation 

Si I est plus grand, les virus pouvent facilement infecter des gens sains , c’est-a-dire de 0 passe a 0.25.
Cependant, on ne peut pas detecter que ces personnes sont infectees , jusqu’a on arrive a l’etat 0.5 qui dure un certain temps ( depend de U )
Dans l’etat 0.5, si M est grand, les virus peuvent facilement tuer les patients,  c’est a dire de 0.5 changent passe a 1.
On s’interesse a etudier que:
La relation entre l’environnement reel et nos variables.
On peut mimer que comment le virus agit dans la realite (Ex : on change M et I, par exemple ces deux variables sont plus grandes dans les region arriere a cause des conditions economiques et hygienique)

Plus precisement,on cree certaine parametres possibles a mettre de I,M et U.
-    on pose les personnes sains,dans la periode d'incubation et infectees peuvent rechercher des medicaments,donc ca va influencer la vitesse de rechercher.La vitesse de rechercher va influencer la capacite de propagation,la capacite de causer la mort et la capacite de mutation.
-    on pose la capacite de propagation depend de facon de propagation et la duree de la periode d'incubation.On pose il y a trois facons de propagation:par l'ocean,par le terre et par l'atmosphere,donc la coefficient de propagation par l'ocean =la rapport de la surfance d'ocean (aleatoire) * le coefficient d'affinite avec l'ocean(aleatoire),analogue par le terre et l'atmosphere.
-    on pose la capacite de mutation depend de resistance au medicament,le coefficient d'affinite avec l'environnement et le symptome(la duree de la periode d'incubation.On tire la probabilite de mutation a l'initialisation aleatoirement,apres chaque etape,la resistance au medicament va changer aleatoirement,cest a dire la probabilite de mutation va changer,donc il va influencer la vitesse de rechercher,la capacite de propagation et la probabilite de mort.Ensuite,on pose la coefficient de symptome qui a la relation entre la probabilite de mort,la probabilite de mutation et la duree de la periode d'incubation.
-    on pose la probabilite de mort a la relation entre la probabilite de guerison et la coefficient de symptome.La probabilite de la guerison depend de la vitesse de rechercher et la coefficient de guerison d'autotherapie.(ca cest aleatoire aussi)

![alt text]（）
