# Sistema de control de versiones

## ¿Que es un sistema de control de versiones?

Un sistema de control de versiones nos ayuda a guardar el historial de cambios y crecimiento de los archivos de nuestro proyecto.

En realidad, los cambios y diferencias entre las versiones de nuestros proyectos pueden tener **similitudes**, algunas veces los cambios pueden ser solo una **palabra** o una parte específica de un archivo específico.

# Tipos de archivos y sus diferencias
*  **Archivos de texto (.txt)** : Son texto plano normal y sin nada especial. LO vemos sin importar de donde lo abramos, ya sea con un bloc de notas o con editores de texto avanzados(***Visial Studio***)
*   **Archivos en word(.docx)** : Podermos guardar imágenes y texto en diferentes tamañis, estilos o colores. Al abrirlo desde un editor de codigo podemos ver que es código binario, muy dificil de entender y muy diferente al texto que estamos acostumbrados. Esto es porque ***Word*** esta optimizado para entender este código especial y representarlo gráficamente.

#

# GIT (fedora 35)

Para su instalación se requiere de ciertos comandos a continuación:

```bash
sudo dnf update
sudo dnf upgrade
sudo dnf install git
git --version

```

![logo Git](https://git-scm.com/images/logo@2x.png)


Git es un software de control de versiones de código de forma distribuida que está optimizado para guardar todos estos cambios de forma **atómica e incremental** , es decir que aplica cambios sobre los últimos cambios, esto sobre los cambios anteriores y así hasta el inicio de nuestro proyecto.

# Algunos comandos básicos de la terminal Lunux basadas en Fedora

- `pwd` : Nos muestra la ruta de carpetas en la que nos encontramos en el momento.

- `cd` : nos permite navergar entre los directorios/carpetas.

- `cd /` : nos dirige al directorio **raiz**.

- `cd /carpeta/subcarpeta` : Navega a una ruta dentro de la carpeta en la cual estamos actualmente.

- `cd ..` : regresa una carpeta hacia atrás. si queres dirigirte al directorio en el que te encontras basta con solo un punto (`cd .`).

- `mkdir` : Nos permite crear carpetas (por ejemplo: `mkdir Carpeta-importante`).

- `touch` : crear archivos (`touch archivo.txt`)

- `rm` : Borra archivos o carpetas (`rm archivo.txt`)

- `cat`: ver el contendio de un archivo (`cat nombre-archivo.txt`)

- `ls` : nos permite ver los archivos de la carpeta donde estamos ahora mismo. Podemos usar uno o mas argumentos para ver más información sobre estos archivos (los argumentos pueden ser `--` + el nombre del argumento o `-` + una sola letra o shortcut por cada argumento).

- `ls -a` : Muestra todos los archivos, incluso los ocultos.

- `ls -l` : muestra los archivos de la carpeta enlistados. sin incluir los ocultos.

- `ls -la` : Muestra en lista todos los archivos, incluyendo los ocultos.

- `history` : Ver los últimos comandos que se ha ejecutado y un numero especial de asignacion que podemos repetir su ejecución con: `!(numero)` ejemplo (`!50`)

- `clear` : para limpiar pantalla o **Ctrl + L** .










