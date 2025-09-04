

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=150&color=0:16A085,100:2980B9&text=Lógica%20de%20Algoritmos&animation=scaleIn&fontColor=FFFFFF&fontSize=50">
</p>

<br>

__📌 O que é um Algoritmo?__  
&nbsp;&nbsp;&nbsp;Um algoritmo é uma sequência **ordenada**, **finita** e **bem definida** de instruções, criada para resolver um problema ou realizar uma tarefa específica.

<br>

__🧠 Exemplo:__

Mover todas as pessoas do lado esquerdo para o lado direito, obedecendo às seguintes regras:
- A canoa suporta no __máximo 130 kg__ por viagem.
- A canoa exige ao menos __uma pessoa a bordo para atravessar__.

<p align="center">
  <img width="650" src="./.imgs/ExemploCanoa.png">
</p>

__Resposta:__ (_Seguindo a sequência de ações:_)

1. __Pessoa A__ e __Pessoa B__ atravessam juntos para o __lado direito__ com a canoa.
2. __Pessoa A__ retorna sozinha para o __lado esquerdo__ com a canoa.
3. __Pessoa A__ e __Pessoa C__ atravessam juntos para o __lado direito__ com a canoa.

<br>

> [!TIP]
> __📌 Dica:__ Muitos problemas podem ser resolvidos de várias formas corretas.  
> Abaixo, uma **solução alternativa** para o problema proposto:
> 
> 1. __Pessoa A__ e __Pessoa B__ atravessam juntos para o __lado direito__ com a canoa.  
> 2. __Pessoa B__ retorna sozinha para o __lado esquerdo__ com a canoa.  
> 3. __Pessoa B__ e __Pessoa C__ atravessam juntos para o __lado direito__ com a canoa.

<br>

__Etapas da construção de um algoritmo:__

- __🔍 <ins>Identificação do problema</ins>__: Entender claramente o que precisa ser resolvido.<br><br>
- __📥 <ins>Definição das entradas</ins>__: Informações que o algoritmo receberá para trabalhar.<br><br>
- __📤 <ins>Definição das saídas</ins>__: Informações que o algoritmo deverá produzir.<br><br>
- __🧭 <ins>Determinação dos passos</ins>__: Estabelecer a sequência lógica de ações que transformarão as entradas nas saídas desejadas.<br><br>
- __🧠 <ins>Construção do algoritmo</ins>__: Representar os passos definidos usando uma linguagem ou notação apropriada (como pseudocódigo ou fluxograma).<br><br>
- __🧪 <ins>Teste e validação</ins>__: Simular ou executar o algoritmo manualmente para verificar se ele funciona corretamente e sem erros.<br><br>

<hr>

<h3>🤖 Linguagens de Programação</h3>

&nbsp;&nbsp;&nbsp;Uma linguagem de programação é um __sistema de comunicação__ entre humanos e computadores.
Ela permite que você escreva __instruções__ que o computador consegue __entender e executar__.

__🧠Pense assim:__

1. Você quer que o computador __faça algo.__
2. Você escreve o que ele deve fazer __usando uma linguagem de programação__<br>
   &nbsp;&nbsp;__🧠 Exemplo:__
   - 🐍 Python
   - ☕ Java
   - ⚙️ C++
3. O computador __interpreta__ ou __compila__ essas instruções e executa as ações.

> [!IMPORTANT]
> __📌 Importante:__ Cada linguagem tem suas __forças e usos específicos__, mas algumas são muito __versáteis__ e podem ser usadas em vários contextos.

__💻 Alguns conceitos de linguagens de programação:__

- __🔤 <ins>Sintaxe</ins>:__ Regras que definem como escrever corretamente o código, parecido com a gramática de um idioma.<br>
  __🧠 Exemplo Portugol:__
  ```portugol
  escreva("Olá")
  escreva "Olá"
  ```
  📌 O conceito de sintaxe é como perguntar:<br>
  _"O código está escrito da forma correta, seguindo as regras da linguagem?"_

  No segundo exemplo, os parênteses `()` foram esquecidos. Isso quebra a sintaxe exigida pela linguagem Portugol e causa um erro de sintaxe — ou seja, o programa não consegue entender o comando.<br><br>
  
