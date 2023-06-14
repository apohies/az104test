## fundamentos 104

New-AzVM : creaciòn de maquina virtual




1 . 104 administracion de los recursos
 - administracion de gobernanza.
 - bloqueo de recursos.
 - inplementacion y adminitracion de recursos de Azure.
 - configuracion de maquinas virtual y mover la mismas a grupos.



 ## Azure Resource Manager
 es la herramienta para la gobernanza de los recursos a traves de la creacion de grupos de trabajo.
 - proporciona una capa de administracion.


 ## Palabras Claves

 - Provedores de recursos :Microsoft key.Vaults
 - los grupos de recursos son una colección lógica de recursos


## alternativas para crear maquinas virtuales
 1 Azure PowerShell
 2 CLI de Azure
 3 Azure Powershel

 modulo AZ. sond cmdLets



 ## Restablecimiento de contraseñas

 SSPR
pasos que se deben llevar a cabo.

-localizacion
- comprobacion
-autenticacion
- restablecimiento de contrasñeas



## Sistema de almacenamiento 

- blob storage funciona a traves de http y https
- Azure files : protocolo network file.
-Azure Queae : mensajeria


## maquinas virtuales

las virtual machine son la son la base de de Iaas (infraestructura como servicio)

tipo maquinas vrituales

- de uso general
-optimizada para procesos.
- ptimizada para memoria.
- optimizada para almacenamiento.
-gpu.
- informatica de alto rendimiento.

- las maquinas virtuales tiene dos discos.
- sistema oeprativo y memoria temporal.


conjuntos de disponibilidad , evitar que se hagan actualizacion masivas que todas queden fuera de servicio.


dominio de error y dominio de actulizacion

- actualizacion : asociados a cambios y modificaciones.
- comprten la estructura fisica.


herramienta para administrar de manera automatica para administrar virtual machines.

Azure virtual machine Scale Set.


# escalbilidad automatica.
manejar el numero de instancias disponibles de maquinas virtuales.

Desired State Configuration es una plataforma de administración en Windows PowerShell. Desired State Configuration permite implementar y administrar datos de configuración para servicios de software y administrar el entorno en el que se ejecutan estos servicios. La plataforma también proporciona un medio para mantener y administrar las configuraciones existentes.


# App services
minimo debe tener region.
numero instancias maquina viertual
tamaño de la instanci de maquina virtual.

maximo numero de instancias aplicacion 30.


# ranuras implementacion
-configuracion de la aplicacion cadenas conexion
- si cuentan con integracion continua
- configuracion de la appservice


microsft insight.

herramienta para determinar el uso de.
tasas de respuesta , excepciones , procesos y rendimientos de carga



# Azure Container instance.

herramienta para la creacion multicontendores.
donde se elegi el tamaño, la red y el uso de recursos.









