# Flujo de la Aplicación

1. **Acceso Público a Consultas (GETs):**
   - Cualquier visitante puede realizar consultas sobre productos, categorías o usuarios(solo si tiene el id) sin necesidad de registrarse. Esto permite a los clientes explorar el contenido del restaurante al abrir la página.

2. **Autenticación para Trabajadores y Dueños (Dashboard):**
   - La autenticación está diseñada para los trabajadores y dueños del restaurante, proporcionándoles acceso al dashboard. Aquí podrán realizar acciones administrativas y gestionar el contenido de la plataforma.

3. **Registro Abierto con Rol Predeterminado:**
   - Cualquier persona puede registrarse en la plataforma y, por defecto, obtendrá el rol de 'user'. Esto facilita la participación de usuarios en la plataforma sin restricciones iniciales.

4. **Rol 'User' - Consultas (GETs):**
   - Los usuarios con el rol 'user' tienen permisos para realizar consultas sobre productos, categorías y usuarios(por id, email o username). Esto les permite explorar y obtener información sin la capacidad de modificar o eliminar datos.

5. **Rol 'Admin' - Control Total sobre Productos y Categorías:**
   - Los usuarios con el rol 'admin' tienen privilegios para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre productos y categorías. Esto implica la capacidad de agregar, modificar y eliminar productos, así como gestionar las categorías existentes.

6. **Rol 'Super-Admin' - Control Total sobre Todo:**
   - Los super administradores tienen privilegios máximos y pueden realizar operaciones CRUD sobre productos, categorías y usuarios. Esto incluye la capacidad de gestionar completamente el contenido y los usuarios de la plataforma.
