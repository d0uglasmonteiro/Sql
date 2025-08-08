Missão Prática | Nível 4 | Mundo 4

Material de orientações para desenvolvimento da missão prática do 4º nível de
conhecimento.

📍 As práticas devem ser feitas individualmente.

RPG0026  - TIRANDO PROVEITO DA NUVEM PARA PROJETOS DE
SOFTWARE

Objetivos da prática

Demonstrar habilidade na criação e gerenciamento de recursos na Nuvem
Azure, adquirindo conhecimento sobre a estrutura básica da plataforma Azure
Utilizar efetivamente o portal Azure para criar e configurar uma Máquina
Virtual (VM), demonstrando compreensão dos recursos e suas funções.
Configurar regras de rede e grupos de segurança, adquirindo conhecimento
sobre a estrutura das regras de rede na Nuvem Azure.
Importar um arquivo .bacpac para um banco de dados no Banco de Dados SQL
do Azure.
Criar e configurar um aplicativo web no Azure, demonstrando compreensão do
mecanismo de hospedagem e implantação de aplicativos web.
Entrega e Progresso

As microatividades irão dar suporte para o desenvolvimento da Missão Prática.
Elas têm apoio/gabarito para resolução no próprio documento;
A entrega esperada é a Missão Prática, descrita neste documento após as
Microatividades;
A missão prática progride 5% na entrega e até 5% dependendo da nota
atribuída pelo tutor em sua correção.
👉 Atividades práticas

TIRANDO PROVEITO DA NUVEM PARA PROJETOS DE
SOFTWARE

Microatividade 1: Criar uma Máquina Virtual
(VM) no Azure

- Material necessário para a prática

Conta no Microsoft Azure.
Navegador Web (Google Chrome, Firefox, MS Edge, Safari ou Opera).
- Procedimentos

Acesse o portal do Azure através do seu navegador web.
No painel de controle do Azure, clique em "Criar um recurso".
3. Selecione a opção "Máquina Virtual".

4. Preencha os campos obrigatórios para a criação da VM, incluindo:

Nome da Máquina Virtual
Região (selecione uma região próxima)
Sistema Operacional (por exemplo, Windows ou Linux)
Tamanho da Máquina Virtual (escolha um que atenda às suas necessidades)
Opções de autenticação (nome de usuário e senha ou chave SSH)
5. Role para baixo e reveja as configurações. Certifique-se de que tudo esteja
correto.

6. Clique em "Revisar + criar" na parte inferior da página.

7. Na página de revisão, verifique novamente todas as configurações. Se estiver
tudo correto, clique em "Criar" para iniciar o processo de criação da VM.

8. Aguarde alguns minutos enquanto o Azure cria a VM. Você verá uma
notificação quando a criação estiver concluída.

9. Após a criação da VM, volte ao painel de controle do Azure e clique em
"Recursos". Verifique se a sua VM está listada lá.

Captura de tela 2025-01-07 100501.jpg
 (Moderado)
- Resultados esperados  ✨

Ao seguir esses passos, você deverá ser capaz de criar com sucesso uma
Máquina Virtual na Nuvem do Azure. Certifique-se de que a VM tenha sido
criada com as configurações desejadas e esteja listada nos recursos do seu
painel do Azure.

Microatividade 2: Configurar Regras de Rede e
Grupos de Segurança no Azure

Material necessário:

Conta na Azure.
Navegador Web: Google Chrome, Firefox, MS Edge, Safari ou Opera.
 

- Procedimentos

Acesse o portal do Azure utilizando seu navegador.
No painel de controle do Azure, clique na VM que você criou na
Microatividade 1 para selecioná-la.
No menu lateral esquerdo, clique em "Configurações de Rede ".
4. Na seção de "Grupo de segurança de rede", clique em "Criar regra de portas"
para criar uma nova “Regra de portas de entrada”.

