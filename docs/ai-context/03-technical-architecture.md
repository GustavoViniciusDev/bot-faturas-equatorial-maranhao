# Arquitetura Técnica

## Stack

- Node.js
- TypeScript
- whatsapp-web.js
- qrcode-terminal
- dotenv

## Estrutura

```txt
bot-faturas-whatsapp/
├── src/
├── downloads/
├── sessions/
├── logs/
├── .env.example
├── package.json
└── tsconfig.json
```

## Regras

- usar LocalAuth;
- salvar sessão persistente;
- logs claros;
- delays randômicos;
- timeout nas mensagens;
- parser resiliente;
- download automático de PDF.
