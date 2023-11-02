# Extrato OFX sem movimentação
Extrato bancário OFX sem movimentação

Se você usa serviços como o [Contabilizei](https://www.contabilizei.com.br/programa-de-indicacao?ref=04209d200efd28c9cddb485e4bbfe3e1&nome=Marcio&email=financeiro@toledointeractive.com&utm_source=plataforma&utm_campaign=MGM&utm_source=plataforma), precisa importar extratos bancários mesmo que não tenha movimentação.
E caso seu banco não exporte OFX você vai precisar disso.

Basta alterar os dados:
- Banco: `ORG`
- Código do Banco: `FID`, `BANKID`
- Agencia: `BRANCHID`
- Conta: `ACCTID`
- Data do Extrato: `DTSERVER`, `DTASOF`
- Data de Inicial: `DTSTART`
- Data do Final: `DTEND`
