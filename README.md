# Noche de Juegos

Set de party games en español para jugar en la tele, el notebook o pasándose el celular.

**Jugar:** https://alenae1993.github.io/Noche-de-Juegos/

## Juegos

| Juego | Basado en | Cómo se juega |
|---|---|---|
| Trivia relámpago | Kahoot | Preguntas de 4 opciones por categorías (Chile, geografía, historia, ciencia, deportes, cine, música) |
| El Rosco | Pasapalabra | Dos equipos, roscos A–Z distintos y reloj por equipo |
| 100 chilenos dijeron | Family Feud | Encuestas (ficticias), 3 errores y robo de puntos |
| El Impostor | Spyfall | Se pasa el dispositivo; todos ven la palabra menos el impostor |
| Onda | Wavelength | El psíquico da una pista y el grupo ubica el objetivo en el dial |
| Dibuja y adivina | Pictionary | Se dibuja en la pantalla con temporizador |
| ¿Quién es más probable? | Juego de fiesta | Pregunta, cuenta regresiva y todos apuntan |
| Feria de cachureos | Pit / La Feria de las Pulgas | Todos cambian cartas a la vez desde el celular gritando la cantidad; gana quien junta 9 iguales y toca la campana (3 a 10 jugadores, solo con sala) |
| Adivina la canción | Hitster | El DJ pone la canción en Spotify; buzzer o adivinar el año |

Incluye un interruptor de contenido +18 (preguntas de carrete y copete).

## Notas

- Todo el juego es un solo archivo, `index.html`, sin dependencias ni build.
- El contenido (preguntas, roscos, encuestas, palabras, canciones) está en listas al inicio del script, fáciles de editar.
- **Sala con celulares:** la pantalla principal crea una sala con un código de 4 letras y cada jugador se une desde su celular abriendo este mismo link. Fuera de claude.ai la conexión es directa entre dispositivos (WebRTC con [PeerJS](https://peerjs.com) y su servidor público gratuito), sin cuentas ni servidor propio. Funciona mejor con todos en el mismo WiFi; algunas redes móviles o corporativas pueden bloquear la conexión directa.
- El botón **← Atrás** y el botón atrás del navegador o del celular vuelven a la pantalla anterior.