5. Crie uma regra para permitir que qualquer pessoa na internet possa acessar
um servidor Web hospedado na máquina virtual criada anteriormente. Preencha
os campos necessários para a regra, incluindo:

Origem: O filtro de origem pode ser qualquer (any), um intervalo de endereços
IP, Meu endereço IP, um grupo de segurança de aplicativo ou uma marca
padrão. Ele especifica o tráfego de entrada de um intervalo de endereços IP de
origem específico que será permitido ou negado por essa regra.
Intervalos de porta de origem: Forneça uma única porta, como, 80; um
intervalo de portas, como, 1024 a 65535, ou uma lista separada por vírgulas de
portas e/ou intervalos de portas únicos, como 80,1024-65535. Isso especifica
de quais portas a entrada de tráfego será permitida ou negada por esta regra.
Forneça um asterisco (*) para permitir o tráfego por meio de qualquer porta.
Destino: O filtro de destino pode ser Qualquer um, um intervalo de endereços
IP, um grupo de segurança de aplicativos ou uma marca padrão. Ele especifica
o tráfego de saída de um intervalo de endereços IP de destino específico que
será permitido ou negado por essa regra.
Serviço: O serviço especifica o protocolo de destino e o intervalo de porta para
essa regra. Você pode escolher um serviço predefinido, como RDP ou SSH, ou
fornecer um intervalo de porta personalizado. Se selecionar um serviço
específico o próximo item (Intervalos de porta de destino) será preenchido
com o valor padrão e não será editável.
Intervalos de porta de destino: Somente editável se na opção anterior for
marcado “Custom”. Forneça uma única porta, como, 80; um intervalo de
portas, como, 1024 a 65535, ou uma lista separada por vírgulas de portas e/ou
intervalos de portas únicos, como 80,1024-65535. Isso especifica de quais
portas a entrada de tráfego será permitida ou negada por esta regra. Forneça
um asterisco (*) para permitir o tráfego por meio de qualquer porta.
Protocolo: Escolha entre as opções disponíveis (Any, TCP, UDP ou ICMP)
Ação: selecione entre permitir ou negar
Prioridade: ordem de processamento da regra. As regras são processadas em
ordem de prioridade; quanto menor for o número, maior a prioridade.
Recomendamos deixar lacunas entre as regras - 100, 200, 300, etc. - para que
seja mais fácil adicionar novas regras sem ter que editar regras existentes.
Nome da regra: Especifique um nome para a regra.
Descrição: Preencha uma descrição da regra especificando a sua finalidade.
Captura de tela 2025-01-07 101829.jpg
 (Moderado)
6. Após preencher todos os campos, clique em "Adicionar" para criar a regra. A
figura a seguir exemplifica a regra criada.

Captura de tela 2025-01-07 102002.jpg
 (Moderado)
- Resultados esperados

O resultado esperado desta microatividade é que o aluno seja capaz de
configurar com sucesso uma regra de segurança de rede no Azure para melhorar
a segurança da rede virtual utilizada pela VM criada na Microatividade 1.
Certifique-se de que a regra seja criada com as configurações desejadas.

Microatividade 3: Criar um banco de dados
SQL do Azure

- Material necessário para a prática

Conta na Azure.
Navegador Web: Google Chrome, Firefox, MS Edge, Safari ou Opera.
- Procedimentos

 

Acesse o portal do Azure usando seu navegador web.
No painel de controle do Azure, clique em "Criar um recurso" no menu.
Selecione “SQL Database” e “Criar”.
.

4. Preencha os campos necessários para a criação do banco de dados, incluindo:

Nome do banco de dados
Grupo de recursos (crie um novo ou selecione um existente)
Servidor do banco de dados (crie um novo ou selecione um existente)
Configurações de segurança, como o usuário que será de administrador do
servidor
5. Se você ainda não tiver um servidor para hospedar o banco de dados, será
necessário criar um novo. Esta etapa é aplicável apenas nesse cenário.

