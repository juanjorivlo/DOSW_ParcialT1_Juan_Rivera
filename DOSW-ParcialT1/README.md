# DOSW_ParcialT1_Juan_Rivera
• Diagramas (Contexto C4, Casos de Uso, Clases).
##1. Diagrama de contexto
![alt text](context.png)
##2 Diagrama caso de uso.
<img width="880" height="728" alt="image" src="https://github.com/user-attachments/assets/a0dfe22a-deb7-4f3e-8b63-ded047c3ec78" />
<img width="880" height="758" alt="image" src="https://github.com/user-attachments/assets/d844530d-990f-45b0-99b4-335df77d2d9b" />
• Requerimientos (Clasificación e Historias de Usuario).
## Historias de usuarios- Funcionales
# FASTEST_AVAILABLE 
 Campo | Descripción |
|------|-------------|
| **ID** | RF-01 |
| **Nombre del requerimiento** |Creación con prioridad tiempo |
| **Descripción** |Como estudiante quiero tener el tutoría lo mas pronto posible, para poder estudiar en la brevedad, temas de mayor prioridad.|
| **Precondiciones** |  Haber tutorores libres y con las siguientes condiciones de aceptación:
- Efectivamente selecciona el tutor disponible más cercano.
  - Que no escoja uno que ya esta seleccionado.
  - Que escoga independiente mente si es profesor o de posgrado.
  - que tengan la duración adecuada.|
| **Actor** | Estudiante|
| **Flujo principal** | 1. El actor ingresa digita FASTEST_AVAILABLE .<br>2. El sistema le muestra las opciones acordes a su elección.<br>3.El estudiante selecciona la mas conveniente. |
| **Diagrama de caso de uso** | ![alt text](Brevedad.png)|
| **Poscondiciones** | La sesión queda agendada para aceptación del monitor.|

 

  

# EXPERT_FIRST 

 Campo | Descripción |
|------|-------------|
| **ID** | RF-02 |
| **Nombre del requerimiento** |Creación con prioridad de Profesor seguido de Posgrado|
| **Descripción** |Como estudiante quiero priorizar la seleccion de monitories de esa materia a primera instancia, en segunda estudiantes de posgrado, para poder maximizar mi aprendizaje.|
| **Precondiciones** |  Haber tutorores libres y con las siguientes condiciones de aceptación:
- Efectivamente selecciona el tutor disponible más cercano.
 - Que solo inscriba a estudiante de posgrados si todos los profesores disponibles en el criterio del estudiante estan ocupados.
 - Que escoga con esse orden de prioridad.
 - Que no escoja uno que ya esta seleccionado.
 - que tengan la duración adecuada.|
| **Actor** | Estudiante|
| **Flujo principal** | 1. El actor ingresa digita EXPERT_FIRST  .<br>2. El sistema le muestra las opciones acordes a su elección.<br>3.El estudiante selecciona la mas conveniente. |
| **Diagrama de caso de uso** |![alt text](<Prioridad profesor.png>)|
| **Poscondiciones** | La sesión queda agendada para aceptación del monitor.|
# PEER_TUTORING
 Campo | Descripción |
|------|-------------|
| **ID** | RF-03 |
| **Nombre del requerimiento** |Creación con únicamente monitor de Posgrado|
| **Descripción** |Como estudiante quiero crear sesiones de monitoria exclusicamente con tutores de posgrado para poder trabajar mas comodamente.|
| **Precondiciones** |  Haber tutorores libres y con las siguientes condiciones de aceptación:
 - Que excluya totalmente a los profesores.
 - No se sobreescriban las sesiones
 - que tengan la duración adecuada|
| **Actor** | Estudiante|
| **Flujo principal** | 1. El actor ingresa digita PEER_TUTORING  .<br>2. El sistema le muestra las opciones acordes a su elección.<br>3.El estudiante selecciona la mas conveniente. |
| **Poscondiciones** | La sesión queda agendada para aceptación del monitor.|
• Patrones de Diseño (Justificación).
• Evidencia TDD.
• Jira URL.
https://parcial1juanrivera.atlassian.net/jira/software/projects/P1JR/boards/2/backlog?atlOrigin=eyJpIjoiMDk5NzBjZGQwNzZhNDUwZWEzNzU5OTFhMDVjNmM1YjYiLCJwIjoiaiJ9
Foto de backlog
[text](../../Downloads/README.md)
• Pull Request URL.



