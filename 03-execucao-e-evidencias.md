# Execução e evidências | Demonstração por leitura

CT001 – Cadastro válido

- Método e rota: `POST /api/usuarios`.
- Dados de entrada. Leia o bloco antes de abrir a resposta.

```json
{
  "nome": "Ana Silva",
  "email": "ana@email.com",
  "senha": "SenhaForte123@"
}
```


## CT002 – E-mail inválido

- Método e rota: `POST /api/usuarios`.
- Dados de entrada. Peça que os alunos identifiquem o único campo alterado.

```json
{
  "nome": "Ana Silva",
  "email": "ana_sem_arroba.com",
  "senha": "SenhaForte123@"
}
```


## Slide 19 | Registro de evidência

- Caso e versão do cenário: CT002 - E-mail inválido
- Método e rota: POST /api/usuarios
- Entrada relevante: "nome": "Ana Silva",
  "email": "ana_sem_arroba.com",
  "senha": "SenhaForte123@"
- Arquivo que serve de evidência nesta simulação: https://github.com/RodHeisenberg/plano-de-testes/edit/main/03-execucao-e-evidencias.md
- Conclusão: O caso está ok! Atende aos requisitos.

