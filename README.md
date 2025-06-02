# Contract Processor

Pequeno sistema em Java para processamento de contratos, com geração automática de parcelas e aplicação de juros e taxas simulando um serviço de pagamento online (Paypal).

## 📌 Objetivo

Dado um contrato (número, data e valor total) e um número de meses, o sistema gera parcelas mensais com base em:

- Juros simples de **1% ao mês**
- Taxa de pagamento de **2% por parcela**

## 💻 Estrutura do Projeto

- `application`: classe principal que roda o programa (`Program.java`)
- `entities`: classes do domínio, como `Contract` e `Installment`
- `services`: lógica de processamento e serviço de pagamento (`PaypalService`)

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/andre3tcss/contract-processor.git
