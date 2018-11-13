---
layout: post2
sectionid: 01-03-objetivos-de-seguridad
sectionclass: h2
title: Mapeo de flujos de información
parent-id: 01-fundacion
image: null
---

Tiempo estimado: 90 min

### Justificación
La idea en esta actividad es entender dónde reposa la información, a través de cuales canales se transmite la información, discutir los niveles de seguridad que brindan estos canales, y asociar los objetos de datos mapeados en la actividad anterior para definir factores clave en la construcción de una política de retención de datos.

### Datos de entrada
* Matriz de consecuencias posibles.
* Mapa de datos con impacto por vulneraciones asociadas.

### Productos
Directos
  * Mapa de datos según los lugares en dónde reposan.
  * Mapa de datos según los canales por donde se transmiten.
  * Análisis básico de seguridad de lugares de reposo y canales de transmisión de información.
  * Directivas básicas sobre el manejo de información según su nivel de sensibilidad.

Indirectos
  * Criterios de selección de canales de transmisión y lugares de reposo seguros para la información.
  * Conocimiento de qué canales de transmisión y cuales lugares de reposo se deben emplear con objetos de datos existentes y nuevos.


### Preparación previa
* En caso de realizar la actividad en digital, se sugiere disponer de una hoja de cálculo u otro software con todos los campos y formatos necesarios.

### Materiales
Notas adhesivas y marcadores o un equivalente digital al igual que en las actividades anteriores.
* Hojas de papel grandes.
En caso de realizar la actividad en digital:
   * Computadora
   * Proyector
   * Hoja de cálculo lista para llenar, mostrando los encabezados con sus categorías.

### Instrucciones
1. Pedir a los participantes que piensen y compartan los lugares y dispositivos en donde reposa la información de la organización. Estos pueden ser físicos y digitales, con estos lugares se pueden construir encabezados de columnas como se muestra en la figura:

  ![Grafico](/es/assets/images/ES-Grafico-8.png)

  Lugares de almacenamiento de la información

Algunos ejemplos que pueden ayudar al grupo a desarrollar mejor la lluvia de ideas son:
* Computadoras portátiles y de escritorio.
* Unidades USB.
* Archivadores.
* Discos duros externos.
* Escritorios.
* CDs.
* Servidor interno.
* Servicios de almacenaje en la nube como Dropbox o Google Drive.
* Teléfonos móviles.
* Software administrativo y/o contable.
2. Continuar la lluvia de ideas pero ahora preguntando a los participantes a través de cuáles medios se transmite la información. Agregar las respuestas a la lista anterior como muestra el gráfico:

  Algunos ejemplos que pueden ayudar al grupo a desarrollar mejor la lluvia de ideas son:
  * Correo electrónico convencional.
  * Servicios de mensajería como Whatsapp, Signal o Telegram.
  * Correo físico.
  * Llamadas telefónicas.
  * Mensajes de texto SMS.
  * Servicios de correo cifrado como Protonmail, Hushmail o Tutanota.
  * Redes sociales.
  * Sitio Web.
  * Administración remota de equipos.

   ![Grafico](/es/assets/images/ES-Grafico-9.png)

   Canales de transmisión de la información

3.  Pensando en los encabezados de las columnas escritas como uno de los ejes de una matriz, colocar en el eje vertical los niveles de impacto usados en la actividad anterior:

Debemos tener cuidado de utilizar los mismos niveles de impacto en caso de que hayan sido definidos de diferentes formas a los propuestos en esta guía.

![Grafico](/es/assets/images/ES-Grafico-10.png)

Niveles de impacto

