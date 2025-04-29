# Autopark Manage

## 1 Integrantes
**Alejandro Cadavid Velez:** Estudiante del programa de Ingenieria Industrial de la Universidad de Antioquia-Seccional de Uraba,Campus Turbo.

**Juan Pablo Osorio Osorio:** Estudiante del programa de Ingenieria Industrial de la Universidad de Antioquia-Seccional oriente.

 **Manuela Lopez Caro:** Estudiante del programa de Ingenieria Industrial de la Universidad de Antioquia - Sede Medellin.

## 2 *Habilidades y Fortalezas*
**Alejandro Cadavid Velez:**

**Juan Pablo Osorio Osorio:** Poseo diversas habilidades como: Escucha activa, colaboración, adaptabilidad, empatía, resolución de conflictos, liderazgo, creatividad, gestión del tiempo, las cuales podre a disposición del grupo para realizar un excelente trabajo.


**Manuela Lopez Caro:** Posee habilidades como manejo del tiempo, excel basico, resolucion de problemas, ingles, etc. Mientras que sus fortalezas son: la proactividad, la resilencia, el trabajo en equipo y la empatia.


## 3 *Dellates del Proyecto*
**Nombre:** Autopark Manage

**Descripcion:** Se realizara una consola en Python para la administración de un parqueadero. Esta consoló permitirá la gestión de usuarios, ingresos y retiros de vehículos, así como el manejo de cobros, facturación y generación de reportes administrativos.

![image](https://github.com/user-attachments/assets/079ed5cd-228e-49fe-95e0-d0fabad7cbdf)

## 4 Software
### Licencia del software
© 2025 por está bajo Creative Commons Atribución-CompartirIgual 4.0 Internacional 
### 


## 5 Reporte de vision
El proposito de este trabajo es crear un programa para almacenar los datos de los usuarios de un parqueadero, es decir; nombre del propietario, placa, promedio de tiempo que estuvo en el parqueadero, etc. De tal forma que le facilite al administrador tener un promedio de los vehiculos que igresan diariamente alli. Por su parte el programa permite que el usuario entienda como se manejan las tarifas dentro de ese establecimiento.

# Especificación de Requisitos

## Requisitos Funcionales

### Registro de Usuarios con Validaciones Específicas
- **Nombre y apellido:** mínimo 3 letras, sin números.
- **Documento:** entre 3 y 15 dígitos, solo números.
- **Placa:** exactamente 6 caracteres (3 letras seguidas de 3 números).

### Gestión de Vehículos
- **Ingreso de vehículos:** solo de usuarios registrados, validando datos y generando recibos.
- **Retiro de vehículos:** cálculo del tiempo de parqueo y cobro automático.

### Tarifas de Cobro
- **Cobro por hora:** $7,000 por cada hora completa.
- **Cobro por cuartos de hora:** $1,500 por cada cuarto de hora.
- **Pago mínimo:** $7,000 si el total es menor a una hora completa.

### Reportes Administrativos
El módulo de administración debe permitir la generación de reportes con:
- Total de vehículos registrados, retirados y en parqueo.
- Total de pagos realizados.
- Tiempo promedio de estancia por vehículo.
- Vehículos con el mayor y menor tiempo de parqueo.
- Lista de usuarios registrados.

### Exportación de Datos
- Generación de archivos CSV con los resultados.
- Registro de eventos en un log con detalles como fecha, hora, acción realizada y tiempo de ejecución.

## Requisitos No Funcionales

- **Rendimiento:** Procesamiento eficiente, sin demoras significativas.
- **Usabilidad:** Interfaz de consola intuitiva y fácil de usar.
- **Fiabilidad:** Validación de datos robusta para evitar errores en registro y cobros.
- **Compatibilidad:** Ejecución en sistemas operativos compatibles con Python.
- **Seguridad:** Acceso al módulo de administración mediante usuario y contraseña.
- **Accesibilidad:** Cumplimiento de estándares básicos para facilitar el uso por cualquier usuario.
- **Versionado:** Control de versiones en GitHub para trazabilidad del desarrollo.


​
