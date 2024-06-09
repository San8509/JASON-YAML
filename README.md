# JASON-YAML introduccion en GitHub
# Informacion de contenido
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
- [JSON](#json)
  - [¿Qué es JSON?](#qué-es-json)
  - [¿Cómo abrir un archivo JSON?](#cómo-abrir-un-archivo-json)
  - [¿Para qué sirve un archivo JSON?](#para-qué-sirve-un-archivo-json)
  - [¿Dónde se utiliza JSON?](#dónde-se-utiliza-json)
  - [Ejemplos de archivos JSON](#ejemplos-de-archivos-json)
    - [Strings](#strings)
    - [Objetos](#objetos)
    - [Arreglos](#arreglos)
    - [Booleanos](#booleanos)
    - [Null](#null)
  
 
> [!CAUTION]
> Warning o Caution si queremos señalar algun tipo de anuncio importante.

## ¿Qué es JSON?
JSON (JavaScript Object Notation) es un formato de texto ligero para el intercambio de datos. Es fácil de leer y escribir para los humanos, y fácil de analizar y generar para las máquinas. JSON se basa en una subconjunto del lenguaje de programación JavaScript, pero es independiente de cualquier lenguaje de programación específico. Es ampliamente utilizado en la transmisión de datos entre un servidor y una aplicación web, sirviendo como una alternativa más sencilla a XML.

## ¿Para qué sirve un archivo JSON?
Un archivo JSON se utiliza para almacenar y transportar datos estructurados. Los archivos JSON son comunes en aplicaciones web, donde se intercambian datos entre un servidor y un cliente. Gracias a su formato legible, JSON es ideal para configuraciones, almacenamiento de datos, y transmisión de información entre servicios.

## Ejemplos de archivos JSON
### Strings
```
{
  "nombre": "Juan",
  "ciudad": "Madrid"
}
```

### Objetos
```
{
  "persona": {
    "nombre": "Ana",
    "edad": 30,
    "ciudad": "Barcelona"
  }
}
```
### Arreglos
```
{
  "frutas": ["Manzana", "Banana", "Naranja"]
}
```
### Booleanos
```
{
  "esActivo": true,
  "esAdmin": false
}
```
### Null
```
{
  "apellido": null
}
```

## ¿Dónde se utiliza JSON?
JSON se utiliza en diversas áreas, incluyendo:
- Aplicaciones web para enviar y recibir datos desde servidores.
- APIs RESTful para la transmisión de datos entre sistemas.
- Configuración de software, donde los archivos JSON almacenan parámetros de configuración.
- Archivos de datos que requieren ser importados o exportados en diferentes aplicaciones y plataformas.
## ¿Cómo abrir un archivo JSON?
Para abrir un archivo JSON, se pueden usar diversos programas y métodos:

- Editores de texto como Notepad++, Sublime Text, o Visual Studio Code.
- Navegadores web que pueden mostrar la estructura JSON.
- Lenguajes de programación como Python, JavaScript, y otros, que tienen bibliotecas para manipular JSON.


## ¿Qué es YAML?
YAML (YAML Ain't Markup Language) es un formato de serialización de datos legible para los humanos, utilizado comúnmente para archivos de configuración. Al igual que JSON, es fácil de leer y escribir, pero tiene una sintaxis más simple y limpia, lo que facilita su uso para los desarrolladores y administradores de sistemas.

## Sintaxis de YAML
YAML utiliza una sintaxis basada en indentación para definir la estructura de los datos, sin el uso de corchetes o comas. Aquí hay un ejemplo básico de un archivo YAML:
```
persona:
  nombre: Ana
  edad: 30
  ciudad: Barcelona

frutas:
  - Manzana
  - Banana
  - Naranja

esActivo: true
apellido: null
```

# Diferencias entre JSON y YAML
- Legibilidad: YAML es generalmente más legible y fácil de escribir para los humanos debido a su sintaxis minimalista, mientras que JSON es más verboso.
- Uso de espacios: YAML depende de la indentación para definir la estructura, mientras que JSON utiliza llaves y corchetes.
- Comentarios: YAML permite comentarios usando #, mientras que JSON no soporta comentarios.
- Compatibilidad: JSON es un subconjunto de JavaScript y es ampliamente soportado en aplicaciones web, mientras que YAML es más común en archivos de configuración.

# Bibliografía
- [JSON](https://blog.hubspot.es/website/que-es-json).
- [YAML](https://www.redhat.com/es/topics/automation/what-is-yaml).
- [Diferencias entre JSON y YAML](https://aws.amazon.com/es/compare/the-difference-between-yaml-and-json/).
