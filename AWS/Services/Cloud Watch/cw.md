# Cloud Watch

Entender como monitorar as aplicações dentro da AWS
o cloudwatch é um centralizador de logs, além de armazenar os logs é possivel criar alarmes


O cloud watch também é utilizado para criar alarmes de custos

#### Como os alarmes são enviados?

As notificações são enviadas atraves do SNS


#### Além da notificação
Além de notificar um alarme também pode gerar uma ação como por exemplo, reiniciar um ec2, realizer um scalling up etc. os servicos de notificacao estão vinculados aos servicos de ec2 e auto scalling


### Eventos
Também é possivel capturar eventos de algum servico aws por exemplo: reiniciar de uma maquina EC2 e enviar uma notificação

#### TAGS

Por fim de monitoramento é sempre importante adiconar tags aos seus recursos.


## erro ao realizar medição

Durante as medições o cloud watch pode não conseguir coletar uma medição.