Clique em "Criar Novo" conforme indicado na imagem abaixo.
Captura de tela 2025-01-07 102840.jpg
 (Moderado)
Acesse a página "Criar Servidor do Banco de Dados SQL", onde você deve
inserir um nome exclusivo para o servidor, escolher uma região próxima a
você, selecionar o método de autenticação como "Use a autenticação SQL",
optar por um logon de administrador exclusivo que atuará como a ID principal
do administrador e definir uma senha. Após preencher os detalhes, clique em
"OK".
Captura de tela 2025-01-07 102953.jpgCaptura de tela 2025-01-07 103010.jpg
6. Clique em "Revisar + criar" para revisar as configurações que você inseriu.

7. Na página de revisão, verifique se todas as configurações estão corretas e, em
seguida, clique em "Criar" para iniciar o processo de criação do banco de dados
SQL.

8. Aguarde alguns minutos enquanto o Azure cria o banco de dados. Você verá
uma notificação quando a criação estiver concluída. A figura a seguir ilustra a
criação do banco de dados.

Captura de tela 2025-01-07 111241.jpg
 (Moderado)
- Resultados esperados

O resultado esperado desta microatividade é que o aluno seja capaz de criar
com sucesso um Banco de Dados SQL na Microsoft Azure. Certifique-se de que
o banco de dados tenha sido criado com as configurações desejadas e que ele
apareça na lista de recursos no painel do Azure.

Microatividade 4: Conecta-se ao seu
banco de dados

- Material necessário para a prática

Conta na Azure.
Navegador Web: Google Chrome, Firefox, MS Edge, Safari ou Opera.
- Procedimentos

Antes de integrar o banco de dados ao seu aplicativo, é essencial garantir sua
conectividade. Esta atividade utiliza a ferramenta Azure CLI (az) para listar e
obter informações sobre o banco de dados, incluindo seu tamanho máximo,
status e a string de conexão necessária para testar a conexão.

 

Acesse o portal do Azure utilizando seu navegador.
Na página inicial clique no botão do Azure Cloud Shell conforme a imagem a
seguir. Azure Cloud Shell é uma experiência de shell baseada em navegador
para gerenciar e desenvolver recursos do Azure. Pense no Cloud Shell como
um console interativo executado na nuvem.
3. Nos bastidores, o Cloud Shell é executado no Linux. Porém, dependendo da
sua escolha de ambiente, Linux ou Windows, há duas experiências a escolher:
Bash e PowerShell. Vamos

 

Captura de tela 2025-01-07 111821.jpg
 (Moderado)
4. Caso você não tenha nenhum armazenamento montado, será solicitado para
que seja criado um.

Captura de tela 2025-01-07 111912.jpg
 (Moderado)
5. Quando prompt do shell aparecer, conforme figura a seguir, você poderá
executar os comandos para verificar as informações do banco.

Captura de tela 2025-01-07 112017.jpg
 (Moderado)
6. Simplifique a execução dos comandos configurando valores padrão. Execute o
seguinte comando az configure, substituindo [server-name] pelo nome do
servidor lógico do SQL do Azure que você criou e [resource-group] pelo grupo de
recursos usado para o servidor:

 

az configure --defaults group=[resource-group] sql-server=[server-name]

 

Para as atividades anteriores o grupo de recursos criado foi Ubuntu_group e o
servidor ubuntu-fullstack. Você deve adaptar os nomes caso tenha utilizado
diferente.

 

Captura de tela 2025-01-07 112137.jpg
 (Moderado)
7. Execute o comando az sql db list a seguir para listar todos os bancos de
dados no servidor lógico do SQL do Azure. Você verá um grande bloco de JSON
como saída.

Captura de tela 2025-01-07 112230.jpg
 (Moderado)
