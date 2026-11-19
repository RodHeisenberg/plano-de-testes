# Plano de testes | Cadastro de usuários

## Identificação

- Projeto: cadastro de usuários
- Finalidade da rodada: Verificar o comportamento do Cadastro de usuários
- Ambiente de exemplo: API fictícia de cadastro, em um ambiente de teste simulado

## O que será testado

- Objetivo desta rodada: Verificar se o cadastro aceita dados válidos e rejeita dados fora da regra
- Operação no escopo: POST /api/usuarios, operação cadastro
- Cenários previstos: Cadastro válido, e-mail sem arroba, senha curta só com numeros
- Outras funcionalidades que ficam para outra rodada: Login e recuperação de senha

## Como a rodada será conduzida

- Recursos e dados necessários: Regras do cadastro, dados da API fictícia
- Quem prepara os casos: O Professor prepara os casos, demonstra a execução e registra os resultados 
- Quem executa e registra: O Professor
- Ordem do trabalho: Escrever os casos, demonstrar as funcionalidades, registrar o que foi observado.

## Condições e riscos

- Critério de entrada. O que precisa estar pronto para começar? Ter a Regra, dados, resultado esperado de cada teste.
- Critério de saída. O que precisa estar registrado para encerrar a rodada? Registra cada resultado de cada caso e indicar quais não funcionaram.
- Risco. O que pode bloquear a execução? A API pode estar indisponível 
- Contingência. O que a equipe faz se isso ocorrer? Conferir o endereço, se continuar registrar como bloqueado.

> Fala para preencher. Primeiro eu digo o que queremos verificar. Depois eu delimito o que entra nesta rodada. Quando outra pessoa abrir este documento, ela precisa entender como o trabalho foi combinado.
