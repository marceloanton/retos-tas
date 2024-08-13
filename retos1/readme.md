
# I.S.F.D y T. N°44 "General Las Heras"

# RETOS PARTE 1 / Segundo Año

## Descripción del reto N°1: Tabla Empleados

1. Crea un programa en Java que se conecte a una base de datos MySQL y cree una tabla llamada `empleados`. La tabla debe tener las siguientes columnas:

* `id` (INT, AUTO_INCREMENT, PRIMARY KEY)
* `nombre` (VARCHAR(50))
* `puesto` (VARCHAR(50))
* `salario` (DECIMAL(10, 2))

### Ejemplo de Entrada/Salida esperada

- Salida:

  ```java
  Se espera que se cree la base de datos en nuestro servidor LOCAL sin errores, y con los datos dados
  ```

#### Recursos adicionales

- Documentación de Java: [Mysql Documentation](https://dev.mysql.com/doc/ "MySQL")

## Descripción del reto N°2: Insertar datos en la tabla

- Extiende el programa anterior para insertar al menos 3 registros en la tabla `empleados`.

### **Instrucciones:**

1. Usa JDBC para insertar datos en la tabla `empleados`.
2. Asegúrate de manejar las excepciones adecuadamente.

#### Recursos Adicionales

* Documentación de Java: [Mysql Documentation](https://dev.mysql.com/doc/ "MySQL")

## Descripción del reto N°3: Consultar Datos de la Tabla

- Crea un programa que consulte y muestre todos los registros de la tabla `empleados`.

### **Instrucciones:**

1. Usa JDBC para consultar los datos de la tabla `empleados`.
2. Muestra los datos en la consola.

#### Recursos Adicionales

* Documentación de Java: [Mysql Documentation](https://dev.mysql.com/doc/ "MySQL")

## Descripción del reto N°4: Actualiza los registros

- Crea un programa que actualice el salario de un empleado en la tabla `empleados` basado en su `id`.

### **Instrucciones:**

1. Usa JDBC para actualizar el registro de un empleado.
2. Pide al usuario el `id` del empleado y el nuevo salario.


#### Recursos Adicionales

* Documentación de Java: [Mysql Documentation](https://dev.mysql.com/doc/ "MySQL")

## Descripción del reto N°5: Eliminar un registro

- Crea un programa que elimine un registro de la tabla `empleados` basado en el `id`.

### **Instrucciones:**

1. Usa JDBC para eliminar un registro.
2. Pide al usuario el `id` del empleado a eliminar.

#### Recursos Adicionales

* Documentación de Java: [Mysql Documentation](https://dev.mysql.com/doc/ "MySQL")

## Evaluación y Feedback

- **Correctitud:** Tu programa debe compilarse sin errores y producir la salida esperada.

* **Estilo de Código:** Asegúrate de seguir las convenciones de estilo de código Java (nombres de variables, indentación, comentarios).
* **Comentarios:** Usa comentarios para explicar partes importantes de tu código.

## Consideraciones Adicionales

1. **Configuración del Entorno:** Asegúrate de tener bien configurado el driver de MySQL en tu proyecto (usualmente el archivo `mysql-connector-java.jar`), segun la version de tu MySQL Server.
2. **Seguridad:** En proyectos reales, es recomendable usar mecanismos de seguridad para manejar las credenciales y las conexiones.
3. **Validaciones:** Implementa validaciones para asegurar la integridad de los datos y manejar posibles errores de manera adecuada.
