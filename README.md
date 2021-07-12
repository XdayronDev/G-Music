[![Discord](https://img.shields.io/discord/658113349384667198.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/e9E8zBYXJf)
![logo](https://i.imgur.com/73OfCtg.png)

# 🤖 G-Music (Bot de Musica Discord)
> G-Music es un bot de musica construido con discord.js y usa Comandos  Handler para [Guia de Discord.js](https://discordjs.guide)

## Requerimientos

1. Discord Bot Token **[Guia](https://portalmybot.com/guia/mybot/cuenta-discord)**
2. YouTube Data API v3 Key **[Guia](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Opcional)** Soundcloud Client ID **[Guia](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v14.0.0 o mas reciente

## 🚀 Para empezar



```
git clone https://github.com/XdayronDev/G-music.git
cd G-Music Public
npm install
```

Una vez finalizada la instalación, puedes usar `node index.js` para iniciar el bot.

## ⚙️ Configuracion

Copia y renombra `config.json.ejemplo` a `config.json` y complete los valores:

⚠️ ** Nota: Nunca confíe ni comparta públicamente sus claves de token o API ** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "!",
  "PRUNING": false,
  "LOCALE": "es",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```

Idiomas que encontraras:
- Ingles (en)
- Arabica (ar)
- Portugués brasileño (pt_br)
- Holandes (nl)
- Frances(fr)
- Aleman (de)
- Italiano (it)
- Coreano (ko)
- Polaco (pl)
- Ruso (ru)
- Chino Simplificado (zh_cn)
- Español (es)
- Sueco(sv)
- Chino Tradicional (zh_tw)
- Turco (tr)
- Vietnamita (vi)


## 📝 Funciones y Comandos

> Nota: el prefix predeterminado es '!'

* 🎶 Reproducir música de YouTube a través de URL

`!play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎 Reproducir música de YouTube a través de una consulta de búsqueda

`!play under the bridge red hot chili peppers`

* 🎶 Reproducir música de Soundcloud a través de URL

`!play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎 Busca y selecciona música para reproducir

`!search Pearl Jam`

Responda con el número de la canción o los números separados por comas que desea reproducir

Ejemplos: `1` o` 1,2,3`

* 📃 Reproducir listas de reproducción de youtube a través de URL

`!playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Reproducir listas de reproducción de youtube a través de una consulta de búsqueda

`!playlist linkin park meteora`
* Now Playing (!np)
* Cola de reproduccion (!queue, !q)
* Bucle / Repetir (!loop)
* Shuffle (!shuffle)
* Control de Volumen(!volume, !v)
* Lyrics (!lyrics, !ly)
* Pausar (!pause)
* Resumir (!resume, !r)
* Saltar (!skip, !s)
* Saltar a la canción n. # en la cola (!skipto, !st)
* Mover una canción en la cola (!move, !mv)
* Eliminar la canción n.# de la cola (!remove, !rm)
*Reproducir un clip de mp3 (!clip song.mp3) (poner el archivo en la carpeta de sonidos)
* Lista de todos los clips (!clips)
* Mostrar api ping (!ping)
* Mostrar el tiempo de actividad del bot (!uptime)
* Alternar la eliminación de mensajes de bot (!pruning)
* Localización en mas de 6 idiomas
* Ayuda (!help, !h)
* Creado con comandos handler, Gracias a [Guia de Discord.js](https://portalmybot.com/guia/mybot/inicio)
* Controles de medios a través de reacciones

![Reacciones](https://i.imgur.com/ptTCcS4.png)

