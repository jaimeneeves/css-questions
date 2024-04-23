<div align="center">
  <h1>Perguntas Básicas e Avançadas sobre CSS</h1>
</div>

---

<p align="center">
Bem-vindos ao nosso repositório GitHub, um tesouro de perguntas sobre CSS que vão do básico ao avançado! 💪🚀 Se você está começando a aprender CSS ou já é um desenvolvedor experiente procurando um desafio, você veio ao lugar certo. Este repositório foi criado com um único objetivo em mente: ajudá-lo a testar, refinar e expandir seu conhecimento de CSS de uma maneira divertida e engajadora.

Então, se você está pronto para embarcar nesta jornada de aprendizado, comece a explorar as perguntas, teste suas habilidades e divirta-se no processo. Boa sorte e esperamos que você aproveite tanto quanto nós ao criar e atualizar este repositório! :heart:
</p>

<p align="center">Sinta-se à vontade para entrar em contato comigo! 😊</p>

---

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

A pseudo-classe `:first-of-type` é usada para selecionar o primeiro elemento de um tipo específico dentro de seu container. No contexto desta pergunta, `div p:first-of-type { ... }` seleciona o primeiro elemento `<p>` dentro de qualquer `<div>`, aplicando estilos apenas a esse parágrafo.

Exemplo Prático:

```css
div p:first-of-type {
  background-color: yellow;  /* Define a cor de fundo como amarela */
  margin-bottom: 20px;       /* Adiciona uma margem inferior de 20px */
}
```

```html
<div>
  <p>Este é o primeiro parágrafo e ele será amarelo com margem maior.</p>
  <p>Este é o segundo parágrafo e não terá os estilos aplicados.</p>
</div>
<div>
  <p>Outro primeiro parágrafo, também estilizado como o primeiro do bloco anterior.</p>
  <p>Este é outro segundo parágrafo sem os estilos especiais.</p>
</div>
```

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

###### 11. Qual propriedade CSS é usada para controlar a largura de um elemento?

- A) `width`
- B) `length`
- C) `size`
- D) `dimension`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `width`

A propriedade `width` em CSS é usada para definir a largura de um elemento. Ela pode ser especificada em várias unidades de medida, como pixels (px), porcentagens (%), ems (em), entre outras. Essa propriedade é fundamental para o layout e dimensionamento de elementos na web.

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

###### 1. Qual propriedade CSS é usada para aplicar uma máscara a um elemento?

- A) `clip-path`
- B) `mask-image`
- C) `background-clip`
- D) `border-mask`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: B) `mask-image`

A propriedade CSS `mask-image` permite aplicar uma máscara a um elemento. Uma máscara define quais áreas do elemento são visíveis e quais são transparentes, usando uma imagem ou um gradiente. Este recurso é poderoso para criar efeitos visuais complexos em interfaces web.

Vamos analisar as outras opções:

a) `clip-path` - Embora clip-path também crie áreas visíveis e invisíveis, ele é usado para recortar um elemento em formas específicas, mas não se baseia em imagens ou gradientes para definir a transparência.

c) `background-clip` - Determina até onde o fundo (como cor ou imagem) deve se estender dentro do elemento, mas não cria uma máscara de transparência.

d) `border-mask` - Não é uma propriedade CSS válida.

</p>
</details>

---

###### 2. Qual propriedade CSS é usada para aplicar múltiplas sombras a um elemento?

- A) box-shadow
- B) text-shadow
- C) multiple-shadow
- D) shadow-layer

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `box-shadow` e B) `text-shadow`

As propriedades `box-shadow` e `text-shadow` em CSS podem ser usadas para aplicar múltiplas sombras a um elemento, seja ele um contêiner (`box-shadow`) ou texto (`text-shadow`). Ambas as propriedades permitem a especificação de múltiplas sombras simplesmente separando-as com vírgulas dentro da mesma declaração. Isso permite a criação de efeitos de profundidade e complexidade visual.

Aqui está o que as outras opções representam:

c) `multiple-shadow` - Não é uma propriedade CSS válida.

d) `shadow-layer` - Também não é uma propriedade CSS válida.

</p>
</details>

---

###### 3. Qual propriedade CSS define a ordem de empilhamento de um elemento?

- A) `z-index`
- B) `stack-index`
- C) `order`
- D) `layer`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `z-index`

A propriedade CSS `z-index` é usada para controlar a ordem de empilhamento dos elementos sobrepostos em uma página. Elementos com um maior `z-index` serão posicionados acima daqueles com um `z-index` menor. Esta propriedade só tem efeito em elementos cuja posição é definida como algo diferente de `static` (como `relative`, `absolute`, `fixed`, ou `sticky`).

Vamos considerar as outras opções:

b) `stack-index` - Não é uma propriedade CSS válida.

c) `order` - Esta propriedade é usada dentro de flexbox para controlar a ordem de exibição dos itens flex, mas não afeta a sobreposição de elementos fora de contextos flex.

d) `layer` - Embora o conceito de camadas seja relevante em design gráfico, layer não é uma propriedade CSS.

</p>
</details>

---

###### 4. Qual função CSS é usada para aplicar cores com transparência?

- A) `rgba()`
- B) `opacity()`
- C) `transparent()`
- D) `alpha()`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `rgba()`

A função `rgba()` em CSS é usada para definir cores com transparência. A sigla RGBA significa Red, Green, Blue, Alpha, onde os três primeiros valores são números que representam a intensidade das cores vermelho, verde e azul, respectivamente, e o último valor (Alpha) representa a transparência da cor. O valor alpha pode ser um número entre 0 (completamente transparente) e 1 (completamente opaco).

Vamos analisar as outras opções:

