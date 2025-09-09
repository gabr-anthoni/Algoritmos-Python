
<p align="center">
  <img width="250" src="./.imgs/python-logo-.png">
</p>

<h1 align="center">🐍 PYTHON</h1>

&nbsp;&nbsp;&nbsp;Python é uma linguagem de programação **simples e versátil.** Seu código é fácil de entender porque se parece com a linguagem humana. Python é amplamente usado em diversas áreas, como desenvolvimento de sites, automação,
ciência de dados, inteligência artificial e muito mais.

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=0:20B2AA,100:FFD43B&text=%20DADOS%20EM%20PYTHON&fontColor=FFFFFF&fontSize=25&fontAlignY=57">
</p>

<h3 align="center">📦 DADOS EM PYTHON :</h3>

Uma **variável** é como uma "*caixa*" onde armazenamos informações.
Como o Python é uma linguagem de **tipagem implícita**, não é preciso especificar o tipo da variável

Aqui estão alguns exemplos de **tipos de dados usados** em Python:
```python
texto       = "Bom dia!"  # String
numero      = 10          # Inteiro
numero_real = 5.5         # Real
booleano    = True        # Booleano
```

- **📝 String** (`str`): Cadeia de caracteres. Pode ser delimitada por aspas duplas (`"`) ou aspas simples (`'`).
Mesmo um único caractere conta como uma string em Python.
- **🔢 Inteiro** (`int`): Número sem casas decimais, positivo ou negativo.
- **🔢 Real** (`float`): Número com casas decimais (*também chamado de ponto flutuante*).
- **✅❌ Booleano** (`bool`): Verdadeiro (`True`) ou Falso (`False`).

<hr>

**🎯 Entrada de dados:**

```python
nome  = input("Digite seu nome:")
idade = int(input("Digite sua idade:"))
```

- A função `input()` recebe um valor **digitado pelo usuário.**
- O texto dentro de `input()`, como `"Digite seu nome"` ou `"Digite sua idade"`, serve como instrução para o usuário **saber o que deve digitar.**
- Tudo o que o usuário digita é **recebido como uma string** (*texto*), a menos que seja **convertido antes com funções** como `int()` (*para inteiros*) ou `float()` (_para números reais_).

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=0:20B2AA,100:FFD43B&text=OPERADORES%20EM%20PYTHON&fontColor=FFFFFF&fontSize=25&fontAlignY=58">
</p>

<h3 align="center">⚙️ OPERADORES EM PYTHON :</h3>

<h4 align="center">🧮 Aritméticos :</h4>

<table border="1" align="center">
  <tr>
    <th>Operador</th>
    <th>Significado</th>
    <th>Exemplo</th>
    <th>Resultado</th>
  </tr>
  <tr>
    <td align="center"><code>+</code></td>
    <td>Soma</td>
    <td align="center"><code>5 + 2</code></td>
    <td align="center"><strong>7</strong></td>
  </tr>
  <tr>
    <td align="center"><code>-</code></td>
    <td>Subtração</td>
    <td align="center"><code>5 - 2</code></td>
    <td align="center"><strong>3</strong></td>
  </tr>
  <tr>
    <td align="center"><code>*</code></td>
    <td>Multiplicação</td>
    <td align="center"><code>5 * 2</code></td>
    <td align="center"><strong>10</strong></td>
  </tr>
  <tr>
    <td align="center"><code>/</code></td>
    <td>Divisão (float)</td>
    <td align="center"><code>5 / 2</code></td>
    <td align="center"><strong>2.5</strong></td>
  </tr>
  <tr>
    <td align="center"><code>//</code></td>
    <td>Divisão inteira</td>
    <td align="center"><code>5 // 2</code></td>
    <td align="center"><strong>2</strong></td>
  </tr>
  <tr>
    <td align="center"><code>%</code></td>
    <td>Módulo (resto)</td>
    <td align="center"><code>5 % 2</code></td>
    <td align="center"><strong>1</strong></td>
  </tr>
  <tr>
    <td align="center"><code>**</code></td>
    <td>Exponenciação</td>
    <td align="center"><code>5 ** 2</code></td>
    <td align="center"><strong>25</strong></td>
  </tr>
</table>

<h4 align="center">📊 Atribuição :</h4>

