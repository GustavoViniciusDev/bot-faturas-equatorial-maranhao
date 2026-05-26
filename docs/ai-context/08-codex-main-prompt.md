# Prompt principal para o Codex

Leia todos os arquivos dentro de docs/ai-context antes de implementar.

## Objetivo

Criar um projeto Node.js com TypeScript usando whatsapp-web.js para automatizar a conversa com a Equatorial Energia Maranhão e baixar automaticamente uma fatura em PDF.

## Stack obrigatória

- Node.js
- TypeScript
- whatsapp-web.js
- qrcode-terminal
- dotenv

## Estrutura obrigatória

```txt
src/
├── index.ts
├── config.ts
├── logger.ts
├── utils/
├── whatsapp/
├── flow/
└── storage/
```

## Regras

- não usar banco;
- não usar painel;
- não usar API HTTP;
- não usar filas;
- foco em baixar uma única fatura;
- implementar máquina de estados;
- implementar parser de referências;
- implementar timeout;
- implementar logs;
- implementar delays randômicos.

## Resultado esperado

Rodar:

```bash
npm run dev
```

Escanear QR Code.

O bot deve:

- conversar com a Equatorial;
- escolher a referência correta;
- baixar o PDF;
- salvar em downloads/.

## Prompt final para execução

Leia todos os arquivos dentro de docs/ai-context antes de implementar.

Crie o MVP completo descrito nos documentos.

Não implemente funcionalidades fora do escopo do MVP.
