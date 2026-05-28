# pensamento-computacional
Portfólio de atividades práticas da disciplina de Pensamento Computacional utilizando a plataforma Scratch.
# Pensamento Computacional - Atividades Scratch

Repositório dedicado ao registro de algoritmos e conceitos teóricos desenvolvidos em aula.

---

## 📌 Lista de Atividades (Conforme o Material Oficial)

### 🧩 Atividade 01 - Uso de Variáveis (Pág. 1)
* **Enunciado**: Crie um programa Scratch que recebe um valor de entrada do usuário (p.ex. o nome do usuário), armazene este valor na variável padrão “resposta” e faça o personagem gato dizer o valor armazenado correspondente.
* **Nota Teórica**: A variável ~resposta~ é uma variável padrão para armazenar o resultado de algo que é digitado.
* **Para Casa**: Como você faria para armazenar o resultado em uma variável chamada NOME?
* **Conceitos Importantes**: Noção de VARIÁVEL; Concatenação de valores (olá + conteúdo da variável “resposta”).
* **Arquivos**: [Código Scratch (Baixar)](./Atividade-01/pensamento_computacional_exercicio_01.sb3) | [Testar Projeto Online](https://scratch.mit.edu/projects/1320771484)

---

### 🧩 Atividade 02 - Repita n Vezes (Pág. 1)
* **Enunciado**: Crie um programa Scratch que receba um número de entrada do usuário, armazene o número na variável padrão “resposta” e faça:
  * Crie uma variável “var” e inicialize seu valor em 1.
  * Repita os procedimentos abaixo n vezes, onde n é o número armazenado na variável “resposta”:
    * Se o valor armazenado em “var” for maior que 5 faça o gatinho dizer “MIAU” por 2 segundos e andar “var”*100 passos (lembre-se de adicionar o comando que permite ao gatinho voltar quando atinge a parede do cenário).
    * Se o valor armazenado em “var” for menor ou igual a 5, faça o gatinho trocar de traje.
    * Por fim, aumente o valor de “var” em 1 e faça o gatinho esperar 2 segundos.
* **Para Casa**: Escreva o fluxograma correspondente.
* **Conceitos Importantes**: Variável usada para limite da iteração (“resposta”); Variável que controla número de ações (“var”); IF-THEN-ELSE.
* **Arquivos**: [Código Scratch](./Atividade-02/pensamento_computacional_exercicio_02.sb3) | [Fluxograma](./Atividade-02/fluxograma-exercicio-2.png) | [Projeto Online no Scratch](https://scratch.mit.edu/projects/1320696919)


---

### 🧩 Atividade 03 - Condicionais Aninhadas e Loops (Pág. 2)
* **Enunciado**: Crie um programa Scratch que receba um número de entrada do usuário, armazene o número na variável padrão “resposta” e faça:
  * Crie uma variável “var” e inicialize seu valor em 1.
  * Repita os procedimentos abaixo até VAR ultrapassar o valor de “resposta”:
    * Se o valor armazenado em “var” for maior que 5 faça o gatinho dizer “MIAU” e andar “var” * 100 passos (lembre-se de adicionar o comando que permite ao gatinho voltar quando atinge a parede do cenário).
    * Senão, se o valor armazenado em “var” for igual a 4, faça com que o gatinho troque de traje.
    * Senão, se o valor armazenado em “var” for menor do que 4, faça o gatinho dizer esse novo valor.
    * Por fim, aumente o valor de “var” em 1 e faça o gatinho esperar 2 segundos.
* **Questões de Estudo**:
  * a) Entre com o valor 0 no início. O que acontece? Por que isso acontece?
  * b) Teste seu programa, para valores 3, 5, e 8.
  * c) Modifique o programa para o gatinho, quando andar, andar “var”*”resposta” passos (ao invés de “var” * 100 passos).
  * d) Modifique o programa para que ao invés de incrementar VAR ao final, subtraia 1.
