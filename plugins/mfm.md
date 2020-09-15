# MobFarmManager
Detta är ett plugin som begränsar antalet monster/djur som kan samlas på samma yta  

Vi har inställningar som kollar antalet entiteter som finns när en sådan spawnar och då kollas 3x3 chunker och räknas som en  

Varje 30e sekund kollas 3 chunker runt varje spelare om det finns för många entiteter i dem och om det finns så rensas dom bort  
  
Entitet grupper:
- Djur - Max 30st inom 3x3 chunker = 9 chunker totalt
  - Grisar
  - Kor
  - Hästar
  - Harar/kaniner
  - Får
  - Kycklingar
  - Sköldpaddor
- Monster - Max 60st inom 3x3 chunker = 9 chunker totalt
  - Zombies
  - Skelett
  - Slime
  - Creepers
  - Bläckfisk

*Saker som inte räknas med*:
- Fulla armor stands
- Fulla item frames
- Entiteter som har plockat upp föremål
- Tama djur
- Döpta djur
- Djur med sadel
- Bäbis djur