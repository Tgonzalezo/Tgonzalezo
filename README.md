# Tamara González Orellana
### Socióloga | En formación como Desarrolladora Full Stack Python Trainee

## Sobre mí

Soy socióloga con experiencia en investigación, análisis y organización de información. Actualmente estoy ampliando mi perfil profesional mediante la formación en desarrollo Full Stack Python.

Me interesa integrar la comprensión de las necesidades de las personas con el desarrollo de aplicaciones web. Busco oportunidades trainee donde pueda aportar, aprender del equipo y fortalecer mis habilidades técnicas.

## Tecnologías y herramientas

- **Backend:** Python y Django.
- **Frontend:** HTML, CSS, JavaScript, Bootstrap y jQuery.
- **Datos:** fundamentos de SQL, SQLite y archivos JSON.
- **Herramientas:** Visual Studio Code, Git y GitHub.
- **Otros conocimientos:** programación orientada a objetos, Tkinter y pruebas automatizadas.

## Proyectos destacados

### 1. Alke Wallet — Módulo 2

Billetera digital educativa que simula registro de usuarios, inicio de sesión, consulta de saldo, depósitos, transferencias y movimientos.

**Tecnologías:** HTML, CSS, Bootstrap, JavaScript, jQuery y LocalStorage.

**Aprendizajes:** construcción de interfaces, interacción con el usuario y almacenamiento de información en el navegador.

**Alcance:** simulación formativa; no procesa dinero real.

[Ver repositorio](https://github.com/Tgonzalezo/proyecto_modulo_2)

### 2. Gestor Inteligente de Clientes — Módulo 4

Aplicación de Python para registrar, buscar, editar y eliminar clientes, diferenciando clientes regulares, premium y corporativos.

**Tecnologías:** Python, Tkinter, JSON y CSV.

**Aprendizajes:** programación orientada a objetos, herencia, polimorfismo, validación de datos, persistencia y manejo de excepciones.

[Ver repositorio](https://github.com/Tgonzalezo/proyecto_modulo_4)

### 3. Gestor de Proyectos y Tareas — Módulo 6

Aplicación web que permite a cada usuario administrar sus proyectos y tareas, con autenticación y restricciones de acceso según propietario.

**Tecnologías:** Python, Django, SQLite, HTML, CSS y Bootstrap/SB Admin 2.

**Aprendizajes:** modelos relacionados, formularios, operaciones CRUD, autenticación, autorización y pruebas automatizadas.

[Ver repositorio](https://github.com/Tgonzalezo/proyecto_modulo_6)

---

## Caso de estudio | Gestor de Proyectos y Tareas

### Descripción de la actividad

Desarrollé una aplicación web para crear y administrar proyectos y tareas. Cada usuario puede gestionar su información desde una interfaz con formularios y un panel de indicadores.

### Desafío principal

Integrar la gestión de proyectos y tareas con el control de acceso: cada persona debía consultar y modificar únicamente la información asociada a su cuenta.

### Solución propuesta

Utilicé el sistema de usuarios de Django y dos modelos propios:

- **Proyecto:** relacionado con su usuario propietario.
- **Tarea:** relacionada con un proyecto, con estado y fecha límite opcional.

Las vistas requieren autenticación y filtran los registros por propietario. Por ejemplo, al editar una tarea, la consulta incorpora `proyecto__usuario=request.user`.

Los formularios validan la información antes de guardarla y permiten crear, editar y eliminar registros.

### Herramientas utilizadas y justificación

Elegí **Django** porque integra herramientas para modelos, formularios, autenticación y pruebas, facilitando la organización del desarrollo.

Utilicé **SQLite** como base de datos para el entorno formativo y **HTML, CSS y Bootstrap/SB Admin 2** para la presentación de la interfaz.

### Principales aprendizajes

- Distinguir autenticación de autorización.
- Relacionar usuarios, proyectos y tareas mediante claves foráneas.
- Consultar y filtrar información con el ORM de Django.
- Validar formularios antes de almacenar datos.
- Organizar modelos, vistas, rutas y templates.
- Verificar comportamientos mediante pruebas automatizadas.

### Resultados y métricas verificables

| Indicador | Resultado |
|---|---|
| Modelos propios | 2: Proyecto y Tarea |
| Estados de tarea | 3: pendiente, en progreso y completada |
| Indicadores del panel | 4: proyectos, tareas, pendientes y completadas |
| Pruebas automatizadas | 11 pruebas ejecutadas correctamente en la revisión del 6 de octubre de 2026 |

Las pruebas incluyen modelos y vistas, creación, edición y eliminación, además de un caso que comprueba que un usuario no puede editar una tarea ajena.

Estas cifras describen el alcance funcional y la validación realizada. No se midieron ahorro de tiempo, rendimiento ni cobertura total de código.

### Habilidades técnicas aplicadas

Python, Django, modelado de datos, ORM, formularios, operaciones CRUD, autenticación, autorización, templates y pruebas automatizadas.

### ¿Por qué elegí este proyecto?

Porque integra interfaz web, lógica de servidor y base de datos. Representa mi avance desde ejercicios iniciales de programación hacia una aplicación con usuarios y datos relacionados.

También permite mostrar cómo abordé una necesidad concreta: organizar información y restringir su acceso según el propietario.

[Explorar el código del caso de estudio](https://github.com/Tgonzalezo/proyecto_modulo_6)

## Otros proyectos

- [Inventario de supermercado en Python — Módulo 3](https://github.com/Tgonzalezo/proyecto-modulo_3)
- [Alke Wallet con Django — Módulo 7](https://github.com/Tgonzalezo/proyecto_modulo_7)

## Contacto

- **Correo:** [tamara.ninoska99@gmail.com](mailto:tamara.ninoska99@gmail.com)
- **LinkedIn:** [Tamara González Orellana](https://www.linkedin.com/in/tamara-gonzález-orellana-9486122a9/)

Los proyectos presentados fueron desarrollados en el marco del curso Desarrollador Full Stack Python Trainee.
