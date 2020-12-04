# Test task - Chess tournament

5 versenyző indul egy sakkversenyen. Mindenki mindenkivel játszik 1 db. partit. Egy parti győzelemért a játékos 2 pontot,
döntetlenért 1 pontot, vereségért 0 pontot kap.

Példa a verseny végső állására:

 `- A B C D E`<br/>
 `A - 2 2 1 0`<br/>
 `B 0 - 1 2 0`<br/>
 `C 0 1 - 1 2`<br/>
 `D 1 0 1 - 2`<br/>
 `E 1 2 0 0 -`<br/>

Magyarázat:

 1. "A" játékos önmagával nem játszik. 
 2. "A" játékos legyőzi "B" játékost, ezzel szerez 2 pontot. 
 3. "A" játékos legyőzi "C" játékost, ezzel szerez 2 pontot. 
 4. "A" játékos döntetlenzik "D" játékossal, ezzel szerez 1 pontot. 
 5. "A" játékos veszít "D" játékossal szemben, ezzel szerez 0 pontot.


## 1. Generáljunk le egy versenyt, feltételzve, hogy egy parti kimenetele véletlenszerű. Jelenítsük meg a konzolban.

   Figyeljünk arra, hogy mivel "A" játékos legyőzte "B" játékost, akkor a "B" játékos sorában lássuk,
   hogy "B" játékos vesztett "A" játékos ellen.
   
   
## 2. Írjuk ki a konzolba, ki nyerte a versenyt, és hány pontot ért el:

pl.:
  `- A B C D E`<br/>
  `A - 1 1 2 1`<br/>
  `B 1 - 2 2 2`<br/>
  `C 1 0 - 2 2`<br/>
  `D 0 0 0 - 2`<br/>
  `E 1 0 0 0 -`<br/>
  
  B játékos nyerte a versenyt, 7 ponttal.
