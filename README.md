# Separação de tarefas para evitar o Burnout no ambiente corporativo.

## 1. Visão Geral

### 1.1 Descrição do Projeto
O projeto tem o objetivo de organizar o pessoal e o corporativo do usuário, trazendo mais leveza ao ambiente de trabalho, impedindo um Burnout. Com foco em hábitos saúdaveis, onde o usuário visualizará como metas a serem concluídas. É uma aplicação Web na qual será feito uma separação de tarefas para o usuário criar, administrar seus hábitos e também visualizar sua evolução no processo.

### 1.2 Escopo do Projeto
O projeto inclui o desenvolvimento de uma aplicação web que permita a criação, edição e acompanhamento do progresso dos hábitos escolhidos pelo usuário. O sistema deve ser acessível via navegador web e deve permitir a autenticação de usuários.

## 2. Requisitos Funcionais

### 2.1 Requisito Funcional 1
- **Descrição**: O sistema deve permitir que os usuários se registrem e façam login.
- **Critérios de Aceitação**: 
  - O usuário deve ser capaz de criar uma conta com um e-mail e senha.
  - O sistema deve autenticar o usuário com base nas credenciais fornecidas.
- **Prioridade**: Alta

### 2.2 Requisito Funcional 2
- **Descrição**: O sistema deve permitir a criação, edição e exclusão de tarefas.
- **Critérios de Aceitação**:
  - O usuário deve ser capaz de adicionar uma nova tarefa com título e descrição.
  - O usuário deve poder editar os detalhes de uma tarefa existente.
  - O usuário deve poder excluir uma tarefa.
- **Prioridade**: Alta

### 2.3 Requisito Funcional 3
- **Descrição**: O sistema deve permitir que os usuários visualizem suas tarefas em uma lista.
- **Critérios de Aceitação**:
  - O usuário deve poder ver uma lista de todas as tarefas em uma página.
  - A lista deve mostrar título e descrição.
- **Prioridade**: Média

## 3. Requisitos Não Funcionais

### 3.1 Requisito Não Funcional 1
- **Descrição**: A aplicação deve ter um tempo de resposta de menos de 5 segundos para carregar páginas.
- **Critérios de Aceitação**: 
  - A página principal deve carregar em menos de 5 segundos em uma conexão de internet padrão.
- **Prioridade**: Alta

### 3.2 Requisito Não Funcional 2
- **Descrição**: O sistema deve ser seguro e proteger as informações dos usuários.
- **Critérios de Aceitação**:
  - As senhas devem ser armazenadas de forma criptografada.
  - O sistema deve estar protegido contra ataques comuns.
- **Prioridade**: Alta

### 3.3 Requisito Não Funcional 3
- **Descrição**: A aplicação deve ser acessível via navegadores modernos (Chrome, Firefox, Edge).
- **Critérios de Aceitação**:
  - O sistema deve ser testado em navegadores e garantir uma boa experiência de usuário.
- **Prioridade**: Média

## 4. Restrições

### 4.1 Restrições Técnicas
- O sistema deve ser desenvolvido usando tecnologias web como HTML, CSS, JavaScript e um framework de backend.
- Não será utilizado armazenamento de dados local; todos os dados serão armazenados em um banco de dados remoto.

### 4.2 Restrições de Tempo
- A primeira versão funcional do sistema deve ser entregue em 3 meses a partir do início do desenvolvimento.

## 5. Dependências

### 5.1 Dependência 1
- **Dependência**: O projeto depende da integração com um serviço de envio de e-mails para confirmação de registro.
- **Impacto**: Se o serviço de e-mails falhar, os usuários não receberão e-mails de confirmação.

### 5.2 Dependência 2
- **Dependência**: O projeto depende da disponibilidade de um servidor de banco de dados remoto.
- **Impacto**: Se o servidor de banco de dados estiver fora do ar, a aplicação não poderá salvar ou recuperar dados.

## 6. Glossário

### 6.1 Tarefa
- **Definição**: Uma unidade de trabalho que um usuário precisa realizar, incluindo um título e descrição.

### 6.2 Autenticação
- **Definição**: O processo de verificar a identidade de um usuário para garantir que apenas usuários autorizados acessem o sistema.

## 7. Referências

### 7.1 Estudo do tema
- [Orientação sobre Saúde mental](https://www.unimed.coop.br/viver-bem/saude-em-pauta/)

### 7.2 Reforço do tema
- [Reforço sobre o tema](http://gov.br/ebserh/pt-br/comunicacao/noticias/a-importancia-do-cuidado-com-a-saude-mental-no-)

### 7.3 Documento de Requisitos
- [Documentação de requisitos](https://afonsolelis.github.io/backend/1_analise_requisitos_viabilidade/)

