Irei implementar configuração básica de segurança nos routers e switchs, ssh, testar ping
e fazer a configuração do LLPD para os vizinhos, conexão ssh e divisão entre as redes.

Também quero testar uma separação de subnetting entre dois PCs do S_Sales, ambos estando em subnetting diferentes
o ping não tem que acontecer.

O teste foi feito e concluido, utilizando a teoria da subnetting,apliquei IPs na mesma faixa porém em subnetting diferentes
como deveria acontecer, o ping não aconteceu, enquanto no outro computador o ping aconteceu perfeitamente.

Também realizei os teste do IPv6, descobri que nos switch temos que ativa ele manualmente via SDM, consegui visualziar o gerenciamento automático do IPv6 que distribuiu para os computadores IPv6 nativamente em LLC, que também testei e se comunicou com o roteador e o switch (no caso o LLC deles).

Laboratório concluido.

Lldp abaixo:

Capability codes:
    (R) Router, (B) Bridge, (T) Telephone, (C) DOCSIS Cable Device
    (W) WLAN Access Point, (P) Repeater, (S) Station, (O) Other
Device ID           Local Intf     Hold-time  Capability      Port ID
S_TI                Gig0/0/1       120        B               Gig0/1
S_Sales             Gig0/0/0       120        B               Gig0/1

Total entries displayed: 2