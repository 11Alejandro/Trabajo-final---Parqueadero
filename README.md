# Administración del estacionamiento Autopark Manage

## Integrantes
**Alejandro Cadavid Vélez:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Seccional Urabá, Campus Turbo.

**Juan Pablo Osorio Osorio:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Seccional Oriente.

**Manuela López Caro:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Sede Medellín.

## Habilidades y Fortalezas
### **Alejandro Cadavid Vélez**  
Habilidades 
- Excel intermedio  
- Pensamiento critico   
- Flexibilidad y adaptabilidad 

Fortalezas:  
- Compromiso
- Responsabilidad
- Compañerismo
- Organizacion

### **Juan Pablo Osorio Osorio**  
Poseo diversas habilidades como:
- Escucha activa  
- Colaboración  
- Adaptabilidad  
- Empatía  
- Resolución de conflictos  
- Liderazgo  
- Creatividad  
- Gestión del tiempo  

Las pondré a disposición del grupo para realizar un excelente trabajo.  

### **Manuela López Caro**  
Habilidades:  
- Manejo del tiempo  
- Excel básico  
- Resolución de problemas  
- Inglés  

Fortalezas:  
- Proactividad  
- Resiliencia  
- Trabajo en equipo  
- Empatía  

## Detalles del Proyecto  
**Nombre:** Autopark Manage  

**Descripción:**  
Este proyecto consiste en el desarrollo de una consola en **Python** para la administración de un parqueadero. La aplicación permitirá:  
- Gestión de usuarios  
- Registro de ingresos y retiros de vehículos  
- Cálculo de cobros y facturación  
- Generación de reportes administrativos  

![image](https://github.com/user-attachments/assets/079ed5cd-228e-49fe-95e0-d0fabad7cbdf)  

## Software  
### **Licencia**  
© 2025 bajo **Creative Commons Atribución-CompartirIgual 4.0 Internacional**  

## Reporte de Visión  
El propósito de este trabajo es desarrollar un programa para gestionar la información de los usuarios de un parqueadero. El sistema almacenará datos como:  
- Nombre del propietario  
- Placa del vehículo  
- Tiempo promedio de estancia  

Esto facilitará al administrador la gestión del flujo de vehículos diarios y la organización de tarifas dentro del establecimiento.  


## Especificación de requisitos

### Requisitos Funcionales

#### Registro de Usuarios con Validaciones Específicas
- **Nombre y apellido:** mínimo 3 letras, sin números.
- **Documento:** entre 3 y 15 dígitos, solo números.
- **Placa:** exactamente 6 caracteres (3 letras seguidas de 3 números).

#### Gestión de Vehículos
- **Ingreso de vehículos:** solo de usuarios registrados, validando datos y generando recibos.
- **Retiro de vehículos:** cálculo del tiempo de parqueo y cobro automático.

#### Tarifas de Cobro
- **Cobro por hora:** $7,000 por cada hora completa.
- **Cobro por cuartos de hora:** $1,500 por cada cuarto de hora.
- **Pago mínimo:** $7,000 si el total es menor a una hora completa.

#### Reportes Administrativos
El módulo de administración debe permitir la generación de reportes con:
- Total de vehículos registrados, retirados y en parqueo.
- Total de pagos realizados.
- Tiempo promedio de estancia por vehículo.
- Vehículos con el mayor y menor tiempo de parqueo.
- Lista de usuarios registrados.

#### Exportación de Datos
- Generación de archivos CSV con los resultados.
- Registro de eventos en un log con detalles como fecha, hora, acción realizada y tiempo de ejecución.

### Requisitos No Funcionales

- **Rendimiento:** Procesamiento eficiente, sin demoras significativas.
- **Usabilidad:** Interfaz de consola intuitiva y fácil de usar.
- **Fiabilidad:** Validación de datos robusta para evitar errores en registro y cobros.
- **Compatibilidad:** Ejecución en sistemas operativos compatibles con Python.
- **Seguridad:** Acceso al módulo de administración mediante usuario y contraseña.
- **Accesibilidad:** Cumplimiento de estándares básicos para facilitar el uso por cualquier usuario.
- **Versionado:** Control de versiones en GitHub para trazabilidad del desarrollo.

## Cronograma del proyecto - Diagrama de Gantt

N. Actividad	 Actividad	Descripción	Semana 	Inicio	Final	Semana 1	Semana 2	Semana 3	Semana 4	Semana 5	Semana 6	Semana 7	Semana 8	Semana 9	Semana 10	Semana 11	Semana 12	Semana 13	Semana 14	Semana 15	Semana 16
1	Conformación del grupo de trabajo	Conformación del equipo de trabajo para el desarrollo del trabajo final del curso.	6	14/04/2025	20/04/2025																
2	Reunión inicial y actas	Reunión para definir responsabilidades y elaborar actas de entendimiento, colaboración y responsabilidad en función del entregable 1. 	7	21/04/2025	25/04/2025																
3	Descripción de los vínculos académicos.	Descripción de los vínculos académicos de cada miembro del equipo con la Universidad. Esta descripción incluye: nombre, tipo de vinculo académico, programa y sede, campus o seccional a la cual pertenece.	8	26/04/2025	2/05/2025																
4	Descripción del proyecto	Descripción general del proyecto. Esta descripción incluye el diseño del nombre y logotipo del proyecto, así como sus funcionalidades, es decir, el propósito y finalidad del proyecto.	8	27/05/2025	2/05/2025																
5	Selección de licencia y descripción del software	Definir la licencia con la cual se registrará el software. Para esto, se hará uso de: https://chooser-beta.creativecommons.org. Además, se definirán los requisitos funcionales y no funcionales del software a implementar.	8	27/05/2025	2/05/2025																
6	Plan de versionado	Diseñar y establecer un control de versiones que registre los cambios realizados al software a lo largo del proyecto. Cada versión debe documentarse con fecha, descripción del cambio y responsable.	9	5/05/2025	11/05/2025																
7	Organización del código  	Crear y mantener una carpeta llamada src en el repositorio de GitHub que contenga todos los archivos y códigos fuente del programa, con estructura clara y comentada.	10	12/05/2025	18/05/2025																
8	Elaboración del manual de usuario 	Crear y mantener una carpeta llamada doc en el repositorio de GitHub que contenga el archivo donde se establesca el funcionamiento del programa paso a paso e instrucciones de uso. 	11	19/05/2025	25/05/2025																
9	Configuración de un nuevo repositorio GitHub	Crear el repositorio en GitHub con una cuenta institucional UdeA, organizarlo con los entregables requeridos y vincular a todos los integrantes del equipo.	12	26/05/2025	1/06/2025																
10	Sustentación del proyecto	Preparar la sustentación del proyecto para la semana 16, en donde todos los integrantes deberán tener dominio del software, demostrar su funcionalidad y responder preguntas del profesor.	16	23/06/2025	27/06/2025																
![image](https://github.com/user-attachments/assets/0338f512-3e10-456c-907f-afb33323f767)


​
