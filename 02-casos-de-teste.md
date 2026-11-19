# Casos de teste | Da regra ao passo a passo

## Molde

- ID e nome: 
- Regra que o caso verifica: 
- Pré-condições. O que precisa estar pronto? 
- Dados de entrada:
- Passos em ordem: POST /api/auth.
- Resultado esperado. O que deve voltar? 200 OK um token JWT 

## Leitura do caso de login

- ID e nome: CT01 - Validar Login
- Pré-condição: O usuário deve estar cadstrado
- Dados de entrada: e-mail e senha
- Método e rota: POST /api/auth.
- Resultado esperado: 200 OK um token JWT 

## Requisito do cadastro

A regra do slide exige nome, e-mail válido e senha forte. Preencha cada linha explicando por que se altera um campo por vez.

| ID | Cenário | Campo que muda | Código e resposta esperados |
|---|---|---|---|
| CT001 | Cadastro válido | Todos os dados foram validados | 201 Created e o identificador do usuário |
| CT002 | E-mail sem arroba | e-mail, retirando o @ | 400 B-R formato inválido |
| CT003 | Senha com três caracteres | Senha, usando apenas três caracteres | 400 senha inválida |


- Dados: use a entrada do slide 18.
- Passo 1: [preencher]
- Passo 2: [preencher]
- Resultado esperado: [preencher]
