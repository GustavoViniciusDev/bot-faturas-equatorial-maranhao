# Fluxo de Negócio

## Entrada esperada

O sistema deve receber inicialmente via `.env` ou arquivo de configuração:

- UC da unidade consumidora;
- mês/ano de referência desejado;
- e-mail cadastrado na conta contrato;
- nome do contato da Equatorial no WhatsApp.

## Exemplo

```env
EQUATORIAL_CHAT_NAME="Equatorial Energia Maranhão"
TARGET_UC="3024668214"
TARGET_REFERENCE="05/2026"
REGISTERED_EMAIL="faturas@alexandriaenergia.com"
```

## Fluxo esperado

1. O bot conecta no WhatsApp Web.
2. O bot localiza o chat da Equatorial Energia Maranhão.
3. O bot envia uma mensagem inicial solicitando segunda via.
4. A Equatorial pede CPF/CNPJ ou Conta Contrato/UC.
5. O bot envia a UC.
6. A Equatorial retorna um imóvel encontrado.
7. O bot confirma com "Sim".
8. A Equatorial retorna uma lista de faturas disponíveis.
9. O bot identifica a opção correspondente ao mês/ano desejado.
10. O bot envia o número da opção correta.
11. O bot escolhe pagamento por boleto.
12. O bot informa o e-mail.
13. O bot recebe o PDF.
14. O bot salva o PDF.
