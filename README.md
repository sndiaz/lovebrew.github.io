## Bienvenido ♥

LÖVE Potion es un framework para desarrollo de juegos homebrew para Nintendo 3DS y Nintendo Switch.

Si eres nuevo y recién estás empezando con LÖVE y/o Lua, te recomiendo de corazón que, primero que nada, hagas click en el enlace "How to LÖVE" (contenido en inglés) en la barra lateral.

Una vez que entiendas cómo funciona LÖVE, échale un vistazo a la sección sobre [compatibilidad](es/compatibility) para ver las diferencias con LÖVE Potion. También puedes ver la referencia de la API actual en la barra lateral.

![](files/lovepotion.png)

## Hola mundo
Este es el código fuente completo para un "Hola mundo" en LÖVE Potion.

```lua
function love.draw()
    love.graphics.print('¡Hola mundo!', 200, 120)
end

-- we need to quit the app when a button is pressed
function love.gamepadpressed(joystick, button)
    love.event.quit()
end
```
