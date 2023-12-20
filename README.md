# TP2

Trabalho 2 da disciplina TPPE no semestre 2023/2.

## 1. Grupo

| Aluno                              | Matrícula  |
| ---------------------------------- | ---------- |
| Guilherme Rogelin Vial             | 190014032  |
| João Pedro Alves Machado           | 212008197  |
| Lucas Braun Vieira Xavier          | 190033088  |
| Lucas Felipe Soares                | 202016767  |
| Lucas Gomes Caldas                 | 212005426  |

## Simplicidade:

Essa constitui a característica mais crucial de um código bem elaborado. Um design simples revela-se fácil de compreender, isento de falhas ou imperfeições desnecessárias, além de ser de execução descomplicada. Ele mantém coerência e consistência. O código simples é o mais conciso possível, sem ultrapassar essa medida. O programador deve se empenhar em determinar a quantidade mínima de código necessária e, em seguida, redijir apenas essa quantidade. É importante lembrar que é sempre possível adicionar mais código posteriormente para funcionalidades extras, mas raramente pode-se remover algo que se tornou intimamente entrelaçado. O conceito chave dessa característica é “Menos é mais”.

### Relação com Maus Cheiros de Código de Fowler:

Um dos maus-cheiros relacionados é a presença de **funções longas**, que desafiam a simplicidade ao estenderem-se desnecessariamente, tornando-se difíceis de entender e manter. Essas funções, ao acumularem excesso de complexidade, geram códigos extensos que dificultam a identificação de sua lógica e propósito.

Da mesma forma, o problema da **classe grande** também se encaixa nesse contexto. Classes extensas e complexas tornam-se obstáculos à clareza do código, desafiando a coesão e consistência desejadas. A analogia com a ideia de que o código deve ser "tão pequeno quanto possível, mas não menor" reflete a importância de evitar o inchaço desnecessário nas funções e classes, respeitando a necessidade de tamanho mínimo sem comprometer a compreensibilidade do código.

### Operação de refatoração:

As principais operações de refatoração nesses casos são **extrair função** e **extrair classe**. Ao extrair uma função, desenvolvedores podem dividir blocos extensos de código em unidades mais gerenciáveis, promovendo a clareza e compreensibilidade. Isso não apenas facilita a manutenção, mas também contribui para a modularidade do código. Similarmente, a refatoração de extrair classe permite separar responsabilidades em unidades coesas, evitando classes grandes e complexas. 

## Elegância

A elegância é uma qualidade que é apreciada em muitas áreas da vida, incluindo a arte, a arquitetura e o design. No contexto do software, a elegância pode ser definida como a qualidade de um software que é simples, eficiente e fácil de entender e usar. A elegância em software é importante por uma série de razões. Em primeiro lugar, ela torna o software mais agradável de usar. Software elegante é fácil de aprender e usar, mesmo para pessoas que não são especialistas em tecnologia. Isso pode ajudar a melhorar a experiência do usuário e aumentar a satisfação do cliente. Em segundo lugar, a elegância em software pode ajudar a reduzir os custos de desenvolvimento e manutenção. Software elegante é mais fácil de manter e atualizar, o que pode economizar tempo e dinheiro. Em terceiro lugar, a elegância em software pode ajudar a aumentar a segurança. Software elegante é mais fácil de entender e analisar, o que pode dificultar a identificação e exploração de vulnerabilidades. Ao nos referirmos a elegância de software, podemos destacar três componentes principais:

### Simplicidade: 

Software elegante é simples de entender e usar. Ele não deve ser complexo ou confuso. Tal característica é abordada no tópico anterior.

### Eficiência: 

Software elegante é eficiente em termos de recursos. Ele deve usar os recursos do sistema de forma eficiente, sem desperdiçar memória ou processamento. Muitos desses aspectos são originados em decorrência de uma boa utilização das estruturas de dados, frameworks adequados e até mesmo conhecimentos acerca da estrutura física dos sistemas de software como HDs, SSD, processadores e etc.

### Estética:

Software elegante é agradável de olhar e usar. Ele deve ter um design atraente e intuitivo. Muitos desses elementos, são abordados durante os estudos de **Interação Humano-Computador**, no qual corresponde uma área do estudo onde procura se melhorar a relação do ser-humano com os sistemas computacionais.

Trazendo um exemplo prático quanto a elegância, podemos destacar a **linguagem de programação Python**: Python é uma linguagem de programação de alto nível que é conhecida por sua clareza e simplicidade. Ela é fácil de aprender e usar, mesmo para pessoas que não são especialistas em programação.

