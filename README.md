# Subnetting

Tramite il subnetting abbiamo diviso una rete, la quale subnet è `255.255.255.0` e che permette l'entrata di 254 host, in 2 sottoreti, **Ufficio Marketing** e **Ufficio IT**, la quale ognuna permette l'entrata di 127 host.
+ **254** $\rightarrow$ Perchè l'host 0 è occupato dall'**ID di rete** e l'host 255 come **broadcast** (Volendo 253 host perchè il router occupa l'host 254).
+ **127** $\rightarrow$ Perchè gli host per la rete da `192.168.0.0` si dimezzano, e la subnet di ogni sottorete diventerà `255.255.255.128`

Le 2 sottoreti :
+ **192.168.0.0** $\rightarrow$ Avrà come range di host `192.168.0.1` a `192.168.0.126` dove `192.168.0.127` sarà utilizzato come broadcast.
+ **192.168.0.128** $\rightarrow$ Avrà come range di host `192.168.0.129` a `192.168.0.254` dove `192.168.0.255` sarà utilizzato come broadcast.
