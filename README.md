Sistema de Gestión de Club de Yates 🚤
Sistema web para la gestión de socios y cuotas de un club de yates. Permite administrar socios, gestionar pagos y llevar un control de las cuotas pendientes y pagadas.

Características Principales 🌟
Gestión de Socios
Creación de Socios

Tipos de socio disponibles:
Básico ($500)
Extra ($800)
Premium ($1000)
Datos requeridos:
Nombre completo
Tipo de documento (DNI/Pasaporte)
Número de documento
Cantidad de cuotas (1-12)
Validaciones

Documento único (no permite duplicados)
Nombre y documento con mínimo 4 caracteres
Feedback visual de errores
Notificaciones de éxito/error
Sistema de Cuotas
Generación automática de cuotas mensuales
Estado de cuotas (pagadas/pendientes)
Visualización de totales:
Total pagado
Total pendiente
Panel de Administración
Acceso protegido con usuario y contraseña
Capacidad de vaciar base de datos
Gestión de usuarios administradores mediante JSON
Tecnologías Utilizadas 🛠️
Frontend
HTML5
CSS3
JavaScript vanilla
Bootstrap 5.3
Librerías
Toastify.js: Notificaciones toast
SweetAlert2: Modales y alertas
Bootstrap: Framework CSS
Almacenamiento
LocalStorage para persistencia de datos


Uso 💡
Crear Nuevo Socio
Click en "CREAR NUEVO SOCIO"
Completar formulario
Click en "Crear Socio"
Buscar/Gestionar Socio
Click en "BUSCAR SOCIO"
Ingresar número de documento
Visualizar cuotas y estados
Click en "PAGAR" para registrar pago de cuota
Administración
Click en "VACIAR SOCIOS"
Ingresar credenciales de administrador
Confirmar acción
Notas Importantes 📝
Los datos se almacenan en el LocalStorage del navegador
Se recomienda hacer respaldo de datos antes de vaciar la base
Las credenciales de administrador deben mantenerse seguras
El sistema está diseñado para uso en navegadores modernos
Características de Seguridad 🔒
Validación de datos en frontend
Protección de panel administrativo
Confirmaciones para acciones críticas
Feedback visual de todas las acciones
Personalización 🎨
El sistema puede personalizarse modificando:

Estilos en css/styles.css
Valores de cuotas en js/Preentrega.js
Imagen de header en img/yatch.webp
Textos y mensajes en los archivos JavaScript
Soporte 🆘
Para reportar problemas o sugerir mejoras, por favor crear un issue en el repositorio.