<table border="1" align="center">
  <tr>
    <th>Símbolo</th>
    <th>Operação matemática</th>
    <th>Exemplo</th>
    <th>Significado equivalente</th>
  </tr>
  <tr>
    <td align="center"><code>+=</code></td>
    <td>Soma e atribuição</td>
    <td align="center"><code>x += 3</code></td>
    <td align="center"><code>x = x + 3</code></td>
  </tr>
  <tr>
    <td align="center"><code>-=</code></td>
    <td>Subtração e atribuição</td>
    <td align="center"><code>x -= 2</code></td>
    <td align="center"><code>x = x - 2</code></td>
  </tr>
  <tr>
    <td align="center"><code>*=</code></td>
    <td>Multiplicação e atribuição</td>
    <td align="center"><code>x *= 4</code></td>
    <td align="center"><code>x = x * 4</code></td>
  </tr>
  <tr>
    <td align="center"><code>/=</code></td>
    <td>Divisão e atribuição</td>
    <td align="center"><code>x /= 5</code></td>
    <td align="center"><code>x = x / 5</code></td>
  </tr>
  <tr>
    <td align="center"><code>//=</code></td>
    <td>Divisão inteira e atribuição</td>
    <td align="center"><code>x //= 2</code></td>
    <td align="center"><code>x = x // 2</code></td>
  </tr>
  <tr>
    <td align="center"><code>%=</code></td>
    <td>Módulo e atribuição</td>
    <td align="center"><code>x %= 3</code></td>
    <td align="center"><code>x = x % 3</code></td>
  </tr>
  <tr>
    <td align="center"><code>**=</code></td>
    <td>Potência e atribuição</td>
    <td align="center"><code>x **= 2</code></td>
    <td align="center"><code>x = x ** 2</code></td>
  </tr>
</table>

<h4 align="center">⚖️ Comparação :</h4>

> [!NOTE]
> Os operadores de comparação em Python sempre retornam um __valor booleano.__

<table border="1" align="center">
  <tr>
    <th>Operador</th>
    <th>Significado</th>
    <th>Exemplo</th>
    <th>Resultado</th>
  </tr>
  <tr>
    <td align="center"><code>==</code></td>
    <td>Igual a</td>
    <td align="center"><code>5 == 2</code></td>
    <td align="center"><strong>False</strong></td>
  </tr>
  <tr>
    <td align="center"><code>!=</code></td>
    <td>Diferente de</td>
    <td align="center"><code>5 != 5</code></td>
    <td align="center"><strong>False</strong></td>
  </tr>
  <tr>
    <td align="center"><code>&gt;</code></td>
    <td>Maior que</td>
    <td align="center"><code>7 &gt; 2</code></td>
    <td align="center"><strong>True</strong></td>
  </tr>
  <tr>
    <td align="center"><code>&lt;</code></td>
    <td>Menor que</td>
    <td align="center"><code>2 &lt; 7</code></td>
    <td align="center"><strong>True</strong></td>
  </tr>
  <tr>
    <td align="center"><code>&gt;=</code></td>
    <td>Maior ou igual a</td>
    <td align="center"><code>8 &gt;= 8</code></td>
    <td align="center"><strong>True</strong></td>
  </tr>
  <tr>
    <td align="center"><code>&lt;=</code></td>
    <td>Menor ou igual a</td>
    <td align="center"><code>4 &lt;= 8</code></td>
    <td align="center"><strong>True</strong></td>
  </tr>
</table>

<h4 align="center">🔗 Lógicos :<h4>

<table border="1" align="center">
  <tr>
    <th>Operador</th>
    <th>Significado</th>
    <th align="left">Lógica<br><code>A</code> condição 1<br><code>B</code> condição 2<br><code>R</code> resultado</th>
  </tr>
  <tr>
    <td align="center"><code>and</code></td>
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
    <td align="center"><code>or</code></td>
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
    <td align="center"><code>not</code></td>
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
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=0:20B2AA,100:FFD43B&text=ESTRUTURAS%20CONDICIONAIS&fontColor=FFFFFF&fontSize=25&fontAlignY=58">
</p>

<h3 align="center">🔀 ESTRUTURAS CONDICIONAIS :</h3>

O programa testa condições e, conforme sejam `True` ou `False`, decide quais blocos de código serão executados.

```python
if condicao1:
    # se condição1 for verdadeira
elif condicao2:
    # se condição1 for falsa e condição2 for verdadeira
else:
    # se nenhuma condição for verdadeira
```

- `if` - Se a condição 1 for `True`
- `elif` - Se a condição 1 for `False` e a condição 2 for `True`
- `else` - Se nenhuma condição for `True`