* **Nota de Observação**: Para acompanhar os valores das variáveis, “clique” ao lado no item correspondente. Lembre-se que ao inserir “esperar” por um ou mais segundos, você tem tempo de observar o que está ocorrendo, senão é rápido demais.
* **Para Casa**: Transforme isto em um fluxograma.
* **Conceitos Importantes**: Variável que controla limite de iterações (“resposta”); Variável que conta número iterações (“var”); IFs aninhados (IF THEN ELSE); Loop zero vezes; Incrementos de passos diferentes; Loop infinito.
* **Arquivos**: [Código Scratch](./Atividade-03/pensamento_computacional_exercicio_03.sb3) | [Fluxograma](./Atividade-03/fluxograma-exercicio_03.png) | [Projeto Online no Scratch](https://scratch.mit.edu/projects/1321649256)

---

### 🧩 Atividade 04 - Troca de Valores (Pág. 3)
* **Enunciado**: Faça um programa Scratch que leia duas variáveis, chamadas PRIMEIRA e SEGUNDA, e faça o gatinho dizer os seus valores. A seguir, troque os valores, de forma que PRIMEIRA contenha o valor de SEGUNDA e vice-versa. O gatinho deve repetir os novos valores.
* **Questão de Estudo**: Veja o código abaixo. Para que é necessário uma variável intermediária TEMP?
* **Para Casa**: Faça o fluxograma correspondente.
* **Conceitos Importantes**: Modificação de valores em memória (troca de valores).
* **Arquivos**: [Código Scratch](./Atividade-04/pensamento_computacional_exercicio_04.sb3) | [Fluxograma](./Atividade-04/fluxograma_exercicio_04.png) [Projeto Online no Scratch](https://scratch.mit.edu/projects/1321649256)

---

### 🧩 Atividade 05 - Funções e Operações: Fatorial (Pág. 4)
* **Enunciado**: Faça um programa Scratch que, dado um número como entrada, calcule o fatorial desse número e faça o gatinho falar esse número (por exemplo, se a entrada for 4, calcula-se 4\*3\*2\*1 e faz o gatinho falar 24). Para isso será necessária a utilização de uma variável para calcular o número fatorial.
* **Conceitos Importantes**: Uso de mais uma variável auxiliar (“aux”) para guardar valores intermediários; Programação de função matemática.
* **Arquivos**: [Código Scratch](./Atividade-05/pensamento_computacional_exercicio_05.sb3)

---

### 🧩 Atividade 06 - Desenho da Reta y=x (Pág. 4)
* **Enunciado**: Faça um programa que desenhe a reta y=x a partir das coordenadas -120, -120.
* **Dica Técnica**: Levantar a caneta e limpar são ações úteis para limpar a tela antes de começar um novo desenho.
* **Conceitos Importantes**: Noções de coordenadas; Equações.
* **Arquivos**: [Código Scratch](./Atividade-06/pensamento_computacional_exercicio_06.sb3)

---

### 🧩 Atividade 07 - Desenho de Parábola (Pág. 5)
* **Enunciado**: Faça o gatinho desenhar uma parábola seguindo a equação y = 1/100*x². Para isso siga os seguintes passos:
  * Ao começar o programa, inicialize a posição x e y do gato em 0.
  * Crie uma variável auxiliar “var” e atribua a ela o valor -100.
  * Limpe a tela de riscos de caneta (Caneta->limpe).
  * Habilite o uso da caneta (Caneta->abaixe a caneta).
  * Repita os seguintes passos até o gato tocar na borda:
    * mude o valor da posição x do gato para “var”.
    * mude y para a equação 1/100 * x².
    * some 1 a variável “var”.
* **Questão de Estudo**: *** O que acontece se “var” aumenta de 2 em 2 ao final?
* **Conceitos Importantes**: Equações; Modificação de variável de controle.
* **Arquivos**: [Código Scratch](./Atividade-07/pensamento_computacional_exercicio_07.sb3)

---

### 🧩 Atividade 08 - Operações com 2 Números (Pág. 5)
* **Enunciado**: Faça um programa que leia 2 números e mostre a soma deles na tela. Agora mude o programa para fazer outras operações: multiplicar, dividir e subtrair.
* **Conceitos Importantes**: Uso de várias variáveis de entrada.
* **Arquivos**: [Código Scratch](./Atividade-08/pensamento_computacional_exercicio_08.sb3)

---

### 🧩 Atividade 09 - Uso de Listas (Págs. 6 e 7)
* **Enunciado**: Crie uma lista que contenha um número N de elementos fornecidos pelo usuário. Insira na lista os números inteiros de 1 até N e depois faça o gatinho repetir o conteúdo da lista de trás para frente. Ao final, o gatinho deve dizer o tamanho da lista.
* **Questões de Estudo e Modificações**: 
  * Perguntas – Porque é preciso modificar xx ao final do primeiro loop?
  * O que mudaria no programa se ao invés do primeiro loop ser "Repita até XX > LIMITE" estivesse escrito "Repita até XX = LIMITE"?
  * Modifique o segundo loop do programa para o gatinho dizer os elementos do início ao fim.
  * Modifique o programa para inserir números pares, de 2 até 2 * N.
  * Modifique o segundo loop do programa para o gatinho dizer a soma dos elementos da lista (Uso de acumulador de valores).
* **Observação Importante do Material**: Por causa das características da estrutura LISTA, a cada vez que o programa é executado, a lista aumenta. Assim, a cada rodada, primeiro ELIMINE a lista minha-lista (no menu a esquerda) e depois CRIE a lista minha-lista. Assim, o programa sempre vai começar com uma lista vazia. Para acompanhar os valores das variáveis, lembre-se de clicar nas caixinhas correspondentes. O programa final da somatória apresentado está em inglês... Isso faz alguma diferença?
* **Para Casa**: Escreva o fluxograma correspondente ao programa Scratch.
* **Conceitos Importantes**: Inserir elementos ao final da lista; Reusar a variável xx para percorrer a lista do início ao fim e depois, no segundo loop, do fim ao início; Loops de 1 a N e de N a 1; Uso de acumulador de valores; Percorrer a lista usando iteração.
* **Arquivos**: [Código Scratch](./Atividade-09/pensamento_computacional_exercicio_09.sb3) | [Fluxograma](./Atividade-09/fluxograma_exercicio_09.png)
