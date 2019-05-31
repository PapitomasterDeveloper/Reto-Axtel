# Reto-Axtel
Un ingeniero de datos encargado de la supervisión del trafico de red, necesita realizar reportes de cantidad de ancho de banda utilizado a lo largo de un periodo de fechas.
Actualmente el ingeniero, utiliza comandos para calcular la cantidad de trafico (MB’s, GB’s) de manera diaria y los inserta en un Excel:
- El hostname del router
- IP
- Ubicación (ciudad)
- Trafico del día

Guarda un histórico para generar graficas que le permiten saber:
- La cantidad total de trafico en un periodo de tiempo de todos los routers.
- El router que mas trafico procesa en un periodo de tiempo.
- El mes con mas trafico de todos los routers.
- Trafico por cada ciudad en un periodo de tiempo.

Su misión, si deciden aceptarla, será crear un aplicativo que abarque dos necesidades:

1. Graficación de datos.
2. Alta de nuevos equipos.
3. Al menos 50 routers tienen que ser monitoreados.
4. Necesitamos un lugar donde podamos dar de alta nuevos routers para monitorear.
5. Necesitamos algún entorno que nos pueda graficar los reportes solicitados anteriormente.
6. Como parte del alcance, necesitamos un API Restful con algún tipo seguridad (a su elección) que permita hacer peticiones regresando los siguientes datos: 
   - Si recibe el campo router=IP, regresara la información del router junto con el trafico total.
   - Si recibe el campo router=IP,dateini=fecha,enddate=fecha, regresa la información del router junto con el trafico de ese rango de fechas.
   - Importante mencionar el manejo de errores en API’s.
