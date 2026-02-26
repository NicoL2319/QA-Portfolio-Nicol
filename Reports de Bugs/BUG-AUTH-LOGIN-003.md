# BUG-AUTH-LOGIN-003 | Longitud máxima: 100 caracteres

## Riesgo Asociado:
Medio

## Prioridad:
Medio

## Entorno:
Producción – Brave

## Pasos para reproducir:
1. Ingresar al link https://teststrack.thiup.com/
2. Ingresar a "Registro"
3. Ingresar un "Nombre" con mas de 100 caracteres
4. Llenar correctamente los demas campos
5. Clic en "Registrarse"

## Resultado esperado:
Notificación al usuario al ingresar un "Nombre" con mas de 100 caracteres 
Impedimento al registrar

## Resultado actual:
1. No se visualiza una notificacion al usuario 
2. El sistema permite ingresar mas de 100 caracteres en el campo "Nombre de usuario"

100 porque:
1. Es suficientemente grande.
2. No es excesivo.
3. Es fácil de manejar en validaciones.

Ademas al visualizar en el modulo de perfil al excederse de los 100 el nombre sobre sale de la interfaz

## Evidencia 
https://drive.google.com/drive/folders/1Ze1dVWaU8dfS98aJjE5yf_pCETcb4jws?usp=sharing 
