# App Cupons

## Product Backlog

- [Estrutura Trello](https://trello.com/b/J9xP1KxS/app-cupons-tex-02)

- [Descritivo](https://docs.google.com/document/d/1ldnP34DRu6awOdTN4513y3yWEWiIRjlY38bhmCazgUU/edit)

# Visão Geral

Adalberto, CEO da empresa X, necessita implementar no seu aplicativo de marketplace a funcionalidade de cupons de descontos para que seus clientes possam obter descontos nos produtos adquiridos através das lojas parceiras.

# Desafio

* Criar um documento EPIC que descreva todos os itens de funcionalidade possíveis na visão do Product Owner.
* Criar um documento Product Backlog que descreva todos os ítens (funcionalidades) por ordem de relevância na visão do Product Owner.
* Criar um documento User Stories que descreva as estórias de cada item do Product Backlog
* Criar um documento Sprint Backlog que defina os itens relevantes, vindos do Product Backlog, a serem desenvolvidos numa primeira Sprint.

# Epic

- Eu como usuário quero obter cupons de descontos no aplicativo de forma prática para realizar compras de produtos diversos.
- Eu como usuário quero poder salvar os cupons para utilizar em uma futura compra e pagar mais barato.
- Eu como usuário quero poder gerenciar minha lista de cupons para saber as informações de uso, validade e desconto.
- Eu como usuário quero poder filtrar meus cupons por data, categoria, lojas, produtos.
- Eu como usuário quero poder compartilhar vouchers com outros usuários.

# Product Backlog

## Dashboard

- Cadastro Básico
- Campo de Pesquisa
- Painel perfil, histórico de cupons, vouchers, favoritos

## Pop-up

- Cadastro Básico

## Cupons

- Indicar Amigos (voucher)
- Notificação sobre a validade dos cupons
- Favoritar cupons
- Mês do aniversário ganha cupons
- Trocar moedas por cupons


# User Stories

| Dashboard                  |                                                                                                                                                                                                            |     |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| Story #1 - Cadastro Básico |
| Descritivo                 | Usuário visitante deverá se cadastrar para obter cupons de descontos, visualizar histórico, favoritos e indicações.                                                                                        |
| Justificativa              | Mediante cadastro o cliente terá benefícios e poderá acompanhar suas ações no aplicativo.                                                                                                                  |
| Solução                    | 1. Usuário preenche os campos requeridos pelo aplicativo (nome, e-mail, senha) Sistema irá validar os dados do formulário - Senha errada recuperar senha Sistema verifica se o usuário já está cadastrado. |

***


| Dashboard                    |                                                                                                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Story #2 - Campo de Pesquisa |                                                                                                                                   |
| Descritivo                   | Usuário visitante/cadastrado poderá filtrar os cupons através da barra de pesquisa por nome, categoria, lojas, produtos           |
| Justificativa                | No painel de usuário, assim como na home do aplicativo, o usuário poderá filtrar os cupons para obter cupons de lojas específicas |
| Solução                      | 1. Passo a passo da barra                                                                                                         |
|                              | 2. O campo de pesquisa é colocado na barra superior                                                                               |
|                              | 3. O campo contém um espaço reservado com um texto cinza: “ Digite o nome da loja ”. O espaço reservado desaparece quando o usuário começa a digitar.                                                                                                                                                  |
|                              | 4. A pesquisa não suporta símbolos especiais ( caracteres ). Se o usuário digitou um símbolo especial, mostre a mensagem de aviso: “ A entrada de pesquisa não pode conter símbolos especiais. ”                   |                                                                                                            

***


| Dashboard                       |                                                                                                     |
| ------------------------------- | ----------------------------------------------------------------------------------------------------|
| Story #3 - Painéis do Dashboard |                                                                                                     |
| Descritivo                      | Usuário cadastrado terá acesso a um painel administrativo.                                          |
| Justificativa                   | No painel o usuário poderá acessar os dados do seu perfil, histórico de cupons, cupons favoritos    |
| Solução                         | 1. Usuário preenche os campos requeridos pelo aplicativo (nome, e-mail, senha)                      |
|                                 | 2. O Sistema irá validar os dados do formulário, se positivo será redirecionado para o painel       |
|                                 |    administrativo. Caso contrário, o usuário deverá corrigir os dados inseridos e tentar novamente. |
|                                 | 3. Se o problema for a senha, o usuário podera recupera-la através do link 'recuperar senha' onde   |
|                                 |    deverá inserir o e-mail para receber a notificação e realizar a ação.                            |
|                                 | 4. Dentro do painel administrativo o usuário poderá acessar os menus perfil, histórico, favoritos   |

***


| Pop-up                     |                                                                                                                                              |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Story #1 - Cadastro Básico |                                                                                                                                              |
| Descritivo                 | O usuário visitante terá a opção de se cadastrar na newsletter para receber cupons por e-mail.                                               |
| Justificativa              | O usuário que se cadastrar na newsletter além de receber as últimas notícias, receberá 1 cupom de desconto por semana num total de 4 por mês |
| Solução                    | Passo a passo da pop-up                                                                                                                      |

***


| Cupons                              |                                                                                                                                             |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Story #1 - Indicar Amigos (Voucher) |                                                                                                                                             |
| Descritivo                          | O usuário cadastrado poderá compartilhar um voucher com amigos e a cada amigo que realizar uma compra o usuário recebera um cupom em troca. |
| Justificativa                       | Motivar o usuário por meio de um sistema onde o mesmo ganha uma porcentagem de desconto/voucher caso indique o app para outra pessoa                                                                                                                                            |
| Solução                             | Usuário envia um link ou compartilha o app para outra pessoa por meio de redes sociais e o sistema valida se a outra pessoa se cadastrou no app, se sim, o usuário que indicou ganha uma porcentagem de desconto/voucher                                                                                                                   |

***

# Sprint Backlog

## Projeto: Sistema de Cupons


### Dashboard

| Tarefa                 | Dev       | Status | Estimativa | Pontos |
| ---------------------- | ----------| ------ | ---------- | ------ |
| Formulário de Cadastro | Guilherme |        |            |        |
| Login Redes Sociais    |           |        |            |        |
| Painel Histórico       |           |        |            |        |
| Painel Favoritos       |           |        |            |        |

***
### Pop-up

| Tarefa                 | Dev | Status | Estimativa | Pontos |
| ---------------------- | --- | ------ | ---------- | ------ |
| Formulário de Cadastro |     |        |            |        |

***
### Feature #1 - Favoritos

| Tarefa               | Dev  | Status | Estimativa | Pontos |
| -------------------- | ---- | ------ | ---------- | ------ |
| Lojas Favoritas      | Kaue |        |            |        |
| Notificação Cupons   | Kaue |        |            |        |
| Notificação Validade | Kaue |        |            |        |

***
### Feature #2 - Campos de Pesquisa

| Tarefa                 | Dev        | Status | Estimativa | Pontos |
| ---------------------- | -----------| ------ | ---------- | ------ |
| Barra de Pesquisa      | Edvaldo    |        |            |        |
| Filtro Categoria       | Edvaldo    |        |            |        |
| Filtro Loja            | Edvaldo    |        |            |        |
| Filtro Produto         | Edvaldo    |        |            |        |

***
### Feature #3 - Voucher Indicação

| Tarefa                 | Dev | Status | Estimativa | Pontos |
| ---------------------- | --- | ------ | ---------- | ------ |
| Link Indicação         | Renato Sousa    |        |            |        |
| Link Personalizado     |     |        |            |        |
| Redes Sociais          |     |        |            |        |

