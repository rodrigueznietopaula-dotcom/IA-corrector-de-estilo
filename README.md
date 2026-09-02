# Escribo, reviso y aprendo — v2

## Estructura
- `index.html`: portada y selector de rol.
- `student.html`: experiencia exclusiva del estudiante.
- `docente.html`: panel separado del docente.
- `assets/styles.css`: estilos.
- `assets/app.js`: interacción, progreso local y prompts.
- `assets/rubrica_mi_cuento.png`: rúbrica real extraída del documento metodológico.
- `docs/Ficha_2_Diseno_Metodologico.docx`: documento original disponible en esta conversación.

## Publicación
Sube toda esta carpeta a un repositorio de GitHub y activa GitHub Pages desde Settings → Pages → Deploy from branch → rama principal → `/root`.

## Datos de estudiantes
No se incluyen usuarios, contraseñas ni nombres en el HTML. El repositorio de GitHub es público si así se configura y no debe contener datos personales de menores.

La arquitectura recomendada para este proyecto es:
**GitHub Pages (interfaz) + cuentas institucionales Microsoft 365 + Microsoft Forms/Excel/OneDrive/SharePoint (datos y portafolio).**

Esto coincide con la propia secuencia, que ya contempla cuentas Microsoft 365 y guardado de versiones en OneDrive.

Si se desea Google, puede sustituirse el almacenamiento por Google Forms + Sheets, pero primero hay que definir la autenticación y permisos.

## Copilot
La interfaz enlaza a:
- https://copilot.cloud.microsoft
- https://m365.cloud.microsoft

Las características disponibles dependen de la cuenta/licencia y configuración institucional.

## Próximo paso
Subir los demás anexos/documentos. Se incorporarán como recursos offline en `docs/` sin alterar sus originales.


### Anexos incorporados en esta versión
- `docs/Patron_Escritura_Andamio_Cognitivo_Grado_Sexto.pdf`
- `assets/protocolo_uso_ia.png`

La vista estudiante ya no muestra un enlace visible hacia la vista docente. Para una separación de seguridad real entre roles y datos de estudiantes se requiere autenticación institucional/backend; GitHub Pages por sí solo no protege una URL privada.