- __🔍 <ins>Semântica</ins>:__ O significado das instruções no código — o que realmente acontece quando o código roda.<br>
  __🧠 Exemplo Portugol:__
  ```portugol
  escreva("Oi!"+"John")
  ```
  📌 Mesmo que a sintaxe esteja correta, você pode se perguntar:<br>
  _"Esse código está fazendo o que eu quero?"_

  - Talvez a intenção fosse mostrar: `Oi! John`.
  - Mas o programa exibirá: `Oi!John`.
  
  A __sintaxe está certa__, mas o significado (a __semântica__) não está como esperado — faltou um espaço entre o ponto de exclamação e o nome.<br><br>
  
- 🛠️ __<ins>Compilação e Interpretação</ins>:__

  - __Compilação:__ Tradução do código para linguagem de máquina antes da execução (mais rápida).

    - É como se pegasse um livro inteiro, traduzisse tudo de uma vez, e entregasse a informação pronta.

  - __Interpretação:__ Execução do código linha por linha, durante o tempo de execução (mais lenta).

    - É como se traduzisse página por página do livro e fosse entregando a informação conforme lê.<br><br>

<hr>

<h3>💼 Técnicas e Boas práticas:</h3>

__🛠️ Técnicas:__<br>
Técnicas são métodos específicos para resolver problemas ou implementar funcionalidades de forma eficiente. Elas são mais voltadas à execução prática do código.<br>
&nbsp;&nbsp;<ins>__Algumas delas são:__</ins>

- __🎯 Foco:__ Manter a concentração durante o desenvolvimento para reduzir erros e aumentar a produtividade.<br><br>
- __🧠 Lógica:__ Capacidade de raciocinar de forma estruturada para resolver problemas computacionais.<br><br>
- __📋 Algoritmo:__ Sequência de passos bem definidos para resolver uma tarefa ou problema específico.<br><br>
  - __⬇️ Entrada:__ Quais dados o algoritmo vai receber?<br><br>
  - __⚙️ Processamento:__ O que ele vai fazer com esses dados? Como eles serão transformados?<br><br>
  - __📤 Saída:__ Qual será o resultado do processamento? Quais informações o algoritmo irá entregar?

**👍 Boas práticas:** Boas práticas são hábitos, comportamentos ou padrões recomendados que ajudam a garantir um código limpo, legível, seguro e fácil de manter. Elas nem sempre são obrigatórias, mas podem evitar muitos problemas no futuro.<br>
&nbsp;&nbsp;<ins>__Algumas delas são:__</ins>

- __🚀 MVP (Produto Mínimo Viável):__ Construa o essencial primeiro. Comece pequeno, valide a ideia, e depois evolua ela aos poucos.<br><br>
- __📝 Documentação:__ Descreva como o sistema funciona, como instalar, rodar e entender partes importantes do código. Ajuda outros desenvolvedores (_e você no futuro_).<br><br>
- __📐 Identação:__ Mantenha o código bem alinhado e estruturado visualmente. Facilita a leitura e evita erros em linguagens sensíveis à indentação (_como Python_).

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=60&color=0:16A085,100:2980B9&text=Representação%20e%20armazenamentos%20de%20dados&fontSize=25&fontAlignY=53&fontColor=FFFFFF">
</p>

&nbsp;&nbsp;&nbsp;Na concepção de algoritmos, devemos considerar que a memória consiste em um __conjunto de posições__ ( _endereços_ ), onde cada posição recebe uma __identificação__ ( _nome_ ) e __armazena um determinado valor.__

> [!NOTE]
> __📌 Nota:__ O valor de um identificador pode ser atribuído por meio do operador `=`.

__🧠 Exemplo:__