### Relação com Maus Cheiros de Código de Fowler:

Um dos maus-cheiros relacionados está atrelado com um código com excesso de **complexidade**, o mesmo pode dificultar a compreensão, manuntenção e a evolução do código. Além mais, podemos destacar o **código incoerente**, esse estilo de código não segue um padrão consistente e torna o mesmo cada vez mais difícil de evoluir e fazer manuntenção, sobretudo para desenvolvedores que possuem menos experiência com esse código em questão. Por fim, podemos citar o **custo de mudanças**, o código é difícil de mudar. Isso pode dificultar a correção de erros, a implementação de novas funcionalidades ou a adaptação a mudanças nas necessidades do negócio.

### Operação de refatoração:

As principais operações de refatoração aplicadas nesse caso são **remoção de código duplicado** e **desacoplando** ou deixando o código mais **modular**. O código duplicado, eleva a complexidade porque qualquer manuntenção feita em um dos trechos do código precisa ser aplicada em todas as demais, além mais, o código duplicado pode ocasionar diminuição do desempenho vista que o compilador ou interpretador do software precisa carregar e analisar o código duplicado duas ou mais vezes. Tratando os códigos desacoplados, é aquele código em que os componentes são interdependentes o mínimo possível, isso significa que cada componente deve ser capaz de funcionar de forma independente, sem depender de outros componentes. Por fim, o código modular é um tipo de código que é dividido em unidades menores, chamadas de módulos, cada módulo é responsável por uma função ou tarefa específica. Tornando assim, mais fácil a **compreensão, manuntenção e melhorando a testabilidade do código**.
 
## Boa documentação

A documentação de software é um conjunto de informações que descreve o software, seu funcionamento e como usá-lo. Ela é importante para todos os envolvidos em um projeto de software, incluindo usuários, desenvolvedores e administradores. A mesma deve possuir formatos de documentação padronizados, cobertura abrangente dos aspectos do software, atualizada regularmente e de preferência esteja disponível em diversos idiomas com a linguagem mais clara e concisa possível. Com a seguinte característica de projeto, podemos melhorar a experiência do usuário com a facilidade de aprendizagem do mesmo com o sistema, facilita o desenvolvimento e manuntenção do software e reduz o custo de investimento com suporte técnico em vista que agora o próprio usuário é capaz de resolver seus próprios problemas. Exemplos de boa documentação: **Linux**,**Python** e **React**.

### Relação com Maus Cheiros de Código de Fowler:

A boa documentação pode ajudar a mitigar os efeitos dos maus-cheiros de código. Ela pode fornecer informações que ajudam os desenvolvedores a entender o código e a tomar decisões informadas sobre como melhorá-lo. Isso é, um código com má documentação está mais suscetível aos maus-cheiros de código. A seguir veremos exemplos que relacionam a boa documentação com maus-cheiros de código.

#### Código complexo

A documentação pode ajudar a explicar o código complexo e a fornecer informações sobre como ele pode ser simplificado. Garantindo assim, que o mesmo agora possa ser evoluido e passível de manuntenção.

#### Código frágil

A documentação pode ajudar a identificar o código frágil e a fornecer informações sobre como ele pode ser tornado mais robusto. Com isso, evitamos que as falhas escorram para outros trechos de código sob efeito de cascata ou até mesmo que não comprometa o funcionamento adequado do código como um todo.

### Código acoplado

A documentação pode ajudar a identificar o acoplamento entre os componentes do código e a fornecer informações sobre como ele pode ser reduzido ou operado.


### Operação de refatoração:

As principais operações de refatoração aplicadas nesse contexto se consistem em: **renomear, mover e combinar**. A seguir, veremos mais detalhadamente sobre essas três operações:

#### Renomear

A operação de renomear consiste em uma melhor adequação dos termos para tornar mais claro para um público não técnico. Por exemplo, um termo técnico como "API" pode ser substituído por "interface de programação de aplicativos".

#### Mover

Uma seção sobre como usar um determinado recurso pode ser movida para o início do documento para que os usuários possam encontrá-la mais facilmente. Além mais, é importante que seja pensando na ordem em que as seções são apresentadas para facilitar no entendimento daquele que se deseja que leia as documentações.

#### Combinar

Duas seções sobre os mesmos tipos de erros podem ser combinadas para reduzir a redundância. Por conseguinte, seções similares devem estar mais próximas na documentação para que se facilite no entendimento lógico acerca de tópicos que possuem certo grau de similaridade.


## Ausência de duplicações:

