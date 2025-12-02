# Simulador de Cubo de Rubik (3D)

## Descripción

Este proyecto es una aplicación de escritorio en Java que simula un Cubo de Rubik 3x3x3 con visualización en 3D. Permite al usuario interactuar con el cubo, ejecutar movimientos válidos, guardar y continuar partidas, y visualizar la solución o los movimientos realizados. La interfaz utiliza pantallas definidas en FXML y componentes gráficos de JavaFX para mostrar las piezas del cubo como mallas tridimensionales.

## Qué hace

- Permite girar las seis caras del cubo (superior, inferior, izquierda, derecha, frontal y trasera).
- Representa el cubo internamente como una estructura de piezas (centros, aristas y esquinas) y mantiene un historial de movimientos.
- Guarda y carga el progreso del jugador en archivos de texto simples (nombre, puntaje, movimientos, tiempo).
- Muestra la representación 3D del cubo usando mallas (`TriangleMesh`) y grupos de `MeshView` en JavaFX.
- Ofrece funcionalidades adicionales en la interfaz como iniciar nueva partida, continuar partida guardada y ver registros (records).

## Características principales

- Interfaz gráfica interactiva basada en JavaFX (ventanas FXML y estilos CSS).
- Visualización 3D de cada "cubito" con mallas trianguladas.
- Lógica del cubo modelada con objetos por pieza (`Cubito`) y una matriz 3x3x3 que representa su estado.
- Almacenamiento simple de partidas y records en archivos de texto.
- Navegación entre vistas mediante controladores separados y un `FlowController`.

## Tecnologías principales

- **Java** (JDK 17)
- **JavaFX** (FXML, `MeshView`, `TriangleMesh`) para la interfaz y gráficos 3D
- **Maven** como herramienta de construcción
- **FXML + CSS** para las vistas y estilos de la interfaz

## Cómo probar (resumen rápido)

1. Abrir el proyecto en tu IDE Java preferido (por ejemplo, IntelliJ IDEA o NetBeans).
2. Compilar y ejecutar la clase principal `cr.ac.una.proyecto1_datos.App`.

Opcional: si el `pom.xml` incluye los plugins necesarios, también se puede ejecutar con Maven (`mvn clean package` o `mvn javafx:run`).

## Screenshots

---

## Contribuyentes

- Luis Vargas (`Luvara`)