> [!IMPORTANT]
> - `if` pode existir sozinho
> - `elif` e `else` só fazem sentido se houver um `if` antes

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=0:20B2AA,100:FFD43B&text=ESTRUTURAS%20DE%20REPETIÇÃO&fontColor=FFFFFF&fontSize=25&fontAlignY=57">
</p>

<h3 align="center">🔄 ESTRUTURAS DE REPETIÇÃO:</h3>

`while` - Usado para repetir enquanto uma **condição for verdadeira.**

```python
contador = 3
while contador > 0:
  print(contador)
  contador -= 1
```

**Saída:**
```txt
3
2
1
```

> [!CAUTION]
> Sempre garanta que o loop `while` tenha uma condição que, em algum momento, se torne falsa.
> Caso contrário, o programa ficará preso em um **loop infinito** que nunca termina.

<hr>

`for` - Usado para **repetir algo um número conhecido de vezes.**

```python
for i in range(3,0,-1):
    print(i)
```

**Saída:**
```txt
3
2
1
```
- O `i` funciona como um contador, que é atualizado a cada **repetição do loop,** conforme o valor definido.
- O `in` indica onde o contador vai “pegar” os **valores para iterar.**
- A função `range()` gera uma sequência de **números que o loop pode percorrer e contar.**

> [!NOTE]
> A função `range()` gera uma sequência de números que pode ser usada em laços for. Ela aceita até três parâmetros:
>
> `range(início, fim, passo)`
> 
> - `início` → Número onde a contagem começa. Se não for informado, o padrão é `0`.
> - `fim` → Número onde a contagem termina (não é incluído no resultado). Esse é obrigatório se você quiser definir um início.
> - `passo` → Valor que será somado ou subtraído a cada repetição (pode ser negativo para contagem regressiva). O padrão é `1`.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=0:20B2AA,100:FFD43B&text=LISTAS,%20TUPLAS,%20DICIONÁRIOS%20E%20CONJUNTOS&fontColor=FFFFFF&fontSize=25&fontAlignY=57">
</p>

<h3 align="center">📋 ARRAYS (listas)</h3>

Uma lista é uma estrutura que guarda vários valores (*de qualquer tipo*) em uma única variável, organizados em ordem, 
entre colchetes `[]` e separados por vírgulas `,`.

```python
frutas = ["maçã", "banana", "uva"]
numeros = [1, 2, 3, 4, 5]
mista = [1, "texto", True]
```
**🔍 Acessar item pelo índice**

Cada item de uma lista tem uma posição (*índice*), que começa em `0`. Você pode acessar um item diretamente usando
o nome da lista seguido do índice entre colchetes `[]`.