<table>
  <tr>
    <th>Identificador</th>
    <th>Operador de<br>Atribuição</th>
    <th>Valor</th>
  </tr>
  <tr>
    <td align="center">Idade</td>
    <td align="center"><code>=</code></td>
    <td align="center">18</td>
  </tr>
  <tr>
    <td align="center">Nome</td>
    <td align="center"><code>=</code></td>
    <td align="center">"Gabriel"</td>
  </tr>
  <tr>
    <td align="center">Altura</td>
    <td align="center"><code>=</code></td>
    <td align="center">1.80</td>
  </tr>
</table>

Um __identificador__ pode ser __classificado__ como:

- __🔁 <ins>Variável</ins>__ : quando seu valor pode ser modificado durante a execução do programa.

  __🧠 Exemplo Pseudocódigo:__
  ```txt
  idade = 18
  idade = 19
  ```
  Aqui, o valor `18` é __descartado__, e agora a variável `idade` guarda `19`.


- __🔒 <ins>Constante</ins>__ : Quando o valor é atribuído, __ele não pode mais ser alterado.__

  __🧠 Exemplo Pseudocódigo:__
  ```txt
  const nome = "João"
  nome = "Pedro" ❌ Error
  ```
  Aqui, o valor `"João"` __não pode ser alterado__, e a tentativa de mudar o valor de `nome` para `"Pedro"` irá causar um __erro.__

> [!IMPORTANT]
> __📌 Importante:__ Em algumas linguagens, o valor de uma __constante__ precisa ser atribuído no momento em que ela é declarada.

<hr>

<h3>Regra de nomeação dos indentificadores:</h3>

O nome de um identificador serve para nomear algo no código, e permitir que esse valor seja acessado, modificado ou reutilizado.<br>
__📌 Por exemplo, ao escrever:__
```txt
numero = 20
```
Você está dizendo que o identificador chamado `numero` guarda o valor `20`. Sempre que você usar `numero` no código, o algoritmo saberá que está se referindo ao valor `20`.

__📌 Existem algumas regras importantes ao nomear um identificador:__
<table>
  <tr>
    <th>Regra</th>
    <th>Explicação</th>
    <th>❌ Exemplos errados</th>
    <th>✅ Exemplos corretos</th>
  </tr>
  <tr>
    <td><strong>Não</strong> pode conter <strong>caracteres especiais</strong></td>
    <td>Um identificador só pode conter letras <code>a-z</code>, <code>A-Z</code>, números <code>0-9</code> e underline <code>_</code>. Caracteres especiais como <code>%</code>, <code>@</code> ou espaços não são permitidos.</td>
    <td>
      <ul>
        <li><code>Valor50%</code></li>
        <li><code>@Email</code></li>
        <li><code>Aniversário Data</code></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><code>Valor50</code></li>
        <li><code>_Email</code></li>
        <li><code>Aniversario_Data</code></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><strong>Não</strong> pode <strong>começar com números</strong></td>
    <td>Identificadores devem começar com uma letra (<code>a-z</code>, <code>A-Z</code>) ou um underline (<code>_</code>). Não podem começar com dígitos.</td>
    <td>
      <ul>
        <li><code>10Pessoas</code></li>
        <li><code>1numero</code></li>
      </ul>
    </td>
    <td>
      <ul>
        <li><code>_10Pessoas</code></li>
        <li><code>numero1</code></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><strong>Não</strong> pode conter <strong>palavras reservadas</strong></td>
    <td>Palavras-chave da linguagem (como <code>if</code>, <code>for</code>, <code>while</code>, etc.) são reservadas e não podem ser usadas como identificadores.</td>
    <td>
        <ul>
          <li><code>for</code></li>
          <li><code>class</code></li>
        </ul>
    </td>
    <td>
        <ul>
          <li><code>forLoop</code></li>
          <li><code>minhaClasse</code></li>
        </ul>
    </td>
  </tr>
</table>

> [!IMPORTANT]
> 📌 **Importante:**  
> Ao criar o nome de um identificador, fique atento às letras **maiúsculas** e **minúsculas**. O nome `Ano` e `ano` são **diferentes**.

