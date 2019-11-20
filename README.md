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

### <span style="color:orange;">Label e Input</span>

```
<label>Nombre:</label> 
<input type="text"  size="15"/>
```

![Label Input](label.jpg "Label e Input")

### <span style="color:orange;">Checkbox y Radio</span>

```
<input type="checkbox" checked/>Seleccionada
<input type="checkbox" />Sin marcar
<input type="radio" checked/>Seleccionada
<input type="radio"/>Sin marcar
```
![Checkbox Radio](checkbox.jpg "Checkbox y Radio")

### <span style="color:orange;">Select</span>

```
<select>
    <option value="opcion 1">Opcion1
    <option value="opcion 2" selected>Opcion2
</select>
```
![Select](select.jpg "Select")

