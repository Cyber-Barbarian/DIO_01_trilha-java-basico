# Conceito de POO

## Tipos de linguagem
* **Baixo nível**: São linguagens que estão mais próximas, da interpretação da máquina, diante do algoritmo desenvolvido. Exemplo: Linguagem Assembly e C.
* **Alto nível**: São linguagens que disponibilizam, uma proposta de sintaxe (forma de escrever processos para serem executados pelo computador) mais próxima de interpretação humana. Exemplo: Java, JavaScript, Python e C++

## Programação estruturada
* **A programação estruturada** é um paradigma de programação, que visa melhorar a clareza, a qualidade e o tempo de desenvolvimento de um programa de computador, fazendo uso extensivo, das construções de fluxo de controle estruturado de seleção ( if / then / else ) e repetição (while e for ), estruturas de bloco e sub - rotinas .

* O que devemos ter em mente, é que na programação estruturada, implementamos algoritmos com estruturas sequenciais denominados de procedimentos lineares, podendo afetar o valor das variáveis de escopo local ou global em uma aplicação.


## Programação orientada a objetos
* **POO** é um paradigma de programação, baseado no conceito de "objetos", que podem conter dados na forma de campos, também conhecidos como atributos, e códigos, na forma de procedimentos, também conhecidos como métodos.

* O que precisamos entender, é que cada vez mais as linguagens se adequam ao cenário real, proporcionando assim, que o programador desenvolva algoritmos mais próximo de fluxos comportamentais, logo, tudo ao nosso redor é representado como Objeto.

```
Enquanto a programação estruturada é voltada a procedimentos e funções, definidas pelo usuário, a programação orientada a objetos é voltada a conceitos, como o de classes e objetos.

```

Como se trata de um contexto análogo ao mundo real, tudo no qual nos referimos são objetos, exemplo: Conta bancária, Aluno, Veículo, Transferência etc.

A programação orientada a objetos é bem requisitada no contexto das aplicações mais atuais no mercado devido a possibilidade de reutilização de código e a capacidade de representação do sistema ser muito mais próximo do mundo real.

Para uma linguagem ser considerada orientada a objetos, esta deve seguir o que denominamos como _**Os quatro pilares da orientação a objetos**_:

*   **Encapsulamento:** Nem tudo precisa estar visível, grande parte do nosso algoritmo pode ser distribuído em métodos com finalidades específicas que complementa uma ação em nossa aplicação.

    Exemplo: Ligar um veículo exige muitas etapas para a engenharia, mas o condutor só visualiza  a ignição, dar a partida e a _“magia”_ acontece.
*   **Herança:** Características e comportamentos comuns podem ser elevados e compartilhados através de uma hierarquia de objetos.

    Exemplo: Um Carro e uma Motocicleta possuem propriedades como placa, chassi, ano de fabricação e métodos como acelerar, frear. Logo para não ser um processo de codificação redundante, podemos desfrutar da herança criando uma classe **Veiculo** para que seja herdada por Carro e Motocicleta.
*   **Abstração:** É a indisponibilidade para determinar a lógica de um ou vários comportamentos em um objeto.

    Exemplo: **Veículo** determina duas ações como acelerar e frear, logo estes comportamentos deverão ser _abstratos_ pois existem mais de uma maneira de se realizar a mesma operação.   ver _Polimorfismo_.
*   **Polimorfismo:** São as inúmeras maneiras de se realizar uma mesma ação.

    Exemplo: Veículo determina duas ações como acelerar e frear, primeiramente precisamos identificar se estaremos nos referindo a **Carro** ou **Motocicleta** para determinar a lógica de aceleração e frenagem dos respectivos veículos.  &#x20;



