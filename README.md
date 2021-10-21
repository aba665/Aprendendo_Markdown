# Conhecendo o Markdown

Resumidamente o Markdown foi criado por o programador de computador  Aaron Swartz e o designer de UI John Gruber com o intuito de fazer com que as pessoas conseguissem entender o texto melhor e que a conversão de Markdown para Html fosse de certa maneira fácil de se realizar, haja vista que em outras linguagens de marcação como o __Html__ por exemplo,  onde a leitura de todo o código html pode se tornar um pouco confusa por questão de muitas tags e especificações. Sabendo-se disso vamos aprender  os caracteres do **Markdown**.

## Criando títulos

"#" - A cerquilha ou jogo da velha é utilizado para criar título e esses titulos tem seis variações de tamanhos que pode ser criado  com o acréscimo de mais uma cerquilha até chegar o número final de variações que é seis:

Obs: Para que funcione tem que retirar as aspas da cerquilha, ela foi utilizada mais acima para mostrar o caractere desejado, senão o texto se tornaria um título.
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

## Criação de um linha horizontal demarcada

Para criar uma linha demarcada utilizaremos três asteriscos ou 3 underline em seguida.

Ex: ***

***
Ex: ---

---

## Negrito e Itálico

Para utilizar o negrito em um texto teremos duas maneiras de utilizar que é com o caractere asterisco "**  **" ou o underline "__  __" e fechá-lo ao final da palavra no texto que desejarmos utilizar o texto em negrito.

Exemplo com aterisco: **João e Maria** são programadores.
    
Exemplo com underline: __Maria e João__ são bons amigos.

Já o texto em itálico utilizaremos só um asterisco  ou um underline e em seguida fechamos ele.

Exemplo com asterisco: *João e Maria* são programadores.
    
Exemplo com underline: _Maria e João_ são bons amigos.

Há outra de maneira de utilizar ambos em um texto, é fácil deixa eu te mostrar.

Exemplo: __*João e Maria*__ não são mais amigos.

É só usarmos dois underline e um asterisco em seguida, e então criaremos um texto em negrito e itálico. 

## Criação de listas

### Lista Numerada

Para criarmos uma lista numerada temos que utilizar um número de sua opção podendo ser o 1, 2,3 e etc. E em seguida adicionamos um ponto e o texto que queremos adicionar.

Ex 1:
---
1. Feijão         
2. Carne          
3. Arroz 
         
Ex 2:

---
3. Macarrão
3. Peixe
3. Pão
---
Obs: A algo engraçado que acontece com esse tipo de lista, nós colocamos o número 3 em todo o exemplo 2 e mesmo assim a lista foi exibida corretamente ou seja em ordem.

### Lista Demarcada

A lista demarcada pode ser criada da seguinte forma, com a inclusão de um único asterisco e o texto ou palavra escolhido.

Ex:
***
* Html
* Java
* C++
***
### Lista de Tarefa

Para criamos é preciso colocar um traço, dar um espaço e em seguida abrir e fechar colchetes e depois adicionar a tarefa. Uma coisa legal desse tipo de lista é que podemos colocar um checklist, ou seja, podemos marcar ou desmarcar uma tarefa. Para marcar ou desmarcar é so colocarmos o x entre o colchetes ou tirá-lo.

---
Ex: 

- [ ] Criar a página de contantos
- [ ] Se reunir com o cliente
---

Obs: Para criarmos um subtipo em uma lista, exemplificando, vamos supor que uma lista 1 tem dois subtipos que é lista 1.1 e lista 1.2 para criamos isso é só incluir abaixo da lista 1; 3 espaços e criar a sua lista ordenada ou demarcada.

## Criação de tabelas

Para a criação de tabela seguremos esses passos:

---
Número | Nome | Nota
--|--|--|
1|João|8,5
2|Maria|7,2
3|Luana|9,0
---

## Demarcando um Comando

Essa demarcação e feito através da abertura e fechamento de duas crase.

Ex: Na linha 65 temos o seguinte comando ``for(i=0; i<=10; i++){``.

Podemos observar que criamos um monoespaço com um fundo cinza onde mostramos um certo comando.

### Dermacação de um Código

Para demarcar um codigo utilizamos também a crase só que ao invés de colocar só duas crase e fechá-la, colocaremos três crase e fechamos a crase.

Ex: Olha o meu programa em C para o cálculo de desconto em um caixa
```
#include <stdio.h>
#include <stdlib.h>

int main()
{
    float valor_bruto=0;
    float desconto=0;
    float valor_liquido=0;
    int qtd_pessoas=0;
    printf("\ndigite o valor total da conta: ");
    scanf("%f",&valor_bruto);
    printf("\nDigite a quantidade de pessoas: ");
    scanf("%d",&qtd_pessoas);
    printf("\nDigite o total de desconto (em porcentagem): ");
    scanf("%f",&desconto);
    valor_liquido = valor_bruto - (valor_bruto*(desconto/100));
    printf("\nValor com desconto = %f", valor_liquido);
    printf("\nValor a ser pago por pessoa = %f", valor_liquido/qtd_pessoas );

    return 0;
}
```

<!-- "``"- utilizada para criar monoespaço e com um fundo cinza, mostrar um comando 
"```  ```" - mostrar um codigo do seu programa em um fundo cinza
":" introduz emoji
"[](link)"
"![descrição da imagem](diretório)" -->
