# - Versión del curso
Versión actual: 1.2.2

# - Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# - Subrayados
Underline 1
---------------

Underline 2
===============

# - Formatos de énfasis
- Formato *itálica* de una forma.
- Formato _itálica_ de otra forma.

- Formato __negrita__ de una forma.
- Formato **negrita** de otra forma.

- Formato ~~tachado~~.

# - Listas
1. Esto es un item
2. Esto es un item
3. Esto es un item

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# - Enlaces
- <a href ="http://www.google.com" title="">Esto es un enlace en HTML</a>
- [Esto es un enlace en Markdown](http://www.google.com)
- [Esto es un enlace al index](index.html)

# - Imágenes
![Logo GitHub](https://www.numipage.com/wp-content/uploads/2016/10/github-logo.png)

# - Code snippets
Código en JSON
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

Código en javascript
```javascript
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

# - Tablas
| Nombre | Apellidos | Documento |
| ------ | --------- | --------- |
| Nacho  | Diez-Quijada Argaya | 29394950-S |
| Paco  | Martínez | 466276367-S |
| Paco  | Martínez | 466276367-S |
| Nacho  | Diez-Quijada Argaya | 29394950-S |

# - Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita. Darle dos intros para "salir" de la cita.

Esto es otro texto fuera de la cita:
> Esto es otra cita

# - Líneas divisoras
Esto es un texto separado por una línea hecha con guiones medios

---

Esto es un texto separado por una línea hecha con asteriscos

***

Esto es un texto separado por una línea hecha con guiones bajos

___

# - Saltos de línea
Esto es nuestro primer párrafo.

```
El intro tiene que ser doble para que se vea el espacio. Si es simple el texto va a continuación y no hace salto de línea como ocurre abajo.
```

Esto es nuestro segundo párrafo.
Esto es nuestro tercer párrafo.


