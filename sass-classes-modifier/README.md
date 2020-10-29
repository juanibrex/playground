# Optimizar clases redundantes con SASS

Minimiza las clases redundantes en el 'html' pero termina sin respetar la metodología BEM 🤷🏻.

## Ejemplo

```css
.button{
  color: red;

  &--primary{
    @extend .button;
    color: yellow;
  }
}
```

## Fuentes
+ https://twitter.com/fenavente/status/1302696948353433600/photo/1
