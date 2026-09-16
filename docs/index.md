# Presentación del curso

---

## 1. Información General del Módulo

* **Curso:** 1º DAM (Desarrollo de Aplicaciones Multiplataforma) - Curso 2026-2027
* **Profesor:** [Nombre del profesor] ([correo@edu.gva.es](mailto:correo@edu.gva.es))
* **Carga horaria:** 96 horas en total (aprox. 3 horas/semana)
* **Centro:** IES Severo Ochoa

### Horario Semanal
* **[Día]:** [hora inicio] - [hora fin] h
* **[Día]:** [hora inicio] - [hora fin] h
* **[Día]:** [hora inicio] - [hora fin] h

> Este módulo profesional tiene el código **0487** dentro del título de Técnico Superior en Desarrollo de Aplicaciones Multiplataforma, y se cursa en 1º curso.

---

## 2. Resultados de Aprendizaje (RA)

* **RA1:** Reconoce los elementos y herramientas que intervienen en el desarrollo de un programa informático, analizando sus características y las fases en las que actúan hasta llegar a su puesta en funcionamiento.
* **RA2:** Evalúa entornos integrados de desarrollo, analizando sus características para editar código fuente y generar ejecutables.
* **RA3:** Verifica el funcionamiento de programas diseñando y realizando pruebas.
* **RA4:** Optimiza código empleando las herramientas disponibles en el entorno de desarrollo.
* **RA5:** Genera diagramas de clases valorando su importancia en el desarrollo de aplicaciones y empleando las herramientas disponibles en el entorno.
* **RA6:** Genera diagramas de comportamiento valorando su importancia en el desarrollo de aplicaciones y empleando las herramientas disponibles en el entorno.

---

## 3. Temporalización

El contenido se distribuye en 6 unidades didácticas organizadas a lo largo de dos evaluaciones *(temporalización orientativa)*.

La secuenciación se ha diseñado para introducir **el control de versiones (Git y GitHub) muy pronto**, justo después de los fundamentos de lenguajes y entornos de desarrollo, de forma que el alumnado lo use desde el principio en el resto de prácticas del curso. Los **diagramas UML** se han reducido a lo realmente usado en la industria hoy en día. El módulo cierra con dos bloques fuertes, **Pruebas** y **Refactorización**, dejando esta última para el final, cuando el alumnado ya tiene una base sólida de programación sobre la que optimizar código.

| Unidad Didáctica | Evaluación | Horas estimadas |
| :--- | :---: | :---: |
| **UD1:** Lenguajes de programación y entornos de desarrollo (IDE) | Primera | 20 |
| **UD2:** Control de versiones: Git y GitHub | Primera | 12 |
| **UD3:** Ingeniería del software y proceso de desarrollo | Primera | 14 |
| **UD4:** UML aplicado: diagramas de clases y de comportamiento | Segunda | 14 |
| **UD5:** Pruebas y depuración | Segunda | 20 |
| **UD6:** Refactorización y optimización de código | Segunda | 16 |

> ℹ️ El contenido de "control de versiones" está encuadrado oficialmente dentro del RA4 (el mismo Resultado de Aprendizaje que la refactorización), aunque aquí se imparta mucho antes. Esto no afecta a la ponderación de dicho RA, que se sigue evaluando de forma acumulada a lo largo del curso (UD2 + UD6).

---

## 4. Criterios de Evaluación

### Ponderación por Resultado de Aprendizaje

Ponderación orientativa de los RA dentro del módulo, en función del peso de sus criterios de evaluación:

| Resultado de Aprendizaje | Porcentaje |
| :--- | :---: |
| **RA1:** Elementos y herramientas del desarrollo de software | 14% |
| **RA2:** Entornos integrados de desarrollo | 16% |
| **RA3:** Verificación y pruebas de programas | 22% |
| **RA4:** Optimización de código (incluye control de versiones y refactorización) | 18% |
| **RA5:** Diagramas de clases | 14% |
| **RA6:** Diagramas de comportamiento | 16% |

!!! warning "Condiciones de Evaluación Continua y Autoría"
    * **Asistencia mínima:** Faltar al **15% o más** de las horas implica la pérdida de la evaluación continua, teniendo que realizar un examen final global del módulo.
    * **Aprobado independiente:** Es necesario **aprobar por separado** cada uno de los Resultados de Aprendizaje.
    * **Verificación de autoría:** Tras la entrega de cualquier práctica, el docente podrá solicitar que se explique cualquier paso realizado. La imposibilidad de justificar la autoría resultará en la **anulación de la práctica (nota nula)**.
    * **Pruebas objetivas:** Se realizarán al final de cada unidad utilizando los ordenadores del aula.