8. Execute novamente o comando para visualizar apenas os nomes dos bancos
de dados. Desta vez, utilize a ferramenta jq, um analisador JSON de linha de
comando, para extrair somente os campos de nome. Direcione a saída dos
comandos az para o jq usando o seguinte comando:

 

az sql db list | jq '[.[] | {name: .name}]'

 

O resultado do comando apresentará atributos "name". Você observará que irá
aparecer dois atributos “name”. Um refere-se ao banco de dados criado nas
atividades anteriores, denominado "fullstack", para este roteiro. No entanto, é
importante observar que o banco de dados do sistema "master" também será
listado, pois inclui os metadados do servidor, como configurações de entrada e
do sistema.

Captura de tela 2025-01-07 112405.jpg
 (Moderado)branco.jpg
9. Execute o comando az sql db show abaixo para obter detalhes específicos
sobre o banco de dados. Substitua [nome-do-banco] pelo nome que você obteve
no comando anterior.

az sql db show --name fullstack

O resultado será uma extensa saída JSON. Para extrair informações relevantes,
utilize a ferramenta jq novamente.

Captura de tela 2025-01-07 112546.jpg
 (Moderado)
10. Execute o comando novamente. Desta vez, redirecione a saída para o jq,
filtrando apenas o nome, tamanho máximo e status do banco de dados
previamente criado. Isso permitirá uma visualização específica, confirmando que
o banco de dados está online e revelando o volume máximo de armazenamento
disponível.

 

az sql db show --name fullstack | jq '{name: .name,
maxSizeBytes: .maxSizeBytes, status: .status}'

Captura de tela 2025-01-07 112648.jpg
 (Moderado)
11. Agora que você possui um entendimento inicial do seu banco de dados, é o
momento de estabelecer uma conexão utilizando a ferramenta sqlcmd. Execute
o comando abaixo para obter a cadeia de conexão do banco de dados que está
sendo utilizado em um formato adequado para o sqlcmd:

 

az sql db show-connection-string --client sqlcmd --name fullstack

 

A saída se assemelha ao exemplo abaixo. Copie esse resultado para utilizar na
etapa seguinte.

 

"sqlcmd -S tcp:ubuntu-fullstack.database.windows.net,1433 -d fullstack -U
<username> -P <password> -N -l 30"

 

12. Execute o comando sqlcmd usando a saída gerada na etapa anterior para
iniciar uma sessão interativa. Certifique-se de remover as aspas e substituir
<username> e <password> pelos dados de usuário e senha que você definiu ao
criar o banco de dados. Após a execução do comando será exibido um prompt
para que sejam executados as instruções T-SQL para criação de tabelas,
inserção e deleção de registros, entre outros. Abaixo está um exemplo de string
de conexão:

 

sqlcmd -S tcp:ubuntu-fullstack.database.windows.net,1433 -d fullstack -U
fullstack -P 'Teste@123' -N -l 30

 

Importante: Coloque sua senha entre aspas simples ' para que “&” e outros
caracteres especiais não sejam interpretados como instruções de
processamento.

 

IMPORTANTE: poderá aparecer uma mensagem de erro semelhante ao exemplo
a seguir:

 

Sqlcmd: Error: Microsoft ODBC Driver 17 for SQL Server:

Cannot open server 'contoso' requested by the login.

Client with IP address 'nnn.nnn.nnn.nnn' is not allowed to access the server.

To enable access, use the Windows Azure Management Portal or run
sp_set_firewall_rule

on the master database to create a firewall rule for this IP address or address
range.

It may take up to five minutes for this change to take effect.

 

Se ocorrer esse erro, será necessário adicionar uma nova regra de firewall ao
cliente. Para fazer isso, siga as etapas abaixo:

