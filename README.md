# sql-select-fundamentals

¿Por qué es mala práctica usar SELECT * en producción? Mencioná al menos dos razones concretas (rendimiento, mantenibilidad, seguridad).

Usar la sentencia SELECT * significa seleccionar todas las columnas de una tabla. Es una mala práctica en producción porque puede consumir recursos innecesarios al recuperar información que no necesitamos. Además, es poco específico y puede dificultar el mantenimiento de las consultas si se modifica la estructura de la tabla.

¿Por qué son importantes los alias para un stakeholder no técnico? Explicá con un ejemplo concreto cómo un alias transforma total_amount en algo que cualquier persona del área de finanzas puede interpretar directamente.

Para una persona no técnica, los nombres de las columnas pueden resultar confusos. El uso de alias facilita la lectura e interpretación de los datos, permitiendo presentar la información de manera más accesible. Por ejemplo, en este caso cambiar total_amount por monto_total permite que el equipo de finanzas comprenda directamente qué representa esa columna.
