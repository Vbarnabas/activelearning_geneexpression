# activelearning_geneexpression
A témalabor során egy olyan algoritmust hoztam létre, ami a következő kísérlettervezési
feladat megoldására lenne alkalmas:

Van egy mintánk, amiről szeretnénk egy génregulációs hálózatot készíteni. Ez a hálózat
egy olyan irányított körmentes gráf, ahol a csúcsok a gének, és egyik génből a másikba
akkor létezik él, ha az első befolyásolja a második expressziós szintjét. A mintáról rendelkezésre álló adat kevés, de képesek vagyunk génkiütés elvégzésére, ezért az aktív tanulás mellett döntünk. A költséges valódi génkiütés elvégzése előtt képesek vagyunk
olyan adatot szimulálni, ami megmutatja nagyjából milyen adat keletkezne a tényleges
kísérlet során. Az eredeti adat és a szimulált adat segítségével kell eldöntenünk, hogy
melyik génre a legérdemesebb elvégezni a tényleges génkiütést a lehető legtöbb új információ érdekében.
