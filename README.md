🚗 Sistema de Parqueadero Inteligente
Proyecto académico desarrollado para la Universidad Cooperativa de Colombia, sede Bogotá por el estudiante Kevin Sebastián Niño Ceballos .

📝 Descripción del Proyecto
Sistema web de gestión de parqueadero que utiliza visión artificial para el reconocimiento de placas en tiempo real. Asigna espacios de parqueo automáticamente, registra entradas y salidas, y actualiza el estado del parqueadero en tiempo real para el usuario.

🌟 Funcionalidades Principales
Reconocimiento de Placas con IA: Uso de cámara web y modelo entrenado para identificar 8 vehículos particulares registrados.
Gestión Automática: Asignación del primer espacio disponible al detectar un vehículo registrado.
Tiempo Real: Interfaz visual que muestra los 8 cajones cambiando de verde (disponible) a rojo (ocupado) al instante.
Control de Acceso: Rechazo automático de vehículos no registrados con alertas en pantalla.
Historial Completo: Tabla de registros que documenta placa, hora de entrada, hora de salida y estado (Registrado/No Registrado).
🛠️ Tecnologías Utilizadas
Tecnología	Propósito
Máquina de enseñanza	Entrenamiento del modelo de IA de reconocimiento de imágenes
TensorFlow.js	Ejecución del modelo de IA directamente en el navegador web
Firebase (Base de datos en tiempo real)	Base de datos en la nube para sincronización instantánea de datos
HTML / CSS / JS	Estructura, diseño y lógica de la aplicación en un solo archivo.
Páginas de GitHub	Hospedaje gratuito y publicación de la aplicación web.
⚙️ ¿Cómo funciona?
La cámara web analiza el entorno en tiempo real usando el modelo de Teachable Machine.
Al detectar una placa con un umbral de confianza superior al 70%, el sistema la identifica.
Si el usuario presiona "Registrar Entrada" , el sistema busca la placa en la base de datos.
Si está registrado: Le asigna el primer cajón disponible (P-001 al P-008) y guarda la hora.
Si no está registrado: Muestra una alerta de denegación y lo registra en el historial.
Al presionar "Registrar Salida" , se libera el cajón ocupado por esa placa y se registra la hora de salida en el historial.
Todos los cambios se reflejan instantáneamente gracias a Firebase Realtime Database.
🔗 Demo en Vivo
Puedes probar el sistema funcionando en tiempo real en el siguiente enlace:👉https://tu-usuario.github.io/parqueadero-inteligente/ (Nota: Reemplaza "tu-usuario" con tu usuario real de GitHub en el archivo README)

👤 Autor
Kevin Sebastian Niño Ceballos Estudiante de Ingeniería - Universidad Cooperativa de Colombia, Bogotá (2026)
