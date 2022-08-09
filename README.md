# **Looking back - Módulo II**

Neste documento iremos rever todos os topicos abordados no **Módulo II** do curso **"Programação Web Fullstack 2022"** da **CAMPINHO DIGITAL**.

## **1.Logica de programação**

  
  **Logica de programação** é a organização coesa de uma sequencia de instruções voltadas a resolução de um problema, ou a criação de um software ou aplicação. 
 Cada  linguagem  tem  suas  próprias particularidades, como sua sintaxe, seus tipos de dados e sua orientação, mas a lógica por trás de todas é a mesma.


### **Algoritmo**


**Algoritmo** é uma sequencia de instruções ou operações utilizadas para alcançar um objetivo.

### **Estrutura Algoritmo**

- **Completo:** Todas as ações precisam ser descritas e devem ser únicas.

- **Sem redundância:** Um conjunto de instruções só pode ter uma única forma de ser interpretada.

- **Determinísmo:** Se as instruções forem executadas, o resultado esperado será sempre atingido.

- **Finito:** As instruções precisam terminar após um número limitado de passos.

Podemos    dividir    um algoritmo  em  três  fases fundamentais: **entrada,processamento e saída.**

- **Entrada:** Recebe as informações necessárias para iniciar nosso algoritmo.

- **Processamento:** São os procedimentos utilizados para chegarao resultado final.

- **Saída:** É o resultado esperado da fase de processamento, dados já processados.


## **2.Git**

**Git** é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software para registrar o histórico de edições dos arquivos. Com  o  **Git**  podemos  desenvolver  projetos  colaborativos,  com  diversas pessoas trabalhando simultaneamente no mesmo código sem riscos de perdermos o que fizemos. O **Git** guarda um histórico de tudo que foi alterado nos arquivos ao longo do tempo, além de mostrar quem foi o autor da mudança.

## **Terminal - Comandos básicos**

- **ls (macOS/Linux)/dir (Windows):** Lista todos os arquivos presentes no diretório atual.
- **mkdir nome-da-pasta:** Cria uma nova pasta.
- **cd nome-da-pasta:** Navega para a pasta especificada (exemplo: cd documentos)
- **cd ..:** Sobe um nível de pasta.
- **touch nome-do-arquivo/dir > nome-do-arquivo:** Cria um novo arquivo.
- **clear:** Limpa todas as informações do terminal.
- **<nome do programa> --version:** Exibe versão instalada.

## **Git - comandos básicos**

- **git init:** Inicializa o git no repositório local.
- **git add nome-do-arquivo ou .:** Adiciona um arquivo modificado ao stagging (área temporária).
- **git status:** Mostra os status dos arquivos modificados.
- **git commit -m "mensagem":** Cria um commit.
- **git pull:** Puxa as atualizações mais recente (remoto -> local).
- **git push:** Envia as atualizações mais recentes (local -> remoto).
- **git remote add origin <caminho>:** Adiciona o seu repositório local ao remoto.
- **git checkout -- <nome-arquivo>:** Descarta as alterações locais do arquivo informado.



## **3.GitHub**

**GitHub** é uma plataforma de hospedagem de código-fonte com controle de versão usando o **Git**. **GitHub** é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com o projeto.

## **4.Estrutura e operadores**

Em ciência da computação, **estrutura de controle** (ou fluxo de controle) refere-se à ordem em que instruções, expressões e chamadas de função são executadas ou avaliadas em programas de computador sob programação imperativa ou funcional.

Os tipos de **estruturas de controle** disponíveis diferem de linguagem para linguagem, mas podem ser cruamente caracterizados por seus efeitos. O primeiro é a continuação da execução em uma outra instrução, como na **estrutura sequencial** ou em uma instrução jump. O segundo é a execução de um bloco de código somente se uma condição é verdadeira, uma **estrutura de seleção**. O terceiro é a execução de um bloco de código enquanto uma condição é verdadeira, ou de forma a iterar uma coleção de dados, uma **estrutura de repetição**.

### **Estrutura sequencial**

Uma **estrutura sequencial** realiza um conjunto predeterminado de comandos de forma sequencial, na ordem em que foram declarados no código fonte. A cada instrução, o contador de programa é incrementado.

### **Estrutura de seleção**

