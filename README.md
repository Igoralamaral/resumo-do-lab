# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# Localizando serviços por categoria 
Na aba de configurações, podemos realizar mudanças como idioma e diferentes temas para o console Azure. Na botão "Todos os serviços", podemos ver várias catagorias como IA + Machine Learning, Análises, Computaração, Contêneires, entre outras. Dessa forma é mais fácil localizar os serviços que queremos utilizar. 

# Benefícios da nuvem 
Especificações de SLA são importantes para gerenciamento de recursos na nuvem, já que cada SLA possuí um determinado tempo previsível por semana para que o recurso fique indisponível. No portal, ao criar máquinas virtuais, cada recurso possuí informações explicando seu funcionamento, inclusive o próprio portal disponibiliza também dicas de como melhor gerenciar os recursos com sugestões de recursos que otimizam o funcionamento de acordo com suas escolhas. Um exemplo é quando se cria uma conta de armazenamento e é possível escolher entre tipos de redundâncias diferentes que implicam em SLA, sendo necessário escolher de acordo com as necessidades do cliente.

# Configurando uma instância no banco de dados da Azure
Quando criamos uma instância de máquina virtual podemos selecionar o sistema operaciona, seu tamanho e podemos ver os custos mensais que aquele serviço vai ter. No portal também é possível selecionar a aba de criação de banco de dados onde devemos primeiro criar um servidor, escolher o tipo do banco de dados e posteriormente também podemos ver a expectativa de custos mensais. 

# Construindo Arquiteturas no Azure
Na plataforma é possível criar grupo de recursos, que é uma coleção de recursos que compartilham o mesmo ciclo de vida, permissões e políticas. Também é possível criar uma rede virtual, pois cada máquina virtual é necessário um IP para aquela máquina. A redeve virtual pode ser alocada diretamente no grupo de recursos criado. 

# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure.
Na Azure é possível configurar uma série de elementos na hora de criar uma máquina virtual. Desde o básico com nome, região, opção de disponibilidade, opção de zona, tamanho da imagem, sistema operacional da imagem até elementos de segurança, rede, gerenciamento, monitoramente; Em cada etapa é possível personalizar da forma que o cliente deseja como estipular uma hora de desligamento, quais aplicativos e extensões serão instalados no momento de criação da máquina virtual entre outros. 

# Dominando o Armazenaeno no Azure
Dentro do console podemos criar contas de armazenamento, sendo necessário a escolha de um nome global único e exclusivo, determinando os serviços de armazenamento e também as opções de redundância. Depois espeficamos os tipos de dados que queremos armazenar de acordo com as opções especificas para aqueles dados. Também foi mostrado as opções de migrações da Azure, como o data box disk, data box, data box heavy, cada um com uma capacidade de armazenameno e quantidade de dias para uso sem custos extras. 

# Entendendo sobre Segurança e Identidade na Azure
No console Azure podemos utilizar as funções e administradores da conta quando usamos o Microsoft Entra ID. Dessa forma é possível configurar elementos de outras contas. Com o RBAC podemos criar, excluir, remover funcionalidades e permissionamentos das contas dentro da nuvem.

# Otimizando custos na Azure
Com a utilização de ferramentas como Calculadora de Custos e Gerenciamento de custos e cobranças, é possível monitorar e estimar os custos de utilização de recursos na Azure. dessa forma podemos observar estimativas de quanto o cliente era gastar, possível alerta de custos, budgets selecionados e também recomendações do advisor. 

# Gerenciando politicas em acessos Azure
Podemos utilizar recuros de gerenciamento de políticas para que a aplicação esteja em conformidade com as leis e politicas da região em que está implementadada, deixando o ambiente seguro com questões de auditoria. O Microsoft Purview permite criar perfis, selecionar grupos de recurso e permitir gerenciar dados que estão ou não na Azure. Microsoft Priva é um exemplo de aplicação que analisa se um recurso está de acordo com requisitos de alguma determinada lei. 

# Ferramentas de implantação na Azure
Dentro do portal da Azure tem uma opção de terminal Powershell ou Bash, em que é possível enviar os comandos diretamente pelo terminal, que são enviados para o centralizador Azure Resource Manager que irá interpretar os comandos e seguir com o fluxo para os recursos. 

# Monitoramente inteligente com o Azure
Com o serviços de monitoramente da Azure podemos ter exibiçõers personalizar de recursos da Azure com o serviços de Integridade de Serviços (Resource Health), e também podemos monitorar, ter uma telemetria dos dados e aplicativos com o Azure Monitor, analisando de forma fácil e verificando a disponibilidade e desempenho das aplicações. 
