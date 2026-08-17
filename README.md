# ci-cd-labs

Repositorio de prácticas y laboratorios para el aprendizaje de **Integración Continua (CI)** y **Despliegue Continuo (CD)**.

---

## 📋 Descripción del Proyecto
Este repositorio contiene la evolución gradual de un pipeline de CI/CD utilizando **GitHub Actions**, abarcando desde la configuración básica de workflows hasta estrategias de branching, pruebas automatizadas, análisis estático y despliegue continuo.

---

## 📂 Estructura del Repositorio

```text
ci-cd-labs/
│
├── .github/
│   └── workflows/
│       └── pipeline.yml       # Definición del flujo de trabajo de CI en GitHub Actions
├── app/
│   └── hello.txt              # Archivo de ejemplo de la aplicación
└── README.md                  # Documentación del proyecto
```

---

## 🛠️ Flujo de Trabajo y Ramas

Para garantizar la calidad y estabilidad del proyecto, se aplica la siguiente estrategia:
- `main`: Rama protegida que contiene la versión estable y lista para producción.
- `feature/*`: Ramas de funcionalidad creadas para desarrollar cambios de forma aislada.
- **Pull Requests (PR)**: Todo cambio debe ser propuesto mediante un PR hacia `main` y pasar exitosamente los controles de CI antes de ser integrado.

---

## 🚀 Laboratorios

- **Laboratorio 1:** Primer pipeline de Integración Continua (trigger en push, información de entorno, fecha y versión de Git).
- **Laboratorio 2:** Branching, Pull Requests, ejecuciones automáticas de CI y protección de la rama `main`.
