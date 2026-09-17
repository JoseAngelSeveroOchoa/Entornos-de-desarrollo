# Presentación del curso

---

## 1. Información General del Módulo

* **Curso:** 1º DAM (Desarrollo de Aplicaciones Multiplataforma) - Curso 2026-2027
* **Profesor:** José Ángel Segarra Castillo ([ja.segarracastillo@edu.gva.es](mailto:ja.segarracastillo@edu.gva.es))
* **Carga horaria:** 96 horas en total ( 3 horas/semana)
* **Centro:** IES Severo Ochoa

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

El contenido se distribuye en **10 unidades didácticas** *(distribución consensuada por el departamento)*, organizadas a lo largo de dos evaluaciones *(temporalización orientativa)*.

Se mantiene el criterio de introducir **el control de versiones (Git y GitHub) desde el primer momento**, para que el alumnado lo use durante todo el resto del curso. Los bloques de **pruebas** se dividen en dos unidades independientes: el diseño de las pruebas (UD4) y su ejecución/validación (UD8). El diseño orientado a objetos (UD5) se trata como unidad propia antes de entrar en los diagramas concretos (UD6 y UD7). El módulo cierra con **Refactorización** (UD9) y **Documentación** (UD10).

| Unidad Didáctica | Evaluación | Horas estimadas | RA principal |
| :--- | :---: | :---: | :---: |
| **UD1:** Control de versiones | Primera | 8 | RA4 |
| **UD2:** Desarrollo y ejecución de software | Primera | 10 | RA1 |
| **UD3:** Instalación y configuración de entornos de desarrollo | Primera | 10 | RA2 |
| **UD4:** Diseño y realización de pruebas | Primera | 10 | RA3 |
| **UD5:** Diseño orientado a objetos. UML | Primera | 6 | RA5 |
| **UD6:** Diagramas de clases | Segunda | 10 | RA5 |
| **UD7:** Diagramas de comportamiento | Segunda | 10 | RA6 |
| **UD8:** Validaciones de software | Segunda | 10 | RA3 |
| **UD9:** Optimización del código. Refactorización | Segunda | 14 | RA4 |
| **UD10:** Documentación de código | Segunda | 8 | RA4 |

> ℹ️ **Sobre el RA4:** su contenido queda repartido en tres unidades no consecutivas (UD1 Control de versiones, UD9 Refactorización, UD10 Documentación). No afecta a su ponderación, que se evalúa de forma acumulada a lo largo de todo el curso.
>
> ℹ️ **Sobre el RA3:** se ha dividido en dos unidades: UD4 (diseño de las pruebas y depuración) y UD8 (ejecución, *frameworks* de prueba y validación de resultados). Igualmente se evalúa de forma acumulada.

---

## 4. Criterios de Evaluación

### Ponderación por Resultado de Aprendizaje

Ponderación orientativa de los RA dentro del módulo, en función del peso de sus criterios de evaluación:

| Resultado de Aprendizaje | Porcentaje |
| :--- | :---: |
| **RA1:** Elementos y herramientas del desarrollo de software | 14% |
| **RA2:** Entornos integrados de desarrollo | 16% |
| **RA3:** Verificación y pruebas de programas | 22% |
| **RA4:** Optimización de código (incluye control de versiones, refactorización y documentación) | 18% |
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
* **Git** y una cuenta de **GitHub**, desde la UD1 y durante todo el resto del curso.
* Un **JDK** (Java Development Kit) y/o el entorno de ejecución correspondiente al lenguaje de trabajo del aula.
* Un **IDE** (Entorno Integrado de Desarrollo): Eclipse, NetBeans, IntelliJ IDEA o Visual Studio Code, según la unidad.
* Herramienta de modelado UML: **Visual Paradigm** (u otra equivalente) para las UD5, UD6 y UD7.
* Framework de pruebas unitarias (p. ej. **JUnit**) para las UD4 y UD8.
* Entornos de virtualización (máquinas virtuales).

---

## 6. Resumen de Contenidos del Módulo

### Bloques que Estudiaremos

