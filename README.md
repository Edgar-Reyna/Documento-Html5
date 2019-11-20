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

```
<label>Nombre:</label> 
<input type="text"  size="15"/>
```

![Label Input](label.jpg "Label e Input")

### Checkbox y Radio

```
<input type="checkbox" checked/>Seleccionada
<input type="checkbox" />Sin marcar
<input type="radio" checked/>Seleccionada
<input type="radio"/>Sin marcar
```
![Checkbox Radio](checkbox.jpg "Checkbox y Radio")

### Select

```
<select>
    <option value="opcion 1">Opcion1
    <option value="opcion 2" selected>Opcion2
    <option value="opcion 3">Opcion3
</select>
```
![Select](select.jpg "Select")


### Tablas

```
<table>
    <thead>
        <tr>
            <th>Columna 1</th>
            <th>Columna 2</th>
            <th>Columna 3</th>
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

| Columna 1 | Columna 2 | Columna 3 |
|:---:|:---:|:---:|
|1|2|3|
|4|5|6|