b) `opacity()` - Não é uma função, mas uma propriedade que ajusta a transparência de um elemento inteiro, afetando não só a cor, mas todos os conteúdos visuais do elemento.

c) `transparent()` - Não é uma função. `transparent` é um valor de cor que pode ser usado para definir uma cor totalmente transparente, mas não permite a especificação de níveis de transparência.

d) `alpha()` - Não é uma função autônoma em CSS. O componente alpha é usado dentro de outras funções de cor como `rgba()` e `hsla()`.

</p>
</details>

---

###### 5. Qual seletor CSS é usado para estilizar todos os elementos irmãos que seguem um elemento especificado?

- A) `+`
- B) `>`
- C) `~`
- D) `*`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: C) `~`

O seletor `~` em CSS, conhecido como seletor de irmãos gerais, é usado para estilizar todos os elementos irmãos que seguem um elemento especificado. Este seletor permite aplicar estilos a todos os irmãos de um mesmo tipo que estão no mesmo nível do DOM e vêm após o elemento especificado.

Exemplo Prático:

Suponha que você tenha um HTML com vários `<p>` e você quer estilizar todos os `<p>` que seguem um `<h1>` específico, mas não os que vêm antes dele. Você poderia usar o seletor `~` da seguinte maneira:

```css
h1 ~ p {
  color: red;
  font-weight: bold;
}
```

```html
<h1>Titulo Principal</h1>
<p>Este parágrafo não será afetado.</p>
<h1>Segundo Título</h1>
<p>Este parágrafo será estilizado.</p>
<p>Este parágrafo também será estilizado.</p>
```

Neste exemplo, apenas os parágrafos que seguem o segundo `<h1>` serão estilizados com texto em vermelho e em negrito. Os parágrafos antes do segundo `<h1>` ou após outro elemento que não seja um `<h1>` não serão afetados.

</p>
</details>

---

###### 6. Qual propriedade CSS controla o comportamento de rolagem suave?

- A) `scroll-behavior`
- B) `overflow-scroll`
- C) `scroll-snap`
- D) `smooth-scroll`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `scroll-behavior`

A propriedade CSS `scroll-behavior` é usada para especificar se a rolagem de um contêiner de rolagem deve ser animada de forma suave (`smooth`) ou instantânea (`auto`). Este é um ajuste útil para melhorar a experiência do usuário ao navegar por páginas que contêm links de âncora ou ao usar métodos de rolagem programáticos em JavaScript.

</p>
</details>

---

###### 7. Qual propriedade CSS permite a criação de colunas para layout de texto?

- A) `column-count`
- B) `flex-wrap`
- C) `grid-template-columns`
- D) `column-layout`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: A) `column-count`

A propriedade CSS `column-count` é usada para dividir o conteúdo de um elemento em várias colunas, proporcionando um layout similar ao de jornais e revistas. Esta propriedade define o número de colunas desejadas, e o navegador automaticamente distribui o conteúdo entre elas.

```css
.news-article {
  column-count: 3;
  column-gap: 20px;  /* Espaço entre as colunas */
}
```

```html
<div class="news-article">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum.
  Vestibulum lacinia accumsan velit, sit amet vestibulum nunc cursus ut. Sed tincidunt...
</div>
```

</p>
</details>

---

###### 8. Para criar um layout de colunas que automaticamente ajusta o número de colunas baseado na largura do viewport, sem utilizar *media queries*, qual propriedade CSS você deve usar e com qual valor?

- A) `column-count: auto;`
- B) `column-width: 200px;`
- C) `flex-basis: 200px;`
- D) `grid-auto-flow: column;`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: B) `column-width: 200px;`

A propriedade `column-width` no CSS é utilizada para especificar a largura mínima das colunas dentro de um elemento com múltiplas colunas. Ao definir esta propriedade, o navegador distribui automaticamente o número de colunas que cabem no contêiner, sem exceder a largura especificada para cada coluna. Isso permite um ajuste automático do número de colunas baseado na largura do viewport, ideal para layouts responsivos.

Exemplo Prático:

Neste exemplo, o contêiner ajusta o número de colunas automaticamente conforme a largura do viewport aumenta ou diminui, tudo isso sem a necessidade de usar media queries. 

```css
.container {
  column-width: 200px;
  column-gap: 20px;
  width: 100%;
  height: 300px;
  border: 1px solid #000;
  padding: 10px;
}

```

```html
<div class="container">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi.</p>
</div>
```

</p>
</details>

---

###### 9. Qual propriedade CSS é usada para aplicar uma transformação 3D a um elemento?

- A) `transform-3d`
- B) `transform-style`
- C) `perspective`
- D) `transform`

<details><summary><b>Resposta</b></summary>
<p>

#### Resposta: D) `transform`

A propriedade CSS `transform` permite aplicar transformações 2D ou 3D a um elemento, como rotacionar, escalar, mover ou inclinar. Para transformações 3D, você pode usar funções como `rotateX()`, `rotateY()`, `rotateZ()`, `translateZ()`, entre outras, que manipulam o elemento no espaço tridimensional.

Exemplo Prático:

Suponha que você deseja aplicar uma rotação 3D em torno do eixo Y para criar um efeito de virada de cartão quando o usuário passa o mouse sobre o elemento:

```css
.card {
  width: 200px;
  height: 100px;
  background-color: #f0f0f0;
  transition: transform 0.5s;
  transform-style: preserve-3d; /* Mantém o estilo 3D */
}

.card:hover {
  transform: rotateY(180deg); /* Rotação em torno do eixo Y */
}
```

```html
<div class="card">
  Passe o mouse aqui para ver o efeito!
</div>
```

Neste exemplo, quando o usuário passa o mouse sobre o `<div class="card">`, ele rotacionará em torno do eixo Y.

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

