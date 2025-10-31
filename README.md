# Taíno vs Caribe — Tres en Raya

**Autor:**  
Pascual Pimentel Vicente 

---

## Descripción del juego

**Taíno vs Caribe** es una versión dominicana del clásico **Tres en Raya (Tic Tac Toe)** desarrollada con **React**.  
Dos jugadores —**Jugador Quisqueya (X)** y **Taíno Caribe (O)**— se enfrentan en un tablero 3x3 para lograr tres en línea.  

Incluye:
- Turnos alternados entre los jugadores.
- Detección automática de ganador o empate.
- Botón de **Reiniciar** para empezar una nueva partida.
- Guardado automático en el navegador con **localStorage**.
- Estilos inspirados en la **bandera dominicana** y sonidos locales.

---

## Lo que aprendí

Durante el desarrollo de este proyecto aprendí a:
- Crear y manejar **componentes funcionales** en React.
- Usar **useState** y **useEffect** para manejar el estado del juego.
- Implementar **persistencia con localStorage** para guardar partidas.
- Aplicar estilos con CSS en componentes de React.
- Comprender mejor cómo **React renderiza y actualiza** la interfaz al cambiar el estado.

---

## La parte más difícil

La parte más retadora fue:
- La **detección del ganador** en el tablero, asegurando que todas las combinaciones posibles se revisaran correctamente.
- Manejar el **estado del juego guardado en localStorage**, para que al recargar la página no se pierda el progreso.
- Ajustar los estilos y colores para lograr un diseño limpio pero con un **toque dominicano auténtico 🇩🇴**.

---

## Cómo ejecutar el proyecto

1. Clonar o copiar el repositorio.  
2. Instalar dependencias:
   ```bash
   npm install
   npm run dev
   http://localhost:5173/