```python
frutas = ["maçã", "banana", "uva", "melancia"]
print(frutas[0])  # "maçã"
print(frutas[1])  # "banana"
print(frutas[2])  # "uva"
print(frutas[3])  # "melancia"
````

**🛠️ Modificar lista**

Você pode **modificar diretamente** os elementos de uma lista usando seu **índice:**
```python
frutas = ["maçã", "banana", "uva", "melancia"]
frutas[2] = "melão"
print(frutas) # ["maçã", "banana", "melão", "melancia"]
```

Mas existem algumas **funções que ajudam modificar uma lista.**

**📋 Lista de funções -** `frutas = ["maçã", "banana", "uva", "melancia"]`
<table border="1" align="center">
  <tr>
    <td><strong>Função</strong></td>
    <td><strong>Significado</strong></td>
    <td><strong>Exemplo</strong></td>
    <td><strong>Lista depois</strong></td>
  </tr>
  <tr>
    <td><code>append()</code></td>
    <td>Adiciona item no final</td>
    <td><code>frutas.append("kiwi")</code></td>
    <td><code>["maçã", "banana", "uva", "melancia", "kiwi"]</code></td>
  </tr>
  <tr>
    <td><code>insert()</code></td>
    <td>Insere item em posição específica</td>
    <td><code>frutas.insert(1, "laranja")</code></td>
    <td><code>["maçã", "laranja", "banana", "uva", "melancia"]</code></td>
  </tr>
  <tr>
    <td><code>extend()</code></td>
    <td>Adiciona itens de outra lista</td>
    <td><code>frutas.extend(["abacaxi", "limão"])</code></td>
    <td><code>["maçã", "banana", "uva", "melancia", "abacaxi", "limão"]</code></td>
  </tr>
  <tr>
    <td><code>remove()</code></td>
    <td>Remove item pelo valor</td>
    <td><code>frutas.remove("banana")</code></td>
    <td><code>["maçã", "uva", "melancia"]</code></td>
  </tr>
  <tr>
    <td><code>pop()</code></td>
    <td>Remove último item (ou por índice)</td>
    <td><code>frutas.pop(2)</code></td>
    <td><code>["maçã", "banana", "melancia"]</code></td>
  </tr>
  <tr>
    <td><code>clear()</code></td>
    <td>Remove todos os itens</td>
    <td><code>frutas.clear()</code></td>
    <td><code>[]</code></td>
  </tr>
  <tr>
    <td><code>sort()</code></td>
    <td>Ordena em ordem alfabética ou crescente</td>
    <td><code>frutas.sort()</code></td>
    <td><code>["banana", "maçã", "melancia", "uva"]</code></td>
  </tr>
  <tr>
    <td><code>sort(reverse=True)</code></td>
    <td>Ordena em ordem reversa</td>
    <td><code>frutas.sort(reverse=True)</code></td>
    <td><code>["uva", "melancia", "maçã", "banana"]</code></td>
  </tr>
  <tr>
    <td><code>reverse()</code></td>
    <td>Inverte a ordem dos itens</td>
    <td><code>frutas.reverse()</code></td>
    <td><code>["melancia", "uva", "banana", "maçã"]</code></td>
  </tr>
</table>

<hr>

<h3 align="center">🔒 TUPLAS</h3>

Uma tupla é uma estrutura de dados **imutável** que pode armazenar **múltiplos valores.**
É semelhante a uma lista, mas **não pode ser modificada** após ser criada. organizados em ordem, entre parênteses `()` e separados por vírgulas `,`.

```python
tupla = (10, 20, 30)
print(tupla[0]) # 10
coordenadas[0] = 30 # Erro : O valor de uma tupla não pode alterado.
```

<hr>

<h3 align="center">📚 DICIONÁRIO</h3>

Um dicionário é uma estrutura de dados que **mapeia chaves a valores.**  

Como criar um dicionário:
- O dicionário é **criado usando chaves** `{}`.
- Cada par `chave:valor` é **separado por dois pontos** `:`.
- Quando há mais de um par, eles são separados por vírgulas `,` e o último par `chave:valor` em um dicionário **não precisa de vírgula.**

```python
dicionario = {
    "nome": "Maria",
    "idade": 25,
    "profissao": "Engenheira"
}
print(dicionario["nome"])      # "Maria"
print(dicionario["idade"])     # 25
print(dicionario["profissao"]) # "Engenheira"
```

**Explicação:**
- A chave `"nome"` está **associada ao valor** `"Maria"`.
- A chave `"idade"` está **associada ao valor** `25`.
- A chave `"profissao"` está **associada ao valor** `"Engenheira"`.

**🛠️ Modificar dicionário**

**✏️ Modificar valor :**
```python
dicionario["idade"] = 26
print(dicionario["idade"]) # 26
```

**➕ Criar chave com valor :**
```python
dicionario["cidade"] = "SP"
print(dicionario["cidade"]) # "SP"
```

**🗑️ Remover par :**
```python
del dicionario["cidade"]
print(dicionario) # {'nome': 'Maria', 'idade': 25, 'profissao': 'Engenheira'}
```

<hr>

<h3 align="center">🧩 CONJUNTOS</h3>

Os conjuntos (*Set*) armazenam valores **sem repetição** e **não possuem ordem fixa.**

**🛠️ Modificar conjuntos -**`conjuntos = {10, 20, 30, 40}`
<table border="1" align="center">
  <tr>
    <th>Função</th>
    <th>Significado</th>
    <th>Exemplo</th>
    <th>Lista depois</th>
  </tr>
  <tr>
    <td><code>add()</code></td>
    <td>Adiciona um elemento</td>
    <td><code>conjunto.add(50)</code></td>
    <td><code>{10, 20, 30, 40, 50}</code></td>
  </tr>
  <tr>
    <td><code>remove()</code></td>
    <td>Remove (<em>erro se não existir</em>)</td>
    <td><code>conjunto.remove(30)</code></td>
    <td><code>{10, 20, 40}</code></td>
  </tr>
  <tr>
    <td><code>discard()</code></td>
    <td>Remove (<em>sem erro se não existir</em>)</td>
    <td><code>conjunto.discard(99)</code></td>
    <td><code>{10, 20, 30, 40}</code></td>
  </tr>
  <tr>
    <td><code>clear()</code></td>
    <td>Remove todos os elementos</td>
    <td><code>conjunto.clear()</code></td>
    <td><code>None</code></td>
  </tr>
</table>


> [!IMPORTANT]
> Qualquer valor duplicado em um conjunto é descartado
> ```python
> conjunto = {10, 20, 20, 30 }
> print(conjunto)  # Saída: {10, 20, 30}
> ```

**🛠️ Operações com Conjuntos**
Os conjuntos são úteis para operações matemáticas como união, interseção e diferença.

<table border="1" align="center">
<tr>
  <td><strong>Símbolo</strong></td>
  <td><strong>Significado</strong></td>
  <td><strong>Exemplo</strong></td>
  <td><strong>Resultado</strong></td>
</tr>
<tr>
  <td align="center"><code>|</code></td>
  <td>União (valores presentes em A ou B)</td>
  <td><code>{10,20,30,40} | {5,10,15,20}</code></td>
  <td align="center">{40, 10, 5, 20, 15, 30}</td>
</tr>
<tr>
  <td align="center"><code>&amp;</code></td>
  <td>Interseção (valores presentes em A e B)</td>
  <td><code>{10,20,30,40} &amp; {5,10,15,20}</code></td>
  <td align="center">{10, 20}</td>
</tr>
<tr>
  <td align="center"><code>-</code></td>
  <td>Diferença (valores em A que não estão em B)</td>
  <td><code>{10,20,30,40} - {5,10,15,20}</code></td>
  <td align="center">{40, 30}</td>
</tr>
<tr>
  <td align="center"><code>^</code></td>
  <td>Diferença simétrica (valores em A ou B, mas não em ambos)</td>
  <td><code>{10,20,30,40} ^ {5,10,15,20}</code></td>
  <td align="center">{40, 5, 15, 30}</td>
</tr>
</table>

<hr>

<h3 align="center">📌 COMPARAÇÃO ENTRE LISTAS, TUPLAS, DICIONÁRIO E SET</h3>

<br>

<table border="1" align="center">
  <tr>
    <th>Estrutura</th>
    <th>Mutável?</th>
    <th>Ordenado?</th>
    <th>Indexado?</th>
    <th>Permite Duplicados?</th>
    <th>Quando usar?</th>
  </tr>
  <tr>
    <td><strong>Lista</strong></td>
    <td>✅ Sim</td>
    <td>✅ Sim</td>
    <td>✅ Sim</td>
    <td>✅ Sim</td>
    <td>Quando precisamos modificar os dados.</td>
  </tr>
  <tr>
    <td><strong>Tupla</strong></td>
    <td>❌ Não</td>
    <td>✅ Sim</td>
    <td>✅ Sim</td>
    <td>✅ Sim</td>
    <td>Quando queremos armazenar dados fixos e imutáveis.</td>
  </tr>
  <tr>
    <td><strong>Dicionário</strong></td>
    <td>✅ Sim</td>
    <td>✅ Sim (desde Python 3.7)</td>
    <td>❌ Não (chaves substituem índices)</td>
    <td>❌ Não (chaves únicas)</td>
    <td>Quando precisamos armazenar dados organizados por chave-valor.</td>
  </tr>
  <tr>
    <td><strong>Set</strong></td>
    <td>✅ Sim</td>
    <td>❌ Não</td>
    <td>❌ Não</td>
    <td>❌ Não</td>
    <td>Quando precisamos armazenar valores únicos e fazer operações de conjuntos.</td>
  </tr>
</table>
<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=40&color=0:20B2AA,100:FFD43B&text=CRIAR%20FUNÇÕES&fontSize=25&fontColor=FFFFFF&fontAlignY=57">
</p>

<h3 align="center">🧪 CRIAR FUNÇÕES</h3>

Uma função é um bloco de código que você cria para **executar uma tarefa específica.**
Você pode chamar (*usar*) essa função várias vezes no seu código, sem precisar repetir o mesmo código sempre.

```python
def ola():
  print("Olá Mundo!")

ola() # "Olá Mundo!"
```
- Aqui você chama a função `ola()`, e quando ela é executada, **imprime** `"Olá Mundo!"` na tela.

```python
def ola(nome):
  print("Olá",nome)

ola("Paulo") # "Olá Paulo"
```
- Aqui a função `ola(nome)` recebe uma informação externa (*no caso, `"Paulo"`*) e usa essa informação para **imprimir uma mensagem** personalizada.

```python
def soma(numero1,numero2):
  return numero1 + numero2

print(soma(10,10))
```
- A função `soma()` **recebe dois valores e retorna a soma deles.**
- O `return` devolve o resultado **para quem chamou a função.** Depois, usamos `print()` para mostrar esse resultado na tela.

