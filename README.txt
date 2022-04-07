Para configurar o wifi, você tem que colocar ¨ifconfig¨ (sem aspas) no terminal e procurar, ele deve ficar no final da linha: 

Esse é o meu

wlp3s0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1280
        inet 192.168.*****  netmask 255.255.255.0  broadcast 192.168.******
        inet6 *********  prefixlen 64  scopeid 0x20<link>
        ether ********* txqueuelen 1000  (Ethernet)
        RX packets 105405  bytes 128963534 (128.9 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 43292  bytes 5655903 (5.6 MB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

você só precisa colocar o nome do lado, no meu caso é wlp3s0, na linha de wifi do conky, que fica no final da linha. troque todos os meus wlp3s0 pelo nome que tiver aparecendo no terminal.


essa configuração vai estar informando seu ip, mascara de rede e etc então se certifique de colocar o certo... 
