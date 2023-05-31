---
layout: editorial
---

# Cálculo de retroativos

| ID   | Título      | Issue                                                      | Tipo                                   | Criado     | Modificado |
| ---- | ----------- | ---------------------------------------------------------- | -------------------------------------- | ---------- | ---------- |
| 0003 | Retroativos | [#3](https://github.com/assoft-portugal/wg-rh-pt/issues/3) | Autoridade Tributária e Aduaneira (AT) | 2023-04-05 | 2023-04-18 |

**Palavras chave**: `novas tabelas de retenção na fonte` `rendimentos` `cálculo de irs` `remunerações` `2023`

## Introdução

Esta página fornece informações sobre o cálculo de retroativos no contexto do IRS. O cálculo de retroativos é necessário quando há pagamentos de rendimentos referentes a um período anterior ao mês em que são efetuados. Nesses casos, a aplicação correta das tabelas de retenção na fonte é fundamental para garantir a precisão do cálculo do imposto.

## Questão

* Como deveremos tratar o cálculo de retroativos do próprio Ano visto que temos uma fórmula de cálculo diferente por semestre?
* Por exemplo, se em julho forem pagas remunerações referentes a junho, qual tabela de retenção na fonte deve ser aplicada aos rendimentos de junho?

## Enquadramento jurídico

O enquadramento jurídico para o tratamento de rendimentos retroativos do próprio ano é fornecido pelo artigo 99º.E do Código do IRS. Esse artigo estabelece o mecanismo de retenção nos rendimentos das categorias A e H e contém informações relevantes para o cálculo de retroativos.

> Artigo 99.º-E
>
> **Mecanismo de retenção nos rendimentos das categorias A e H**
>
> 1. A importância apurada mediante aplicação das taxas de retenção é arredondada para a unidade de euros inferior.
> 2. Quando **forem pagos ou colocados** à disposição do respetivo titular **rendimentos das categorias A ou H em mês, do mesmo ano, diferente daquele a que respeitam**, recalcula-se o imposto e retém-se apenas a diferença entre a importância assim determinada e aquela que, com referência ao mesmo período, tenha eventualmente sido retida.

De acordo com esse artigo, parece-nos que é necessário aplicar a fórmula que se aplicava no período ao qual os rendimentos retroativos se referem, em vez de utilizar as tabelas do momento de colocação à disposição dos montantes, como mencionado na regra geral do artigo 99ºC, que contempla a regra geral de retenção na fonte.

> Artigo 99.º-C
>
> **Aplicação da retenção na fonte à categoria A**
>
> 1. Sem prejuízo do disposto na alínea a) do n.º 1 e no n.º 8 do artigo 99.º, **a retenção de IRS é efetuada sobre as remunerações mensalmente pagas ou postas à disposição dos seus titulares, mediante a aplicação das taxas que lhes correspondam, constantes da respetiva tabela.**

## Solução

A solução para o cálculo de retroativos é considerar que o IRS é ajustado mês a mês, conforme estabelecido no artigo 99.º E, alínea 2, do CIRS. Essa abordagem implica o recalculo do imposto e reter apenas a diferença entre a importância assim determinada e aquela que, com referência ao mesmo período, tenha sido eventualmente retida.

## Exemplo

Para ajudar a compreender o cálculo de retroativos, vamos apresentar um exemplo prático.

Suponha que temos os seguintes rendimentos e taxas de retenção na fonte para os meses de janeiro a julho:

<table data-header-hidden data-full-width="false"><thead><tr><th width="145"></th><th align="right"></th><th align="right"></th><th align="right"></th><th width="109" align="right"></th><th width="89" align="right"></th><th width="88" align="right"></th><th width="85" align="right"></th><th width="91" align="right"></th><th align="right"></th></tr></thead><tbody><tr><td></td><td align="right"></td><td align="right"></td><td align="right"><strong>Janeiro</strong></td><td align="right"><strong>Fevereiro</strong></td><td align="right"><strong>Março</strong></td><td align="right"><strong>Abril</strong></td><td align="right"><strong>Maio</strong></td><td align="right"><strong>Junho</strong></td><td align="right"><strong>Julho</strong></td></tr><tr><td>Rendimento</td><td align="right">1000.00</td><td align="right">1100.00</td><td align="right">100.00</td><td align="right">100.00</td><td align="right">100.00</td><td align="right">100.00</td><td align="right">100.00</td><td align="right">100.00</td><td align="right">1100.00</td></tr><tr><td>Taxa</td><td align="right">11.20%</td><td align="right">12.00%</td><td align="right"></td><td align="right"></td><td align="right"></td><td align="right"></td><td align="right"></td><td align="right"></td><td align="right"></td></tr><tr><td>Imposto</td><td align="right">112.00</td><td align="right">132.00</td><td align="right">20.00</td><td align="right">20.00</td><td align="right">20.00</td><td align="right">20.00</td><td align="right">20.00</td><td align="right">20.00</td><td align="right">122.00</td></tr></tbody></table>

A partir desses dados, podemos calcular o imposto retido em cada mês. Suponhamos que em julho ocorra o pagamento de retroativos referentes ao mês de junho, no valor de 600.00.

**Recibo de Julho**:

Vencimento base ....... 1100.00\
Retroativos .................. 600.00\
IRS ................................ 242.00
