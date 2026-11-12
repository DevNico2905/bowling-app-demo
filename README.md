# Bowling App Demo 🎳

**Demo pública de [La Bolera Universo](https://www.nick-bern.com/#projects)**, el sistema de gestión y puntuación que desarrollé y que está en producción en una bolera (cliente real).

🔗 **Demo en vivo:** https://bowlingdemo.nick-bern.com

> Esta **no** es la versión de producción. Producción tiene login, autorización de dispositivos, caja diaria, reportes por correo y panel de administración, y su código es privado (cliente). Esta demo deja solo la pantalla de juego, sin login ni backend, para que cualquiera pueda probarla.

## Qué puedes probar

- Registrar jugadores y anotar sus lanzamientos frame a frame.
- Puntuación de boliche con strikes, spares y bonificaciones del frame 10.
- Partidas por tiempo (30 o 60 minutos) con cuenta regresiva, avisos y cierre suave: al llegar a cero se termina la ronda en curso antes de finalizar.
- Partidas encadenadas: al terminar el frame 10 empieza otra partida mientras quede tiempo.
- Pantalla final con ganadores.
- Extender tiempo o cancelar una partida, acciones protegidas con contraseña. En la demo la contraseña es **`demo1234`**.

Todo corre en el navegador: no hay servidor ni base de datos.

## Stack

Angular 20 (componentes standalone) · TypeScript · Tailwind CSS 4 · DaisyUI

## Ejecutar en local

```bash
npm install
npm start        # http://localhost:4200
npm run build    # → dist/bolera/browser/
```

## Autor

Nicolás Bernal · [nick-bern.com](https://www.nick-bern.com) · [GitHub](https://github.com/DevNico2905)
