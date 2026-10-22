# PROYECTA-IA — Acceso central

Repositorio: `proyecta-ia-acceso`

Archivo que utilizan todos los chatbots:
`https://luisctito-sketch.github.io/proyecta-ia-acceso/access.js`

## Actualización de nuevos estudiantes

Cuando exista una nueva lista de estudiantes:

1. Generar las nuevas huellas de C.I. utilizando el mismo `salt` e `iterations`.
2. Actualizar el arreglo `studentHashes` en `access.js`.
3. Reemplazar **solo `access.js`** en este repositorio.
4. Esperar a que GitHub Pages publique el cambio.
5. Todos los chatbots quedan actualizados automáticamente.

NO es necesario editar uno por uno los repositorios de los chatbots.

## Seguridad

Los números de C.I. no están escritos en texto plano en `access.js`; se almacenan huellas derivadas mediante PBKDF2/SHA-256.
Este sistema es una barrera de acceso para el aula, no un sistema institucional de autenticación.


## Actualización 2026-10-22
- Se añadió un nuevo estudiante autorizado a la base central.
- No se modificaron los accesos existentes ni la clave docente.
- Los chatbots enlazados a `access.js` reciben la actualización automáticamente al reemplazar este archivo en GitHub.
