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
U = (0, 0)
U = (0, 0, 0)
U = (0, 0, 0, 0)
```
* **Vetor Oposto ou Simétrico**: Dois vetores, um *oposto a outro* no plano cartesiano, contendo o mesmo <u>**módulo**</u> (tamanho), mesma direção, apenas sentidos diferentes. Exemplo:
```
U = (8, 9); -U = (-8, -9)
U = (8, 9, 10); -U = (-8, -9, -10)
U = (8, 9, 10, 11); -U = (-8, -9, -10, -11)
```
* **Vetor Unitário**: É um vetor *U* qye seu <u>**módulo**</u> (tamanho) é 1, ou seja, `|U| = 1`.
* **Vetores Colineares** (Paralelo): são colineares se dois vetores tiverem a mesma direção, ou seja, pertence a mesma reta e/ou paralelo a ela.
* **Vetores Coplanares**: Quando dois vetores fazem parte de um mesmo plano. Exemplos:
```
Exemplo 1
U = (10, 15)
V = (5, 8)
```
```
Exemplo 2
U = (3, 7, 2)
V = (4, 7, 0)
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
U1 = (0, 5)
U2 = (0, 5)
U1 = U2
```
```
Exemplo 2
U1 = (15, 25)
U2 = (15, 25)
U1 = U2
```

### Exercício
Sejam `U = (x - 1, 3)` e `V = (3, 2y - 1)`. Determine o valor de `|x|` e `|y|` para que `U = V`.
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
U = (4 - 1, 3)      = (3, 3)
V = (3, 2 * 2 - 1)  = (3, 3)
U = V
```

FONTE: [S.O.S SABER - YouTube](https://www.youtube.com/watch?v=S6TdSAY-RnU&list=PLO3hBdfBc4pFef1zn1oZyYXLomL9MiX-C&index=2)