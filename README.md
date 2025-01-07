
# Gestión de Averías

Este proyecto es un sistema de gestión de averías con roles de usuario. Permite:

- Consultar averías (usuarios).
- Añadir, modificar y eliminar averías (administradores).

## Tecnologías utilizadas
- **Frontend**: HTML + Bootstrap.
- **Backend**: Flask (Python).
- **Base de datos**: Supabase.

## Estructura de la base de datos
### Tabla `users`
- `id`: Identificador único.
- `username`: Nombre de usuario.
- `password`: Contraseña.
- `role`: Rol (`admin` o `user`).

### Tabla `averias`
- `id`: Identificador único.
- `codigo_fallo`: Código del fallo.
- `descripcion`: Descripción del problema.
- `solucion`: Solución recomendada.

## Próximos pasos
1. Implementar login y niveles de usuario.
2. Diseñar la interfaz web.
3. Desplegar en Render.