
# Exemplo GitHub Actions: Pipeline Básico

Este exemplo mostra um pipeline básico usando GitHub Actions.

### ✨ O que faz

- **Pipeline** (`pipeline-basico`):
  - É acionado manualmente pelo botão **Run workflow** no GitHub (usando `workflow_dispatch`).
  - Executa em uma máquina Ubuntu.
  - Roda um único comando: imprime no log a mensagem  
    ```
    Configuração inicial do pipeline
    ```

### 📂 Estrutura

```
.github/
└── workflows/
    └── pipeline-basico.yml
```

### 💡 Para que serve

👉 Use este modelo como base para:
- Testar configurações iniciais do seu pipeline.
- Criar pontos de partida para fluxos maiores.
- Executar workflows manualmente sem depender de push, PR ou cron.
