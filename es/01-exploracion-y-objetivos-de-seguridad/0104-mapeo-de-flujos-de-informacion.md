---
sectionid: 01-03-objetivos-de-seguridad
sectionclass: h2
title: Mapeo de flujos de información
parent-id: 01-fundacion
---

* ¿En dónde reposa la información?
* ¿Por donde se transmite la información?
* ¿Algunos de los anteriores se consideran canales inseguros?
* ¿Quiénes manejan la información vs quiénes deberían manejarla? - Mínimo privilegio (explicar ventajas)

7. Mapeo de dispositivos y canales de comunicación usados.
8. Mapeo de personas que manejan las piezas.
9. Cruzar la información completa para generar directivas.

### Justificación
La idea en esta actividad es entender en dónde reposa la informacion, por qué canales se transmite, discutir los niveles de seguridad que brindan estos canales y asociarlos a los objetos de datos que se mapearon en la actividad anterior para definir factores clave en la construcción de una política de retención de datos

### Datos de entrada
* Matriz de consecuencias posibles.
* Mapa de datos con impacto por vulneraciones asociadas.

### Productos
* Directos
  * Mapa de datos según los lugares en dónde reposan
  * Mapa de datos según los canales por donde se transmiten
  * Análisis básico de seguridad de lugares de reposo y canales de transmisión de información
  * Directivas básicas sobre el manejo de información según su nivel de sensibilidad
* Indirectos
  * Criterios de selección de canales de transmisión y lugares de reposo seguros para la información
  * Conocimiento de qué canales de transmisión y lugares de reposo se deben emplear con objetos de datos existentes y nuevos

### Actividades propuestas

#### Mapa y directivas iniciales de retención de datos
Tiempo estimado: XX min

##### Preparación previa


##### Materiales
* Notas adhesivas y marcadores o un equivalente digital al igual que en las actividades anteriores
* Hoja grande y solo x en matriz

##### Instrucciones
1. eje horizontal con lugares de reposo (Grafico)
2. agregar a eje horizontal canales de transmisión (Grafico)
3. usar de eje vertical el mismo de consecuencias de la actividad anterior (Grafico)
4. Preguntar por los objetos de datos en cada categoría en donde se almacenar o transmiten (paso laaargo, solo marcar con X) (Grafico)
5. Introducir los conceptos que sean pertinentes sobre seguridad para lugares de almacenamiento y canales de transmisión
  * Cifrado
  * Cifrado punto a punto
  * Seguros, candados, cajas, etc.
  * Accesibilidad de recursos
  * etc.
6. Discutir con el grupo si hay canales que se consideran inseguros y donde información sensible se almacene o transmita (Grafico "comentado")
7. plantear una modificación en la matriz en donde se defina qué tipo de información por sensibilidad debe estar en cada columna de la matriz y consideraciones de esas columnas (que un equipo debe estar cifrado, que se debe usar VPN o https para acceder a x recurso, etc.). El uso de otro color puede ser beneficioso para trabajar sobre la misma matriz y ver las diferencias entre lo que se hace y lo que se debería hacer de ahí en adelante (Grafico)

##### Cierre de la actividad
Al finalizar la actividad se puede discutir y hacer énfasis en lo que se logró:
* Se mapearon todas las formas de comunicación y los lugares de reposo de la información
* Se asociaron los objetos de datos de la organización en estos canales y lugares de reposo
* Se inició la discusión sobre el nivel de seguridad de los medios usados para guardar y transmitir información y se establecieron algunas premisas básicas desde donde se construirá la política de retención de datos de la organización

Hay que tomar en cuenta que para elaborar una política de retención de datos completa es importante considerar además de los medios de almacenamiento y comunicación de los objetos de datos:
* Por cuánto tiempo cada objeto de datos debe ser guardado (caducidad de la información)
  * Al momento de borrar los objetos de datos por caducidad se deben procesar de alguna forma?
    * Ejemplo: procesar estadísticas anuales de denuncias que se van a borrar
* Quiénes manejan la información: considerando el principio del mínimo privilegio
* Quiénes son responsables de la generación, almacenamiento y custodia de la información.

### Referencias
*
