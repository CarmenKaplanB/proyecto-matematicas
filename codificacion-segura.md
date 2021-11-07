# Los principios de codificación segura.

![descarga](https://user-images.githubusercontent.com/71624038/140627011-bb216a87-2ae2-4908-92ea-0cdac88dba46.jpg)


Para comenzar a explicar los principios de la codificación segura necesitamos centrarnos inicialmente en que es la codificación segura. Para ello, de acuerdo con la página My server name. (s. f.). La codificación segura es diseñar y desarrollar software evitando las debilidades que conducen a vulnerabilidades relacionadas con la seguridad al adherirse a los estándares de seguridad especificados y las mejores prácticas de la industria.

Ahora que todo está más claro, entendamos algunos principios básicos de la codificación segura. Conforme a la investigación de We live security. (s. f.). estos son algunos de los principios que no podemos dejar pasar por alto:

1. Partiendo siempre de un modelo de permisos mínimos, es mejor ir escalando privilegios por demanda de acuerdo a los perfiles establecidos en las etapas de diseño.

2. Si se utiliza un lenguaje que no sea compilado, asegurarse de limpiar el código que se pone en producción, para que no contenga rutinas de pruebas, comentarios o cualquier tipo de mecanismo que pueda dar lugar a un acceso indebido.

3. Nunca confiar en los datos que ingresan a la aplicación, todo debe ser verificado para garantizar que lo que está ingresando a los sistemas es lo esperado y además evitar inyecciones de código.

4. Hacer un seguimiento de las tecnologías utilizadas para el desarrollo. Estas van evolucionando y cualquier mejora que se haga puede dejar obsoleta o inseguras versiones anteriores.

5. Todos los accesos que se hagan a los sistemas deben ser validados.

6. Para intercambiar información sensible utilizar protocolos para cifrar las comunicaciones, y en el caso de almacenamiento la información confidencial debería estar cifrada utilizando algoritmos fuertes y claves robustas.

7. Cualquier funcionalidad, campo, botón o menú nuevo debe agregarse de acuerdo a los requerimientos de diseño. De esta forma se evita tener porciones de código que resultan siendo innecesarias.

8. La información almacenada en dispositivos móviles debería ser la mínima, y más si se trata de contraseñas o datos de sesión. Este tipo de dispositivos son los más propensos a ser que se pierdan y por lo tanto su información puede ser expuesta más fácilmente.

9. Cualquier cambio que se haga debería quedar documentado, esto facilitará modificaciones futuras.

10. Poner más cuidado en los puntos más vulnerables, no hay que olvidar que el nivel máximo de seguridad viene dado por el punto más débil.

Nos queda claro que al momento de desarrollar debemos estar al pendiente de cada principio pues recordemos que con el más mínimo error o falla en nuestro incumplimiento de los principios podría costarnos caro, y podría ser un incidente grande hacia la empresa. Es por ello que debemos ser desarrolladores responsables y cumplir con las recomendaciones que se nos atribuyen.

Y por supuesto ser confidentes con la información delicada que podría caer en nuestras manos como desarrolladores, debemos usar claves seguras y robustas al momento de desarrollar.
