# BUG-AUTH-LOGIN-004 | Solo caracteres permitidos: letras (incluyendo tildes, ñ, ü), espacios y guiones

## Riesgo Asociado:
Medio

## Prioridad:
Medio

## Entorno:
Producción – Brave

## Pasos para reproducir:
1. Ingresar al link https://teststrack.thiup.com/
2. Ingresar a "Registro"
3. Ingresar un "Nombre" con caracteres no permitidos
4. Llenar correctamente los demas campos
5. Clic en "Registrarse"

## Resultado esperado:
1. Notificación al usuario al ingresar un "Nombre" con caracteres no permitidos
2. Impedimento al registrar

## Resultado actual:
1. No se visualiza una notificacion al usuario 
2. El campo permite el ingreso de números
No permitir números ayuda a garantizar:
- Exactitud
- Coherencia
- Confiabilidad del dato

## Evidencia 
https://drive.google.com/drive/folders/1JX9W9Fi4WC8m816DffiRvDr7D_hIx7oS?usp=sharing 
