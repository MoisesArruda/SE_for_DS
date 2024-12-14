# Observações sobre o livro.

Um bom entendimento sobre engenharia de software é primordial para todos aqueles que trabalham com código e desejam melhorar a qualidade destes. Sabendo da importância e dos beneficios em se trabalhar com um código de qualidade, como reduzir o tempo final de desenvolvimento com um código bem estruturado, tratamento de erros [error handling], fácil manuntabilidade, passagem de conhecimento menos dolorosa e a oportunidade de continuar desenvolvendo seu código para que ganhe uma robustez conforme o tempo.

**IDE** - Ambiente de desenvolvimento integrafo.

**Running Time** - Tempo de execução.

**Error Handling** - Tratamento de Erros.

**Logging** - Registro de Logs.

**Deployment** - Implantação.

## Categorias que tornam um código bom.

1. Simplicidade: Um código simples é melhor que um complexo, sendo sempre importante se evitar o *DRY[Don´t repeat yourself*]

2. Modularidade: Modularidade é a arte de de dividir um grande sistema em componentes menores.

3. Legibilidade: A leitura déve ser fácil para que outras pessoas consigam entende-lo e reproduzi-lo

4. Desempenho: Além de eficiente, devemos mensurar o tempo de execução como o uso de memória

5. Robustez: A execução deve ser completa e livre de falhas, garantindo sua reprodução total.

## Capitulo 2: Classes, métodos e atributos

1. Classe: Uma classe define um objeto, que nada mais é do que uma representação abstrata de uma entidade.

2. Atributos da classe: Variáveis definidas dentro da classe ou no momento que criamos sua instância. Cada objeto pode ter dados diferentes armazenados.

3. Instância da classe: Um objeto individual, ou seja, uma classe que foi chamada e definida é uma instância. Essa poderá ser utilizada para acessar os métodos e atributos da classe.

4. Métodos: Podemos entender os métodos como funções dentro da classe, basicamente são ações que podemos realizar nos objetos, incluindo modificações em atributos.

    4.1. __init__: Método especial responsável por armazenar atributos quando iniciamos uma instância.

    4.2. classemethod: Estes métodos realizam alterações sobre os atributos da classe, e não sobre os métodos em si. A modificação é executada em todas as instâncias que estão no código. Possuí a caracteristica de ser inicializada com o parametro *cls* e não self.

    4.3. staticmethod: Podem ser chamadas sem a necessidade da criação de uma instância da classe, por isso não recebem os parametros self e cls. Esses métodos realizam ações independentes que façam sentido dentro do contexto da classe(como a soma de um livro + imposto).

5. Atributos dos métodos: Variáveis definidas dentro dos métodos, onde poderão ser passados na criação destes atributos ou na chamada dos métodos.
 
    5.1. Self: Argumento self se refere a instância do objeto que é criado.

## Resumo

Uma classe é uma abstração de algo, utilizamos para facilitar o desenvolvimento e entendimento do código,  nossa classes possuem atributos(variáveis) que serão acessadas por todas as instâncias de nossa classe, se quisermos modificar esses atributos de forma que suas alterações se reflitam em todas as instâncias, utilizamos o *classmethod*. Nossas classes podem possuir métodos(funções) que realizam ações, ou modificam dados atribuídos aos nossos atributos de métodos, sendo sempre acessado pelo argumento self. Se quisermos realizar ações independentes da estrutura da classe, utilizamos o staticmethod.
