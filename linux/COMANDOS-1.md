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

- basicos
```
pwd
whoami
uname -s
ls -1 -lah
sort
wc [-clmw] [file ...] bites, lineas, caracter, letras
```
- procesos
```
ps fax
history
history | head -n2
history | tail -n2
top
htop
```
- mas usados
```
touch file{1..10}
cat
mkdir {bin,doc,Uebungen}
mkdir index{1..10}
cd - cd ../ cd / cd $HOME

echo "hola" > test.txt
echo "hola" >> test.txt

rm -rf
rmdir
mv [renombrar, mover]

grep
ifconfig | grep 'netmask' | grep 'broadcast'
```
- utiles
```
open *.doc
open frage*.txt
open http://www.apple.com/

rsync -av archivo directorio
cp -r -R -a[suma de varios]
cp *.txt

curl ifconfig.me
curl -LO https://github.com/mctechnology17/youtube_repo_mc_technology/blob/main/windows/WINDOWS.md
wget https://github.com/mctechnology17/youtube_repo_mc_technology/blob/main/windows/WINDOWS.md
```
- compresion
```
zip -9 datei.zip datei
unzip datei.zip
zipinfo

tar cvzf archivo.tar.gz archivo/*
tar -xvzf archivo.tar.gz
```

- copiar pegar
```
pwd | pbcopy
pbpaste

// MacOS
pbcopy
pbpaste

//Linux
sudo apt install xclip xsel
// agregar a bash o zsh
// option 1
alias pbcopy='xclip -selection clipboard'
alias pbpaste='xclip -selection clipboard -o'
// option 2
alias pbcopy='xsel --clipboard --input'
alias pbpaste='xsel --clipboard --output'

// Windows
clip

Ejemplo:
pwd | cpy
git branch | cpy
```
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
