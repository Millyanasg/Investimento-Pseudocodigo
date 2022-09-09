# Investimento-Pseudocodigo
<h4>Simulação de carteira de investimento.</h4>


Uma carteira de investimentos bem diversificada, pode e deve ser composta por ativos de renda fixa e renda variável, mas isso vai depender do perfil do investidor.
Caso o investidor tenha zero tolerância a volatilidade (oscilação do valor de seus ativos), ele não deve comprar ações na bolsa de valores diretamente. (GUEDINE, 2021).
Neste programa, o cliente da corretora poderá definir um percentual de diversificação entre as seguintes opções de investimento:
````
     1 - CDBs (XX%)
     2 - Ações (XX%)
     3 - Fundos Imobiliários (XX%)
     4 - Stocks (XX%)
     5 - Reits (XX%)
````

Os passos a serem executados no sistema pelo usuário, são:
* Passo 1: Indicação do valores percentuais sobre cada investimento
* Passo 2: Indicar os valores que já possui investido em cada categoria

**Como Regra do sistema <i>(requisitos)</i>, você tem que:**

* 1 O total percentual dos objetivos deve somar 100%. Caso seja diferente, uma mensagem deve ser mostrada ao usuário indicando o problema, deve-se pedir para repetir o preenchimento.
* 2 Todos os valores de investimento devem ser preenchidos, caso o usuário não queira investir em alguma das categorias, deve-se digitar 0
* 3 Ao final das entradas de valores, deverá apresentar um resumo indicando o % de objetivos pretendido, o % atual.
* 3.1 Objetivos pretendido (mostras as categorias e seus respectivos valores percentuais)
* 3.2 Objetivo atual deve sergui a regra:

````
 A = Soma todos os valores investidos
 B = Valor indicado de invetimento em cada categoria
 C = B multiplico por 100
 D = C/A 
 ````
  * esta regra deve ser utilizada em cada categoria
