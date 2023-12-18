# TP2

Trabalho 2 da disciplina TPPE no semestre 2023/2.

## 1. Grupo

| Aluno                              | Matrícula  |
| ---------------------------------- | ---------- |
| Lucas Felipe Soares                | 202016767  |
| João Pedro Alves Machado           | 212008197  |
| Lucas Gomes Caldas                 | 212005426  |
| Lucas Braun Vieira Xavier          | 190033088  |
| Guilherme Rogelin Vial             | 190014032  |

## Simplicidade:

Essa constitui a característica mais crucial de um código bem elaborado. Um design simples revela-se fácil de compreender, isento de falhas ou imperfeições desnecessárias, além de ser de execução descomplicada. Ele mantém coerência e consistência. O código simples é o mais conciso possível, sem ultrapassar essa medida. O programador deve se empenhar em determinar a quantidade mínima de código necessária e, em seguida, redijir apenas essa quantidade. É importante lembrar que é sempre possível adicionar mais código posteriormente para funcionalidades extras, mas raramente pode-se remover algo que se tornou intimamente entrelaçado. O conceito chave dessa característica é “Menos é mais”.

### Relação com Maus Cheiros de Código de Fowler:

Um dos maus-cheiros relacionados é a presença de **funções longas**, que desafiam a simplicidade ao estenderem-se desnecessariamente, tornando-se difíceis de entender e manter. Essas funções, ao acumularem excesso de complexidade, geram códigos extensos que dificultam a identificação de sua lógica e propósito.

Da mesma forma, o problema da **classe grande** também se encaixa nesse contexto. Classes extensas e complexas tornam-se obstáculos à clareza do código, desafiando a coesão e consistência desejadas. A analogia com a ideia de que o código deve ser "tão pequeno quanto possível, mas não menor" reflete a importância de evitar o inchaço desnecessário nas funções e classes, respeitando a necessidade de tamanho mínimo sem comprometer a compreensibilidade do código.

### Operação de refatoração:

As principais operações de refatoração nesses casos são **extrair função** e **extrair classe**. Ao extrair uma função, desenvolvedores podem dividir blocos extensos de código em unidades mais gerenciáveis, promovendo a clareza e compreensibilidade. Isso não apenas facilita a manutenção, mas também contribui para a modularidade do código. Similarmente, a refatoração de extrair classe permite separar responsabilidades em unidades coesas, evitando classes grandes e complexas. 
