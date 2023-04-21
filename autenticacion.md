# Inicio de sesión

## Datos de ingreso.

- Nombre.
- Datos biométricos.
    - Reconocimiento facial.
    - Huella digital. (opcional)

## Descripción del proceso.

1. El Usuario accede la sección de login.
2. El login le solicita al usuario su nombre de acceso.
3. El login solicita  al usuario los datos biométricos.
    1. El sistema lanzará una ventana emergente que solicitará el permiso para acceder a la camara del dispositivo.
    2. El sistema le indicará al usuario la forma en que el mismo tiene que presentar sus datos en el sistema para realizar la validación de acceso en el sistema.
        1. El sistema finalizará el reconocimiento facial en cuanto se complete el registro de los datos faciales.
        2. En caso de que el sistema no sea capaz de reconocer los datos faciales del usuario, el sistema cancelará la solicitud de datos faciales y soltará un mensaje emergente donde solicite limpiar la camara del dispositivo. 
    3. En el caso de que el usuario cuente con la tecnología adecuada, el sistema le solicitará que registre su huella dactilar para validar el proceso al usuario.
        1. El sistema finalizará el reconocimiento de huella dactilar hasta que el sistema pueda registrar la huella dactilar o hasta que el usuario cancele el reconocimiento de huella dactilar.
        2. En el caso de que el sistema no pueda reconocer la huella dactilar ingresada, cancelará el registro de huella dactilar y solicitará al usuario comprobar sensor de su dispositivo.
4. El sistema comprueba que el usuario se encuentre registrado dentro del sistema y posteriormente valida el acceso.
    1. El sistema comprobará que los datos presentados por el usuario en el sistema de inicio de sesión sean correctos y que se encuentren dentro de la base de datos del sistema.
    2. De acuerdo a respuesta de la comprobación de datos, el sistema hará lo siguiente:
        1. Los datos son correctos, redirigir al usuario al acceso solicitado.
        2. Los datos son incorrectos, el sistema borrará los datos ingresados y solicitará al usuario volver a ingresar los datos ingresados de manera correcta. (Esta instrucción se realizará hasta que el usuario ingrese la información correcta)