Na página inicial do Azure, vá para "Serviços do Azure" e selecione "Todos os
recursos". Isso abrirá o painel de todos os recursos.
Localize o seu banco de dados e selecione-o. Isso abrirá o painel do banco de
dados SQL que você criou, neste roteiro, o banco chamado fullstack.
No menu superior, escolha "Definir o firewall do servidor". Isso abrirá o painel
de Rede.
Na seção "Regras de firewall", escolha "Adicionar uma regra de firewall". Isso
abrirá o painel para adicionar uma nova regra de firewall.
Insira um "Nome de regra" exclusivo e, em seguida, insira o endereço IP da
mensagem de erro nos campos "IP inicial" e "IP final".
Caso o acesso ao banco seja realizado através de endereços IP alocados para
qualquer serviço ou ativo do Azure, marcar o campo “Exceções: Permitir que
serviços e recursos do Azure acessem este servidor”
Clique em "OK".
Clique em "Salvar".
Execute novamente o comando.
 

- Resultados esperados

O resultado esperado dessa atividade é que através dos comandos az seja
possível obter informações cruciais sobre o banco de dados, incluindo seu
tamanho máximo, status e a string de conexão necessária para testar a conexão.
Por fim, realizar uma conexão bem-sucedida ao Banco de Dados Azure SQL

Microatividade 5: CRUD em um Banco de
Dados SQL do Azure

- Material necessário para a prática

Conta na Azure.
Navegador Web: Google Chrome, Firefox, MS Edge, Safari ou Opera.
- Procedimentos

Neste roteiro de prática, exploraremos passos essenciais para a criação,
conexão e manipulação de um banco de dados SQL no ambiente Azure.
Utilizando instruções T-SQL, abordaremos desde a criação de tabelas até
operações CRUD (Create, Read, Update, Delete).

 

A atividade inclui a criação de uma tabela denominada "Drivers" com atributos
específicos. Posteriormente, verificaremos a existência da tabela, inseriremos
dados de exemplo, realizaremos consultas para leitura, efetuaremos
atualizações e exclusões, concluindo com a verificação da tabela vazia.

 

1. Acesse o portal do Azure utilizando seu navegador.

2. Na página inicial acesse o Azure Cloud Shell para executar os comandos para
manipulação do banco de dados SQL.

3. Realize a conexão com o banco de dados conforme a atividade anterior.

4. Operação de criação de tabela: Na sessão sqlcmd, execute as seguintes
instruções T-SQL para criar uma tabela chamada Drivers. A tabela é composta
por quatro colunas: um identificador exclusivo, sobrenome, nome do motorista e
cidade de origem do motorista.

 

CREATE TABLE Drivers (DriverID int, LastName varchar(255), FirstName
varchar(255), OriginCity varchar(255));

GO

5. Verificação da Existência da Tabela Drivers: 2. Execute as seguintes
instruções T-SQL para verificar se a tabela Drivers existe. Você deverá obter
uma saída conforme a imagem a seguir.

 

SELECT name FROM sys.tables;

GO

branco.jpgCaptura de tela 2025-01-07 141244.jpg
 

6. Operação de inserção: Para testar a operação de criação de registros no
banco de dados, execute as instruções T-SQL a seguir para adicionar uma linha
de exemplo à tabela.

 

INSERT INTO Drivers (DriverID, LastName, FirstName, OriginCity) VALUES (754,
'Silva', 'João', 'Rio de Janeiro');

GO

Captura de tela 2025-01-07 141406.jpg
 (Moderado)
7. Operação de Leitura: Para realizarmos uma operação de leitura, execute as
seguintes instruções T-SQL para listar as colunas DriverID e OriginCity de todas
as linhas na tabela. Será exibido um resultado com DriverID e OriginCity para a
linha que você criou na etapa anterior, conforme a imagem a seguir.

 

SELECT DriverID, OriginCity FROM Drivers;

GO

Captura de tela 2025-01-07 141512.jpg
 (Moderado)
 

8. Operação de Atualização: Para testar a operação de atualização, execute as
instruções T-SQL a seguir para alterar a cidade de origem de "Rio de Janeiro"
para "São Paulo" do motorista com uma DriverID igual a 754.

 