#### 1. Control de versiones
* Por qué versionar el código desde el primer día, aunque se trabaje solo.
* Conceptos básicos: repositorio, commit, rama (*branch*), *merge*.
* Flujo de trabajo habitual: `clone`, `add`, `commit`, `push`, `pull`.
* Trabajo colaborativo en GitHub: *forks*, *pull requests*, resolución de conflictos.
* Integración del control de versiones en el propio IDE.
* Buenas prácticas: mensajes de commit, `.gitignore`, ramas por funcionalidad.

#### 2. Desarrollo y ejecución de software
* Relación entre el software y los componentes del sistema informático (memoria, procesador, periféricos).
* Clasificación de los lenguajes de programación según su nivel de abstracción y su forma de ejecución.
* **Código fuente, código objeto y código ejecutable:** diferencias entre ambos y el papel de las máquinas virtuales.
* Herramientas implicadas en la obtención de código ejecutable a partir del código fuente: compiladores, intérpretes y traductores de lenguajes.
* Fases del ciclo de vida de una aplicación: análisis, diseño, codificación, pruebas, documentación, explotación y mantenimiento.
* Modelos de ciclo de vida (cascada, iterativo, ágil).

#### 3. Instalación y configuración de entornos de desarrollo
* Funciones y componentes de un IDE: editor, compilador/intérprete, depurador, asistente de interfaces gráficas.
* Instalación, configuración y personalización de un IDE.
* **Entornos propietarios frente a entornos libres:** comparativa de características.
* **Ejemplos de software:** Eclipse, NetBeans, IntelliJ IDEA, Visual Studio Code.
* Integración del IDE con el control de versiones y con herramientas externas.

#### 4. Diseño y realización de pruebas
* Tipos de pruebas: funcionales, estructurales, de regresión y unitarias.
* Diseño de casos de prueba: qué probar y cómo definir los datos de entrada y los resultados esperados.
* Herramientas de depuración: puntos de ruptura, seguimiento de variables, ejecución paso a paso.
* Documentación del plan de pruebas.

#### 5. Diseño orientado a objetos. UML
* Conceptos básicos de la programación orientada a objetos: clases, atributos, métodos y visibilidad.
* Objetos, instanciación y encapsulación.
* Relaciones entre clases: herencia, composición y agregación.
* UML como lenguaje de modelado: para qué sirve separar el diseño de la implementación.
* Tipos de diagramas UML y en qué fase del desarrollo se usa cada uno.

#### 6. Diagramas de clases
* Notación de un diagrama de clases: atributos, métodos, visibilidad, tipos.
* Representación de las relaciones entre clases (herencia, composición, agregación, asociación).
* Generación de código a partir de un diagrama de clases.
* **Ingeniería inversa:** obtención de un diagrama de clases a partir de código ya existente.

#### 7. Diagramas de comportamiento
* **Diagramas de casos de uso:** actores, escenarios y relaciones (inclusión, extensión, generalización). Muy usados para documentar requisitos.
* **Diagramas de secuencia:** línea de vida de un objeto, activación y envío de mensajes. Los más usados hoy en día para documentar interacciones y APIs.
* *Mención breve* a los diagramas de actividad como alternativa a un diagrama de flujo clásico. Se deja fuera el diagrama de colaboración, en desuso frente al de secuencia.

#### 8. Validaciones de software
* Ejecución de las pruebas diseñadas en la UD4 y registro de resultados.
* Introducción a *frameworks* de pruebas unitarias (p. ej. JUnit).
* Automatización de pruebas e integración con el control de versiones.
* Informes de validación y control de calidad del software.

#### 9. Optimización del código. Refactorización
* Concepto y limitaciones de la refactorización: por qué se hace después de tener el código funcionando y bien probado.
* Patrones de refactorización más habituales.
* Uso de analizadores de código estático.
* Relación entre refactorización, pruebas y control de versiones (una rama de Git por cada refactor).

#### 10. Documentación de código
* Uso de comentarios y convenciones de documentación.
* Herramientas de generación automática de documentación (por ejemplo, Javadoc).
* Documentación como parte del propio proceso de desarrollo, no como tarea final aislada.