4. Preguntar por los objetos de datos en cada nivel de impacto en donde se almacenan o se transmiten. Se recomienda no tomar nota de cada objeto de datos, sino marcar cada coincidencia de nivel de impacto asociado con el lugar de almacenaje o medio de transmisión de información. idealmente se recomienda tener la matriz en una hoja grande papel que permita marcar con X en los lugares que corresponda como se muestra en el gráfico.
  * Este paso puede ser largo, hay que tomar previsiones en la planificación de la agenda.
  * Puede ayudar tener las notas adhesivas o equivalentes de la actividad anterior para los objetos de datos por nivel de impacto como guía visual para los participantes.

  5. Introducir los conceptos que sean pertinentes sobre seguridad para lugares de almacenamiento y canales de transmisión según los items que se tengan como lugares de almacenaje y medios de transmisión de información.
    * Cifrado.
    * Cifrado punto a punto.
    * Seguros, candados, cajas fuertes, etc.
    * Accesibilidad de recursos (Quién tiene acceso a qué).
    * Consideraciones de servicios en la nube.
    * etc.

  El éxito de este paso está muy relacionado con el conocimiento que tengan el facilitador y el grupo sobre los equipos y servicios utilizados. Puede suceder que en alguna actividad aparezcan servicios que el facilitador desconoce, es importante tener la capacidad de preguntar al grupo lo que sepan y de investigar por cuenta propia cualquier consideración de seguridad pertinente al item desconocido.

  ![Grafico](/assets/images/EN-Graphic-11.png)

  Medios de almacenaje y transmisión de datos por nivel de impacto actualmente empleados por la organización

6.  Discutir con el grupo si hay canales que se consideren inseguros donde información sensible se almacene o transmita. Algunas preguntas clave pueden ser:
  * ¿Algunos de los anteriores se consideran canales inseguros?.
  * ¿Algunos de estos lugares de almacenaje son de facil acceso para personas no autorizadas?.

  ![Grafico](/assets/images/EN-Graphic-12.png)

  Discusión de mapa de datos

7.  Plantear al grupo una modificación en la matriz en donde se defina qué tipo de información por nivel de impacto debe estar en cada columna de la matriz, y las consideraciones pertinetes en cada caso (si un equipo debe estar cifrado para contener cierta información, si se debe usar VPN o https para acceder a un recurso específico, etc.). El uso de otro color puede ser beneficioso para trabajar sobre la misma matriz, facilita la actividad para ver mejor las diferencias entre lo que se hace actualmente en la organización y lo que se debería hacer desde ese momento en adelante.

![Grafico](/assets/images/EN-Graphic-13.png)

Medios de almacenaje y transmisión de datos por nivel de impacto propuesto para la organización  

### Cierre de la actividad
Al finalizar la actividad se puede discutir y hacer énfasis en lo que se logró:
* Se mapearon todas las formas de comunicación y los lugares de reposo de la información.
* Se asociaron los objetos de datos de la organización en estos canales y lugares de reposo.
* Se inició la discusión sobre el nivel de seguridad de los medios usados para guardar y transmitir información y se establecieron algunas premisas básicas desde donde se construirá la política de retención de datos de la organización.

Es necesario tomar en cuenta que para elaborar una política de retención de datos completa es importante considerar otras cosas además de los medios de almacenamiento y comunicación de los objetos de datos, por ejemplo:
* Por cuánto tiempo cada objeto de datos debe ser guardado (caducidad de la información).
* De qué forma se deben borrar los objetos de datos por caducidad. Ejemplo: procesar estadísticas anuales de denuncias que se van a borrar.
* Quiénes manejan la información: implementación del principio del mínimo privilegio.
* Quiénes son responsables de la generación, almacenamiento y custodia de la información.

### Referencias

<ul class="ref-ul">

<li><a target="_blank" href="https://ssd.eff.org/es/module/%C2%BFqu%C3%A9-es-el-cifrado"><div class="ref-1">R7: </div>Que es Cifrado? - Surveillance Self Defense EFF</a>

</li>
<li><a target="_blank" href="https://securityinabox.org/es/guide/secure-file-storage/"><div class="ref-1">R8: </div>Proteger los archivos sensibles en tu Computadora</a>
</li>

<li><a target="_blank" href="https://ssd.eff.org/es/module/comunic%C3%A1ndote-con-otros#1"><div class="ref-1">R9: </div>Comunicandote con otros - cifrado punto-a-punto - Surveillance Self Defense EFF</a>

</li>
<li><a target="_blank" href="https://www.eff.org/node/82654"><div class="ref-1">R10: </div>Secure Messaging Scorecard - Evaluación de servicios de mensajería instantánea EFF</a> - Aunque se encuentra desactualizada sigue siendo un recurso valioso de consultar.
</li>

</ul>
