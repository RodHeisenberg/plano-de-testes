# Relatório de incidente | BUG-042

- Título. Resuma o comportamento observado: POST /api/usuarios devolve 500 ao receber e-mail sem arroba.
- Caso de teste relacionado: CT002
- Ambiente e versão: homologação fictícia, v1.2.
- Pré-condições: API de cadastro disponível.
- Severidade. Qual é o impacto? Muito Severo
- Prioridade. Com que urgência o caso deve ser tratado? Urgente

## Passos para reproduzir

1. enviar o cadastro do CT002 com email = ana_sem_arroba.com.
2. Esperado: HTTP 400 e mensagem de formato de e-mail inválido.
3. Obtido: HTTP 500, erro interno no servidor.
4. Evidência: cartão da resposta 500.

## Comparação

- Esperado conforme o caso: [preencher]
- Obtido na simulação: [preencher]
- Evidência disponível: [preencher]
- Trecho de log simulado: [preencher]

