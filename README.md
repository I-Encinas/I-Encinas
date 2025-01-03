## Hi there 👋
# Puzzle Solver en Kotlin

Este proyecto implementa un solucionador automático de un rompecabezas deslizante de 3x3 en **Kotlin**. El programa utiliza técnicas heurísticas para determinar los movimientos óptimos y resolver el puzzle, asegurándose de que siempre sea resoluble.

---

## Tabla de Contenidos
- [Descripción](#descripción)
- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Ejecución](#ejecución)
- [Estructura del Código](#estructura-del-código)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Descripción

El objetivo principal de este proyecto es resolver un puzzle deslizante de manera programática. El puzzle consiste en un tablero 3x3 que contiene números del 0 al 8, con un espacio vacío que permite mover los números adyacentes. El programa evalúa los movimientos posibles utilizando una combinación de heurísticas `g` y `h` para encontrar la solución más eficiente.

---

## Características

- **Generación aleatoria de estados iniciales:** Siempre genera un estado resoluble.
- **Algoritmo heurístico:** Combina heurísticas de proximidad y peso para encontrar soluciones óptimas.
- **Registro de movimientos:** Guarda las jugadas realizadas para evitar bucles.
- **Estructura modular:** Métodos independientes para calcular heurísticas, manejar movimientos y verificar soluciones.

---

## Requisitos

- **Kotlin:** Versión 1.6 o superior.
- Un entorno de desarrollo compatible, como IntelliJ IDEA o cualquier editor con soporte para Kotlin.

---

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/tu-repositorio.git

**I-Encinas/I-Encinas** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
# Puzzle Solver en Kotlin

Este proyecto implementa un solucionador automático de un rompecabezas deslizante de 3x3 en **Kotlin**. El programa utiliza técnicas heurísticas para determinar los movimientos óptimos y resolver el puzzle, asegurándose de que siempre sea resoluble.

---

## Tabla de Contenidos
- [Descripción](#descripción)
- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Ejecución](#ejecución)
- [Estructura del Código](#estructura-del-código)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Descripción

El objetivo principal de este proyecto es resolver un puzzle deslizante de manera programática. El puzzle consiste en un tablero 3x3 que contiene números del 0 al 8, con un espacio vacío que permite mover los números adyacentes. El programa evalúa los movimientos posibles utilizando una combinación de heurísticas `g` y `h` para encontrar la solución más eficiente.

---

## Características

- **Generación aleatoria de estados iniciales:** Siempre genera un estado resoluble.
- **Algoritmo heurístico:** Combina heurísticas de proximidad y peso para encontrar soluciones óptimas.
- **Registro de movimientos:** Guarda las jugadas realizadas para evitar bucles.
- **Estructura modular:** Métodos independientes para calcular heurísticas, manejar movimientos y verificar soluciones.

---

## Requisitos

- **Kotlin:** Versión 1.6 o superior.
- Un entorno de desarrollo compatible, como IntelliJ IDEA o cualquier editor con soporte para Kotlin.

---

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/tu-repositorio.git

2. Abre el proyecto en tu entorno de desarrollo favorito.
3. Asegúrate de tener configurado Kotlin en tu entorno.

## Ejecución

1. Ejecuta el archivo `Main.kt`.
2. Sigue las instrucciones en la consola para observar el proceso de solución paso a paso.
3. El programa terminará cuando el puzzle esté resuelto.

---

## Estructura del Código

- **`main`**: Punto de entrada del programa. Contiene el bucle principal para ejecutar los movimientos.
- **Funciones clave**:
  - `esResoluble`: Determina si el estado inicial del puzzle es resoluble.
  - `generarEstadoAleatorio`: Genera un tablero inicial válido.
  - `heuristica_g` y `heuristca_h`: Evalúan la calidad de un movimiento.
  - `hallar_adyacetes`: Encuentra las posiciones adyacentes al espacio vacío.
  - `movimientos`: Realiza un movimiento basado en la evaluación heurística.

---

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el código, por favor:
1. Haz un fork del repositorio.
2. Crea una nueva rama con tus cambios:
   ```bash
   git checkout -b feature/nueva-funcionalidad
3. Realiza un pull request describiendo tus cambios.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
<!--
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
