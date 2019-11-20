# Guia Basica para crear Paginas WEB
* [x] Estructura del documento html5
* [x] Principales etiquetas
* [ ] Agregando estilos con CSS
* [ ] Agregando funcionalidad con scripts
* [ ] Envio y recibo de datos entre paginas web
* [ ] Conectar con Base de datos MySQL
* [ ] Programacion PHP
* [ ] CRUD PHP MySQL Servidor Local
* [ ] ...

# Estructura documento HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Titulo del documento</title>
        <!-- Estilos CSS dentro del documento -->
        <style>
            /* estilos */
            body{background-color:color;}
        </style>

        <!-- Estilos CSS desde otro documento -->
        <link rel="stylesheet" type="text/css" href="estilos.css">
    </head>
    <body>

    <!-- Cuerpo del Documento -->
    Etiquetas, Inputs, Select, Tablas, Formularios, Checkbox, etc

    <!-- Carga de scripts al finalizar la carga del documento -->
    <script>
        function nombre_de_la_funcion(){
            <!-- codigo del script-->
        }
    </script>

    <!-- Carga de scripts desde otro documento -->
    <script type="text/javascript" src="scripts.js"></script>
    </body>
</html>
```

***

# Etiquetas html

### Label e Input
```html
<label>Nombre:</label> 
<input type="text"  size="15"/>
```
![Label Input](label.jpg "Label e Input")

### Checkbox y Radio
```html
<input type="checkbox" checked/>Seleccionada
<input type="checkbox" />Sin marcar

<input type="radio" checked/>Seleccionada
<input type="radio"/>Sin marcar
```
![Checkbox Radio](checkbox.jpg "Checkbox y Radio")

### Select
```html
<select>
    <option value="opcion 1">Opcion1
    <option value="opcion 2" selected>Opcion2
    <option value="opcion 3">Opcion3
</select>
```
![Select](select.jpg "Select")


### Tablas
```html
<table>
    <thead>
        <tr>
            <th>Titulo Columna 1</th>
            <th>Titulo Columna 2</th>
            <th>Titulo Columna 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr>
            <td>4</td>
            <td>5</td>
            <td>6</td>
        </tr>
    </tbody>
</table>
```
| Titulo Columna 1 | Titulo Columna 2 | Titulo Columna 3 |
|:---:|:---:|:---:|
|1|2|3|
|4|5|6|

### Textarea
```html
<textarea cols="50" rows="15">Contenido...</textarea>
```
![textarea](textarea.jpg "textarea")

### Formularios
```html
<form action="url documento, script, etc" method="POST o GET">
    <label>Nombre:</label> <input type="text"/><br/><br/>
    <label>Apellido:</label> <input type="text"/><br/><br/>
    <label>Edad:</label> <input type="text"/><br/><br/>
    <input type="submit" value="Aceptar"/>
</form>
```
![formulario](formulario.jpg "formulario")

***
