#  **Requisitos Funcionais -  Funcionalidades do Sistema**


## **Autenticação de Usuário**

-   O sistema deve permitir que o usuário realize login com nome de usuário e senha válidos
    
-   O sistema deve exibir mensagens de erro em caso de login inválido

##  **Dashboard Inicial**
Depois do login, o sistema deve exibir o painel com atalhos e widgets

- Funcionalidades que são esperadas dessa parte :
	- Exibir widgets de : Avisos , Fluxo de Trabalho ,Empregados
	- Navegação pelos menus laterais
	- Acesso às áreas : Admin, PIM , Leave, Time, Recruitmente, etc...


##  **Gestão de Funcionários (Módulo PIM)**
O sistema deve permitir o gerenciamento dos colaboradores

- Funcionalidades que são esperadas dessa parte :
	- Lista completa com todos os funcionários cadastrados 
	- Botão "Add" para adicionar um novo funcionário
	- Opção de editar ou excluir um funcionário existente
	- Buscar funcionário por nome, ID, cargo, status


##  **Gerenciamento de Férias (Leave)**
O sistema deve permitir que o administrador possa visualizar e gerenciar requisições de licença

- Funcionalidades que são esperadas dessa parte :
	- Aprovação ou rejeição de solicitações 
	- Visualização do saldo de férias de determinado funcionário
	- Filtro de solicitação por data, status, nome do colaborador 


##  **Recrutamento (Recruitment)**
O sistema deve permitir a gestão de candidatos e vagas abertas

- Funcionalidades que são esperadas dessa parte :
	- Visualização da lista de vagas e candidatos
	- Adicionar novos candidatos
	- Filtro de candidatos por nome , cargo e status


## **Administração (Admin)**
Gerencia usuários, pápeis e permissões

- Funcionalidades que são esperadas dessa parte :
	- Adicionar diferentes usuários com diferentes níveis de acesso ao sistema
	- Editar e deletar usuários 
	- Aplicar filtros por tipo de usuários, status e nome 


## **Controle de Ponto (Time)**
Gerencia registros de entrada/saída dos funcionários

- Funcionalidades que são esperadas dessa parte :
	- Visualização dos horários registrados por funcionários
	- Filtros por nome, data, status
	- Geração de relatórios


## **Relatórios**
O sistema deve permitir a geração de relatórios de outras funcionalidades

- Funcionalidades que são esperadas dessa parte :
	- Selecionar tipo de relatório 
	- Definir filtros personalizados 
	- Gerar e visualizar relatórios


## **Diretório**
Lista de colaboradores da empresa

- Funcionalidades que são esperadas dessa parte :
	- Filtro por nome,cargo, e localização
	- Exibir informações de cada funcionário


## **Manutenção**
O sistema deve ser capaz de controlar senhas e logs

- Funcionalidades que são esperadas dessa parte :
	-  Acesso restrito a administradores, mediante reautenticação.
    -  Funcionalidade de busca de eventos por data, usuário ou tipo de ação


## **Qualificações (My Info -> Qualifications)**
O sistema deve ser capaz de visualizar e editar qualificações dos funcionários

- Funcionalidades que são esperadas dessa parte :
	- Adição de cursos e certificações 
	- Upload de documentos importantes 
