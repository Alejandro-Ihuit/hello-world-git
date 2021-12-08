# VERSIÓN DEL CURSO
## Versión actual: 1.2.2

# CABECERAZ
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4 
##### Cabecera H5
###### Cabecera H6

Underline 1
-----------
Underline 2
===========
Emphasys
=====
- formato italica *forma 1*
- formato italica _forma 2_
-  formato bold o strong **forma 1** o __forma 2__
-  formato tachado ~~ejemplo~~
# LISTAS
Lista ordenada
1. Item
2. Item 
3. Item

Lista desordenadas se usan guión medio
- Item 1 desordenado
- Item 2
- Item 3

# LINKS
- <a href="http://www.google.com">Link convencional de HTML</a>
- [Link en markdown](http://www.google.com)

# IMAGENES
![Logo Github](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

# Code Snippets
Sirve para resaltar porciones de código p.ej:
###### NOTA: Se tiene que escribir el tipo de lenguaje despues de las tildes invertidas de la parte superior (```JSON).
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
Ej. 2 con JS
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
# TABLAS
| Persona | Apellido | Documento |
|---------|----------|-----------|
|Alejandro|  Ihuit   |    INE    |
|Daniel   |  Peraza  |  TELMEX   |

# *Blockquotes* o citas
Se emplea con el signo de mayor ej:
> JavaScript es un lenguaje de tipado dinámico

# Líneas divisoras
Existen tres formas mediante guiones medios, asteriscos o guiones bajos en grupos de 3 ej:

Texto de ejemplo que está dividido por guiones medios 

---
Texto de ejemplo dividido por asteriscos
***
Otro texto, con guiones bajos
___




# Saltos de línea (o *line breaks*), 
simple *enter*, para usarlos

Esto sería un primer párrafo.

Esto sería un segundo párrafo.