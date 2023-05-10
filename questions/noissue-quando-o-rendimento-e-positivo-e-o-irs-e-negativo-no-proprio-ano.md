# Quando o rendimento é positivo e o IRS é negativo no próprio ano



<table><thead><tr><th>ID</th><th>Título</th><th data-type="content-ref">Issue</th><th>Tipo</th><th>Criado</th><th>Modificado</th></tr></thead><tbody><tr><td>N/A</td><td>Quando o rendimento é positivo e o IRS é negativo no próprio ano</td><td></td><td>Autoridade Tributária e Aduaneira (AT)</td><td>2020-07-15</td><td>2020-07-15</td></tr></tbody></table>

## Questão

### Declarações de substituição do próprio ano

São o caso de declarações de substituição no ano corrente para resolução de situações que resultem em rendimento positivo com IRS negativo no próprio mês.

#### Solução encontrada pelos fabricantes

* Retro cálculo processado desde o início do exercício (geralmente desde Janeiro)
* Várias declarações de substituição de rendimentos no ano corrente.

#### Impacto e consequência nos utilizadores

As consequências medem-se acima de tudo numa perda de performance e no aumento de funções redundantes para os utilizadores.

#### **Performance**:

* Obriga à obtenção de n(X) DMR no sistema fonte
* Submissão de todas as DMR n(X) de substituição novamente na plataforma da Autoridade Tributária e Aduaneira

{% hint style="warning" %}
#### Fabricantes de maior dimensão

Pese embora este problema seja transversal a todos os fabricantes de software de gestão de recursos humanos, ele é mais visível naqueles que lidam com clientes de grande dimensão, com um grande número de empregados.
{% endhint %}

#### Exemplo de caso

Empregado recebe Subsídio de Natal em regime de duodécimos.

* Salário: `1200.00`
* Duodécimo de Sub. Natal: `50.00`
* Taxa com ref. 1200 (valor estimado): `14.5%`
* Cálculo mensal de IRS (50.00 x 14.5%): `7.00`

#### Gera um IRS negativo no seguinte caso

* Empregado sai da empresa no mês de **Abril**
* Duodécimo de Sub. Natal (50.00 x 3): `150.00`
* Subsídio de Natal Anual (taxa de referência de 0%): `400.00`
* Valor a pagar e a reportar na DMR (400.00 - 150.00): `250.00`
* **Retenção a declarar (3 primeiros meses):** **`-21.00`**

#### Sugestão

Possivelmente, seria mais simples na DMR de Abril apresentar sob o código `A4` com o montante positivo de `150.00` e a retenção negativa de `-21.00`, possibilitando a validação com o total retido até à data?

| Report | Código | Rendimento |    IRS | Segurança Social |
| ------ | ------ | ---------: | -----: | ---------------: |
| DMR    | A4     |     250.00 | -21.00 |            27.50 |

## Solução

{% hint style="info" %}
A solução proposta foi validada em conjunto com a Direção de Serviços do Imposto sobre o Rendimento das Pessoas Singulares (DIRS) da Autoridade Tributária e Aduaneira (AT).
{% endhint %}

A Autoridade Tributária e a Aduaneira (AT) esclarece que não pode haver lugar a devolução de IRS aos trabalhadores neste caso. O mesmo fica registado como um pagamento por conta que é posteriormente objeto de acerto no final do ano fiscal, entre o contribuinte e a AT.

Sobre este assunto, só **podem ser objeto de correção** os rendimentos. A componente de retenções, ou seja, a inserção de rendimentos positivos, **não poderá levar** no presente caso à devolução de IRS.

{% hint style="success" %}
#### Não há lugar a devolução de IRS

É a AT que efetua o acerto de retenção com o trabalhador no final do ano.
{% endhint %}

A retenção foi realizada com base nos pressupostos conhecidos e corretamente efetuada, daí não há lugar a devolução.

Num caso em que o trabalhador saia da empresa, tendo tudo positivo, **mas em que o sindicato é negativo** (relativamente ao mês anterior no próprio ano), a AT esclarece que deve ser feita a **substituição da declaração de origem**, ou seja, a do mês anterior.
