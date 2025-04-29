# Administración del estacionamiento Autopark Manage

## Integrantes
**Alejandro Cadavid Vélez:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Seccional Urabá, Campus Turbo.

**Juan Pablo Osorio Osorio:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Seccional Oriente.

**Manuela López Caro:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Sede Medellín.

## Habilidades y Fortalezas
### **Alejandro Cadavid Vélez**  
(Información pendiente)  

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


​
