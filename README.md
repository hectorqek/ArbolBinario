# ArbolBinario

1.	Abrir la Solución en Visual Studio > 2017, la cual está en la carpeta TreeBinary  TreeBinary.sln.
2.	Colocar como proyecto de inicio APITreeBInary.
3.  Compilar la solución.
4.	Ejecutar la Aplicación.
5.	Al iniciar, diríjase al menú Api, el cual desplegara una pantalla con dos enlaces de información de los 2 Api.
6.	Al ingresar cada uno contara con el apartado Request Formats / (application/json, text/json) el cual es que usaremos para validar el funcionamiento del Api.
7.	Ingresar a la aplicación Postman el cual nos permitirá testear los API.

Api1: Url
http://localhost:64330/api/TreeBinary/CreateTreeBinary
Request:
{
  "treeBinary": [
    "34",
    "36"
  ]
}


Api2: Url
http://localhost:64330/api/TreeBinary/ParentNode
Request:
{
  "treeBinary": [
    "67",
    "76",
    "85",
    "39",
    "74",
    "83",
    "28",
    "44",
    "87",
    "29",
  ],
  "NodoOne": "74",
  "NodoTwo": "28"
}