---

## 5. Herramientas Necesarias

Para el seguimiento de las clases prácticas y teóricas se utilizará:

* Correo del estudiante (Outlook institucional).
* Plataforma de aprendizaje **Aules**.
* Un **JDK** (Java Development Kit) y/o el entorno de ejecución correspondiente al lenguaje de trabajo del aula.
* Un **IDE** (Entorno Integrado de Desarrollo): Eclipse, NetBeans, IntelliJ IDEA o Visual Studio Code, según la unidad.
* **Git** y una cuenta de **GitHub**, desde la UD2 y durante todo el resto del curso.
* Herramienta de modelado UML: **Visual Paradigm** (u otra equivalente) para los diagramas de clases y comportamiento.
* Entornos de virtualización (máquinas virtuales).

---

## 6. Resumen de Contenidos del Módulo

### Bloques que Estudiaremos

#### Lenguajes de programación y entornos de desarrollo (IDE)
* Relación entre el software y los componentes del sistema informático (memoria, procesador, periféricos).
* Clasificación de los lenguajes de programación según su nivel de abstracción y su forma de ejecución.
* **Código fuente, código objeto y código ejecutable:** diferencias entre ambos y el papel de las máquinas virtuales.
* Funciones y componentes de un IDE: editor, compilador/intérprete, depurador, asistente de interfaces gráficas.
* Instalación, configuración y personalización de un IDE.
* **Entornos propietarios frente a entornos libres:** comparativa de características.
* **Ejemplos de software:** Eclipse, NetBeans, IntelliJ IDEA, Visual Studio Code.

#### Control de versiones: Git y GitHub
* Por qué versionar el código desde el primer día, aunque se trabaje solo.
* Conceptos básicos: repositorio, commit, rama (*branch*), *merge*.
* Flujo de trabajo habitual: `clone`, `add`, `commit`, `push`, `pull`.
* Trabajo colaborativo en GitHub: *forks*, *pull requests*, resolución de conflictos.
* Integración del control de versiones en el propio IDE.
* Buenas prácticas: mensajes de commit, `.gitignore`, ramas por funcionalidad.

#### Ingeniería del software y proceso de desarrollo
* Fases del ciclo de vida de una aplicación: análisis, diseño, codificación, pruebas, documentación, explotación y mantenimiento.
* Modelos de ciclo de vida (cascada, iterativo, ágil) y su relación con el trabajo diario en el IDE.
* Herramientas implicadas en la obtención de código ejecutable a partir del código fuente: compiladores, intérpretes y traductores de lenguajes.

#### UML aplicado
* Conceptos básicos de la programación orientada a objetos: clases, atributos, métodos y visibilidad.
* **Diagramas de clases:** objetos, instanciación y relaciones (herencia, composición, agregación). Generación de código a partir de un diagrama de clases e **ingeniería inversa**.
* **Diagramas de casos de uso:** actores, escenarios y relaciones (inclusión, extensión, generalización). Muy usados para documentar requisitos.
* **Diagramas de secuencia:** línea de vida de un objeto, activación y envío de mensajes. Los más usados hoy en día para documentar interacciones y APIs.
* *Mención breve* a los diagramas de actividad como alternativa a un diagrama de flujo clásico. Se deja fuera el diagrama de colaboración, en desuso frente al de secuencia.

#### Pruebas y depuración
* Tipos de pruebas: funcionales, estructurales, de regresión y unitarias.
* Herramientas de depuración: puntos de ruptura, seguimiento de variables, ejecución paso a paso.
* Introducción a *frameworks* de pruebas unitarias (p. ej. JUnit).
* Documentación del plan de pruebas.

#### Refactorización y optimización de código
* Concepto y limitaciones de la refactorización: por qué se hace después de tener el código funcionando y bien probado.
* Patrones de refactorización más habituales.
* Uso de analizadores de código estático.
* Relación entre refactorización, pruebas y control de versiones (una rama de Git por cada refactor).
* Documentación del código: comentarios, convenciones y herramientas de generación automática (por ejemplo, Javadoc).