Também chamada de **expressão condicional** ou ainda **construção condicional**, a estrutura de seleção realiza diferentes computações ou ações dependendo se a seleção (ou condição) é **verdadeira** ou **falsa**. A condição é uma expressão processada e transformada em um valor **booleano**.

### **Estrutura de repetição**

Uma **estrutura de repetição** realiza e repete diferentes computações ou ações dependendo se uma condição é **verdadeira** ou **falsa**, condição essa que é um expressão processada e transformada em um valor **booleano**. Está associado a ela além da condição (também chamada **"expressão de controle"** ou **"condição de parada"**) o bloco de código: verifica-se a condição, e caso seja **verdadeira**, o bloco é executado. Após o final da execução do bloco, a condição é verificada novamente, e caso ela ainda seja **verdadeira**, o código é executado novamente.

Deve-se observar que, caso o bloco de código nunca modificar o estado da condição, a estrutura será **executada para sempre**, uma situação chamada **laço infinito**. Da mesma forma, é possível especificar uma estrutura em que o bloco de código modifica o estado da condição, mas esta é sempre verdadeira.



## **OPERADOR LÓGICO**
É um elemento de ligação das palavras que compõem um comando
de pesquisa. É o operador lógico que indica para o sistema a maneira como se quer que uma palavra esteja em relação à outra dentro do documento, para que esse documento seja recuperado. Há três operações lógicas principais envolvidas na função de pesquisa que são representadas pelos operadores **AND, NOT e OR.** 

### **1. Operador E (AND)**

O Operador **“E”** ou **“AND”** resulta em um valor **VERDADEIRO** se os dois valores de entrada da operação forem **VERDADEIROS**, caso contrário o resultado é **FALSO**. Abaixo a tabela-verdade da operação **E**.


VALOR 1    |VALOR 2     |OPERAÇÃO E
------     |-------     |-------
VERDADEIRO |VERDADEIRO  |VERDADEIRO
VERDADEIRO |FALSO       |FALSO
FALSO	   |VERDADEIRO	|FALSO
FALSO	   |FALSO	    |FALSO


### **2. Operador OU (OR)**

O Operador **“OU” ou “OR”** resulta em um valor **VERDADEIRO** se ao menos **UM** dos dois valores de entrada da operação for **VERDADEIRO**, caso contrário o resultado é **FALSO**. Abaixo a tabela-verdade da operação **OU**.


VALOR 1	   |VALOR 2    |OPERAÇÃO OU
------     | ------    | ------ 
VERDADEIRO |VERDADEIRO |VERDADEIRO
VERDADEIRO |FALSO  |VERDADEIRO
FALSO      |VERDADEIRO |VERDADEIRO
FALSO	   |FALSO      |FALSO


### **3. Operador NÃO (NOT)**

O Operador **“NÃO”** ou **“NOT”** é o único operador que recebe como entrada apenas um valor, e sua função é simplesmente inverter os valores. Ou seja, se o valor de entrada for **VERDADEIRO**, o resultado será **FALSO** e se o valor de entrada for **FALSO**, o resultado será **VERDADEIRO**. Abaixo a tabela-verdade da operação **NÃO**.

VALOR DE ENTRADA |OPERAÇÃO NÃO
------           | ------
VERDADEIRO       |FALSO
FALSO	         |VERDADEIRO


## **5.Variaveis**

As **variáveis** são estruturas importantes em qualquer programação, independentemente da linguagem que se utilize para implementar os códigos ou programas. Elas podem ser entendidas como uma caixinha, onde os dados são armazenados temporariamente ou em definitivo e que são manipuladas durante a execução do programa.

Para fazer um bom uso de variáveis de programação é crucial compreender quais são os tipos. Confira a seguir os principais!

**1. int:**
As variáveis **int** são utilizadas para definirem números inteiros. Eles podem ser positivos ou negativos. Porém, não podem incluir números com duas casas decimais.

**2. float:**
As variáveis do tipo **float** são utilizadas para armazenar números reais. Elas são empregadas em operações simples que contenham números com duas casas decimais. O armazenamento dos dados ocorre com precisão simples.

**3. double:**
As variáveis do tipo **double** são semelhantes às variáveis **float**. Elas permitem o armazenamento de números reais, ou seja, com ponto flutuante, mas com precisão dupla. Isso dá às variáveis double o dobro da capacidade das variáveis float.

