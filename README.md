### Uso

- La app es creada con el fin de visualizar fallas tipicas en las unidades de la linea de produccion
- En la primera pantalla podemos encontrar tres botones para interactuar con la app
-En la primera seccion de cargar fallas podemos ingresar para cargar alguna nueva falla
- Dentro de la seccion carga podemos ingresar los datos generales de la falla como lo es el ID, nombre de la falla, observaciones.
- Tambien contamos con la opcion de limpiar para borrar todos los files que escibimos anteriormente
-Tenemos un boton de guardar para poder guardar los datos en la base
- En la seccion ver fallas podemos visualizar las fallas que ya se encuentran previamente guardadas

## algunos comando en su son:
- this.fecha_insertar = fecha_insertar;
        this.nombre_usuario = nombre_usuario;
        this.unaFalla = unaFalla;
- public NombreFalla(String nombre, int unidad) {
        this.nombre = nombre;
        this.unidad = unidad;
-public static void main(String[] args) {
        Principal princ = new Principal();
        princ.setVisible(true);
        princ.setLocationRelativeTo(null);

## Requerimientos
- ApacheNeatbeas
- Windows verios mayor a windows 10

## Instalacion
- La instalacion es basica la cual podemos encontrar todos los archivos en el repositorio.
- importante verifiacr que todas las dependencias de los reuqerimientos se descarguen corrrectamente.

## Contribucion
1. Boton de carga de datos.
2. Boton de ver datos
3. Boton de salir.
4. ID Falla
5. Nombre de falla.
6. Posible solucion.
7. Observaciones.
8. Limpiar
10. Guardar.

## Roadmap
- Se agregara el nombre de usuario.
- Modificacion de contraseña.
- Fecha de la agregacion de la falla.
- Identificacion de la unidad.
- la base de datos se agrega con mySQL.
- Se agreagan funciones como **Falla ya agregada** para evitar repetir la falla
- Las funcionalidades de **Salir** arrojara el mensaje **¿seguro que quieres salir de la aplicacion?**



<p>
Espero que la app sea de una gran utilidad
<p>

</p>
