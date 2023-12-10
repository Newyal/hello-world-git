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

# Formatos de énfasis
- letra *italica* de la primera forma.
- letra _italica_ de la segunda forma.
- letra **strong o bold** de la segunda forma.
- letra __strong o bold__ de la segunda forma.
- letra ~~tachado~~, formato normal.
aqui podemos usar *forato itálico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada 
- Esto es un item de lista desordenada 
- Esto es un item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://logos-marques.com/wp-content/uploads/2021/03/GitHub-Embleme.png)

# Code Snippets

Código en Jason
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
Código en Javascript
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
```
# Tablas
| Nombre | Apellidos | Documento |
| ------ | --------- | --------- |
| Maxi | Burgos | 3425565 |
| Tomas | Tompson | 234524 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas divisoras
Esto es un texto que será dividido por guiones

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guiones bajos

___

# Saltos de línea (line breaks)
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- lista
