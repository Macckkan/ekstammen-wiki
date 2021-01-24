# MobFarmManager
Detta är ett plugin som begränsar antalet monster/djur som kan samlas på samma yta  

Vi har inställningar som kollar antalet entiteter som finns när en sådan spawnar och då kollas 3x3 chunker och räknas som en  

Varje 30e sekund kollas 3 chunker runt varje spelare om det finns för många entiteter i dem och om det finns så rensas dom bort  
  
>Grupper:
>- Djur - *Max **30st** inom 3x3 chunker = 9 chunker totalt*
>>  - Grisar
>>  - Kor
>>  - Hästar
>>  - Harar/kaniner
>>  - Får
>>  - Kycklingar
>>  - Sköldpaddor
>- Monster - *Max **60st** inom 3x3 chunker = 9 chunker totalt*
>>  - Zombies
>>  - Skelett
>>  - Slime
>>  - Creepers
>>  - Bläckfisk
>
>- Enskilda monster/djur/föremål
>>  - Elder Guardian - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Wither skeleton - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Strax - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Husk - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Skeleton horse - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Zombie horse - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Armorstand - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Zombiefied piglin  - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Enderman - *Max **12st** inom 3x3 chunker = 9 chunker totalt*
>>  - Endermite - *Max **30st** inom 3x3 chunker = 9 chunker totalt*
>>  - Guardian - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Shulker - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Iron golem - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Rabbit - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Polar bear - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Parrot - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Turtle - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Phantom - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Cod - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Salmon - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Putterfish - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Tropical fish - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Drowned - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Dolphin - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Panda - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Fox - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Bee - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Hoglin - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>>  - Piglin - *Max **10st** inom 3x3 chunker = 9 chunker totalt*
>>  - Zoglin - *Max **20st** inom 3x3 chunker = 9 chunker totalt*
>
>*Saker som inte räknas med*:
>>- Fulla armor stands
>>- Fulla item frames
>>- Entiteter som har plockat upp föremål
>>- Tama djur
>>- Döpta djur
>>- Djur med sadel
>>- Bäbis djur