<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=180&text=DANIEL%20SASTRE&fontAlign=50&fontAlignY=38&fontSize=42&desc=DEV%20%7C%20LINUX%20%7C%20SYSTEMS%20%7C%20RASPBERRY%20PI&descAlign=50&descAlignY=60&animation=fadeIn&color=0:0d1117,50:0b3d2e,100:00ff88&fontColor=ffffff&descColor=8affc1"/>

```text
daniel@satoda:~$ whoami
Daniel Sastre

daniel@satoda:~$ cat focus.txt
Melososoft · Linux · Sistemas · Backend · Raspberry Pi · Automatización

daniel@satoda:~$ echo $LOCATION
Mallorca, España
```

### `> Construyendo cosas, rompiéndolas y entendiendo por qué funcionan.`

[![Melososoft](https://img.shields.io/badge/MELOSOSOFT-00ff88?style=for-the-badge\&logoColor=black)](https://melososoft.com)
[![GitHub](https://img.shields.io/badge/@Satodaplay-161b22?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Satodaplay)
![Mallorca](https://img.shields.io/badge/Mallorca-0d1117?style=for-the-badge\&logo=googlemaps\&logoColor=00ff88)

</div>

---

## `$ cat about_me.txt`

No me gusta quedarme únicamente en programar una parte de un proyecto.

Me gusta montar **el sistema entero**.

Una web que habla con un backend, el backend con un servidor, el servidor con una Raspberry Pi, todo conectado por VPN y automatizado para que funcione sin tener que estar pendiente constantemente.

Ahora mismo estoy centrado principalmente en **montar Melososoft**, crear nuestros propios productos y trabajar en proyectos reales.

```bash
#!/bin/bash

INTERESES=(
    "Linux"
    "Backend"
    "Redes"
    "Raspberry Pi"
    "Automatización"
    "Servidores"
    "Desarrollo web"
)

echo "No hace falta hardware enorme para hacer cosas interesantes."
```

---

# `~/melososoft`

## 🟢 Melososoft

Estoy montando **Melososoft** junto a mi socio.

Nuestra idea es bastante sencilla:

> Crear soluciones tecnológicas útiles sin complicarlas más de lo necesario.

Trabajamos y experimentamos con:

```text
├── Desarrollo web
├── Aplicaciones web
├── WordPress
├── Herramientas internas
├── Automatización
├── Linux
├── Servidores
├── Redes
├── Raspberry Pi
└── Productos propios
```

🌐 **[melososoft.com](https://melososoft.com)**

---

# `~/projects/meloscreen`

## 🖥️ MeloScreen

Uno de los proyectos en los que más estoy trabajando actualmente.

**MeloScreen** es nuestro sistema de cartelería digital basado principalmente en Raspberry Pi.

La idea es poder colocar un dispositivo pequeño detrás de una pantalla y que se encargue de gestionar y reproducir contenido de manera autónoma.

```text
                       ┌──────────────────┐
                       │   PANEL CENTRAL  │
                       └────────┬─────────┘
                                │
                         WireGuard / Red
                                │
              ┌─────────────────┼─────────────────┐
              │                 │                 │
              ▼                 ▼                 ▼
        ┌──────────┐      ┌──────────┐      ┌──────────┐
        │   Pi #1  │      │   Pi #2  │      │   Pi #N  │
        │  Linux   │      │  Linux   │      │  Linux   │
        └────┬─────┘      └────┬─────┘      └────┬─────┘
             │                 │                 │
             ▼                 ▼                 ▼
          Pantalla          Pantalla          Pantalla
```

### Algunas cosas que hace

```yaml
media:
  - imágenes
  - vídeos
  - gifs

system:
  cache_local: true
  fallback: true
  logs: true
  remote_control: true
  multi_device: true

network:
  vpn: WireGuard

hardware:
  platform: Raspberry Pi
```

Aquí estoy mezclando prácticamente todo lo que más me gusta:

**Linux + redes + hardware + automatización + desarrollo.**

---

# `~/stack`

<div align="center">

### `Languages / Development`

<img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,express,python,php,java,spring&theme=dark" />

### `Systems / Infrastructure`

<img src="https://skillicons.dev/icons?i=linux,ubuntu,bash,raspberrypi,docker,git,github,vscode&theme=dark" />

### `Databases`

<img src="https://skillicons.dev/icons?i=mysql,postgres&theme=dark" />

</div>

<br>

```text
WEB             HTML · CSS · JavaScript · React
BACKEND         Node.js · Express · Python · PHP · Java · Spring Boot
DATABASE        MySQL · MariaDB · PostgreSQL
SYSTEMS         Linux · Ubuntu · Windows Server
NETWORKING      WireGuard · MikroTik
HARDWARE        Raspberry Pi
CMS             WordPress · WooCommerce
TOOLS           Git · GitHub · VS Code · Maven · Bash
```

> No soy experto en cada tecnología de la lista. Son herramientas que he utilizado y con las que me sé manejar en distintos proyectos.

---

# `~/projects`

## 💬 Melo Support

Sistema que estamos desarrollando para gestionar el soporte de clientes de Melososoft.

```text
Melo Support
│
├── Tickets
├── Clientes
│   ├── Cuenta
│   ├── Servicios
│   └── Historial
│
├── Chat
├── Email
├── Panel administrador
└── Portal cliente
```

La idea es no depender de veinte herramientas diferentes para algo que podemos integrar directamente en nuestra propia plataforma.

---

## 🤖 Abyssmo

Framework básico desarrollado en **Python** para bots de Discord.

Incluye sistemas como:

```python
features = [
    "personajes",
    "combates",
    "intercambios",
    "matrimonios",
    "divorcios",
    "carruseles interactivos"
]
```

[![Repositorio](https://img.shields.io/badge/VER_REPOSITORIO-161b22?style=for-the-badge\&logo=github\&logoColor=00ff88)](https://github.com/Satodaplay/Abyssmo)

---

## 🐧 DownloadTool

Uno de mis proyectos antiguos pero que representa bastante bien una cosa que me gusta:

**automatizar tareas repetitivas.**

Es un script Bash para preparar rápidamente una instalación nueva de Ubuntu e instalar herramientas que utilizaba habitualmente.

```bash
sudo ./install.sh

[+] Actualizando sistema...
[+] Instalando Git...
[+] Instalando SSH...
[+] Instalando Python...
[+] Instalando herramientas...
[+] Sistema preparado.
```

[![Repositorio](https://img.shields.io/badge/VER_REPOSITORIO-161b22?style=for-the-badge\&logo=github\&logoColor=00ff88)](https://github.com/Satodaplay/DownloadTool)

---

# `~/philosophy`

```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   Una Raspberry Pi de 30€ bien utilizada puede hacer        │
│   bastante más de lo que parece.                            │
│                                                             │
│   Me interesan especialmente las soluciones donde           │
│   software + sistemas + redes + hardware trabajan juntos.   │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

Me atrae especialmente intentar hacer cosas útiles con **hardware modesto**.

No porque sea obligatorio usar una Raspberry Pi para todo, sino porque tener recursos limitados te obliga a pensar mejor cómo haces las cosas.

Intento evitar meter diez capas de software cuando una solución sencilla puede funcionar mejor.

---

# `~/systems`

Algunas de las cosas con las que he trabajado:

```ini
[linux]
Ubuntu = yes
Debian = yes
Bash = yes

[servers]
Windows_Server = yes
Ubuntu_Server = yes
VPS = yes

[network]
WireGuard = yes
MikroTik = yes
VPN = yes

[hardware]
Raspberry_Pi = yes

[storage]
NAS = yes

[virtualization]
VirtualBox = yes
WSL2 = yes
```

---

# `~/github --stats`

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=Satodaplay&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00ff88&icon_color=00ff88&text_color=c9d1d9" />

<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Satodaplay&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00ff88&text_color=c9d1d9" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Satodaplay&theme=github-dark-blue&hide_border=true&background=0D1117&ring=00FF88&fire=00FF88&currStreakLabel=00FF88" />

</div>

---

# `~/currently`

```bash
daniel@satoda:~$ ps aux | grep daniel

daniel   1337  building    Melososoft
daniel   1338  developing  MeloScreen
daniel   1339  learning    Backend
daniel   1340  managing    Linux servers
daniel   1341  testing     Raspberry Pi
daniel   1342  automating  Everything possible
```

### Ahora mismo estoy centrado en:

* 🏢 sacar adelante **Melososoft**
* 🖥️ seguir desarrollando **MeloScreen**
* 🐧 mejorar cada vez más con **Linux**
* 🌐 backend y arquitectura
* 🔌 redes y servidores
* 🍓 Raspberry Pi
* ⚙️ automatización
* 🧰 crear herramientas propias

---

# `~/background`

Mi base viene de **Sistemas Microinformáticos y Redes**, y después también he pasado por desarrollo web.

Con el tiempo he acabado tirando cada vez más hacia un punto intermedio entre las dos cosas:

```text
              DESARROLLO
                  ▲
                  │
                  │
     SISTEMAS ◄───┼───► REDES
                  │
                  │
                  ▼
              HARDWARE
```

Y ahora mismo mi foco principal está fuera de estudiar:

**montar la empresa, desarrollar productos y seguir aprendiendo haciendo cosas reales.**

---

# `~/contact`

<div align="center">

### ¿Quieres encontrarme?

[![Melososoft](https://img.shields.io/badge/MELOSOSOFT-00ff88?style=for-the-badge\&logoColor=000000)](https://melososoft.com)

[![GitHub](https://img.shields.io/badge/GITHUB-SATODAPLAY-161b22?style=for-the-badge\&logo=github\&logoColor=ffffff)](https://github.com/Satodaplay)

<br>

```text
daniel@satoda:~$ logout
Connection to github.com closed.
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:0d1117,50:0b3d2e,100:00ff88"/>

</div>
