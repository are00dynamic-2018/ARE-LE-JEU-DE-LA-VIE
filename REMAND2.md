# propagation d'une maladie
les membres de groupe:
Ji Yinzhe
Zhao Zixuan
Liu Yuhao
Lu Zhaojie

Introduction:
 On utilise 4 nombres pour présenter 4 états dans ce phénomène d’infectation ,
- 0: les personnes sains
- 1: mort
- 0.25: les personnes dans la période d’incubation
- 0.5: les personnes infectées

Ensuite, pour les variables, on considère de mettre:
-	 I1: probabilité d'infectation de la maladie
-	 M: le taux de mortalité
-	 U: la durée de la période d’incubation 
-  I2: probalilité de comtamination par la maladie
-  P: % de probabilité pour attendre le virus dans les populations initiales
-  S: la probabilité de guérison
-  J: jours

Après,on pose des relations de variables:
-  La rapport des personnes infectées et la rapport des personnes mortes déterminent la vitesse de recherche des médicaments.Plus de personnes infectées et mortes,plus de la vitesse de recherche des médicaments.
-  La vitesse de recherche des médicaments va déterminer la probabilité de guérison.
-  La probabilité de guérison est composée par la guérison par soi-même et la guérison médicale.
-  la probabilité de guérison va influencer la taux de mortalité.
-  la probabilité d'infectation de la maladie et la probalilité de comtamination par la maladie sont défini directement au début.

Plus précisement,on pose des formules selon des relations de variables:
-  la rapport des personnes infectées:les personnes infectées/les personnes totales.
-  la rapport des personnes mortes:les personnes mortes/les personnes totales.
-  la vitesse de recherche des médicaments=1*(la rapport des personnes infectées)+2*(la rapport des personnes mortes).
-  la probabilité de guérison=10+10*(la vitesse de recherche des médicaments).
        (où le premier"10"est la probabilité de guérison par soi-même et le deuxième "10"est un coeffience défini par nous)
-  le taux de mortalité=5*((100-la probabilité de guérison)/100)

Le processus de propagation:
Regarder les graphes suivants:

Remarque:les processus est:les personnes sains->les personnes dans la période d’incubation->les personnes infectées->les     personnes mortes.(c'est-à-dire 0->0.25->0.5->1)

Ensuite,on change des valeurs initialisées et dessine les graphe:les personnes saines et les personnes mortes respectivement en fonction des jours.


la courbe rouge: le nombre de personnes sains
la courbe bleue: le nombre de personnes mortes



N=100
P=10
I1=100
I2=100
M=5
J=200
U=3
S=10

![graphe 1](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/1.png?raw=true)

N=100
P=10
I1=50
I2=100
M=5
J=200
U=3
S=10

![graphe 2](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/2.png?raw=true)


N=100
P=10
I1=100
I2=100
M=15
J=200
U=3
S=10

![graphe 3](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/3.png?raw=true)

N=100
P=10
I1=100
I2=100
M=5
J=200
U=3
S=30

![graphe 4](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/4.png?raw=true)

N=100
P=10
I1=100
I2=50
M=5
J=200
U=3
S=10

![graphe 5](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/5.png?raw=true)

N=100
P=10
I1=50
I2=50
M=5
J=200
U=3
S=10

![graphe 6](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/6.png?raw=true)

N=100
P=10
I1=100
I2=100
M=5
J=200
U=10
S=10

![graphe 7](https://github.com/are00dynamic-2018/Propagation-d-une-maladie-/blob/image/index.png?raw=true)