**4. char:**
Esse tipo de variável é utilizado para armazenar um único caractere (como uma letra). Nesse caso, as variáveis desse tipo não podem ser utilizadas em operações de soma, subtração, divisão ou multiplicação. Afinal, o software interpretará o conteúdo como se ele fosse uma letra.

**5. string:**
As **strings** são variáveis utilizadas para o armazenamento de faixas de texto. 
Por ser uma variável para texto, as strings não podem ser adotadas em operações matemáticas. Mas elas são úteis para exibir mensagens para os usuários, armazenar nomes e outros tipos de registros importantes.

**6. boolean:**
As variáveis do tipo **boolean**, ou apenas **booleanas**, são implementadas com um único objetivo: adotar valores de verdadeiro ou falso. Isso permite ao software validar registros, definir quais passos tomar após uma ação do usuário, ou automatizar processos.



## **6.Introdução a Javascript**

**JavaScript** é uma linguagem de programação que permite a você implementar itens complexos em páginas web. — toda vez que uma página da web faz mais do que simplesmente mostrar a você informação estática — mostrando conteúdo que se atualiza em um intervalo de tempo, mapas interativos ou gráficos 2D/3D animados, etc. — você pode apostar que o **JavaScript** provavelmente está envolvido.
## **7.NodeJs**

O **Node.js** pode ser definido como um ambiente de execução Javascript server-side. Isso significa que com o Node.js é possível criar aplicações Javascript para rodar como uma aplicação standalone em uma máquina, não dependendo de um browser.

Ao discutir o **Node.js**, uma coisa que definitivamente não deve ser omitida é o suporte interno ao gerenciamento de pacotes usando o **NPM**, uma ferramenta que vem por padrão a cada instalação do Node.js. 


## **8. Logica Aplicada**

**Comparadores logicos**

### **IF/ELSE**

A condicional **if** é uma estrutura condicional que executa a afirmação, dentro do bloco, se determinada condição for verdadeira. Se for falsa, executa as afirmações dentro de **else**.

### **Estrutura do IF/ELSE**
~~~javascript
if(condição){
    Bloco de Código1
}
else{
    Bloco de Código2
}
~~~

**1. Condição:** Expressão que pode ser avaliada como ***true*** ou ***false***.

**2. Bloco de Código1:** Código executado quando a condição for determinada como ***true***.

**3. Bloco de Códigos2:** Código executado quando a condição for determinado como ***false***.

~~~javascript
let senha = "123456"
if(nome == "senha"){
    console.log("ACESSO PERMITIDO")
}
else{
    console.log("SENHA INCORRETA, ACESSO NEGADO!")
}
~~~

**SWITCH CASE**

O **Switch Case** é outra maneira de trabalharmos com condições a partir de uma expressão aonde há uma melhor legibilidade do código.

~~~javascript
switch(dias){
    case 1:
        console.log("Domingo")
        break;
    case 2:
        console.log("Segunda")
        break;
    case 3:
        console.log("Terça")
        break;
    case 4:
        console.log("Quarta")
        break;
    case 5:
        console.log("Quinta")
        break;
    case 6:
        console.log("Sexta")
        break;
    case 7:
        console.log("Sabado")
        break;
}
~~~

## **9. Condicional Avançado**

**Atribuição Booleana →** Atribuir **true** ou **false** para uma variável através de uma expressão lógica.

~~~javascript
Let Questao = "Certo"
Let Verdadeiro = Questao == "Certo" // Será atribuido um valor true
Let Falso = Questão == "Falso" // Será atribuido um valor false
~~~

**Operadores  Ternários →**  Expressão lógica que retorna **true** ou **false**, representada através de **?** e **:**

~~~javascript
Let Verdadeiro = true
Let Questão = Verdadeiro ? "Certo" : "Errado" // Será atribuido a variavel "Questão" o valor "Certo"
~~~

## **10. WHILE**

O loop **WHILE** é uma estrutura de repetição e contém  uma  expressão **booleana** com  uma  condição  que  retornará **verdadeiro** ou **falso**. Ele executa o  bloco de código, desde que a expressão condicional especificada seja devolvida.

### **Estrutura do WHILE**

