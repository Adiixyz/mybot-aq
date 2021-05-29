<p align="center">
<img src="https://media.giphy.com/media/4dM1U76aAQ3dbE6bc3/giphy.gif" alt="GIF" width="128" height="128"/>
</p>
<p align="center">
<a href="#"><img title="Adiixyz" 
src="https://img.shields.io/badge/Adiixyz-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>

# Installation (Termux)
```bash
> pkg install git -y
> pkg install nodejs -y
> pkg install ffmpeg -y
> pkg install imagemagick -y
> git clone https://github.com/Adiixyz/mybot-aq
> ls
> cd mybot-aq
> ls
> npm install
> node index.js
(scan qr)
```

# Installation (Windows)
* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFMPEG [`Click Here`](https://ffmpeg.org/download.html) (don't forget to path)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php) (if nulis want work,  checklist columns 1,2,3,5,6)

```bash
> open cmd/git bash/powershell
> git clone https://github.com/Adiixyz/mybot-aq
> cd mybot-aq
> npm install
> node index.js
(scan qr)
```

## Arguments `node . [--options] [<session name>]`

### `--self`

Activate self mode (Ignores other)

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--big-qr`

If small qr unicode doesn't support

### `--restrict`

Enables restricted plugins (which can lead your number to be **banned** if used too often)

* Group Administration `add, kick`

### `--img`

Enable image inspector through terminal

### `--nyimak`

No bot, just print received messages and add users to database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```


# Thanks to
* Adiixyz [`Adiixyz`](https://github.com/Adiixyz)
* Nurutomo [`Nurutomo`](https://github.com/Nurutomo)
