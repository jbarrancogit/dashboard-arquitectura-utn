# Dashboard de Estudio — Arquitectura de Computadoras

**UTN FRM — ISI — 2do semestre, 1er ano**

Dashboard interactivo de estudio para preparar el final de Arquitectura de Computadoras. Un unico archivo HTML autocontenido, sin dependencias externas, desplegado en GitHub Pages.

**[Abrir Dashboard](https://jbarrancogit.github.io/dashboard-arquitectura-utn/)**

---

## Que incluye

### Panel Inteligente
- Recomendacion diaria basada en progreso, flashcards pendientes y bolillas debiles
- Progreso general y por unidad (U1-U5)
- Meta semanal de horas de estudio + racha de dias consecutivos
- Estadisticas: ejercicios, temas, flashcards, sesiones pomodoro

### Teoria (3 capas)
53 tarjetas de teoria organizadas en 7 unidades tematicas:
- **Capa 1** — Resumen esencial (siempre visible)
- **Capa 2** — Explicacion completa con ejemplos, formulas y tablas
- **Capa 3** — Material de referencia: PDFs del campus, videos YouTube, datasheets

### Ejercicios
186 ejercicios unificados:
- 89 ejercicios de examen con soluciones completas
- 97 ejercicios de trabajos practicos
- Filtros por unidad, estado, dificultad y tipo
- Sistema de estrellas y seguimiento de estado

### Flashcards con Repeticion Espaciada
50 flashcards con algoritmo hibrido:
- 3 botones: **No se** (repaso manana) / **Casi** (en 3 dias) / **Lo se** (intervalo x2)
- Modo "Hoy": sesion con solo las cards que toca repasar
- Modo "Todas": grilla completa con filtros por unidad
- Intervalos dinamicos que se ajustan a los dias restantes antes del examen

### Bolillero
Simulador del sorteo de bolillas del examen oral:
- Saca 2 bolillas al azar, elegis 1 y practicas la exposicion
- Checklist de temas a cubrir por bolilla
- Rating de 1-5 estrellas, historial y deteccion de bolillas debiles

### Modo Examen
- **Simulacro de Admision**: 1 ejercicio al azar + timer de 15 minutos
- **Simulacro Moodle**: preguntas multiple choice con timer de 2 horas
- **5 Examenes Probables**: escenarios completos con ejercicio de admision + guia oral

### Recursos
Todo el material del campus organizado por unidad:
- Guias de trabajos practicos
- Datasheets de circuitos integrados
- Videos de YouTube por tema
- Libro de la catedra y programa

### Plan de 8 Semanas
- Cronograma con fases: Aprender, Practicar, Demostrar
- Progreso de ejercicios calculado automaticamente
- Timer Pomodoro integrado (50min trabajo / 10min descanso)
- Boton flotante para acceder al timer desde cualquier seccion

---

## Arquitectura tecnica

| Aspecto | Detalle |
|---------|---------|
| Formato | Archivo HTML unico (~6100 lineas) |
| Dependencias | Ninguna (vanilla HTML/CSS/JS) |
| Persistencia | localStorage con migracion automatica v2 → v3 |
| Backup | Exportar/importar datos como JSON |
| Deploy | GitHub Pages (rama `main`) |
| Responsive | Desktop (sidebar 220px), tablet (sidebar 60px), mobile (bottom nav) |

## Materia

| Campo | Detalle |
|-------|---------|
| Codigo | 07 |
| Profesor titular | Perez, Santiago |
| Nivel | 1er ano, 2do semestre |
| Examen final | Oral + ejercicio de admision |

### Unidades tematicas

1. Representacion de datos y codigos
2. Algebra de Boole y sistemas digitales
3. Memorias electronicas
4. Arquitectura de computadoras (Maquina Elemental)
5. Modos de direccionamiento y 8088
6. Arquitecturas avanzadas
7. Entrada/Salida y perifericos

---

**Autor:** Juan Ignacio Barranco Bastan — Leg. 44041
