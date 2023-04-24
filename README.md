# SiteAgendamentosOnline

## Épicas: Login do Site de Agendamentos de consultas

### User Stories: criar um tela com para login do usuário

Como um usuario do Site de Consultas

Quero Acessar a minha conta

Para agendar minha consulta

Tarefas tecnicas:
* Inputs da do email e senha e botao de login
    * Criterios de aceitação:
        * o usuario deve fornecer as informações
        * o sistema deve autenticar o usuario
        * Abrir a tela inicial
    * Tarefa Tecnica:
        * Utilizar Query no banco de dados para buscar o usuario e senha - 5 pontos
        * verificar o hash da senha - 3 ponts
        * criacao da tela de login - 8 pontos


### RICE
    | funcionalidade | R | I | C | E | Prioridade |
    | Query banco de dados | 50 | 2 | 80% | 5 | 16 |
    | hash senha | 50 | 2 | 70% | 3 | 33,3 |
    | Criacao da tela | 50 | 3 | 100% | 8 | 19 |