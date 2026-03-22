¿Qué tipo de relación existe entre "Vehículo" y "Camioneta"? ¿Es herencia, agregación o asociación?
Es una relación de Herencia. La clase Camioneta hereda los atributos generales de la clase Vehículo, actuando como una especialización de la misma.

¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?
Se representa mediante la multiplicidad en la relación entre Cliente y Vehículo (o Alquiler), especificando el rango 0..3 en el extremo correspondiente del diagrama UML.

¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?
Se deben utilizar modificadores de acceso Privados (-) para proteger los datos de las clases (Encapsulamiento), permitiendo el acceso a ellos únicamente a través de métodos públicos.