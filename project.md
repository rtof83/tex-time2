# App Cupons

## Product Backlog

- [Estrutura Trello](https://trello.com/b/J9xP1KxS/app-cupons-tex-02)

- [Descritivo](https://docs.google.com/document/d/1ldnP34DRu6awOdTN4513y3yWEWiIRjlY38bhmCazgUU/edit)

- [Mapa de Empatia](https://drive.google.com/drive/folders/1EJPQFSgj7BTso8r5jv6O8IuPC2nihPWJ)

- [Figma](https://www.figma.com/team_invite/redeem/lDA3vcrSIdcS8eqz18Vxes)

- [Roteiro Apresentação (modelo)](https://github.com/rtof83/tex-time2/blob/main/files/Roteiro-Apresentacao.pdf)

- [Apresentação](https://docs.google.com/presentation/d/1EPY5Xbut3-CbFTXr7oPY2WVc2SuIuk0rr0Kw8OuzB5I/edit#slide=id.p)

&nbsp;

---

&nbsp;

# Visão Geral

Adalberto, CEO da empresa X, necessita implementar no seu aplicativo a funcionalidade de cupons de descontos para que seus clientes possam obter descontos nos produtos adquiridos através das lojas parceiras.

&nbsp;

# Desafio

* Criar um documento EPIC que descreva todos os itens de funcionalidade possíveis na visão do Product Owner.
* Criar um documento Product Backlog que descreva todos os ítens (funcionalidades) por ordem de relevância na visão do Product Owner.
* Criar um documento User Stories que descreva as estórias de cada item do Product Backlog
* Criar um documento Sprint Backlog que defina os itens relevantes, vindos do Product Backlog, a serem desenvolvidos numa primeira Sprint.

&nbsp;

# Epic

- Eu como usuário quero obter cupons de descontos no aplicativo de forma prática para realizar compras de produtos diversos.
- Eu como usuário quero poder salvar os cupons para utilizar em uma futura compra e pagar mais barato.
- Eu como usuário quero poder gerenciar minha lista de cupons para saber as informações de uso, validade e desconto.
- Eu como usuário quero poder filtrar meus cupons por data, categoria, lojas, produtos.
- Eu como usuário quero poder compartilhar vouchers com outros usuários.

&nbsp;

# Product Backlog

## Dashboard

- Cadastro Básico
- Campo de Pesquisa
- Painel perfil, histórico de cupons, vouchers, favoritos

## Pop-up

- Cadastro Básico

## Cupons

- Indicar Amigos (voucher)
- Regra do voucher
- Notificação sobre a validade dos cupons
- Favoritar cupons
- Mês do aniversário ganha cupons
- Trocar moedas por cupons

&nbsp;

# User Stories

| Dashboard                    |                                                                                                                                   |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Story #1 - Cadastro Básico |
| Descritivo                 | Usuário visitante deverá se cadastrar para obter cupons de descontos, visualizar histórico, favoritos e indicações.                                                                                        |
| Justificativa              | Mediante cadastro o cliente terá benefícios e poderá acompanhar suas ações no aplicativo.                                                                                                                  |
| Solução                      | 1. Usuário preenche os campos requeridos pelo aplicativo (nome, e-mail, senha).                                                                                                         |
|                              | 2. Sistema irá validar os dados do formulário.                                                                               |
|                              | 3. Senha incorreta e recuperar senha.                                                                                                                                                  |
|                              | 4. Sistema verifica se o usuário já está cadastrado.                   |

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
| Story #3 - Painéis |                                                                                                     |
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
| Cupons                              |                                                                                                                                             |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Story #2 - Regra do voucher |                                                                                                                                             |
| Descritivo                          | O usuário pode trocar uma certa quantia de cupons de desconto para um voucher com valor cheio |
| Justificativa                       | Motivar o usuário para conseguir fazer compras que possuem um valor mais alto |
| Solução                             | O usuário salva os cupons que quer trocar em um sistema específico dentro do app, o sistema valida se os cupons salvos podem ser trocados, se sim, o usuário ganha um código para ser usado como voucher, se não, o sistema retorna com uma mensagem dizendo "os cupons selecionados não podem ser trocados por voucher" |

***
| Cupons                              |                                                                                                                                             |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Story #3 - Notificação sobre a validade dos cupons  |                                                                                                                                             |
| Descritivo                          | O usuário cadastrado receberá uma notificação sobre os cupons que estão com a data de vencimento próxima. |
| Justificativa                       | Informar o usuário por meio do sistema quais cupons estão com a data de validade próxima para que ele não perca os descontos oferecidos pelo cupom.                                                                                                                                            |
| Solução                             | Ao entrar na área destinada aos cupons, o usuário terá uma seção com os cupons com validade inferior a 15 dias.                                                                                                                   |

&nbsp;

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

| Tarefa                 | Dev           | Status | Estimativa | Pontos     |
| ---------------------- | ------------- | ------ | ---------- | ---------- |
| Link Indicação         | Renato Sousa  |        |            |            |
| Regra do voucher       | Renato Sousa  |        |            |            |
| Link Personalizado     | Renato Tadeu  |        |            |            |
| Redes Sociais          | Renato Tadeu  |        |            |            |
