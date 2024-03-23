# Vetores

*São "**seguimentos orientados**" presentes no <u>plano cartesiano</u>, usados para representar grandezas escalares (massa, pressão...) e grandezas físicas vetoriais (velocidade, força e deslocamento).*

Vetores podem possui várias dimensões:
* Vetores com 2 dimensões: R² `(x, y)`
* Vetores com 3 dimensões: R³ `(x, y, z)`
* Vetores com 4 dimensões: R⁴ `(x, y, z, w)` = `R * R * R * R` = `{x, y, z, w | x, y, z, w ∈ R}`

Todo vetor possui um ponto referencial *x* e *y* ou *z* quando for 3 dimensões ou *w* quando ofr 4 dimensões.

## Tipos de Vetores

* **Vetor Nulo**: É unm vetor com seus valores iguais a zero, ou seja, tudo zero. Exemplo:
```
u = (0, 0)
u = (0, 0, 0)
u = (0, 0, 0, 0)
```
* **Vetor Oposto ou Simétrico**: Dois vetores, um *oposto a outro* no plano cartesiano, contendo o mesmo [modulo](#módulo-de-um-vetor), mesma direção, apenas sentidos diferentes. Exemplo:
```
u = (8, 9); -u = (-8, -9)
u = (8, 9, 10); -u = (-8, -9, -10)
u = (8, 9, 10, 11); -u = (-8, -9, -10, -11)
```
* **Vetor Unitário**: É um vetor *u* que seu [modulo](#módulo-de-um-vetor) é 1, ou seja, `|u| = 1`.
* **Vetores Colineares** (Paralelo): são colineares se dois vetores tiverem a mesma direção, ou seja, pertence a mesma reta e/ou paralelo a ela.
* **Vetores Coplanares**: Quando dois vetores fazem parte de um mesmo plano. Exemplos:
```
Exemplo 1
u = (10, 15)
v = (5, 8)
```
```
Exemplo 2
u = (3, 7, 2)
v = (4, 7, 0)
```

##  Igualdade de Vetores

Um vetor é igual ao outro se:
* O *x* do primeiro vetor for igual ao *x* do segundo vetor: `x1 = x2`
* O *y* do primeiro vetor for igual ao *y* do segundo vetor: `y1 = y2`
* O *z* do primeiro vetor for igual ao *z* do segundo vetor: `z1 = z2`
* O *w* do primeiro vetor for igual ao *w* do segundo vetor: `w1 = w2`

Exemplos:
```
Exemplo 1
u1 = (0, 5)
u2 = (0, 5)
u1 = u2
```
```
Exemplo 2
u1 = (15, 25)
u2 = (15, 25)
u1 = u2
```

### Exercício
Sejam `u = (x - 1, 3)` e `v = (3, 2y - 1)`. Determine o valor de `|x|` e `|y|` para que `u = v`.
```
x - 1 = 3
3 = 2y - 1

// Parte 1
x = 3 + 1 => 4

// Parte 2
3 + 1 = 2y
4 / 2 = y => 2

// Resultado
x = 4
y = 2
u = (4 - 1, 3)      = (3, 3)
v = (3, 2 * 2 - 1)  = (3, 3)
u = v
```

## Soma de Vetores

É a soma entre dois **pontos** de um plano cartesiano, somando cada um dos eixos (x, y, z, w...). Fórmula:
```
u1 = (x1, y1)
u2 = (x2, y2)
u1 + u2 = (x1 + x2, y1 + y2)
```

## Subtração de Vetores

É a subtração entre dois **pontos** de um plano cartesiano, subtraindo cada um dos eixos (x, y, z, w...). Fórmula:
```
u1 = (x1, y1)
u2 = (x2, y2)
u1 - u2 = (x1 - x2, y1 - y2)
```

## Multiplicação de Vetores - Produto Escalar

É a multiplicação entre dois **pontos** de um plano cartesiano, multiplicando cada um dos eixos (x, y, z, w...) e por fim somando-os, formando um produto escalar `α` (alfa). Fórmula:
```
u1 = (x1, y1)
u2 = (x2, y2)
u1 * u2 = (x1 * x2 + y1 * y2) = α
```

Diferente da soma e subtração, a multiplicação traz um valor real, não um vetor, que representa uma medida da magnitude de um vetor na direção de outro vetor, muito usado para calcular projeções de um vetor sobre o outro.

## Multiplicação por um escalar

É a multiplicação entre um número real ([Produto Escalar](#multiplicação-de-vetores---produto-escalar)) e um vetor, resultando em um novo vetor. Fórmula:
```
u = (x, y)
αu = α(x, y) => (αx, αy)
```

## Módulo de um vetor

O módulo de um vetor se refere ao seu tamanho, onde nó multiplicamos o vetor por ele mesmo e depois aplica a raiz quadrada. Fórmula:
```
u = (x, y)
|u| = √(u²) = √(x² + y²)
```

## Ângulo entre dois vetores

O ângulo entre dois vetores (Ø), se dá quando ambos partem de um mesmo ponto e para calcular, seguindo esta fórmula:
```
cos Ø = (u * v) / (|u| * |v|)
```

FONTE: [S.O.S SABER - YouTube](https://www.youtube.com/watch?v=TP2o31y5_GU&list=PLO3hBdfBc4pFef1zn1oZyYXLomL9MiX-C&index=2)