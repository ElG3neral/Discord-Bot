# Discord-Bot
Es un bot de discord con un sistema de reproducción de música, comandos de moderación y comandos extras.

# Por qué hice este proyecto?
Lo hice porque quería mejorar mis habilidades en programación así como también ayudar a personas que no tienen conocimientos en programación a que puedan usar estos codigos en caso de que deseen un bot de discord propio.

# Tutorial de como usar los comandos:
## 🔵 Comandos de moderación:
Para banear a un usuario permanentemente usas: !ban (@user) (reason)

Para solo banearlo temporalmente usas esto: !tempban (@user) (duration) (reason)

Para desbanear solo se usa: !unban (@user) o (id)

Para solo sacarlo del servidor (Esto permite que se pueda unir nuevamente al servidor.): !kick (@user) (reason)

Para mutear se usa el: !mute (@user) (reason) > Es necesario tener el rol 'Muted' creado sin los permisos para chatear o interactuar en canales de voz. Puedes modificar el nombre del rol mediante el codigo fuente <

Para mutear temporalmente: !tempmute (@user) (duration) (reason)

Para desmutear: !unmute (@user) (reason)

## 🔴 Comandos para reproducir canciones desde youtube:
Para reproducir y agregar canciones a la cola se utiliza: !play (Artista y cancion) o (link del video)

Para parar la cancion: !stop y eliges el cotejo, en caso de que no quieras le das a la X

Para pausar: !pause

Para resumir: !resume

Para saltar la canción: !skip

Para borrar la cola o playlist, puedes usar: !clearqueue

Para desconectar al bot: !leave

## 🟢 Comandos extras:
Para saber la latencia del bot, utilizas: !ping

Para saber la cantidad total de miembros excluyendo bots: !miembros

Para borrar todo el chat, utilizas: !clearall > Tienes que establecer el limite de mensajes que quieres que borre en el codigo fuente <

Para borrar una cantidad especifica de mensajes: !clear (cantidad)

### 🎁 Regalo:

    if ctx.message.channel.name != 'comandos':
            await ctx.send("No puedes usar comandos en este canal. Por favor utiliza el canal #comandos.")
            return
        
Esto sirve para hacer que un comando solo funcione en un canal especifico. 

Ejemplo: En las funciones que comienzan en 'async def nombre:' abajo de eso pegas lo que te puse y donde dice 'comandos' lo cambias por el canal donde quieres que se utilice el comando. 

