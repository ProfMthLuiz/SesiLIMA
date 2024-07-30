<h2>Seletor Universal ( * )</h2>

```
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
```

<p>Este seletor aplica os estilos a todos os elementos na página.</p>

<br>
<br>

<h2>Seletor de Classe ( . )</h2>

```
.section p {
  font-size: 25px;
}
```

<p>Este seletor aplica os estilos a todos os elementos <p> que são filhos de um elemento com a classe section.</p>

<br>
<br>

<h2>Seletor Filho ( > )</h2>

```
.section > p {
  text-shadow: 2px 2px #000;
}
```

<p>Este seletor aplica os estilos a todos os elementos <p> que são filhos diretos de um elemento com a classe section.</p>

<br>
<br>

<h2>Seletor de Irmãos Adjacentes ( + )</h2>

```
.section h1 + p {
  text-transform: uppercase;
}
```

<p>Este seletor aplica os estilos ao elemento <p> que é imediatamente precedido por um elemento <h1> dentro de um elemento com a classe section.</p>

<br>
<br>

<h2>Seletor Geral de Irmãos ( ~ )</h2>

```
.section h1 ~ p {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
```

<p>Este seletor aplica os estilos a todos os elementos <p> que são precedidos por um elemento <h1> dentro de um elemento com a classe section.</p>

<br>
<br>

<h2>Seletor de Atributo ( a[href^="https"] )</h2>

```
a[href^="https"] {
  color: red;
}
```

<p>Este seletor aplica os estilos a todos os elementos <a> cujo atributo href começa com "https".</p>

<br>
<br>

<h2>Seletor de Elemento ( tag )</h2>

```
h2 {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  color: aquamarine;
  text-shadow: 2px 2px red;
  font-weight: 100;
}
```

<p>Este seletor aplica os estilos a todos os elementos <h2>.</p>

<br>
<br>

<h2>Seletores Agrupados ( , )</h2>

```
h3,
h4 {
  font-size: 25px;
  color: brown;
}
```

<p>Estes seletores aplicam os mesmos estilos aos elementos <h3> e <h4>.</p>

<br>
<br>
