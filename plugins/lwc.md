# LWC

Detta plugin tillåter spelare att skydda sina dörrar, kistor, ugnar m.m

## <ins>Låsbara block</ins>  
>- chest
>- beacon
>- trapped_chest
>- furnace
>- dispenser
>- dropper
>- barrel
>- blast_furnace
>- cartography_table
>- composter
>- grindstone
>- lectern
>- loom
>- smoker
>- stonecutter
>- shulker_box
>- white_shulker_box
>- orange_shulker_box
>- magenta_shulker_box
>- light_blue_shulker_box
>- yellow_shulker_box
>- lime_shulker_box
>- pink_shulker_box
>- gray_shulker_box
>- light_gray_shulker_box
>- cyan_shulker_box
>- purple_shulker_box
>- blue_shulker_box
>- brown_shulker_box
>- green_shulker_box 
>- red_shulker_box 
>- black_shulker_box 
>- sign 
>- iron_door 
>- oak_door 
>- spruce_door 
>- birch_door 
>- jungle_door 
>- acacia_door 
>- dark_oak_door 
>- iron_trapdoor 
>- oak_trapdoor 
>- spruce_trapdoor 
>- birch_trapdoor 
>- jungle_trapdoor 
>- acacia_trapdoor 
>- dark_oak_trapdoor 
>- crimson_trapdoor 
>- oak_fence_gate 
>- spruce_fence_gate 
>- birch_fence_gate 
>- jungle_fence_gate 
>- acacia_fence_gate 
>- dark_oak_fence_gate 
>- white_banner 
>- orange_banner 
>- magenta_banner 
>- light_blue_banner 
>- yellow_banner 
>- lime_banner 
>- pink_banner 
>- gray_banner 
>- light_gray_banner 
>- cyan_banner 
>- purple_banner 
>- blue_banner 
>- brown_banner 
>- green_banner 
>- red_banner 
>- black_banner 
>- white_wall_banner 
>- orange_wall_banner 
>- magenta_wall_banner 
>- light_blue_wall_banner 
>- yellow_wall_banner 
>- lime_wall_banner 
>- pink_wall_banner 
>- gray_wall_banner 
>- light_gray_wall_banner 
>- cyan_wall_banner 
>- purple_wall_banner 
>- blue_wall_banner 
>- brown_wall_banner 
>- green_wall_banner 
>- red_wall_banner 
>- black_wall_banner 
>- player_head 
>- wither_skeleton_skull 
>- skeleton_skull 
>- creeper_head 
>- zombie_head 
>- hopper 
>- iron_block 
>- gold_block 
>- diamond_block 
>- emerald_block 

## <ins>Kommandon</ins>  
>- **/cpublic** | Skapar ett publikt skydd. Alla kan använda blocket men ingen annan kan skydda det.
>- **/cprivate** | Skapar ett privat skydd.  
Privat betyder privat: du kan ge andra spelare eller grupper tillgång till blocket. Detta gör du genom att lägga till dem efter "private". Du kan lägga till fler än en grupp och/eller spelare per kommando.
Om du använder ett "@" före gruppens/spelarens namn kommer denna att kunna modifiera blocket och lägga till andra användare men de kan inte hindra ägaren från att modifiera det.  
  *Exempel:*  
  `/lwc -c private Användarnamn g:Gruppnamn @användarnamn2`  
  `/cprivate Username g:Groupname @username2`  
>- **/cpassword** | Lösenordsskydda ett block  
Varje gång du loggar in kommer du behöva skriva lösenordet för att komma åt blocket. *(Om någon annan kan lösenordet har dom också tillgång till blocket)*  
>- **/cmodify** | Modifiera ett existerande skydd. *Lägg till/ta bort spelare/grupper*  
Se exemplen i /cprivate ovan. Samma gäller med detta kommando men "-" kan också användas framför spelare/grupper.  
  *Exempel:*  
  `/lwc -m -g:Medlemmar` | Tar bort åtkomst för alla Medlemmar  
  `/cmodify -Användarnamn1 @Användarnamn2` | Tar bort åtkomst för Användarnamn1 och ger Användarnamn2 avancerad tillgång  
  `/cmodify town:NågonStad` | Ger alla invånare i [staden](towny.md) NågonStad tillgång till blocket  
>- **/cunlock** | Lås upp ett lösenordsskyddat block  
>- **/cinfo** | Slå på ett skyddat block för att få information om det  
>- **/cremove** | Tar bort skyddet från ett block
>- **/climits** | Visar hur många skyddade block du kan äga  
>- **/lwc mode <mode namn> on/off**  
>> *Beständigt läge* låter dig utföra ditt senaste kommando på flera blocks tills du stänger av det.  
>>- **/lwc mode persist on/off** | Aktiverar/avaktiverar beständigt läge  
>>
>> *Droptransport läge* låter droppade föremål åka in i en utsedd kista  
>>- **/lwc mode droptransfer select** | Bestämmer vilken kista droppade föremål ska gå till   
>>- **/lwc mode droptransfer on/off** | Aktiverar/avaktiverar läget  
>>- **/lwc mode droptransfer status** | Visar status på läget  
>
>- **/lwc flag <flaggnamn> on/off** | Användbara flaggor: *magnet, redstone, autoclose, allowexplosions, hopper*  
>>- **Magnet**: Drar in föremål som droppats nära den skyddade kistan (eller andra block med förråd)  
>>  *Alias: /cmagnet on/off*  
>>- **Redstone**: Om detta är på så kan redstone påverka det skyddade blocket t ex. öppna dörrar, stänga av hoppers  
>>  *Alias: /credstone on/off*  
>>- **AutoClose**: Stänger automatisk en skyddad dörr om den öppnas  
>>  *Alias: /cautoclose on/off*  
>>- **AllowExplosions**: Tillåter det skyddade blocket att förstöras av en explosion  
>>  *Alias: /callowexplosions on/off*  
>>- **Hopper**: Kontrollerar om en hopper kan användas på ett skyddat block  
>>  *Alias: /chopper on/off*  
