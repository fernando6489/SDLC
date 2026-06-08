# SDLC
# Proyecto Final - Ciclo de Vida de Desarrollo de Software (SDLC)

**Instituto Tecnológico Superior Quito Metropolitano**  
**Autor:** Wladimir Fernando Vega Herrera  
**Docente:** Ing. Pablo Navarrete MSc.  
**Carrera:** Desarrollo de Software  

---

## 📌 Objetivos
Aplicar metodologías ágiles en proyectos que simulen desarrollos reales con el fin de fomentar el pensamiento crítico.

---

## 📖 Introducción
Desarrollar un proyecto simulado siguiendo la metodología **SCRUM**, que incluya el análisis de requerimientos, diseño, codificación, pruebas, despliegue y mantenimiento.  
Se hará uso de herramientas de gestión y control de versiones como **Jira, Trello, Git y GitHub** para planificar, organizar y documentar el trabajo del equipo.

---

## 🌱 Justificación Ambiental
El uso de herramientas digitales reduce el consumo de recursos físicos (papel, transporte, insumos), promoviendo prácticas sostenibles en el desarrollo de software.  
Esto contribuye directamente al **ODS 13 Acción por el clima**, fomentando una cultura tecnológica responsable y ambientalmente consciente.

---

## ⚙️ Desarrollo

### 4.1 Diseño de Arquitectura del Sistema
**Requisitos relacionados:**
- RF-001 Registro de usuarios  
- RF-002 Inicio de sesión  
- RF-004 Cartelera  
- RF-007 Selección de asientos  
- RF-008 Pago online  
- RNF-001 Tiempo de respuesta < 2 segundos  
- RNF-003 Soporte de 500 usuarios concurrentes  

**Decisión de diseño:**  
Se selecciona una arquitectura web de **tres capas** por su separación de responsabilidades, escalabilidad, mantenimiento sencillo y reutilización de componentes.

**Tecnologías:**
- Frontend → Angular  
- Backend → Spring Boot  
- Base de datos → MySQL  

📷 *[Insertar imagen: Diagrama de arquitectura]*

---

### 4.2 Diseño del Modelo de Datos
**Entidades principales:** Usuario, Película, Sala, Función, Asiento, Compra, Ticket.  

📷 *[Insertar imagen: Modelo entidad–relación (ER)]*

---

### 4.3 Diseño Orientado a Objetos
Principios aplicados: **Encapsulamiento, alta cohesión, bajo acoplamiento**.  

📷 *[Insertar imagen: Diagrama de clases UML]*

---

### 4.4 Diseño del Flujo de Compra (Secuencia)
Escenario: Cliente compra una entrada.  
Reglas de negocio:  
- RN-01 Máximo 8 entradas por compra.  
- RN-02 No vender si la función empieza en menos de 30 minutos.  

📷 *[Insertar imagen: Diagrama de secuencia]*

---

### 4.5 Diseño de Interfaces (Wireframes)
Pantallas: Cartelera, selección de asientos, compra.  
Requisito no funcional: **Diseño adaptable (responsive)**.  

📷 *[Insertar imágenes de wireframes]*

---

## 📚 Marco Teórico
El ciclo de vida del desarrollo de software (SDLC) es una metodología estructurada e iterativa utilizada por los equipos de desarrollo para construir, entregar y mantener sistemas de software de alta calidad y rentables.  
Divide el desarrollo en fases distintas, repetibles e interdependientes, cada una con objetivos y entregables que guían la siguiente fase. (IBM, 2026)

---

## 📊 Resultados
- Se definió una arquitectura escalable y mantenible.  
- Se diseñó un modelo de datos completo y normalizado.  
- Se elaboraron diagramas UML (clases, secuencia, ER).  
- Se validó el cumplimiento de requisitos no funcionales.  
- Se estableció la trazabilidad entre requisitos y diseño.  

---

## ✅ Conclusiones
**Conclusión ambiental:**  
El proyecto demuestra que el uso de metodologías ágiles y herramientas digitales contribuye a la sostenibilidad, reduciendo el consumo de recursos físicos y fomentando prácticas responsables en el desarrollo de software.  

**Conclusión del proyecto:**  
La aplicación del ciclo de vida del software bajo **SCRUM y XP** permitió estructurar un sistema escalable, mantenible y orientado a la calidad. El diseño fortalece competencias técnicas en arquitectura, modelado de datos, UML y gestión de requisitos, además de potenciar el trabajo colaborativo.  

---

## 📚 Referencias
- IBM. (s.f.). *¿Qué es el ciclo de vida del desarrollo de software (SDLC)?*. IBM Think. Recuperado el 7 de junio de 2026, de [https://www.ibm.com/es-es/think/topics/sdlc](https://www.ibm.com/es-es/think/topics/sdlc)  
- Elsevier. (s.f.). *Software Development Lifecycle*. ScienceDirect Topics. Recuperado el 7 de junio de 2026, de [https://www.sciencedirect.com/topics/computer-science/software-development-lifecycle](https://www.sciencedirect.com/topics/computer-science/software-development-lifecycle)  
