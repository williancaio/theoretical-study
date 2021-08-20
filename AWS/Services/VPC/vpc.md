# VPC
Vpc é o ambiente de rede dentro da AWS. é possivel extender a rede local para dentro da aws. esse recuros é conhecido como site to site.

VPc é uma rede virtual isolada logicamente dentro da aws. Subrede é um segmento dentro da vpc onde é possivel ter recursos de maneira isolada. As subnets estão distribuidas dentro das AZs


Por padrão as vpcs default não tem acesso à internet, o acesso pela internet é feita através de um internet gateway


é possivel aplicar regras via security groups e ACLs, as acls funcionam como uma segunda camada de proteção, o sg é o primeira camada de proteção

nat gateway permite conexao da rede privada com a internet somente outbound.