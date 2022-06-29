# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de Enfasis
- formato *italica* de la primera forma
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~, formato normal.
- Aqui podemos usar el *formato italico*, pero tambien **bold** y el ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en MarkDown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTFT1MO4Ln0Ynz4VKkD2EDyylsYzoVg1d8FiQ&usqp=CAU)

# Code Snippets
Codigo en Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Miguel | Rios | 402366371 |
| Angel  | Adar | 173663204 |

