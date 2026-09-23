# proyectoJuego-Tecnolog-asSistemasInformaci-n
Repositortio para la documentacion y subia de archivos para el proyecto
# primer apartado reporte de divicion de responsabilidades

1. Alberto González Ruiz
Rol Principal: Artista 3D / Level Designer & Technical Artist
Responsabilidades Específicas:
Modelado 3D de Personajes y Entorno: Creación de los modelos personajes y gatos siendo los 12 agentes de soporte en la base. Modelado de elementos del escenario (árboles, rocas del puzle de presión, cuencos de comida, camas).
Diseño de Niveles (Level Design): Construcción y distribución espacial del mapa dividido en zonas (Santuario Base, Zona de Plataformas/Parkour del entorno).
Optimización y Renderizado (Rendering): Configuración de la iluminación integrada en Godot 4.7.2 LTS, texturizado estilizado (atlas de texturas asistidos por IA), y aplicación de estrategias de rendimiento visual (como LODs visuales o ajustes de materiales) para asegurar los 60 FPS estables a 1080p.
2. Andrés Mateo Dorantes
Rol Principal: Programador de Sistemas, Jugabilidad e Inteligencia Artificial
Responsabilidades Específicas:
Mecánicas de Jugabilidad (Gameplay): Implementación del controlador de movimiento en tercera persona (caminar, correr, salto con asistencia de agarre o doble salto del plan de descope). Programación de las interacciones principales (acariciar, alimentar, llevar/soltar objetos o rocas de puzle).
Inteligencia Artificial y Agentes Autónomos: Configuración del sistema NavMesh3D en Godot y programación de la Máquina de Estados Finitos (FSM) ligera para los 15 agentes autónomos (comportamientos de deambular, comer, dormir y huir/permanecer estáticos).
Sistemas de Gestión y Puzles: Desarrollo de la lógica detrás de la barra de felicidad global del santuario (consumo temporal y restauración por interacción) y el script del mecanismo de presión que desbloquea el puente hacia "Lumina".
3. Cintia Fernanda Reyes Hernández
Rol Principal: Diseñadora de Texto, QA (Testeo) y Documentación
Responsabilidades Específicas:
Documentación y GDD: Redacción, actualización y mantenimiento del Game Design Document (GDD), bitácoras de diseño, diagramas de flujo y control del alcance (MVP vs. Stretch Goals) a lo largo de los hitos del proyecto.
Diseño Narrativo y de Texto (UX Writing): Creación de los textos de la interfaz de usuario (UI), indicadores de felicidad, descripciones de los gatos rescatados y mensajes de estado (condiciones de victoria y derrota).
Control de Calidad (Testeo / QA): Ejecución sistemática de pruebas de rendimiento y jugabilidad frente a los criterios de aceptación (verificar que el personaje no se trabe en colisiones, validación de la estabilidad de los 15 agentes en pantalla y testeo del bucle de puzles bajo la resolución y framerate objetivo).
