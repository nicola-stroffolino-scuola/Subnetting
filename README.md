# Subnetting

Tramite il subnetting abbiamo diviso una rete, la quale subnet è `255.255.255.0` si dimezzano, e la subnet di ogni e che permette l'entrata di 254 host, in 2 sottoreti, **Ufficio Marketing** e **Ufficio IT**, la quale ognuna permette l'entrata di 127 host.
+ **254 :** Perchè l'host 0 è occupato dall'**ID di rete** e l'host 255 come **broadcast** (Volendo 253 host perchè il router occupa l'ID 254).
+ **127 :** Perchè gli host per la rete da `255.255.255.0` si dimezzano, e la subnet di ogni sottorete diventerà `255.255.255.128`
