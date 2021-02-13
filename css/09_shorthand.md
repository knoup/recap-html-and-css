# Shorthand

* Junção de propriedades
* Resumido
* legível

```css
{
    /* background properties */
    background-color: #000;
    background-image: url(images/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* background shorthand */
    background: #00 url(image/bg.gif) no-repeat left top;


    /* font properties */
    font-style: italic;
    font-weight: bold;
    font-size: .8em;
    line-height: 1.2;
    font-family: Arial, sans-serif;

    /* font shorthand */
    font: italic bold .8em/1.2 Arial, sans-serif;
}

```

## Detalhes

* Não irá considerar propriedades anteriores.
* Valores não especificados irão assumir o valor padrão.
* Geralmmente, a ordem descrita não importa, mas se houver muitas propriedades com valores semelhantes, pode haver problema.