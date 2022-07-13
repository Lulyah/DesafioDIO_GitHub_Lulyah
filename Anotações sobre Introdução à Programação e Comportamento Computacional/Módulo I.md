# **Parte I: Pensamento computacional**

4 Pilares do comportamento computacional

- Decomposição
- Reconhecimento de padrões
- Abstração = extrapola para uma     forma generalista
- Design de algoritmos 

*Não necessariamente se usará todos de uma vez, podendo ser utilizados um ou outro apenas...*

**Raciocínio Lógico**

1. Indução
2. Dedução
3. Abdução 

**Padrões** 

- Aplicações

A) Classificação de dados: detectar anomalias dentro da rede, quando o padrão se extrapola

B) Reconhecimento de imagens: placa de carro

C) Reconhecimento de fala: qual idioma está sendo falado pela pessoa

D) Análise de cenas: **

E) Classificação de documentos: eletrônico ou físico

**Desenvolvimento do Programa**

- Análise: estudo e definição dos     dados de entrada e saída
- Algoritmo: descreve o problema     por meio de ferramentas narrativas, fluxograma ou pseudocódigo
- Codificação: quando você     utilizar de alguma linguagem de programação para poder codificar aquele     algoritmo

**Como construir um algoritmo**

- Compreender o problema;
- Definir os dados de entrada;
- Definir o processamento: quais     operações serão realizadas?
- Definir dados de saída;
- Utilizar um método de     construção;
- Teste e diagnóstico.

**Construção de algoritmos**

- Narrativa: utiliza linguagem     natural / diversas interpretações possíveis;
- Fluxograma: utilização de     símbolos pré-definidos / estrutura gráfica / que ação está sendo executada     / conhecimento prévio dos símbolos
- Pseudocódigo: portugol /     conjunto de regras definidas / passos a serem seguidos

# **Parte II: Introdução à Lógica de Programação**

*O que é Lógica?*

Uma forma de pensamento estrutura que auxilia a encontrar o verdadeiro ou não dentro de um contexto, ou seja, auxilia na resolução de problemas.

**Técnicas de Lógica de Programação**

- Linear : modelo de     desenvolvimento e resolução de problemas / muito envolvida na matemática /     ordenação de elementos por uma única propriedade. 
- Estruturada: organização,     disposição e ordem dos elementos essenciais que compõem um corpo, sendo     concreto ou abstrato. Coloca-se um pouco mais de complexidade, mas     acarreta muitas vantagens.
- Modular: temos partes independentes que são controladas por um conjunto de regras / cada módulo tem seu conjunto de regras específicos. 

# Parte III: linguagens de programação

*Características de um programa*

**Desenvolvimento de programas**

1. Legibilidade; - boa leitura //     estado que é legível
2. Redigibilidade; - faça o que se     comprometa a fazer // 
3. Confiabilidade; - seja     confiável // verifição de tipos; trata de exceções; uso de ponteiros;     compatibilidade entre compiladores
4. Custo - baixo valor de produção

 **Análise de códigos** 

*Compilador*

1º Lexical analyzer ou Scanner (leitura do programa fonte letra por letra 

- Particionar - identificar os     elementos (tokens) e agrupá-los. 
- Classificar - Os Elementos são:     identificadores; palavras reservadas; números e strings. 
- Eliminar - Vai eliminar:     caracteres, espaços em branco, comentários

2º Syntax analyzer

- A forma que o programa define     através de palavras reservadas ou indexação qual a estrutura relacionada     para codificação dentro daquela linguagem específica.

3º Semantic analyzer

- Está relacionado ao significado     // o significado dos sinais ou símbolos

**Paradigamas de programação**

"Trata-se da forma de resolução de problemas com diretrizes e limitações específicas de cada paradigma utilizando linguagem de programação".

Possui regra pra resolver o problema // limitado para um conceito específico

_Alguns paradigmas_

- Orientação à objeto -
- Procedural - chamadas     sucessivas e procedimentos separados // ideia de sequência
- Funcional - instruções baseadas     em funções
- Estruturado - estrutura de     blocos alinhados
- Computação distribuída -     funções executadas de forma independente // blocos que funcionem     independentes no cluster 

**Paradigma do Estruturado [C]**

_Conceitos_

- Sequência ; decisão ; interação
- Aprendizagem

_Utilizar_

- Problemas simples e diretos
- Aprender a programar
- POO ainda não é compreendido     por muitos

**_Exemplo em C_**

Function fatorial(x){

​     if (x> 1){

​        return x*fatorial(x-1);

​     }

}

**Paradigma Orientada à Objeto**

- Análogo ao mundo real
- Um objeto possui atributo,     comportamento e estado

**Pilares de Orientação a Objeto**

- Herança -
- Encapsulamento -
- Polimorfismo - 
- Abstração -

**Código SOMA_INTERVALO**

Programa {

funcao inicio() {

  inteiro x, y

  escreva("Digite os números para encontrar a soma do intervalo ")

  leia(x)

  leia(y)

  escreva(soma_intervalo(x,y))

} 

funcao inteiro soma_intervalo(inteiro x, inteiro y){

  inteiro total, resultado_parcial

  total = y/2

  resultado_parcial = y+x

  inteiro resultado = total * resultado_parcial

  retorne resultado

​       }

}

