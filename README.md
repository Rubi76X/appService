# Hospedar aplicaciones web

##### Azure App Service le permite **crear y hospedar aplicaciones web, back-ends móviles y API RESTful** en el lenguaje de programación que prefiera sin tener que administrar la infraestructura. Ofrece escalado automático y alta disponibilidad, es compatible con Windows y Linux y permite implementaciones automatizadas desde GitHub, Azure DevOps o cualquier repositorio Git

##### En la práctica se hospedo una página web de un restaurante, la cual se encontraba almacenada en un repositorio de github. La implementación se realizo desde el azure portal.

### Paso 1: Crear recurso
##### Se creó un recurso de app service
![](/src/P1.png)

### Paso 2: Ingresar datos basicos
##### Se le deben indicar ciertos datos basicos, como el nombre del grupo del recurso, el nombre la aplicación web, el tipo de lenguaje que utiliza, la región y el tamaño. Este ultimo determina el precio de la página. La aplicación se puede perzonalizar de manera mas completa, configurando la red, etiquetad para una mejor organización, etc, pero para la práctica solo se configuraron los datos basicos. 
![](/src/P2.png)

### Paso 3: Crear
##### Despues de ingresar los datos basicos, se le da en le boton revisar y crear y al pasar unos minutos el recurso estara implementado y listo para su configuración.
![](/src/P3.png)
![](/src/P3.1.png)

### Paso 4: Centro de implementación
##### Para conectar el repositorio remoto de github a azure, se configuro en el centro de inplementación, en el cual se inicio sesion en la cuenta de github y posterior de indico el nombre del repositorio asi como la rama en la que se encontraba.
![](/src/P4.png)
![](/src/P4.1.png)

### Paso 5: Cargar página
##### Despues de guardar los cambios, la página comienza a cargarse, esto se muestra en el apartado actions, dentro del repositorio de github
![](/src/P5.png)
![](/src/P5.1.png)

### Paso 6: Página hospedada
##### En github se puede visualizar cuando se termine de cargar la aplicación web, solo se debe ingresar al enlace para ser mostrada 
![](/src/P6.png)
![](/src/P6.1.png)