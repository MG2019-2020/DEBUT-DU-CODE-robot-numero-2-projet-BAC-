a1=0
a2=1
a3=2
a4=3
a5=4
b1=0
b2=1  
b3=2
b4=3
b5=4
c1=0
c2=1
c3=2
c4=3
c5=4
d1=0
d2=1
d3=2
d4=3
d5=4
e1=0
e2=1
e3=2
e4=3
e5=4
coord= [[a1, a2 ,a3 ,a4 ,a5],
        [b1, b2 ,b3 ,b4 ,b5],
        [c1, c2 ,c3 ,c4 ,c5],
        [c1, c2 ,c3 ,c4 ,c5],
        [e1, e2 ,e3 ,e4 ,e5]]
import random
position=0
gagne=4
graphe=[[a1, a2 ,a3 ,a4 ,a5],
        [b1, b2 ,b3 ,b4 ,b5],
        [c1, c2 ,c3 ,c4 ,c5],
        [c1, c2 ,c3 ,c4 ,c5],
        [e1, e2 ,e3 ,e4 ,e5]] 
fin=4
nbsimul=600
for n in range(nbsimul): #for n in range(0):
    position=random.choice(graphe[position])  
    if position==fin+4:gagne+=1
print(gagne/nbsimul)
#La partie avec ELSE ne marhce pas et n'est pas terminé
else: print("nouvelle tent")

  position=random.choice(graphe[position])
