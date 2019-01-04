# Plano de gerência de configuração

### Introdução
Esse documento tem como finalidade apresentar as políticas do projeto para controle de gerência de configuração e mudança.

### Planejamento do gerenciamento de configuração do software
#### Ferramentas
O projeto irá utilizar as seguintes ferramentas, que compõe o ambiente de desenvolvimento, e suas versões:

Ferramenta | Versão | Descrição
---------- | ------ | ---------
Python | 3.7.2 | Linguagem de programação utilizada no projeto
Django | 2.1.4 | Framework para desenvolvimento de aplicações
PostgreSQL | 11.1 | Banco de dados relacional
Git | 2.10.1 | Sistema de versionamento de código
GitHub | - | Repositório de código fonte
Travis | - | Ferramenta de integração contínua

Os testes e a cobertura de código podem ser verificados a cada commit submetido para o repositório no GitHub, assim, há uma garantia para o projeto dos efeitos de alterações no código.

### Controle de configuração do software
#### Níveis de controle de configuração
Nível | Descrição
----- | ---------
Controlada | A mudança somente será feita após a aprovação do(a) time/equipe
Monitorada | A mudança somente será feita a partir de uma política estabelecida para a configuração
Comunicada | A mudança pode ser feita por qualquer membro do(a) time/equipe mediante a comunicação para os outros integrantes

#### Definição de nível para as configurações
Configuração | Nível
------------ | -----
Ambientes de desenvolvimento e produção | Controlada
Codificação | Monitorada
Documentação do projeto | Comunicada

### Política de nomenclaturas
O projeto irá seguir os padrões de nomenclatura organizados da seguinte forma:

#### Tabela geral
Ordem | Código | Descrição
----- | ------ | ---------
1 | CSS | Empresa - Codelab Software Studio
2 | CC | Projeto - Compra Certa
3 | Tabela complementar | Hardware, software, documentação
4 | - | Numeração

#### Tabela complementar
Código | Descrição
------ | ---------
RT | Roteador
SW | Switch
SR | Servidor
VM | Máquina Virtual
CT | Container
DC | Documentação

#### Exemplos
`CSS-CC-SR01` (Codelab Software Studio, Compra Certa, Servidor 01)  
`CSS-CC-CT05` (Codelab Software Studio, Compra Certa, Container 05)
