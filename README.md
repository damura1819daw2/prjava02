# prjava02

Instruccions realitzades pels següents apartats:
  1- Git checkout -b branca00. 
     Fent git status diu que estic en la branca00 I que no hi ha res per commit pero hi ha  fitxers no seguits (untracked).
  5- git checkout master
     git log 
     No apareix el commit realitzat amb la branca00
  10- Git checkout master
      No apareix cap de les línies afegides (està com el commit inicial)
      git merge branca00 → Ara apareixen tots els canvis realitzats
  14- Git push origin branca01 → Canvis pujats a Github I apareix la nova branca01.
  
  
  
Resposta a les preguntes dels apartats següents:
  6- No apareix perquè estic a la branca master, on aquest canvi no s’ha realitzat.
  7- Git checkout branca00
     Sí que apareix la darrera línia perquè estic a la branca amb la que s’ha realitzat el canvi.
  12- Git push → Només s’ha pujat la branca master perquè el fer el merge hem aplicat els canvis 
      de la branca00 a la branca master fent que aquesta desapareixés.