> [!TIP]
> 📌 __Dica de boas práticas:__
> Sempre que for criar o nome de uma variável, tente deixá-lo o mais __autoexplicativo__ possível.
> 
> **Exemplo:**  
> Em vez de usar `L_atual`, prefira `local_atual` — _assim, quem lê o código entende facilmente o que aquele valor representa._

<hr>

<h3>📚 Tipos de valores</h3>

- 🔢 Valores numéricos<br>
Representam quantidades ou medidas.

  - __Inteiro__ (`int`): números sem casas decimais.<br>
    🧠 Exemplos: `5`, `-3`, `0` e `2025`

  - __Real__ (`float`/`double`): números sem casas decimais.<br>
    🧠 Exemplos: `2.5`, `-1.2`, `-0.333` e `4932.0`

> [!NOTE]
> __📌 Nota:__ Em algumas linguagens, existe apenas o tipo `float`.<br>
> Porém, nas linguagens que também oferecem o tipo `double`, ele é usado quando se deseja mais precisão e maior alcance numérico.
> | Característica | `float`           | `double`          |
> | -------------- | ----------------- | ----------------- |
> | Tamanho        | 32 bits (4 bytes) | 64 bits (8 bytes) |
> | Precisão       | \~7 dígitos       | \~15 dígitos      |
> | Uso comum      | Cálculos simples  | Cálculos precisos |

- 🎭 Valores lógicos<br>
Representam condições de __verdadeiro__ ou __falso.__

  - __Booleano__ (`bool`): assume apenas dois valores: `verdadeiro`/`true` ou `falso`/`false`.<br>
    🧠 Exemplos: `maior_de_idade = true` e `tem_carteira = false`

  - __Inteiro__ (`0` ou `1`): em algumas linguagens, o valor lógico pode ser representado por números (`0` = `falso`, `1` = `verdadeiro`).<br>
    🧠 Exemplos: `maior_de_idade = 1` e `tem_carteira = 0`

- 🔤 Valores de texto<br>
Representam letras, símbolos ou frases.

  - __Caractere__ (`char`): representa um único símbolo ou letra.<br>
    🧠 Exemplos: `'A'`, `'2'` e `'%'`

  - __Cadeia de caracteres / String__ (`string`): representa um conjunto de caracteres, ou seja, um texto.<br>
    🧠 Exemplos: `"Olá Mundo!"`, `"Luiz"` e `"P3dr_0"`


> [!IMPORTANT]
> __📌 Importante:__ Em algumas linguagens, existe uma diferença importante entre usar aspas simples `'` e aspas duplas `"`:
> - __Aspas simples `'`__ → Representam um caractere único (ex: `'A'`)
> - __Aspas duplas &nbsp;`"`__ → Representam uma string (uma sequência de caracteres, ex: `"Ana"`)

> [!NOTE]
> __📌 Nota:__ Alguns caracteres, especialmente os presentes na tabela __ASCII__, ocupam __1 byte__ de armazenamento.<br>
> No entanto, caracteres especiais — como letras acentuadas (ex: `'á'`, `'ê'`, `'ç'`) — que fazem parte da tabela __UTF-8__, podem ocupar __2 bytes ou mais__, dependendo do símbolo.
>
> __🧠 Exemplos:__<br>
> | Caractere | Código ASCII (Decimal) | UTF-8 (Hexadecimal) | Bytes |
> | --------- | ---------------------- | ------------------- | ----- |
> | `A`       | 65                     | `41`                | __1__ |
> | `@`       | 64                     | `40`                | __1__ |
> | `Ç`       | ❌ Não existe          | `C3 A1`            | __2__ |
> | `漢`      | ❌ Não existe          | `E6 BC A2`         | __3__ |
> | `🙂`      | ❌ Não existe          | `F0 9F 99 82`      | __4__ |

<hr>

<h3>🧩 Carcteres de escape</h3>

