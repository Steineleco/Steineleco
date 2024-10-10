Configurando uma instância de Banco de Dados na Azure

No tópico foi falar dos tipos de serviços em nuvem como PaaS, SaaS e IaaS.

Na criação de máquinas virtuais temos muitos detalhes.

sendo eles images x tamanho, ou seja dependendo do tipo da imagem, o mesmo já traz o valor que será gasto mensal em caso de mater a máquina 
em funcionamento.

Tudo o que for criar é minha responsabilidade como infraestrutura.

Na aba de discos podem ser adicionados mais discos caso se faça necessário além do padrão

Parte de redes, onde pode ser criado uma VPN, redes virtuais, endereçamento, se a máquina vai estar exposta para a internet ou não.

Parte de gerenciamento se vai habilibar a proteção da VM ou não, como vai funcionar a conexão, hora de reinicialização automática, para 
melhor performance da máquina, se vai habilitar o desligamento automático ou não.

==========================================================================================================================================

A criação de um banco de dados:

assinatura, grupo de recursos.

nome do banco de dados

criar um servidor simbolico

método de autenticação

definir admnistrador

modelo de redundância do armazenamento do backup

ao montar a vm o sistema te dá uma previsão de custo mensal.

todo cenário de gerenciamento está assossiado ao modelo de serviço, quanto mais estiver envolvido mais a Microsoft estará e vice versa.

Infraestrutura como serviço é o que sempre demanda do nosso lado, fazer ajuste, manutenção e configuração.

O modelo que dá menos dor de cabeça é o software como serviço.
