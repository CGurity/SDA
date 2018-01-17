---
sectionid: 01-03-objetivos-de-seguridad
sectionclass: h2
title: Information-flow-mapping 
parent-id: 01-fundacion
---

### Justification
The main idea in this activity is to understand where the information lies, through which channels the information is transmitted, also to discuss the levels of security provided by these channels, and to associate data objects mapped in the previous activity in order to define key factors towards the construction of a data retention policy.

### Input data
* Matrix of possible consequences.
* Data map depicting impact due to associated violations.

### Products
* Direct
  * Data map listing places where information lies.
  * Data map listing channels through which information is transmitted.
  * Basic security analysis according to where information lies and through which channels information is transmitted.
  * Basic directives about handling of information according to their level of sensitivity.
* Indirect
   * Criteria for selecting secure transmission channels and storage places.
   * Knowledge of which transmission channels and places should be used for existing and new data objects.

### Proposed activities

### Mapping and initial data retention policies
estimated time: 45 min

### Previous planning

### Materials
* Post-its or sticky notes and markers or a digital equivalent as in previous activities.
* Large sheet and only x on matrix.
### Instructions
1. Ask the participants to think and share places and devices where the data of the organization is stored. These can be on paper, digitally or in any other way. Now you can build column headers as shown in the figure:
  ![Grafico](../img/bocetos-sda-0104-1.png)
 Some examples that may help the group to a better developed brainstorming are:
   * Laptops and desktops.
   * USB drives.
   * Filing cabinets.
   * External hard drives.
   * Desks
   * CDs.
   * Internal server.
   * Cloud storage services such as Dropbox or Google Drive.
   * Mobile phones.
   * Administrative and / or accounting software.
2. Continue the brainstorming but now ask the participants through which means the information is transmitted. Add answers to the previous list as the chart shows:
  ![Grafico](../img/bocetos-sda-0104-2.png)
 Some examples that may help the group to experience a better developed brainstorming are:
   * Conventional email.
   * Messaging services such as WhatsApp, Signal or Telegram.
   * Traditional mail service.
   * Phone calls.
   * SMS text messages.
   * Encrypted email services such as Protonmail, Hushmail or Tutanota.
   * Social networks.
   * Website.
   * Remote management of equipment.
3. Thinking about the headings of the columns written as one of the axes of a matrix, place on the vertical axis levels of impact used in the previous activity:
  ![Grafico](../img/bocetos-sda-0104-3.png)
It is important to use the same levels of impact if  the participants defined differently to those proposed in this guide.

4. Ask about the data objects in each level of impact where they are stored or transmitted. It is recommended not to take note of each data object, but to mark each coincidence of impact level associated with the storage location or means to transmit data. Ideally it is recommended drawing the matrix on a large sheet of paper that allows to mark with X in the corresponding places as shown in the graph.
* This step can be long, so you must take precautions when planning.
* It may help to have the post-its, sticky notes or equivalents of the previous activity for the data objects by impact level as a visual guide for the participants.
  ![Grafico](../img/bocetos-sda-0104-4.png)
5. Introduce pertinent concepts about security for storage places and transmission channels according to the items held as storage places and means to transmit data.
 * Encryption
 * Point to point encryption.
 * Insurance, locks, safes, etc.
 * Accessibility of resources (Who has access to what).
 * Considerations of services in the cloud.
 * etc.

 Success of this step is closely related to the knowledge that the facilitator as well as the group own about the equipment and services used. It may happen that in some activities there are services that the facilitator does not know about. It is important to ask the group not only what they know but also to investigate any security considerations pertinent to unknown items.
  
6. Discuss along with the group if there are considered unsecure channels in which sensitive information is stored or transmitted. Some key questions can be:
* Are some of the above considered unsecure channels ?.
* Are some of these storage places easy to access for unauthorized people?.
  ![Grafico](../img/bocetos-sda-0104-5.png)
7. Suggest to the group a modification in the matrix where it is defined what type of information per level of impact should be in each column, and the pertinent considerations in each case (if a computer must be encrypted to contain certain information, if you must use VPN or https to access a specific resource, etc.). The use of another color can be effective and useful to work on the same matrix, makes  the activity easier to see the differences between what is currently done in the organization and what should be done from that moment on.
  ![Grafico](../img/bocetos-sda-0104-6.png)

### Closure of the activity
At the end of the activity you may discuss and emphasize all what has been achieved:
* Sereral forms of communication and places for data storage were mapped.
* The data objects of the organization were associated in channels and storage places.
* Discussion began based on the level of security of the means used to store and transmit data, and establish basic premises from which the data retention policy of the organization will be built on.

It is necessary to take into account that in order to elaborate a complete data retention policy it is important to consider other things besides the means of storage and communication of the data objects, for example:
* For how long each data object should be in storage (expiration of data).
* How data objects should be deleted by expiration.
  * E.g.,: Prepare annual reports of complaints that will be deleted.
* Who manages the data: implementation of the principle of minimum privilege.
* Who are the decision-makers in terms of creation, storage and custody of the data.

### References
* [¿Qué es el cifrado? - Surveillance Self Defense | EFF](https://ssd.eff.org/es/module/%C2%BFqu%C3%A9-es-el-cifrado)
* [Proteger los archivos sensibles en tu computadora - Cifrado de archivos | Security in a box](https://securityinabox.org/es/guide/secure-file-storage/)
* [Comunicándote con otros - Cifrado punto a punto - Surveillance Self Defense | EFF](https://ssd.eff.org/es/module/comunic%C3%A1ndote-con-otros#1)
* [Secure Messaging Scorecard - Evaluación de servicios de mensajería instantánea | EFF](https://www.eff.org/node/82654) - Aunque se encuentra desactualizada sigue siendo un recurso valioso de consultar