Caracteres de escape são __símbolos especiais__ usados dentro de strings para representar ações ou caracteres que __não podem ser digitados diretamente__ ou que têm funções especiais, como pular uma linha, adicionar tabulação, inserir aspas dentro do texto, entre outros.

Eles sempre começam com uma barra invertida `\`, seguida por __um ou mais caracteres.__

__🧠 Exemplos:__

| Caractere | Função                                                                                                    | Exemplo         | Saída              |
| --------- | --------------------------------------------------------------------------------------------------------- | --------------- | ------------------ |
| `\a`      | __Alerta sonoro__ (_bip_) Em muitos sistemas modernos,<br> esse som pode __não ser reproduzido__          | `"Bomdia\a"`    | O texto com o beep |
| `\n`      | __Nova linha__ (_quebra de linha_)                                                                        | `"Bom\nDia"`    | `Bom`<br>`Dia`     |
| `\t`      | __Tabulação__ (_espaço extra_)                                                                            | `"Bom\tDia"`    | `Bom   dia`        |
| `\b`      | __Backspace__ (_Apaga o anterior_)                                                                        | `"Bon\bm"`      | `Bom`              |
| `\\`      | __Barra invertida__ `\` dentro da string                                                                  | `"Bom\\dia"`    | `bom\dia`          |
| `\"`      | __Aspas duplas__ `"` dentro da string delimitada por aspas duplas                                         | `"\"Bom\" dia"` | `"Bom" dia`        |
| `\'`      | __Aspas simples__ `'` dentro da string delimitada por aspas simples                                       | `'Bom \'dia\''` | `Bom 'dia'`        |


<hr>

<h3>📌 Quais os conceitos de tipagem Tipagem?</h3>

__Tipagem__ é o __conjunto de regras__ que uma linguagem de programação usa para __trabalhar com tipos de dados.__
Ou seja, ela define como os valores (números, textos, booleanos, listas, etc.) são interpretados, usados e combinados dentro de um programa.

<h4>Tipagem Explícita vs Implícita </h4>

- __✍️ <ins>Tipagem explícita</ins>:__
  É preciso __declara o tipo da variável manualmente na hora de criar ela.__ Muito comum em linguagens compiladas e mais “rígidas”.<br>
  __🧠 Exemplo:__

  ```txt
  int X = 10
  string Y = "Olá"
  ```
  Aqui, o tipo de cada variável (`int` e `str`) foi definido explicitamente.

- __🕵️‍♂️ <ins>Tipagem implícita</ins>:__
  __Não é necessário declarar o tipo da variável__ — a linguagem deduz automaticamente com base no valor atribuído.<br>
  __🧠 Exemplo:__

  ```txt
  X = 10
  Y = 'G'
  ```
  Aqui, `X` é identificado como `int` e `Y` como `str`, sem precisar declarar os tipos.
  
<h4>Tipagem Estática vs Dinâmica</h4>

- __🔄 <ins>Tipagem dinâmica</ins>:__
  Tipagem dinâmica é quando o tipo da variável é determinado em __tempo de execução__, e __pode mudar ao longo do programa.__<br>
  __🧠 Exemplo:__

  ```txt
  X = 10
  X = "Olá"
  ```
  O valor de `x` pode começar como um número inteiro `10`, mas depois mudar para uma string `"Olá"`.

- __🔗 <ins>Tipagem estática</ins>:__
  Tipagem estática é quando o __tipo da variável é definido no momento da declaração__ e __não pode ser alterado durante a execução do programa.__ Linguagens com tipagem estática verificam os tipos em __tempo de compilação__, ajudando a prevenir __erros antes do programa rodar.__<br>
  __🧠 Exemplo:__
   
  ```txt
  int X = 10
  X = "Olá" ❌ Error
  ```
  O valor de `x` é declarado como inteiro `10` e só poderá receber outros inteiros.

__Tipagem Forte vs Fraca__

- __💪 <ins>Tipagem Forte</ins>:__
  O programa não permite que você faça operações com tipos diferentes.<br>
  __🧠 Exemplo:__

  ```txt
  X = "10"
  Y = 5
  leia( X + Y ) ❌ Error
  ```
  Aqui, `X` é uma string `"10"`, e `Y` é um inteiro `5`.<br>
  Tentar somar os dois causa __erro__, porque a linguagem __não deixa misturar tipos diferentes__ diretamente.

- __🤏 <ins>Tipagem Fraca</ins>:__
  O programa permite operações entre tipos diferentes, fazendo conversões automáticas ( _às vezes inesperadas_ ).<br>
  __🧠 Exemplo:__

  ```txt
  X = "10"
  Y = 5
  leia( X + Y )
  ```
  Aqui, `X` é uma string `"10"`, e `Y` é um inteiro `5`.<br>
  Ao somar, o programa __converte__ `Y` para string e __concatena__, resultando em `"105"`.<br><br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=60&color=0:16A085,100:2980B9&text=Operadores%20em%20Algoritmos&fontSize=25&fontAlignY=53&fontColor=FFFFFF">
</p>

__📌 O que são operadores?__  
&nbsp;&nbsp;&nbsp;Operadores são símbolos usados em algoritmos para realizar operações com variáveis e valores, como cálculos, comparações e decisões lógicas. Eles são fundamentais para que o algoritmo possa tomar decisões, repetir ações e processar dados corretamente.

<h3>🔢 Operadores Aritméticos</h3>

🧮 Usados para realizar __cálculos matemáticos simples.__

| Operador | Significado    | Exemplo  | Resultado  |
| -------- | -------------- | -------- | ---------- |
| `+`      | Adição         | `5 + 5`  | `10`       |
| `-`      | Subtração      | `5 - 3`  | `2`        |
| `*`      | Multiplicação  | `3 * 2`  | `6`        |
| `\`      | Divisão        | `8 / 2`  | `4`        |
| `%`      | Resto          | `3 % 8`  | `2`        |

<h3>🔢 Operadores de atribuição</h3>

🧮 Usados para realizar um __cálculo matemático simples e rápido.__

| Operador  | Significado    | Exemplo   | Igual a     |
| --------- | -------------- | --------- | ----------- |
| `+=`      | Adição         | `X += 5`  | `X = X + 5` |
| `-=`      | Subtração      | `X -= 3`  | `X = X - 3` |
| `*=`      | Multiplicação  | `X *= 2`  | `X = X * 2` |
| `\=`      | Divisão        | `X /= 2`  | `X = X / 2` |
| `%=`      | Resto          | `X %= 8`  | `X = X % 8` |

<h3>⬆️⬇️ Operadores de incremento e decremento</h3>

🧮 Usados para __adicionar ou subtrair 1 do valor de uma variável.__

| Operador | Siginificado | Exemplo   | Resultado |
| -------- | ------------ | --------- | --------- |
| `++`     | Incremento   | `5++`     | `6`       |
| `--`     | Decremento   | `5--`     | `4`       |

<h3>🔍 Operadores Relacionais</h3>

📏 Usados para __comparar dois valores.__ O resultado dessas comparações é sempre será um valor __booleano.__

| Operador | Significado        | Exemplo  | Resultado |
| -------- | ------------------ | -------- | --------- |
| `==`     | "Igual a"          | `5 == 5` | `true`    |
| `!=`     | "Diferente de"     | `5 != 3` | `true`    |
| `>`      | "Maior que"        | `7 > 4`  | `true`    |
| `<`      | "Menor que"        | `3 < 2`  | `false`   |
| `>=`     | "Maior ou igual a" | `6 >= 6` | `true`    |
| `<=`     | "Menor ou igual a" | `4 <= 3` | `false`   |

<h3>🧠 Operadores Lógicos</h3>

⚙️ Usados para combinar __condições booleanas.__ São essenciais para tomar decisões mais __complexas.__


<table>
  <tr>
    <th>Operador</th>
    <th>Significado</th>
    <th align="left">Lógica<br><code>A</code> condição 1<br><code>B</code> condição 2<br><code>R</code> resultado</th>
  </tr>
  <tr>
    <td><code>&&</code> ou <code>and</code></td>
    <td>E - Só retorna <code>true</code> se ambas as condições forem <strong>verdadeiras</strong></td>
    <td>
      <table>
        <tr><th>A</th><th>B</th><th>R</th></tr>
        <tr><td>1</td><td>1</td><td>1</td></tr>
        <tr><td>0</td><td>1</td><td>0</td></tr>
        <tr><td>1</td><td>0</td><td>0</td></tr>
        <tr><td>0</td><td>0</td><td>0</td></tr>
      </table>
    </td>
  </tr>
  <tr>
    <td><code>||</code> ou <code>or</code></td>
    <td>OU - Só retorna <code>true</code> se uma das condições forem <strong>verdadeiras</strong></td>
    <td>
      <table>
        <tr><th>A</th><th>B</th><th>R</th></tr>
        <tr><td>1</td><td>1</td><td>1</td></tr>
        <tr><td>0</td><td>1</td><td>1</td></tr>
        <tr><td>1</td><td>0</td><td>1</td></tr>
        <tr><td>0</td><td>0</td><td>0</td></tr>
      </table>
    </td>
  </tr>
  <tr>
    <td><code>!</code> ou <code>not</code></td>
    <td>NÃO - <strong>inverte</strong> o valor lógico.</td>
    <td align="center">
      <table>
        <tr><th>A</th><th>R</th></tr>
        <tr><td>1</td><td>0</td></tr>
        <tr><td>0</td><td>1</td></tr>
      </table>
    </td>
  </tr>
</table>

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=60&color=0:16A085,100:2980B9&text=Estruturas%20Condicionais&fontSize=25&fontAlignY=53&fontColor=FFFFFF">
</p>

As __estruturas condicionais__ permitem que o algoritmo escolha caminhos diferentes dependendo do valor de uma condição. Elas utilizam operadores relacionais e lógicos para avaliar __expressões booleanas e executar uma ou mais linhas de código.__

__🧠 Exemplo Pseudocódigo:__
```
se nota >= 7 então
    escreva "Aprovado"
