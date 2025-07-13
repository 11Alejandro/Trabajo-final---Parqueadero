# Administración del estacionamiento Autopark Manage

## Integrantes
**Alejandro Cadavid Vélez:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Seccional Urabá, Campus Turbo.

**Juan Pablo Osorio Osorio:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Seccional Oriente.

**Manuela López Caro:** Estudiante del programa de Ingeniería Industrial de la Universidad de Antioquia – Sede Medellín.

## Habilidades y Fortalezas
### **Alejandro Cadavid Vélez**  
Habilidades: 
- Excel intermedio  
- Pensamiento critico   
- Flexibilidad y adaptabilidad 

Fortalezas:  
- Compromiso
- Responsabilidad
- Compañerismo
- Organizacion

### **Juan Pablo Osorio Osorio**  
Habilidades:
- Escucha activa  
- Colaboración  
- Empatía  
- Resolución de conflictos  
- Liderazgo   
- Gestión del tiempo
  
Fortalezas:
- Comunicación efectiva
- Resolución de problemas
- Pensamiento crítico
- Trabajo en equipo
- Adaptabilidad
- Organización
- Creatividad  

### **Manuela López Caro**  
Habilidades:  
- Manejo del tiempo  
- Excel básico    
- Inglés
- Resolución de problemas

Fortalezas:  
- Trabajo en equipo
- Proactividad  
- Resiliencia    
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
El propósito de este trabajo es diseñar y desarrollar **Autopark Manage**, un sistema integral de gestión para parqueaderos que permita controlar eficientemente el ingreso, registro, estancia y salida de vehículos, centralizando la información de los usuarios y facilitando la administración del flujo vehicular.
El software almacenará y gestionará datos clave como:
- Nombre y apellido del usuario
- Número de documento, el cual será  el identificador del usuario en el sistema.
- Placa del vehículo
- Hora y fecha de ingreso y salida
- Tiempo total de estancia
- Cálculo y visualización del recibo de pago
- Reportes administrativos como historial de retiros, permanencias y total de usuario registrados.

### **Funcionalidades clave del sistema**
- Registro y validación automática de usuarios previos a su registro en el sistema. 
- Ingreso y retiro de vehículos con control de disponibilidad de celdas (máximo 64), validación de horarios, registro previo del usuario y cobro automático con emisión automática del recibo de pago en pantalla, con desglose del tiempo de permanencia y la tarifa aplicada.
- Reportes administrativos en los cuales se podrán visualizar aspectos claves de la administración y gestión del parqueadero, tales como; número de usuarios, cantidad de vehículos en el parqueadero, tiempos de estadía (mayor y menor) y cantidad de vehículos registrados. 


### **Acceso y roles de usuario**
- Los usuarios generales (clientes del parqueadero) solo interactuaran presencialmente en el punto de ingreso, registrando sus datos mediante el operador.
- La administradores  accederán mediante usuario y contraseña al módulo de administración, desde donde pueden visualizar todos los registros y reportes automáticos.

A manera de conclusión y resumen, el sistema de gestión de **Autopark Manage** representara una solución integral y altamente beneficiosa para cualquier parqueadero, ya que automatiza los procesos de registro, control y retiro de vehículos, reduciendo significativamente los errores humanos y optimizando el tiempo. En este sentido, su implementación permite una gestión más organizada de los espacios disponibles, el control preciso de los tiempos de estancia y la generación automática de reportes. Además, mejora la transparencia en el cobro de tarifas, facilita la toma de decisiones administrativas mediante estadísticas confiables. 

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
<img width="973" height="606" alt="image" src="https://github.com/user-attachments/assets/9caa3f68-3dc5-4862-bfb4-c707c11dfafd" />


### Presupuesto del Proyecto en tiempo equivalente a valor SMLV

![image](https://github.com/user-attachments/assets/ca0b4ea0-e441-4cdb-a5db-71888b7bf7a7)


​
