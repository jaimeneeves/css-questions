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

#### Resposta: A) `background-color`

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

#### Resposta: C) Posição do elemento

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

#### Resposta: B) `div p:first-of-type { ... }` 

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

#### Resposta: A) `border-style: dotted;`

Para criar uma borda pontilhada, você deve usar `border-style: dotted;`.

</p>
</details>

---

###### 5. Qual valor de `position` é usado para sobrepor elementos?

- A) `static;`
- B) `fixed;`
- C) `absolute;`
- D) `relative;`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: C) `absolute;`

O `position: absolute;` permite que um elemento seja posicionado em relação ao seu contêiner mais próximo não estático, podendo sobrepor outros elementos.

</p>
</details>

---

###### 6. Qual propriedade CSS é usada para criar espaçamento entre as bordas de dois elementos adjacentes?

- A) `margin`
- B) `padding`
- C) `border`
- D) `spacing`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `margin`

A propriedade CSS `margin` é usada para criar espaço ao redor dos elementos, fora de quaisquer bordas definidas. Ela é eficaz para controlar o espaçamento entre elementos adjacentes, garantindo que haja uma separação visual entre eles sem alterar o espaço interno do elemento, o qual é controlado pela propriedade `padding`.

Vamos analisar as outras opções para entender por que são incorretas:

b) `padding` - Esta propriedade adiciona espaço dentro de um elemento, entre o conteúdo e a borda, e não afeta o espaçamento entre elementos adjacentes.

c) `border` - Define a borda ao redor do elemento, mas não cria espaço entre elementos.

d) `spacing` - Não é uma propriedade CSS válida.

</p>
</details>

---

###### 7. Qual propriedade CSS controla o tamanho da fonte?

- A) `font-size` 
- B) `text-size`
- C) `font-weight`
- D) `text-style`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `font-size`

A propriedade CSS `font-size` é usada especificamente para definir o tamanho da fonte de um texto dentro de um elemento HTML. Ela pode ser definida usando diferentes unidades de medida como pixels (`px`), pontos (`pt`), ems (`em`), porcentagens (`%`), entre outros.

</p>
</details>

---

###### 8. Qual propriedade CSS controla a visibilidade de um elemento?

- A) `visibility`
- B) `display`
- C) `opacity`
- D) `view`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `visibility`

A propriedade CSS `visibility` é usada para controlar a visibilidade de um elemento na página. Os valores possíveis incluem `visible` (o padrão, que torna o elemento visível), `hidden` (que esconde o elemento, mas ainda ocupa espaço na página), e `collapse` (usado principalmente com tabelas para ocultar linhas ou colunas).

Vamos considerar também as outras opções:

b) `display` - Esta propriedade controla se um elemento é exibido ou não, incluindo como ele é renderizado na página. Valores como none podem fazer um elemento desaparecer completamente, diferentemente de visibility, onde o espaço ainda é ocupado.

c) `opacity` - Controla a transparência de um elemento. Um valor de 0 faz o elemento ficar totalmente transparente, mas ainda interativo e ocupando espaço.

d) `view` - Não é uma propriedade CSS válida.

</p>
</details>

---

###### 9. Qual propriedade CSS ajusta o espaço entre caracteres?

- A) `letter-spacing`
- B) `word-spacing`
- C) `text-spacing`
- D) `space-between`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `letter-spacing`

A propriedade CSS `letter-spacing` é usada para ajustar o espaço entre os caracteres de um texto. Isso permite um controle mais fino sobre a aparência do texto, podendo melhorar a legibilidade ou criar um efeito visual específico. A propriedade aceita valores como `normal` (o padrão), ou uma medida específica (por exemplo, `2px`, `-1px`).

Vamos analisar as outras opções:

b) `word-spacing` - Esta propriedade ajusta o espaço entre palavras, não entre caracteres.

c) `text-spacing` - Não é uma propriedade válida em CSS.

d) `space-between` - Embora seja um valor que pode ser usado em propriedades como `justify-content` para espaçamento entre itens flexíveis ou de grade, não é usado para ajustar espaçamento entre caracteres.

</p>
</details>

---

###### 10. Qual propriedade CSS permite animar a transição entre estados?

- A) `animation`
- B) `transition`
- C) `transform`
- D) `animate`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: B) `transition`

A propriedade CSS `transition` é usada para animar mudanças de propriedades de CSS ao longo do tempo, como cor, tamanho, posição, entre outras. Isso permite que as mudanças de estilo não ocorram instantaneamente, mas sim gradualmente durante um período de tempo especificado, criando uma experiência visual suave e agradável.

Aqui está o que cada uma das outras opções significa:

a) `animation` - Embora também usada para animações, a propriedade `animation` é mais complexa e geralmente é usada em conjunto com `@keyframes` para definir animações detalhadas que incluem múltiplos estados e timings.

c) `transform` - Esta propriedade é usada para aplicar transformações geométricas a um elemento (como rotação, escala, movimento, inclinação), mas por si só não cria uma animação ao longo do tempo.

d) `animate` - Não é uma propriedade CSS válida.

</p>
</details>

---

###### 11. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 12. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 13. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 14. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 15. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 16. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 17. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 18. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 19. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 20. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 21. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 22. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 23. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 24. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 25. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 26. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 27. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 28. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 29. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 30. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 31. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 32. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 33. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 34. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 35. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 36. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 37. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 38. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 39. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 40. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 41. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 42. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 43. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 44. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 45. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 46. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 47. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 48. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 49. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 50. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

## Avançadas

###### 1. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 2. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 3. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 4. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 5. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 6. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 7. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 8. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 9. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 10. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 11. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 12. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 13. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 14. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 15. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 16. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 17. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 18. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 19. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 20. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 21. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 22. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 23. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 24. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 25. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 26. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 27. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 28. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 29. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 30. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 31. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 32. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 33. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 34. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 35. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 36. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 37. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 38. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 39. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 40. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 41. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 42. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 43. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 44. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 45. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 46. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 47. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 48. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 49. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

###### 50. ???

- A) ???
- B) ???
- C) ???
- D) ???

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: ?) ???

???

</p>
</details>

---

