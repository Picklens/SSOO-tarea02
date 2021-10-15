# SSOO-tarea02

##### AUTOR: Benjamin Alejandro Leon Gonzalez

##### CORREO: benjamin.leong@alumnos.uv.cl

Lo primero que hacemos es extraer los datos de https://api.warframe.market/v1/items con el comando **curl**, los datos estan en formato json. Al tener los datos en formato json podemos usar **jq** para filtrar lo que necesitamos, en este caso solo necesitamos 'id' y 'item_name' que se encuentran dentro de este archivo, por lo que eliminamos los datos que no necesitamos ('url_name' y 'thumb') con el comando **del**. Al realizar esto, redirecionamos los datos con el comando **>>** al archivo creado con el nombre 'items.json'. Al terminar todo el proceso, se muestra la frase 'JSON CREADO CON EXITO'.

