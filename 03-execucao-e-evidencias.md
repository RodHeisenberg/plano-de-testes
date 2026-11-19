# Execução e evidências | Demonstração por leitura

Slides 17 a 19. Em uma execução real, uma ferramenta enviaria a requisição à API e exibiria a resposta. Na gravação, o professor representa esses dois momentos abrindo os cartões locais. Registre os resultados como **simulados**.

Antes de revelar uma resposta, mostre a entrada e faça uma pausa para quem estiver assistindo prever o que vai voltar. Aponte a primeira linha da resposta, que contém o código HTTP. Depois aponte o JSON, que contém os dados ou a mensagem.

## Slide 17 | CT001 – Cadastro válido

- Método e rota: `POST /api/usuarios`.
- Dados de entrada. Leia o bloco antes de abrir a resposta.

```json
{
  "nome": "Ana Silva",
  "email": "ana@email.com",
  "senha": "SenhaForte123@"
}
```

- Esperado: [preencher antes de abrir a resposta]
- Abra [ct001-resposta-201.txt](exemplos/ct001-resposta-201.txt).
- Obtido na simulação: [preencher após ler a resposta]
- Situação do caso: [preencher]

## Slide 18 | CT002 – E-mail inválido

- Método e rota: `POST /api/usuarios`.
- Dados de entrada. Peça que os alunos identifiquem o único campo alterado.

```json
{
  "nome": "Ana Silva",
  "email": "ana_sem_arroba.com",
  "senha": "SenhaForte123@"
}
```

- Esperado: [preencher antes de abrir a resposta]
- Abra [ct002-resposta-400.txt](exemplos/ct002-resposta-400.txt), na versão v1.1.
- Obtido na simulação: [preencher após ler a resposta]
- Situação do caso: [preencher]

## Slide 19 | Registro de evidência

- Caso e versão do cenário: [preencher]
- Método e rota: [preencher]
- Entrada relevante: [preencher]
- Código e corpo da resposta: [preencher]
- Arquivo que serve de evidência nesta simulação: [preencher]
- Conclusão: [preencher]

> Fala para preencher. Escrevi o esperado antes de abrir o cartão. Agora vou copiar o que a resposta mostra. Se ela traz o código e a mensagem que o caso previa, o teste passa. No caso do e-mail inválido, a rejeição é o comportamento esperado.
