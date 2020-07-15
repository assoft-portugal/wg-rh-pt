# noissue-Reporte de rendimentos negativos

## Questão

### Reporte de valores negativos anos anteriores 

Os valores negativos relativos a rendimentos pagos em anos anteriores devem ser declarados através da substituição da DMR e da declaração individual do  
empregado.

#### Exemplos de caso

* Todas as ausências do mês de dezembro dos colaboradores inclusive as posteriores à data de processamento de ordenados de dezembro \(processamento ordenados dezembro tem lugar por volta do dia 15 no máximo quer no sector público quer no sector privado\). 
* Um prémio pago em Novembro 2019 ao empregado por erro, é devolvido em Fevereiro de 2020, no momento em que o erro é detetado. Deveria ser reportado no momento de devolução, com referência ao período económico em que se refere. 
* Reintegração de empregado por ordem de tribunal.

### Rendimentos negativos do próprio ano

Existem igual casos em que é necessário retificar rendimentos negativos no decorrer do próprio ano.

#### Exemplos de caso

* Subsídio de natal pago em duodécimos 
* Subsidio de natal pago em Novembro \(sobre a estimativa de trabalho ano \(12/12\) completo\) e ajustado em Dezembro para \(11/12\) derivado de ausência no mês de Dezembro

## Solução

{% hint style="info" %}
A solução proposta foi validada em conjunto com a Direção de Serviços do Imposto sobre o Rendimento das Pessoas Singulares \(DIRS\) da Autoridade Tributária e Aduaneira \(AT\).
{% endhint %}

A Autoridade Tributária e a Aduaneira \(AT\) esclarece que a correção das situações aqui descritas acontecem através de declarações de substituição, tendo sido aberta a possibilidade de, no período  
compreendido **entre fevereiro e dezembro de cada ano**, poderem ser declarados movimentos negativos referentes a meses transatos, mas sempre referentes ao ano civil em curso.

As correções aos meses de **dezembro têm**, obrigatoriamente, que ser feitas por declaração de substituição porque as DMR’s de janeiro, não podem, de forma alguma, reportar valores negativos \(sendo a primeiro do ano não comporta correções\). Esta é uma imposição legal.

A entrega de declarações de substituição e a do mês também é realizada **por ordem cronológica**.

As validações são feitas mensalmente e sempre por ordem cronológica, para garantirem que os acumulados do ano não são negativos. A AT valida um batch de DMRs por noite como forma de controlar que inexistência de acumulados de rendimentos inferior a zero.

{% hint style="success" %}
### Validações a ter em conta

* Por ano
* Por contribuinte
* Por natureza de rendimento
* Por ordem cronológica de datas \(mês 1 ao mês 12\)
* Os acumulados não podem ser negativos \(todas as colunas\)
* Não podem existir declarações com erros sob pena das subsequentes não poderem ser validadas
{% endhint %}

Os problemas de performance têm essencialmente que ver com a necessidade de submissão de declarações por ordem do período a que se referem, para garantir que os acumulados do trabalhador se mantém positivos. Esta é uma validação crítica para a geração do DUC.

