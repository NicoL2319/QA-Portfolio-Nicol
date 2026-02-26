# BUG-AUTH-LOGIN-002 | Validaciones del campo "Nombre de Usuario" (UserName)

## Riesgo Asociado:
Medio

## Prioridad:
Medio

## Entorno:
Producción – Brave

## Pasos para reproducir:
1. Ingresar al link https://teststrack.thiup.com/
2. Ingresar a "Registro"
3. Ingresar un "Nombre" con menos de 3 caracteres
4. Llenar correctamente los demas campos
5. Clic en "Registrarse"

## Resultado esperado:
Notificación al usuario al ingresar un "Nombre" con minimo de 3 caracteres 
Impedimento al registrar

## Resultado actual:
1. No se visualiza una notificacion al usuario 
2. Permite el registro: Actualmente permite crear una cuenta con un "Nombre de usuario" de un solo caracter, lo que puede probocar vulnerabilidad en la seguridad, confunsion por parte del usuario y no tendría sentido exigir seguridad en password y permitir un identificador trivial.

## Evidencia 
https://drive.google.com/drive/folders/1a1Ce6rYYbVcI1TxTU-5lh3LeXE5djTTK?usp=sharing 
