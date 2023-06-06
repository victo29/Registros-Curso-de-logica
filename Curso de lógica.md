# CURSO DE LÓGICA DE PROGRAMAÇÃO
## Link do vídeo onde foi retirado todo conteúdo 
<https://youtu.be/iF2MdbrTiBM>

-Os exercícios que foram passados na aula não estão aqui, somente na aula para acessá-los 

## Porque um software é criado?
-Para solucionar problemas do dia a dia

-Automação e otimização de processos
 ## Como software é criado do zero e onde a lógica se encaixa nisso?
### Ciclo de Desenvolvimento de software
1-Idealização: Onde se cria a ideia inicial do projeto

2-Especificação de requisitos: documenta o que o software 
deve e o que não deve fazer

3-Validação da solução: Validar se o projeto é realmente o 
que deve ser feito

4-Desenvolvimento e testes

5-Implatação e Entrega

## O problema que todo iniciante enfrenta
### Querer ir direto para o código
### Todos passam por isso:

Normal #1 – Vai escrever código lentamente

Normal #2 – Vai resolver os mesmos problemas em situações diferentes

Normal #3 – Vai se achar incapaz ou insuficiente

Normal #4 – Vai gradualmente conseguir solucionar problemas mais 
facilmente 

## O que são algoritmos e como montar um do zero
### O que são algoritmos?
-Um algoritmo é uma série de instruções a serem seguidas para solucionar um problema
### Quando os algoritmos devem ser criados?
-Sempre que queremos montar uma sequência de passos necessários para solucionar um problema
### MÉTODO 5Q’s para montar um algoritmo :
1-Quais são os dados de entrada necessários?

2-O que devo fazer com estes dados?

3.Quais são as restrições deste problema?

4.Qual é o resultado esperado?

5.Qual a sequência de passos a serem feitas para chegar ao resultado?


## 4 conceitos OBRIGATÓRIOS para ser capaz de resolver problemas!
 1.Variáveis: Guardam informações na memória do computador

2.Condicionais: São representações de questionamentos

3.Laços de repetição: Faz com que ações sejam repetidas por uma certa quantidade de vezes. Possuem um ponto final e um ponto inicial, ou em alguns casos uma condição que irá significar o final daquele laço de repetição

4.Coleções: Coleções de valores que estão armazenados em um local só


## Criando soluções com Pseudocódigo
-O pseudocódigo é uma descrição dos passos necessários para resolver um determinado problema em uma linguagem natural, que não está ligada diretamente a uma linguagem de programação

### Pseudocódigo sintaxe:
-Input: palavra usada para receber dados do usuário

-print: exibir o resultado no console

-if condição: condicional que controla se algo deve ou não ser feito

-else: cláusula a ser executada caso nenhuma condicional if seja executada

-loop de X a Y: laço de repetição que irá iterar de x a y

-loop de X em Y: laço de repetição que irá iterar x em uma coleção y

-while X: laço de repetição que acontecerá enquanto uma condição for verdadeira


## Criando soluções com Fluxogramas
-O fluxograma é uma forma visual gráfica de um fluxograma

 ### Elementos de um fluxograma:
-Linha de Fluxo: indica o fluxo da lógica ao se conectar com os outros símbolos

-Início/Fim: Representa a início ou fim do fluxograma.

-Entrada/saída: Usado para receber entrada ou saída de dados.

-Processamento: Usado para operações matemáticas


## Programas com python
-A partir deste ponto os testes feitos a baixo serão feitos em python

-Os teste foram realizados através do site: https://replit.com/~

-O site permite que você crie um ambiente de programação online, onde você pode escrever e executar código python.
## Variáveis
-É quando se armazena valores na memória do seu computador

-Não devem conter caracteres especiais 

### Tipos de dados que se pode armazenar na memória do computador:
-Números: armazenam números 

Ex: velocidade_Internet = 10

-Valores booleanos: valores de verdadeiro ou falso (True e False)

 Ex: esta_aberto = True

-strings: valores em formato de texto

Ex: nome = “Hello world!”

-float: valores decimais

Ex: nota_de_um_filme  = 8.5



## Laços de repetição
-É uma maneira de executar o mesmo código varias vezes

-A partir dos lações de repetições se pode iterar listas

For palavra in range (1,4)                     
{                                       
Print(“Carrregando”)              
}                                                                                                          


Nomes = [“Victor”, “João”, “Carlos”]

For nome in nomes                                         
{         
Print(nome)                                        
}                     

## Listas
-Para acessar um valor dentro de uma lista deve se utilizar dos indicies que começa sempre do 0

Preços = [10, 20, 30]

-Para acessar o número 10 você teria que utilizar o indicie 0
                                           
Print(preços[0]) 

-Uma lista pode agrupar uma grande diversidade de elementos

Diversidades = [10, 20, 30, “Victor”, True, “Arroz”]

