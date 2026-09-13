# Texto

## Hierarquia de títulos

HTML possui 6 níveis de títulos, do `<h1>` ao `<h6>`.

```html
<h1>Título principal</h1>
<h2>Seção</h2>
<h3>Subseção</h3>
```

A hierarquia deve representar a **estrutura do conteúdo**, e não apenas o tamanho do texto.

## Parágrafos

```html
<p>Este é um parágrafo.</p>
```

## Quebra de linha

```html
<br>
```

Quebra a linha sem criar um novo parágrafo.

## Negrito e ênfase

### Não semânticas

```html
<b>Texto em negrito</b>
<i>Texto em itálico</i>
```

Alteram principalmente a aparência.

### Semânticas

```html
<strong>Texto importante</strong>
<em>Texto enfatizado</em>
```

Além da aparência, indicam o **significado** do conteúdo.

## Texto marcado

```html
<mark>Texto marcado</mark>
```

Destaca um trecho de texto.

## Texto grande e pequeno

```html
<big>Texto grande</big>
<small>Texto pequeno</small>
```

`<small>` é usado para textos de menor importância, como observações ou informações complementares.

> `<big>` é uma tag antiga e não deve ser usada em HTML moderno. Para controlar tamanho, utilize CSS.

## Texto deletado e inserido

```html
<del>Texto removido</del>
<ins>Texto inserido</ins>
```

* `<del>` → indica conteúdo removido
* `<ins>` → indica conteúdo adicionado

## Sobrescrito e subscrito

### Sobrescrito

```html
x<sup>2</sup>
```

Resultado: x²

Usado para expoentes e outras informações acima da linha.

### Subscrito

```html
H<sub>2</sub>O
```

Resultado: H₂O

Usado para fórmulas químicas e outras informações abaixo da linha.

## Resumo

```text
<h1> - <h6> → títulos
<p>           → parágrafo
<br>          → quebra de linha

<b>           → negrito visual
<strong>      → importância

<i>           → itálico visual
<em>          → ênfase

<mark>        → texto marcado
<small>       → texto menor/complementar
<del>         → texto removido
<ins>         → texto inserido
<sup>         → sobrescrito
<sub>         → subscrito
```

> **Prefira tags semânticas quando elas representam o significado do conteúdo.**
