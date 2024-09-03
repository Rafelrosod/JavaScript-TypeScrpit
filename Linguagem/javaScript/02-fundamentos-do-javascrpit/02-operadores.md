# Operadores

Operadores em JavaScript são símbolos que permitem realizar operações em valores (ou variáveis). Eles são fundamentais para manipular dados, comparar valores, e controlar o fluxo de execução de um programa. A seguir, estão os principais tipos de operadores em JavaScript:

### Operadores Aritméticos

##### Os operadores aritméticos realizam operações matemáticas básicas.

- **`+ (Adição):`** Soma dois valores.

```javascript
let a = 5 + 3; // 8
```

- **`- (Subtração):`** Subtrai um valor de outro.

```javascript
let b = 10 - 2; // 8
```

- **`* (Multiplicação):`** Multiplica dois valores.

```javascript
let c = 4 * 2; // 8
```

- **`/ (Divisão):`** Divide um valor por outro.

```javascript
let d = 16 / 2; // 8
```

- **`% (Módulo):`** Retorna o resto da divisão de dois valores.

```javascript
let e = 10 % 3; // 1
```

- **`(Exponenciação):`** Eleva um valor à potência de outro.

```javascript
let f = 2 ** 3; // 8
```

### Operadores de Atribuição

##### Os operadores de atribuição atribuem valores às variáveis.

- **`= (Atribuição Simples):`** Atribui o valor do lado direito à variável do lado esquerdo.

```javascrpit
let x = 5;
```

- **`+= (Atribuição com Adição):`** Soma e atribui.

```javascript
x += 3; // x agora é 8
```

- **`-= (Atribuição com Subtração):`** Subtrai e atribui.

```javascript
x -= 2; // x agora é 6
```

- **`*= (Atribuição com Multiplicação):`** Multiplica e atribui.

```javascript
x _= 2; // x agora é 12
```

- **`/= (Atribuição com Divisão):`** Divide e atribui.

```javascript
x /= 3; // x agora é 4
```

- **`%= (Atribuição com Módulo):`** Aplica módulo e atribui.

```javascript
x %= 3; // x agora é 1 3. Operadores de Comparação
Esses operadores comparam dois valores e retornam um valor booleano (true ou false).
```

### Operadores de Comparação

##### Esses operadores comparam dois valores e retornam um valor booleano (`true` ou `false`)

- **`== (Igualdade):`**= Compara valores, mas não tipos.

```javascript
5 == "5"; // true
```

- **`=== (Igualdade Estrita):`** Compara valores e tipos.

```javascript
5 === "5"; // false
```

- **`!= (Desigualdade):`** Compara valores, mas não tipos.

```javascript
5 != "5"; // false
```

- **`!== (Desigualdade Estrita):`** Compara valores e tipos.

```javascript
5 !== "5"; // true
```

- **`> (Maior que):`** Verifica se um valor é maior que outro.

  > 10 > 5; // true

* **`< (Menor que):`**Verifica se um valor é menor que outro.

```javascript
> 5 < 10; // true
```

- **`>= (Maior ou igual):`** Verifica se um valor é maior ou igual a outro.

```javascript
  > 10 >= 10; // true
```

- **`<= (Menor ou igual):`** Verifica se um valor é menor ou igual a outro.

```javascript
5 <= 10; // true 4. Operadores Lógicos
```

### Operadores Lógicos

##### Os operadores lógicos são usados para combinar expressões booleanas.

- **`&& (E Lógico):`** Retorna true se ambos os operandos forem verdadeiros.

```javascript
true && false; // false
```

- **`|| (Ou Lógico):`** Retorna true se pelo menos um dos operandos for verdadeiro.

```javascript
true || false; // true
```

- **`! (Não Lógico):`** Inverte o valor booleano.

```javascript
!true; // false 5. Operadores de Incremento e Decremento
```

### Operadores de Incremento e Decremento

##### Esses operadores aumentam ou diminuem o valor de uma variável em 1.

- **`++ (Incremento):`** Aumenta o valor da variável em 1.

```javascript
let y = 5;
y++; // y agora é 6
```

- **`-- (Decremento):`** Diminui o valor da variável em 1.

```javascript
let z = 5;
z--; // z agora é 4 6. Operadores de String
```

### Os operadores de string

###### são usados para concatenar strings.

- **` + (Concatenação):`** Junta duas ou mais strings.

```javascript
let saudacao = "Hello" + " " + "World"; // "Hello World"
```

### Operador Condicional (Ternário)

##### Este operador é uma abreviação para uma condição if-else.

##### condition ? expr1 : expr2: Retorna expr1 se a condição for verdadeira, senão retorna expr2.

```javascript
let idade = 18;
let podeVotar = idade >= 18 ? "Sim" : "Não"; // "Sim"
```
