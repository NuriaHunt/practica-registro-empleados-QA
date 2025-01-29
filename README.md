# practica-registro-empleados-QA
Práctica de testing en un formulario de registro de empleados en GeekRetail. Incluye reporte de bugs.
Sitio de practica- Formulario empleados
Practica de pruebas de sitios web
Eres un QA de un equipo de desarrollo en una empresa de Retail  y se te ha asignado las pruebas de la siguiente historia de usuario que ya esta instalada  en un ambiente de pruebas lista para ser probada dentro de un sprint X.
Ambiente de pruebas: https://testing1.geekqa.net/
Actividad: Diseña los casos de prueba que consideres necesarios y ejecutalos sobre el sitio.
Nota: Este sitio ha sido desarrollado por un programador junior , tiene en total 8 bugs que debes encontrar y reportar! 
Historia de Usuario:
Título: Registro de Empleados en el Sistema de GeekRetail
Descripción: Como administrador de recursos humanos de GeekRetail, quiero un formulario de registro de empleados que capture información variada a través de múltiples tipos de entradas y valide adecuadamente la información para asegurar la integridad de los datos ingresados. El formulario deberá ser fácil de usar y reflejar el estilo moderno de la marca, además de mostrar los datos registrados en una tabla y un mensaje de éxito.
Criterios de Aceptación:
1.	El formulario debe capturar 13 tipos diferentes de información:
•	Nombre completo (texto)
•	Edad (número)
•	Fecha de nacimiento (fecha)
•	Género (radio buttons)
•	Dirección (texto)
•	Correo electrónico (email)
•	Número de teléfono (teléfono)
•	Cargo (texto)
•	Departamento (desplegable)
•	Estado del contrato (checkbox)
•	Horario de trabajo (texto)
•	URL de perfil profesional (URL)
•	Salario esperado (número)
2.	Validaciones típicas:
•	Todos los campos son obligatorios, excepto el URL del perfil profesional.
•	La edad debe estar entre 18 y 65 años.
•	El correo electrónico debe tener un formato válido.
•	El número de teléfono debe tener al menos 10 caracteres numéricos.
•	La URL debe ser válida si se proporciona.
•	El salario debe ser un número mayor a 0.
•	El nombre y la dirección deben tener al menos 3 caracteres.
3.	Al enviar el formulario:
•	Si pasa las validaciones, debe mostrar la información en una tabla.
•	Se debe mostrar un mensaje de éxito.
•	Si hay un error, se debe indicar el campo correspondiente con el error.


