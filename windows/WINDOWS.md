[![MC Technology](../doc/mctechnology_extendido.GIF)](https://www.youtube.com/channel/UC_mYh5PYPHBJ5YYUj8AIkcw)
# youtube_repo_mc_technology

Redes | [Reddit](https://www.reddit.com/user/mctechnology17), [YouTube](https://www.youtube.com/channel/UC_mYh5PYPHBJ5YYUj8AIkcw?view_as=subscriber), [Facebook](https://m.facebook.com/mctechnology17/), [Twitter](https://twitter.com/mctechnology17), [Instagram](https://www.instagram.com/mctechnology17/), [Twitch](https://www.twitch.tv/mctechnology17), [TikTok](https://www.tiktok.com/@mctechnology17), [Telegram](https://t.me/mctechnology)
------|-----
Projectos | [Jailbreak Repo](https://mctechnology17.github.io), [vim-tools](https://github.com/mctechnology17/vim-tools), [WEB](https://mctechnology17.com), [UI Glitch](https://repo.packix.com/package/com.mctechnology.uiglitch/)

- [Introducción](#Introducción)
- [Personalisar Windows](#Pasos)
- [Suscribirse es agradecer :D](#Suscríbete)
- [Ultimo video subido a YouTube](#Video)
- [Licencia](#Licencia)

----

## Introducción
- Respositorio para mi canal de [YouTube](https://www.youtube.com/channel/UC_mYh5PYPHBJ5YYUj8AIkcw?view_as=subscriber)

## Pasos
Aqui encuentras una estructura de la repo de los archivos subidos.
- Configura la WSL para Windows:
	- Primero ejecuta la PowerShell como administrador y luego copia este comando.
	- `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`
	- Una realizado el proceso recuerda reiniciar la PC o Laptop.
	- A continuación, descarga la Distro de Linux de tu elección de la tienda de Microsoft. Yo en el video lo muestro con Ubuntu 20.04 LTS. Los pasos detallados los encuentras [aquí](https://docs.microsoft.com/en-us/windows/wsl/install-win10) por Microsoft.
	- Ahora instala Windows Terminal Preview desde la tienda de Microsoft.
	- Puedes instalar tambien temas para la terminal desde [aquí](https://windowsterminalthemes.dev/). Este paso es opcional.
	- Ahora inicia tu Windows Terminal Preview ya con Ubuntu.
	- Instalar zsh con el siguiente comando:
		- `sudo apt install zsh`
		- Una vez instalado zsh, aplica este comando para que sea tu consla predeterminada:
			- `chsh -s /bin/zsh`
	- Ahora es el turno de oh-my-zsh:
		- `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
	- Ahora le toca a powerline10k:
		- `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`
		- Despues de la instalación exitosa ejecuta este comando:
			- `p10k configure`
			- Recuerda qu puedes visitar el repositorio para mas detalles [aquí](https://github.com/romkatv/powerlevel10k#oh-my-zsh).
			- [Aquí](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k) encuentras las fonts recomendas por el desarrollador. Para instalarlas en windows sigue estos pasos:
				- Descargar los archivo .ttf
				- Click derecho
				- Instalar para todos
				- Recuerda instalar los 4 Archivos
## Suscríbete
- Recuerda que si te sirvio puedes hacermelo saber, suscribiendote a mi [canal](https://www.youtube.com/watch?v=gKkFuM8Ky1I&t=88s), dandole me gusta o compartiendo el video.
- Tambien puedes apoyarme directamente por [aquí](https://www.paypal.me/mctechnology17)
- [![MC Technology](../doc/paypal_qr.png)](https://www.paypal.me/mctechnology17)


## Video
- Este es mi Video más reciente en YouTube
[![Mira el video aquí](https://i.ytimg.com/vi/gKkFuM8Ky1I/maxresdefault.jpg)](https://www.youtube.com/watch?v=gKkFuM8Ky1I&t=88s)

- Este es mi Video más visto en YouTube
[![Mira el video aquí](https://i.ytimg.com/vi/KQ7OgQYRgZc/maxresdefault.jpg)](https://www.youtube.com/watch?v=KQ7OgQYRgZc)

## Licencia
[Licencia](./LICENSE)
