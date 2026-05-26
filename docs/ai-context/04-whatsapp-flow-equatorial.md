# Fluxo Conversacional da Equatorial

## Menu inicial

A Equatorial normalmente apresenta:

1. Falta de Energia
2. Religação
3. Código de Barra para Pagamento
4. Consulta de Débitos
5. Cadastro de Tarifa Social
6. Segunda via de Fatura

O bot deve solicitar:

```txt
Segunda via Fatura
```

## Identificação

A Equatorial solicita CPF/CNPJ/Conta Contrato.

O bot deve enviar a UC:

```txt
3024668214
```

## Confirmação

A Equatorial pergunta se o imóvel está correto.

O bot responde:

```txt
Sim
```

## Lista de faturas

Exemplo:

```txt
1 - Referência: 05/2026 - Valor: R$ 63,28
2 - Referência: 04/2026 - Valor: R$ 71,10
```

O bot deve encontrar:

```txt
05/2026
```

e responder:

```txt
1
```

## Método de pagamento

Responder:

```txt
Pagar boleto
```

## E-mail

Enviar o e-mail configurado.

## PDF

Baixar e salvar automaticamente.
