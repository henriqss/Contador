# ⏱️ Contadores

Site simples e responsivo para acompanhar períodos de tempo através de contadores regressivos.

Os contadores são carregados automaticamente a partir do arquivo `contadores.txt`.

## 🎨 Estados do contador

Cada contador possui três estados:

| Cor | Estado | Funcionamento |
|---|---|---|
| ⚪ Cinza | Ainda não começou | Conta regressivamente até o horário de início |
| 🩷 Rosa | Em andamento | Conta regressivamente até o horário de término |
| 🟢 Verde | Concluído | Conta quanto tempo já passou desde o término |

### Exemplo

```text
⚪  Antes do início
        ↓
🩷  Durante o período
        ↓
🟢  Depois do término
