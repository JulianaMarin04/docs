# Formatos de cabeceras
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6

Subrayado 1
----------

Subrayado 2
===========

# Formatos de enfasis de textos
- Formato de letra *italica* de la primer forma
- Formato de letra _italica_ de la segunda forma
- Formato negrita **bold o strong** primera forma
- Formato negrita __bol o strong__ segunda forma
- Tachado de texto ~~Tachado~~

# Listas
1. item 1 lista ordenada
2. item 2 lista ordenada
2. item 3 lista ordenada
2. item 4 lista ordenada

- lista con viñetas
- lista con viñetas

# Links - Enlaces
- <a href="http://google.com"> Esto es un link en html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un links al index](index.html)

# Imagenes
![Descripcion de la imagen -> url donde se encuentra la imagen](https://kinsta.com/es/wp-content/uploads/sites/8/2018/05/qu%C3%A9-es-github-1.png)


# Fragmentos de codigo
 Codigo en JSON
```JSON
 [
    {
        "title": "apples",
        "count": [12000,20000],
        "description": {"text": "...", "sensitive": false}
    },
    {
         "title": "oranges",
        "count": [17500, null],
        "description": {"text": "...", "sensitive": false}
    }
 ]
```

Codigo en JavaScript
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
| Juliana| Marin | 123125 |
| Pepito | Perez | 458568 |


# Citas 
Esto es un texto que hace referencia a la realizacion de una cita:
> Esto es una sita, para salir de ella dos veces enter 

Hola mundo esto ya no es una cita
