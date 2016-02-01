###Reinicie o Asterisk de ambos servidores.###
```
/etc/init.d/asterisk restart
```
###Veja na CLI de ambos os servidores se os troncos estão registando.###
```
CLI> sip show registry
```
```
CLI> sip show peers
```
###Atualizando as configurações nos servidores.###
```
CLI> dialplan reload
```