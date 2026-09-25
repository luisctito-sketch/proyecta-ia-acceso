# PROYECTA-IA — ACCESO CENTRAL

Repositorio existente que debe mantenerse con el mismo nombre:

`proyecta-ia-acceso`

Archivo consumido por todos los chatbots:

`https://luisctito-sketch.github.io/proyecta-ia-acceso/access.js`

## Actualización 25/09/2026

La lista autorizada fue sincronizada con la nómina reciente de Taller de Tesis II:

- 54 estudiantes autorizados.
- Se retiraron 5 estudiantes que ya no aparecen en la nómina.
- Se incorporaron 3 estudiantes nuevos.
- Se conserva el acceso docente existente.
- Los C.I. no aparecen en texto plano dentro de `access.js`; se almacenan como huellas PBKDF2/SHA-256.

## Para subir a GitHub

En el repositorio `proyecta-ia-acceso`, reemplaza:

- `access.js`
- `index.html`
- `README.md`

La actualización de `access.js` se propaga a todos los chatbots que ya están enlazados al acceso central.

## Futuras actualizaciones

Cuando cambie la nómina, no es necesario editar cada chatbot. Se actualiza solamente este repositorio central.