A estrutura do **WHILE** é dividida em duas partes:
~~~javascript
while(condição){
    Bloco de códigos
}
~~~

**1. Condição:** Uma expressão executada depois de cada passagem do loop. Se essa condição for **verdadeira**, o **Bloco de códigos** é executado. Quando a condição for **falsa**, o loop é encerrado e o código depois do loop continua sendo executado.

**2. Bloco de códigos:** Código executado enquanto a condição do loop for **verdadeira**.

~~~javascript
Let numero = 0
while(numero<5){
    numero++
}
       // Exemplo de While
~~~

## **11. FOR**

O loop **FOR** é um comando que tem comportamento igual ao **while**, porém ele permite expressar contadores como parte do comando e não como lógica separada.

### **Estrutura do FOR**

A estrutura do **FOR** é dividida em três partes:

~~~javascript
for("primeiro Parte";"Segundo Parte";"Terceiro Parte"){}
~~~

**1. Primeira Parte:** Executa uma única vez antes de rodar o bloco de códigos.

**2. Segunda Parte:** Condição para a execução do bloco de códigos.

**3. Terceira Parte:** É executado toda vez que o bloco de códigos é executado.

~~~javascript
Let numero = "5"
for(i=0; i<numero; i++){}
       
       // Exemplo de FOR
~~~

## **12. String**

Uma **string**  nada  mais  é  que  uma lista  de caracteres,  no  qual  cada  elemento  da  lista  é representado por um caractere.

~~~javascript
    Let String = " Minha String "
    Console.log(String)

       // Exemplo de String
~~~

### **Concatenação de Strings**

A **concatenação de strings** é juntar duas strings um após o final da outro. Essas operações podem ser feitas utilizando o **+**.

~~~javascript
    Let Primeira_String = " Leonardo "
    Let Segunda_String = " Lima "
    Let String_Resultado = Primeira_String + " " + Segunda_String
    Console.log("Meu nome é: ",String_Resultado)

       // Exemplo de Concatenação de Strings
~~~       

### **Interpolação de Strings**

A  **interpolação de Strings** é uma maneira de criar strings com variáveis diferentes. Ela utiliza  `` e identifica as variáveis com : **${NOME_VARIAVEL}**

~~~javascript
    Let nome = " Leonardo "
    Let string = ` O meu nome é ${nome} `
    Console.log(string)

       // Exemplo de Interpolação de Strings
~~~

### **Principais Códigos de String**

- **string.length:** Permite saber quantos caracteres a **string** possui.
- **string.charAt(posição):** Retorna o caractere para a **posição** informada. Lembrando que a primeira posição começa com **0**.
- **string.slice(inicio,fim):** Retorna as letras a partir de um **inicio** e **fim**.
- **string.toLowerCase() e string.toUpperCase():** Diminui ou aumenta a caixa de texto(LETRAS MAIUSCULAS e letras minusculas).
- **trim():** Remove espaços brancos no começo ou fim de texto.
- **includes():** Permite saber se a **string** contém um certo texto.
- **indexOf(palavra):** Retorna o índice no qual uma **palavra** é encontrada em uma string.
- **split/tokenize():** Permite separara a **string** em um **array** de caractere.

## **13. Array**

Os ***arrays*** são a estrutura de dados mais básica da programação. Um array é  uma variável que possui uma coleção de valoresar armazenados em sequência. Em javascript, os arrays podem guardar valores de diferentes tipos.

    
~~~javascript
Let carro = ["honda","ford","fiat","chevrolet"]
Console.log(carro)

      // Exemplo de Arrays com marcas de carros como variaveis
~~~

### **Principais Códigos de Array**

- **array.push(variavel):** Adiciona o elemento "variavel" no final da **array**.
- **array.pop:** Remove o último elemento do **array**.
- **array.shift:** Remove o primeiro elemento do **array**.
- **array[indice]:** Retorna o elemento pelo **índice** informado.
- **array.length:** Retorna a quantidade de elementos do **array**.
- **array.splice(indice,quantidade):** Permite adicionar ou remover elementos informando o **índice** e **quantidade**.
- **array.concat(array2):** Permite concatenar dois arrays em um só, sequenciamente.
- **array.join(separador):** Exibe uma **string** concatenando todos os de um **array**, unidos por um **separador** determinado.