# Contexto del Proyecto: CampusFlow

## Descripción de la Aplicación
"CampusFlow" es una aplicación de gestión de tareas académicas y avisos para estudiantes.

### Características y Funcionalidades:
- **Diseño y Navegación:** Navigation Drawer con enlaces a "Mis Asignaturas", "Avisos del Campus" y "Ajustes". Pantalla principal con Tabs para "Tareas Pendientes" y "Tareas Completadas".
- **Controles:** Floating Action Button (FAB) para añadir tareas. Formulario de nueva tarea con Spinner para asignatura e ImageButton para prioridad alta.
- **Visualización de Datos:** RecyclerView con CardViews personalizados (título, fecha, icono de asignatura).
- **Interacción:** Menú contextual (pulsación larga) con "Editar" y "Eliminar". Confirmación requerida para eliminar.
- **Persistencia:** SQLite para almacenamiento local.
- **Ajustes:** Cambio de nombre de perfil y activar/desactivar notificaciones push.
- **Notificaciones (FCM + PHP):** Backend en PHP para simular panel de profesor y enviar notificaciones vía FCM.
- **Feedback:** Uso de SnackBar o Toast para confirmar acciones (guardar, editar, eliminar).

## Reglas de Trabajo Estrictas
1. **Desarrollo por Fases:** Completar solo UNA FASE a la vez.
2. **Parada Obligatoria:** Detenerse al finalizar cada fase.
3. **Esperar Aprobación:** No avanzar hasta recibir "Aprobado", "Continuar" o correcciones.
4. **Resumen de Commit:** Generar un resumen profesional al final de cada fase.
5. **Gestión de TODO.md:** Crear y actualizar `TODO.md`. Marcar tareas completadas con `[x]` tras la aprobación.
6. **Revisión de Silenciosa:** Revisar este archivo antes de cada respuesta para mantener la coherencia.
7. **Idioma:** Comunicación y código (comentarios, strings) exclusivamente en español castellano.

## Fases de Desarrollo
- **FASE 0:** Inicialización y Contexto.
- **FASE 1:** Interfaz Base (Navigation Drawer, Action Bar, Tabs, Icono).
- **FASE 2:** Persistencia de Datos (Modelos y SQLite).
- **FASE 3:** Interfaz de Datos y Controles (RecyclerView, FAB, Spinners).
- **FASE 4:** Interacción y Feedback (Menús contextuales, Diálogos, Toasts/Snackbars).
- **FASE 5:** Ajustes (Settings Activity).
- **FASE 6:** Notificaciones FCM y PHP.
- **FASE 7:** Compilación y Firma (APK y ZIP).