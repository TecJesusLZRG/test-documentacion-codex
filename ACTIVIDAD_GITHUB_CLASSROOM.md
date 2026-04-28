# Actividad: Propuesta de Práctica Temática Pequeña (Enfoque en Documentación)

## 1) Título de la práctica

**Diseño de Práctica Temática: Proyecto Pequeño en Terminal**

> Puedes adaptar el título final de tu propuesta a algo más específico, por ejemplo:
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general

En esta actividad **no se evalúa un sistema grande**, sino tu capacidad para **diseñar, justificar y documentar** una práctica temática pequeña que pueda desarrollarse de forma realista en este curso.

Vas a construir una **propuesta de proyecto pequeño** donde primero explicas:
- qué problema resuelve,
- para quién está pensado,
- cómo se organizará el repositorio,
- y cómo validarás su funcionamiento con pruebas simples.

Después, de forma opcional, podrás incluir un prototipo mínimo.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** úsalo solo si tu idea será **muy pequeña y acotada** (por ejemplo, utilidades mínimas de entrada/salida, operaciones básicas o ejercicios de arquitectura muy concretos).

### Enfoque obligatorio
La prioridad es:
1. **Documentación clara**
2. **Planeación realista**
3. **Estructura del repositorio**
4. **Explicación del caso de uso**

El código puede ser mínimo. Recuerda que el proyecto debe ser compatible con tiempos cortos y herramientas con límites de uso (como versiones gratuitas de asistentes de IA).

### Restricciones del alcance
Para mantener el proyecto pequeño, **evita**:
- frameworks grandes,
- APIs pagadas,
- bases de datos,
- servicios en la nube,
- contenedores,
- dependencias complejas o difíciles de instalar.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Elementos opcionales (si decides mostrar un prototipo mínimo):
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

Usa esta estructura base como referencia:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `main.<ext>` depende del lenguaje elegido:
> - ARM64 Assembly: `main.S` (o `.s`)
> - C: `main.c`
> - Python: `main.py`
> - Bash: `main.sh`

---

## Guía de contenido por archivo

### `README.md`
Incluye:
1. Nombre del proyecto.
2. Lenguaje principal elegido y justificación breve.
3. Problema que resuelve (2–4 párrafos).
4. Alcance: qué sí hará y qué no hará.
5. Instrucciones mínimas para ejecutar (aunque sea prototipo).
6. Estructura del repositorio (resumen corto con viñetas).

### `docs/propuesta.md`
Incluye:
1. **Tema de la práctica**.
2. **Objetivo general** y 2–3 objetivos específicos.
3. **Descripción funcional mínima** (qué hace el proyecto de inicio a fin).
4. **Justificación técnica** del lenguaje elegido.
5. **Plan de trabajo pequeño** (3–6 pasos realistas).
6. **Riesgos y límites** (qué podría complicarse y cómo lo reducirás).

### `docs/caso_de_uso.md`
Incluye al menos:
1. Actor principal (quién usa la herramienta).
2. Contexto (en qué situación la usa).
3. Flujo principal paso a paso.
4. Entradas esperadas.
5. Salidas esperadas.
6. Criterios de éxito del caso de uso.

### `docs/estructura_repositorio.md`
Incluye:
1. Árbol del repositorio actualizado.
2. Explicación breve de cada carpeta/archivo clave.
3. Convenciones de nombres (archivos, scripts, pruebas).
4. Decisión sobre manejo de dependencias (idealmente mínimo o nulo).

### `docs/plan_de_pruebas.md`
Incluye:
1. Lista de pruebas manuales o simples automatizadas.
2. Casos normales, casos límite y casos de error.
3. Para cada prueba: entrada, comando (si aplica), resultado esperado.
4. Criterio de “aprobado” para considerar funcional el prototipo.

---

## Criterios de evaluación sugeridos

1. **Claridad de la propuesta (30%)**
   - El problema y objetivo se entienden sin ambigüedades.
2. **Calidad de la documentación (30%)**
   - Archivos completos, coherentes y bien estructurados.
3. **Viabilidad técnica (20%)**
   - Proyecto pequeño, realista y acorde al lenguaje seleccionado.
4. **Estructura de repositorio y pruebas (20%)**
   - Organización clara y plan de validación útil.

---

## Recomendaciones finales para estudiantes

- Empieza por delimitar una idea **chiquita pero completa**.
- Si eliges ARM64, reduce alcance al máximo.
- Es mejor una propuesta simple, bien argumentada y bien documentada, que una idea grande incompleta.
- Redacta pensando en que otra persona pueda continuar tu proyecto solo leyendo tus documentos.

---

## Entrega

Sube tu propuesta al repositorio asignado en GitHub Classroom respetando la estructura solicitada. Asegúrate de que los archivos obligatorios existan y tengan contenido sustancial.