UPDATE Drivers SET OriginCity='São Paulo' WHERE DriverID=754;

GO

 

Após a execução da operação de atualização, refaça a operação de leitura para
confirmar a atualização dos registros. O resultado esperado está apresentado na
figura a seguir.

Captura de tela 2025-01-07 141624.jpg
 (Moderado)
 

9. Operação de exclusão: para realizar a exclusão de um registro na tabela
execute as instruções T-SQL a seguir.

 

DELETE FROM Drivers WHERE DriverID=745;

GO

 

Após a execução da operação de exclusão, execute as intruções T-SQL a seguir
para verificar se a tabela Drivers está vazia. O resultado esperado está
apresentado na figura a seguir, que apresenta a tabela sem nenhuma linha/
registro.

 

SELECT COUNT(*) FROM Drivers;

GO

Captura de tela 2025-01-07 141731.jpg
 (Moderado)
- Resultados esperados

 O resultado esperado dessa microatividade é a execução dos procedimentos
deve criar, ler, atualizar e excluir registros na tabela Drivers, demonstrando o
funcionamento das operações CRUD no Banco de Dados SQL do Azure. Você
terá uma compreensão prática de como interagir com o banco de dados usando
o Cloud Shell e terá praticado comandos da CLI do Azure, fortalecendo suas
habilidades em T-SQL

Missão Prática | Tirando proveito da nuvem
para projetos de software  💻

Nessa atividade revisaremos tudo o que utilizamos nas microatividades
anteriores. Revisaremos todos os componentes e técnicas implementados no
desenvolvimento do banco de dados SQL Azure para a LogiMove Transportes.
Isto inclui a configuração do ambiente Azure, a criação e o gerenciamento das
tabelas, e a inserção e consulta de dados.

Contextualização

A LogiMove Transportes, uma empresa renomada no setor de logística de
transporte, enfrenta desafios significativos em sua operação diária. A
coordenação entre agendadores, despachantes, motoristas e clientes é crucial,
mas o processo atual, baseado em formulários de papel e comunicações
telefônicas, tem se mostrado ineficiente.

Problemas Identificados:

 

Excesso de papelada, muitas vezes incompleta ou sem assinaturas.
Dificuldade na disponibilidade dos distribuidores, resultando em atrasos.
Motoristas frequentemente parados, esperando por coordenação.
Atraso nas remessas, afetando negativamente a satisfação do cliente e os
negócios recorrentes.
 

Solução Proposta:

Para resolver esses desafios, a empresa decide migrar para um sistema digital,
substituindo formulários de papel e chamadas telefônicas por documentos
digitais e comunicação online. A implementação de autenticação digital permitirá
uma coordenação e acompanhamento eficazes das remessas, acessíveis via
navegador web ou aplicativo móvel.

 

Projeto de Banco de Dados:

Como líder de desenvolvimento de software, você propõe o desenvolvimento de
um protótipo que inclui a criação de um banco de dados no Azure SQL. Este
banco de dados será projetado para armazenar informações cruciais, incluindo:

 

Dados dos motoristas: informações pessoais, qualificações, histórico de
viagens.
Informações dos clientes: detalhes de contato, histórico de pedidos,
preferências.
Detalhes dos pedidos: informações do pedido, status, cronograma de entrega.
O protótipo servirá como base para o aplicativo de produção futuro. Portanto,
as escolhas tecnológicas feitas agora devem ser escaláveis e compatíveis com
as soluções finais.
 

Objetivos do Projeto:

Desenvolver um banco de dados robusto e seguro no Azure SQL.
Garantir que o banco de dados possa escalar conforme a empresa cresce.
Facilitar a integração com outras plataformas e serviços.
O projeto visa transformar radicalmente a maneira como a LogiMove
Transportes opera, aumentando a eficiência, reduzindo atrasos e melhorando a
satisfação do cliente. A adoção de uma solução baseada em Azure SQL é um
passo significativo em direção à digitalização e modernização das operações da
empresa.

