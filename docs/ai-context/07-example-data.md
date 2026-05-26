# Dados de Exemplo

## .env.example

```env
EQUATORIAL_CHAT_NAME="Equatorial Energia Maranhão"
TARGET_UC="3024668214"
TARGET_REFERENCE="05/2026"
REGISTERED_EMAIL="faturas@alexandriaenergia.com"

DOWNLOAD_DIR="./downloads"
SESSION_DIR="./sessions"

MESSAGE_TIMEOUT_MS=90000
MIN_DELAY_MS=2000
MAX_DELAY_MS=5000
```

## Exemplo de parser

Entrada:

```txt
1 - Referência: 05/2026 - Valor: R$ 63,28
```

Saída:

```json
{
  "option": "1",
  "reference": "05/2026",
  "amount": "63,28"
}
```
