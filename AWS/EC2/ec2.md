# EC2

O AWS EC2 permite você criar instancias sobre demandas cobrada por segundo de uso e pela configuração da maquina.

## Tipos de EC2[1]

* *Uso geral*
O EC2 de uso geral é o mais generico e o mais utilizado. Ele fornece um equilibrio entre recursos de computação e memoria, esse tipo de servidor pode ser usado para uma api por exemplo

* *Otimizado para computação*
Geralmente utilizado para aplicação com alto consumo de CPU. Geralmente jogos, uso de machine learning etc.

* *Otmizados para memoria*
Utilizada por aplicações que necessitam carregar muitas informações na memoria

* *Computação acelerada*
Utilizada geralmente para machine learning, essas maquinas utilizam GPU

* *Otimizadas para armazenamento*
Maquinas utilizadas para alta carga de leitura e escrita

# Como acessar as maquinas
Há duas formas de se conectar nas maquinas EC2

##### SSH
Dessa maneira é necessário expor sua maquina para a internet e utilizar uma chave criada no momento da criação da maquina.

##### System manager
Dessa maneira não é utilizada nenhuma chave e também não é necessário deixar a maquina exposta a internet. Dessa maneira é necessário configurar a role da maquina para permitir o acesso.

## EC2 aws marketplace
É utilizado para obter uma imagem já customziada para alguma finalidade, por exemplo uma instancia para um wordpress, um mysql.

## User data
User data é o lugar onde adicionamos scripts para ser rodados no momento em que a maquina esta sendo criada.

# Fontes
- [Tipos de instância do Amazon EC2[1]](https://aws.amazon.com/pt/ec2/instance-types/?trkCampaign=acq_paid_search_brand&sc_channel=PS&sc_campaign=acquisition_BR&sc_publisher=Google&sc_category=Cloud%20Computing&sc_country=BR&sc_geo=LATAM&sc_outcome=acq&sc_detail=ec2%20instance%20types&sc_content={ad%20group}&sc_matchtype=e&sc_segment=490489530680&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|Cloud%20Computing|EC2|BR|EN|Sitelink&s_kwcid=AL!4422!3!490489530680!e!!g!!ec2%20instance%20types&ef_id=CjwKCAjw3_KIBhA2EiwAaAAliuzLDKNZl_rEDI6lld1E790VSjhR79fEz8OSq2X_O60DjrfZL1Di-BoCcMQQAvD_BwE:G:s&s_kwcid=AL!4422!3!490489530680!e!!g!!ec2%20instance%20types)