Roteiro de prática 📝

- Material necessário para a prática

Conta na Azure.
Navegador Web: Google Chrome, Firefox, MS Edge, Safari ou Opera.
 

- Procedimentos

 

Esta atividade tem por objetivo desenvolver um banco de dados no Azure SQL
para a LogiMove Transportes, uma empresa de logística. O objetivo é migrar de
um sistema baseado em papel para uma solução digital, utilizando autenticação
digital para melhor coordenação e rastreamento de remessas. O banco de dados
armazenará informações sobre motoristas, clientes e pedidos.

1. Configuração do Ambiente Azure:

Criar uma conta no Azure.
Configurar uma instância do Azure SQL Database.
Estabelecer os parâmetros de segurança, como firewalls e regras de acesso.
2. Design do Banco de Dados:

Definir a arquitetura do banco de dados considerando as necessidades da
empresa.
Criar um diagrama de entidade-relacionamento (ER) para visualizar as
relações entre as tabelas.
3. Implementação do Banco de Dados:

Utilizar T-SQL para criar tabelas, definir chaves primárias, chaves estrangeiras
e índices.
 

Sugestão de Estrutura das Tabelas

1. Tabela de Motoristas (Drivers):

DriverID (Chave Primária)
Nome
CNH
Endereço
Contato
2. Tabela de Clientes (Clients):

ClientID (Chave Primária)
Nome
Empresa
Endereço
Contato
3. Tabela de Pedidos (Orders):

OrderID (Chave Primária)
ClientID (Chave Estrangeira)
DriverID (Chave Estrangeira)
Detalhes do Pedido
Data de Entrega
Status
 

Comandos T-SQL

Criação de Tabelas:
 

CREATE TABLE Drivers (

    DriverID INT PRIMARY KEY,

    Nome VARCHAR(100),

    CNH VARCHAR(20),

    Endereço VARCHAR(200),

    Contato VARCHAR(50)

);

 

CREATE TABLE Clients (

    ClientID INT PRIMARY KEY,

    Nome VARCHAR(100),

    Empresa VARCHAR(100),

    Endereço VARCHAR(200),

    Contato VARCHAR(50)

);

 

CREATE TABLE Orders (

    OrderID INT PRIMARY KEY,

    ClientID INT,

    DriverID INT,

    DetalhesPedido TEXT,

    DataEntrega DATE,

    Status VARCHAR(50),

    FOREIGN KEY (ClientID) REFERENCES Clients(ClientID),

    FOREIGN KEY (DriverID) REFERENCES Drivers(DriverID)

);

- Resultados esperados  ✨

Ao concluir a atividade espera-se que o aluno provisione um banco de dados
para a LogiMove Transportes e que esteja funcional e otimizado para operações
diárias e preparado para escalabilidade futura. Para isso as seguintes etapas
deverão ser concluídas e apresentadas:

 

1. Configuração e Acesso ao Banco de Dados:

Banco de dados configurado corretamente no Azure SQL.
Acesso ao banco de dados estabelecido sem problemas, garantindo
conectividade e segurança.
2. Criação e Estruturação das Tabelas:

Tabelas criadas no banco de dados de acordo com a estrutura sugerida,
incluindo tabelas para Motoristas, Clientes e Pedidos.
3. Inserção e Gestão de Dados:

Dados de teste inseridos nas tabelas, cobrindo diferentes cenários e casos de
uso.
4. Execução e Validação de Consultas:

Consultas T-SQL executadas com sucesso, com capacidade de recuperar,
filtrar e ordenar dados conforme necessário.
5. Operações CRUD Eficientes:

Demonstração de operações CRUD - Criar, Ler, Atualizar e Deletar dados.
Testes para assegurar que as operações CRUD estão funcionando conforme
esperado, com respostas rápidas e precisas.







