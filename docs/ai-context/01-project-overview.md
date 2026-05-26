# Projeto: Bot de Coleta de Faturas via WhatsApp

## Objetivo

Criar um MVP de um bot automatizado para WhatsApp que consiga conversar com o atendimento virtual da Equatorial Energia Maranhão e baixar automaticamente a segunda via de uma fatura de energia.

O objetivo inicial é validar a coleta de apenas 1 fatura, usando uma UC fixa e um mês/ano de referência fixo.

## Problema atual

Hoje o time de faturamento precisa acessar manualmente o WhatsApp da Equatorial, informar a Unidade Consumidora, navegar pelo menu, escolher a fatura correta, selecionar forma de pagamento e baixar o PDF.

Esse processo é repetitivo e pode ser automatizado.

## Escopo do MVP

O MVP deve:

- conectar em um número WhatsApp Business próprio;
- iniciar conversa com a Equatorial Energia Maranhão;
- solicitar segunda via de fatura;
- informar a UC;
- confirmar o imóvel encontrado;
- selecionar a referência correta;
- escolher pagamento por boleto;
- informar o e-mail cadastrado;
- receber o PDF;
- baixar o PDF;
- salvar o arquivo localmente.

## Fora do escopo do MVP

Não implementar ainda:

- painel administrativo;
- banco de dados;
- múltiplas UCs;
- filas;
- Redis;
- BullMQ;
- login de usuários;
- API HTTP;
- integração com ERP;
- IA conversacional complexa.

Este MVP deve ser simples, direto e funcional.
