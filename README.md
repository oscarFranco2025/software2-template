# Proyecto – Ingeniería de Software II

## Objetivo del proyecto

Desarrollar un sistema software aplicando el proceso Ágil-UC / AgilSoft, cubriendo:

* Requisitos
* Análisis
* Diseño
* Construcción
* Pruebas
* Entrega final

---

## Uso de esta guía

Este repositorio y sus lineamientos constituyen una **guía de trabajo estructurada** para el desarrollo del proyecto.

Sin embargo, **no es una camisa de fuerza**.

Los equipos pueden:

* adaptar la organización de archivos,
* proponer mejoras en la estructura,
* incorporar herramientas o enfoques adicionales,

**siempre y cuando:**

* se mantenga una organización clara y consistente,
* se garantice la trazabilidad entre requisitos, diseño, código y pruebas,
* los entregables del proceso (AgilSoft / Ágil-UC) sigan siendo evidentes,
* el repositorio continúe siendo la fuente única y verificable del proyecto.

📌 En otras palabras:
Se permite flexibilidad en la forma, pero no en el fondo del proceso ni en la calidad de los resultados.

---

## Estructura del repositorio

```text
docs/
  00-lanzamiento/
  01-requisitos/
  02-analisis/
  03-diseno/
  04-pruebas/
  05-sprints/
  06-cierre/

src/        → código fuente
tests/      → pruebas
```

---

## Flujo de trabajo (OBLIGATORIO)

### 1. Crear una tarea (Issue)

Antes de desarrollar, se debe crear un Issue:

* Feature → nueva funcionalidad
* Bug → error

---

### 2. Crear rama de trabajo

Siempre desde `develop`:

```bash
git checkout develop
git pull
git checkout -b feature/nombre-corto
```

Ejemplos:

```bash
feature/login-usuario
feature/uc-01-registro
```

---

### 3. Desarrollo

* Hacer commits frecuentes
* Subir cambios:

```bash
git push origin feature/nombre-corto
```

---

### 4. Crear Pull Request

Siempre hacia:

```text
feature → develop
```

El Pull Request debe incluir:

* Descripción clara del cambio
* Issue relacionado
* Evidencia en la carpeta `docs/`

---

### 5. Revisión

* Otro integrante debe revisar
* Debe haber mínimo 1 aprobación

---

### 6. Integración

* Merge a `develop`
* Al finalizar el sprint:

```text
develop → main
```

---

## Ramas del proyecto

* `main` → versión estable (ENTREGA)
* `develop` → integración del equipo
* `feature/*` → trabajo individual

---

## Entregables por sprint

Cada sprint debe incluir:

### En `docs/`

* Casos de uso
* Especificaciones
* Modelos de análisis
* Diseño
* Evidencias de pruebas
* Resultados

---

## Evidencias (MUY IMPORTANTE)

Todo debe quedar en:

```text
docs/04-pruebas/evidencias/
```

Ejemplos:

* Capturas de pantalla
* Videos
* Logs
* Resultados de pruebas

---

## Definición de Terminado (DoD)

Un ítem se considera terminado si:

* Está implementado
* Tiene pruebas
* Cumple criterios de aceptación
* Está documentado
* Tiene evidencia
* Fue revisado por otro integrante

---

## Reglas importantes

* No hacer push directo a `main`
* Todo cambio debe ir por Pull Request
* Cada estudiante es responsable de sus casos de uso
* Todo debe quedar en el repositorio

---

## Evaluación

Se evaluará:

* Uso correcto de Git (ramas, PR)
* Calidad de requisitos
* Modelos de análisis
* Diseño
* Código
* Pruebas
* Evidencias
* Trazabilidad

---

## Recomendaciones

* Trabajar en equipo
* No dejar todo para el final
* Mantener el repositorio actualizado
* Documentar todo

---

## Nota final

Este repositorio es la **fuente oficial de evaluación**.
Si no está en el repositorio, no existe.
