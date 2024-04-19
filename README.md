<div align="center">
  <h1>Perguntas Básicas e Avançadas sobre CSS</h1>
</div>

## Básicas

###### 1. Qual propriedade CSS altera a cor de fundo de um elemento?

- A) background-color
- B) color
- C) bgcolor
- D) background-image

<details><summary><b>Resposta</b></summary>
<p>

#### A resposta correta é: A) `background-color`

A propriedade CSS `background-color` é usada especificamente para definir a cor de fundo de um elemento HTML.
Esta propriedade aceita valores de cor, como nomes de cores (por exemplo, `red`), valores HEX (por exemplo, `#FF0000`), valores RGB (por exemplo, `rgb(255, 0, 0)`), e mais.

</p>
</details>

---

###### 2. O que a propriedade `z-index` controla no CSS?

- A) Tamanho do elemento
- B) Cor do elemento
- C) Posição do elemento
- D) Nenhum dos anteriores

<details><summary><b>Resposta</b></summary>
<p>

#### A resposta correta é: C) Posição do elemento

`z-index` Controla a sobreposição dos elementos, determinando qual elemento aparece na frente de outro quando eles se sobrepõem.

</p>
</details>

---

###### 3. Como você faria para aplicar um estilo somente ao primeiro parágrafo dentro de um `<div>`?

- A) div p:first-child { ... }
- B) div p:first-of-type { ... }
- C) div:first p { ... }
- D) div p:first { ... }

<details><summary><b>Resposta</b></summary>
<p>

#### A resposta correta é: B) `div p:first-of-type { ... }` 

A pseudo-classe `:first-of-type` é usada para selecionar o primeiro elemento de um tipo específico dentro de seu contêiner. No contexto desta pergunta, `div p:first-of-type { ... }` seleciona o primeiro elemento `<p>` dentro de qualquer `<div>`, aplicando estilos apenas a esse parágrafo.

As outras opções têm significados diferentes:

a) `div p:first-child { ... }` - Esta pseudo-classe seleciona o primeiro filho dentro de um `<div>`, mas somente se for um `<p>`. Se houver outro elemento antes do primeiro `<p>`, ele não será selecionado.

c) `div:first p { ... }` - Esta sintaxe é incorreta e não representa uma forma válida de seleção em CSS.

d) `div p:first { ... }` - Também não é uma sintaxe válida em CSS, pois `:first` não existe como pseudo-classe.

</p>
</details>

---

###### 4. Como você faria uma borda pontilhada?

- A) `border-style: dotted;`
- B) `border-line: dots;`
- C) `border: dots;`
- D) `style: dotted;`

<details><summary><b>Resposta</b></summary>
<p>

#### A resposta correta é: A) `border-style: dotted;`

Para criar uma borda pontilhada, você deve usar `border-style: dotted;`.

</p>
</details>

---
