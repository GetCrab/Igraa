1. Udes u level editor,tab modes, nades Nav Mesh Bounds Volume, ubacis u mapu i pokrijes 
   cijelo podrucje na kojem oces testirat AI (na podrucju na kojem oces testirat stavis da 
   je dno Nav Mesh Bounds Volume malo ispod poda mape i to je to). Pritisnes P i vidis jel
   sve zeleno (ako nije zeleno AI tu nemoze ic).
2. Udes u CharacterVP za nas lik, dodas dvije varijable, jednu FirstAI, koja je tipa 
   AI Character Advanced Object Reference. Te drugu Help, koja je tipa Integer.
3. Udes u folder AI, nades AI_CharacterAdvanced i ubacis ih koliko oces (za svakog moras
   pod Animation -> Anim Class stavit NobuoAnimBP). Tribas ih ubacit unutar Nav Mesh-a kojeg 
   si prije napravia.