Código bem projetado não contém duplicações, ele nunca precisa se repetir. A duplicação é a inimiga de um design elegante e simples. Código redundante e desnecessário leva a um programa frágil. Dadas duas partes semelhantes de código que diferem apenas em detalhes mínimos, você pode encontrar e corrigir um bug em uma e depois esquecer de corrigir o mesmo bug na outra. Isso compromete claramente a segurança do código.

A maioria das duplicações ocorre através da programação de copiar e colar código no editor. Ela pode surgir de maneira mais sutil através da reinvenção de soluções já existentes por programadores que não compreendem o sistema como um todo.

### Relação com Maus Cheiros de Código de Fowler:

A presença de duplicações no código está diretamente relacionada a vários maus cheiros definidos por Martin Fowler, incluindo:

**Duplicação de Código:** Duplicações são consideradas um mau cheiro significativo, pois aumentam a complexidade e a chance de inconsistências entre partes semelhantes do código.  
**Funções Longas:** Duplicações frequentemente resultam em métodos e funções mais longas, pois partes do código são repetidas em várias partes do programa.

### Operação de refatoração:

**Extrair função:** Essa operação envolve a identificação de código duplicado e a criação de uma função ou método para realizar a tarefa duplicada, promovendo a reutilização.

## Portabilidade

a portabilidade se refere à capacidade do código ou do software de ser transferido ou executado em diferentes ambientes ou plataformas sem a necessidade de grandes alterações ou adaptações. Ou seja, é a característica de um sistema que permite que ele seja facilmente utilizado em diferentes sistemas operacionais, hardwares ou ambientes de execução.

### Relação com Maus Cheiros de Código de Fowler:

A relação dos maus cheiros de código, conforme descrita por Fowler, quando aplicada à portabilidade, destaca a importância de um design sensível às exigências de diferentes plataformas, sem comprometer desnecessariamente a qualidade do código. É ressaltado que um design eficiente não garante automaticamente a portabilidade, mas deve ser adaptável às necessidades específicas de cada ambiente.

Uma abordagem recomendada é a criação de uma camada de abstração de plataforma, atuando como uma interface entre o código principal e as particularidades de sistemas operacionais ou hardware. Essa estratégia permite implementar essa camada de maneira flexível em cada plataforma, facilitando a adaptação do código para ambientes diversos.

### Operação de refatoração:

Uma operação de refatoração válida para lidar com a portabilidade seria a criação de uma camada de abstração, isolando o código específico de plataformas em métodos ou funções separadas. Isso permite que o código principal interaja com uma interface genérica, facilitando modificações para suportar diferentes ambientes sem impactar diretamente o restante do código.

## Elegância

Elegância no desenvolvimento de software, referindo-se à criação de soluções simples e eficientes, é essencial para lidar com a portabilidade. A eliminação de Maus Cheiros de Código, padrões problemáticos, é crucial nesse processo.

### Relação com Maus Cheiros no Código de Fowler:
A busca pela elegância está ligada à identificação e eliminação dos Maus Cheiros, padrões problemáticos de práticas de programação. Em termos de portabilidade, a elegância implica em criar um design sensível a diferentes plataformas, evitando códigos duplicados e dependências excessivas.

Um código elegante para portabilidade deve ser flexível, adaptando-se a diversos ambientes sem perder legibilidade. A eliminação de Maus Cheiros relacionados à portabilidade envolve a criação de estruturas que facilitem a adaptação a sistemas operacionais, hardwares ou ambientes distintos.

### Operação de refatoração:

A operação de refatoração é fundamental para atingir a elegância. Na portabilidade, criar uma camada de abstração para isolar as peculiaridades de plataformas é uma forma de refatoração que aprimora a elegância do código.

Refatorar para portabilidade inclui reorganizar o código, identificar padrões comuns e criar interfaces genéricas. Isolar o código específico de plataformas em funções separadas, conforme sugerido na operação de refatoração, contribui para a elegância ao permitir que o código principal interaja com uma interface genérica, facilitando manutenção e adaptação a diferentes ambientes.

## Referências Bibliográficas

Goodliffe, P. (2006). Code craft : The practice of writing excellent code. No Starch Press, Incorporated.

Fowler M, Beck K. Refactoring : Improving the Design of Existing Code. Addison-Wesley; 2019.

BROPHY, P. The library in the twenty-first century. London: Facet, 2007.

Barbosa, S.D.J.; Silva, B.S. Interação Humano-Computador. Série SBC, Editora Campus-Elsevier, 2010.

AUGUSTO, J. Guia de Orientação e Desenvolvimento de Sites. [s.l.] Saraiva Educação S.A., [s.d.].

‌
