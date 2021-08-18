# Auto Scalling

o AWS Auto scalling é um serviço do EC2 reponsavél por monitorar a saúde das maquinas ec2 e caso aconteça algum problema ele lança novas instancias.

## O Auto Scalling funciona com

- Instancias EC2
- tasks ECS
- tabelas e indices do DynamoDB
- replicas do Autora


## escalar o amazon ec2
Você configura um número minimo de instancias e um número maximo de instancias. Para manter o número minimo o autoscalling vai verificar se o EC2 esta healthy e também vai verificar a rota de healthy da sua aplicação.


## E se meu trafego aumentar, como lançar novas maquinas?

É possivle criar *Scalling policy* para monitorar

#### Tipos de métricas
- Média da rede IN
- Média da rede OUT
- Número de request no load balancer por target
- Média de CPU utilizada


Dessa forma é feito scalling up ou scalling down dos seus recursos. O scalling up é feito até o maximo e o scalling up é feito até o minimo.