# Seguridad del repositorio

## ¿Por qué se excluyen archivos (.gitignore)?
- Contraseñas y configuración local: si se publican, otra persona podría acceder.
- Dependencias, binarios y temporales: se pueden regenerar y ensucian el repositorio.
- Bases de datos locales y logs: pueden contener datos personales.

## Permisos recomendados
- Read: personas que solo leen.
- Write: personas que trabajan con ramas y pull requests.
- Admin: la persona responsable del proyecto.

## Medidas de seguridad
- La rama main está protegida: solo se cambia con pull request y aprobación.
- Todas las cuentas usan verificación en dos pasos.
- No se suben credenciales. Si se filtra una, se cambia de inmediato.

## Copias de seguridad y recuperación
- Copia periódica con Code → Download ZIP.
- Fork del repositorio en otra cuenta.
- Versiones publicadas en Releases.
- Un cambio malo se deshace con el botón Revert del pull request.
- Una rama borrada se recupera con Restore branch.
