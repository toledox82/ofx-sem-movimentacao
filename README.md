# Extrato OFX sem movimentação
Extrato bancário OFX sem movimentação

Se você usa serviços como o contabilizei, precisa importar extratos bancários mesmo que não tenha movimentação.
E caso seu banco não exporte OFX você vai precisar disso.

Basta alterar os dados:
- Banco: `ORG`
- Código do Banco: `FID`, `BANKID`
- Agencia: `BRANCHID`
- Conta: `ACCTID`
- Data do Extrato: `DTSERVER`, `DTASOF`
- Data de Inicial: `DTSTART`
- Data do Final: `DTEND`
