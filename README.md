# Planificador de Correlativas UTN (Plan 2023)

Herramienta web simple (HTML + CSS + JavaScript) para planificar la cursada de Ingeniería en Sistemas de Información usando correlativas del Plan 2023.

Permite armar el plan por años, ver qué materias se habilitan según lo ya asignado y validar el avance para el Título Intermedio.

## Demo online

- [Abrir planificador en GitHub Pages](https://ricardoaguirresanchez.github.io/planificator_utn_se_subjects/planificador-correlativas.html)

## Funcionalidades

- Armado manual del plan por año (1° a 8°).
- Agregado de materias habilitadas por correlativas.
- Reubicación de materias entre años.
- Visualización de materias pendientes y habilitadas.
- Validación de requisitos para Título Intermedio (TI):
  - Materias requeridas.
  - Seminario Integrador (TI).
  - Mínimo de 3 electivas.
- Persistencia local del plan con `localStorage`.

## Archivos principales

- `planificador-correlativas.html`: aplicación principal autocontenida.
- `documentacion/Correlativas-plan-2023.pdf`: base de correlatividades usada para el plan general.
- `documentacion/titulo_intermedio.pdf`: referencia para requisitos del título intermedio.

## Uso

1. Abrir `planificador-correlativas.html` en cualquier navegador moderno.
2. En cada año, agregar materias habilitadas.
3. Revisar las secciones de estado y validación TI para ver faltantes.

## Notas

- Esta herramienta es de apoyo para planificación académica.
- Verificá siempre los requisitos oficiales con tu Facultad Regional.
