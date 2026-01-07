# ⚡ Elo Programming Language

**Elo** é uma linguagem de programação focada em **produtividade máxima** e **experiência humana**. Ela foi desenhada para automatizar tarefas, lidar com APIs e arquivos de forma nativa, sem a verbosidade de linguagens tradicionais.

## ✨ Diferenciais
- **Sintaxe em Português:** Natural e direta.
- **Bateria Inclusa:** Funções de rede (HTTP) e sistema de arquivos integradas.
- **Feedback Amigável:** Erros que explicam o que aconteceu e como consertar.

## 🛠️ Comandos Principais
| Comando | Descrição |
| :--- | :--- |
| `seja` | Define uma variável ou constante. |
| `exibir` | Mostra informações no terminal com cores. |
| `buscar em` | Realiza uma requisição HTTP GET e já converte para JSON. |
| `gravar` | Salva o conteúdo de uma variável em um arquivo físico. |
| `esperar` | Pausa a execução por um tempo determinado. |

## 🚀 Exemplo Rápido
```elo
seja api = "[https://api.exemplo.com/dados](https://api.exemplo.com/dados)"
exibir "Conectando ao servidor..."
seja info = buscar em api
gravar info em "resultado.json"
exibir "Processo finalizado com sucesso!"