senão se nota >= 5 então
    escreva "Recuperação"
senão
    escreva "Reprovado"
fim se
```
<h3>💡 Comandos condicionais</h3>
Com esses comandos é possivel fazer estruturas condicionais

| Comando             | Significado                                                                   |
| ------------------- | ----------------------------------------------------------------------------- |
| `if`                | __Executa__ um bloco de código se a condição for `true`.                      |
| `elif` ou `else if` | __Executa__ um bloco de código se o `if` for `false` e a condição for `true`. |
| `else`              | __Executa__ um bloco de código se nenhuma das condições forem `true`.         |
| `switch`            | (_Em algumas linguagens_) testa vários valores possíveis.                     |

> [!IMPORTANT]
>__📌 Importante:__<br>
> Os __comandos__ `elif` (_ou `else if`_) e `else` só podem ser __usados depois__ de um `if`, pois __dependem dele__ para fazer sentido.
> 
> Já o comando `if` pode __funcionar sozinho__, sem `elif` ou `else`.

__🧠 Exemplo de `if`/se,`else if`/senão se e `else`/senão em portugol:__
```txt
se(nota >= 7){
      escreva("Aprovado")
} senao se(nota >= 5){
      escreva("Recuperação")
} senao {
      escreva("Reprovado")
}
```

- ✅ Se o `se` for __verdadeiro__ → executa o bloco correspondente.
> [!NOTE]
> __📌 Nota:__ Se o `se` for __verdadeiro__ o `senao se` e `senao` são ignorados completamente.
- ✅ Se o `se` for __falso__ e `senão se` __for verdadeiro__ → executa o bloco correspondente.
- ✅ Se nenhuma condição for __verdadeira__ → executa o bloco correspondente `senão`.

<hr>

O `switch` testa __múltiplas possibilidades__ de valor usando casos (`case`), e executa o bloco de código correspondente ao __primeiro caso que casar__ com o valor fornecido.

__🧠 Exemplo de `switch`/escolha em portugol:__

```txt
escolha(numero){
      caso 1:
        escreva("Olá")
        pare
      caso 2:
        escreva("Opa")
        pare
      caso 3:
        escreva("Eae")
        pare
      caso contrario:
        escreva("Thau")
        pare
```
1. __🔍 Primeiro, você informa qual valor será testado.__
   - No exemplo, é a variável `numero`.
2. __⚙️ Depois, o programa compara esse valor com cada `caso`.__
   - Se encontrar um valor correspondente, ele:
     - Executa o bloco de código dentro desse `caso`.
     - Usa o `pare` (equivalente a `break`) para sair do bloco escolha/switch e não continuar testando os outros casos.
3. __🚩 Se nenhum dos casos for atendido, o `caso contrario` (_equivalente a `else`_) será executado.__
   -  Ele funciona como um plano B, garantindo que alguma ação será tomada mesmo se nenhum caso específico for compatível.

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=60&color=0:16A085,100:2980B9&text=Estruturas%20de%20Repetição%20e%20Laços&fontColor=FFFFFF&fontSize=25&fontAlignY=53">
</p>

As __estruturas de repetição,__ também chamadas de __laços de repetição ou loops,__ são usadas em programação para executar um bloco de código várias vezes, __dependendo de uma condição.__

<h3>🔁 Comandos de repetição</h3>

| **Comando**  | **Significado**                                                                                                        |
| ------------ | ---------------------------------------------------------------------------------------------------------------------- |
| `while`      | Só entra no bloco se a condição for **verdadeira**, e continua enquanto ela for verdadeira                             |
| `do...while` | **Executa o bloco ao menos uma vez**, mesmo que a condição seja falsa no início; continua se a condição for verdadeira |
| `for`        | Define um contador e **executa o bloco de código um número determinado de vezes**                                      |

> [!CAUTION]
> __📌 Atenção:__ Lembre-se de sempre verificar se os loops `while` e `do...while` possuem uma maneira de sair, ou seja, uma condição que eventualmente se __torne falsa.__ Caso contrário, o código pode entrar em um loop infinito, __travando o programa.__

__🧠 Exemplo de `while`/enquanto em portugol:__

```txt
inteiro numero = 3

enquanto(numero > 0){
   escreva("Repetição ",numero,"\n")
   numero -= 1
}
```

__📤 saída:__
```txt
Repetição 3
Repetição 2
Repetição 1
```

- O programa analisa a __condição__ `numero > 0_`.
- Se a condição for __verdadeira__, ele entra no bloco e executa os comandos.
- É importante modificar o valor da variável `numero` dentro do bloco, para que a condição possa se tornar __falsa__ e o loop termine.
- Quando `numero` chega a `0,` a condição `numero > 0` se torna falsa, e o loop é __encerrado.__

<hr>

__🧠 Exemplo de `do...while`/faça...enquanto em portugol:__

```txt
inteiro numero = 3
faca{
   escreva("Repetição ",numero,"\n")
}enquanto(numero > 3)
```

__📤 saída:__
```txt
Repetição 3
```

- O comando __faca...enquanto__ executa o bloco primeiro, depois __verifica a condição.__
- Neste caso, numero começa em `3`.
- O bloco é executado, __imprime__ `"Repetição 3"`.
- Só então a condição `numero > 3` é testada — e como é __falsa, o loop termina.__

<hr>

__🧠 Exemplo de `for`/para em portugol:__

```txt
para (inteiro numero = 0; numero < 3; numero++){
  escreva("Repetição",numero,"\n")
}
```

__📤 saída:__
```txt
Repetição 0
Repetição 1
Repetição 2
```

- O __loop começa__ com `numero = 0`.
- Ele __executa enquanto__ `numero < 3` (_ou seja, 0, 1 e 2_).
- A cada repetição, ele __incrementa__ `numero` __em 1__ com `numero++`.
- Dentro do bloco, ele __imprime__ a frase com o valor atual de `numero`.


