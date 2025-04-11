# aesculi
ÆsculIA - README

Estructura del proyecto:
- frontend/: Interfaz web (Dashboard Calíope/Apolo)
- backend/: API en FastAPI con IA médica y endpoints protegidos
- IA/: Núcleo de razonamiento, diagnóstico y autoaprendizaje
- assets/: Recursos visuales, logos y presentaciones
- staging_demo/: Vista previa en entorno seguro (Railway compatible)

Despliegue en Railway:
1. Subir cada carpeta como servicio independiente si deseas modularizar.
2. Alternativamente, subir todo comprimido como un solo servicio.
3. Configura variables de entorno desde el dashboard de Railway.
4. Asegúrate de tener una base de datos PostgreSQL o MongoDB enlazada.

Notas:
- La IA cuenta con fallback offline para pacientes sin conexión.
- Profesionales pueden generar clases con evidencia científica real.
- PQRS gestionado por IA legal, multilingüe, con adaptación a país.
- Todos los módulos están listos para multiplataforma y smartwatches.
- Diseño visual puede adaptarse entre estilo Apple y clásico griego.
