<h1 align="center">AI FURINA</h1>

### *`❕️ Información importante`*
Este proyecto **no está afiliado de ninguna manera** con `WhatsApp`, `Inc. WhatsApp` es una marca registrada de `WhatsApp LLC`, y este bot es un **desarrollo independiente** que **no tiene ninguna relación oficial con la compañía**.

<details>
<summary><b> Descripción</b></summary>

Ai Furina es una bot de WhatsApp multifuncional basado en `baileys`. Esta bot ofrece una variedad de características para mejorar tu experiencia en WhatsApp.

#### Características
Configuración avanzada de grupos 
Bienvenidas personalizadas  
Herramientas útiles  
Juegos RPG (Gacha y Economía)  
Funciones de Inteligencia Artificial  
Descargas y búsquedas multi-plataforma  
Sub-Bots (JadiBot)  
Extensiones adicionales
</details>

---

### **Click en la imagen para descargar termux**
<a
href="https://www.mediafire.com/file/wkinzgpb0tdx5qh/com.termux_1022.apk/file"><img src="https://qu.ax/finc.jpg" height="125px"></a> 

### **➮ Instalación por termux**
<details>
<summary><b>Instalación Manual</b></summary>

> *Comandos para instalar de forma manual*
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install -y git nodejs ffmpeg imagemagick yarn
```
```bash
git clone https://github.com/Lc-Novikov/AI-Furina && cd AI-Furina
```
```bash
yarn install
```
```bash
npm install
```
```bash
npm start
```
> *Si aparece **(Y/I/N/O/D/Z) [default=N] ?** use la letra **"y"** y luego **"ENTER"** para continuar con la instalación.*
</details>

<details>
  <summary><b>Comandos para mantener más tiempo activo el Bot</b></summary>

> *Ejecutar estos comandos dentro de la carpeta AI-Furina*
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 
#### Opciones Disponibles
> *Esto eliminará todo el historial que hayas establecido con PM2:*
```bash 
pm2 delete index
``` 
> *Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:*
```bash 
pm2 logs 
``` 
> *Si desea detener la ejecución de Termux use:*
```bash 
pm2 stop index
``` 
> *Si desea iniciar de nuevo la ejecución de Termux use:*
```bash 
pm2 start index
```
---- 
### En caso de detenerse
> _Si despues que ya instalastes el bot y termux te salta en blanco, se fue tu internet o reiniciaste tu celular, solo realizaras estos pasos:_
```bash
cd && cd AI-Furina && npm start
```
----
### Obtener nuevo código QR 
> *Detén el bot, haz click en el símbolo (ctrl) [default=z] usar la letra "z" + "ENTER" hasta que salga algo verdes similar a: `AI-Furina $`*
> **Escribe los siguientes comandos uno x uno :**
```bash 
cd && cd AI-Furina && rm -rf sessions/Principal && npm run qr
```
----
### Obtener nuevo código de teléfono 
```bash 
cd && cd AI-Furina && rm -rf sessions/Principal && npm run code
```
</details>

<details>
<summary><b>Actualizar AI-Furina</b></summary>

> **Utiliza esta opción únicamente si deseas actualizar a la última versión de AI-Furina. Hemos implementado un método ingenioso mediante comandos para realizar la actualización, pero ten en cuenta que al usarla se eliminarán todos los archivos de la versión actual y se reemplazarán con los de la nueva versión. Solo se conservará la base de datos, por lo que será necesario volver a vincular el Bot.**  

**Comandos para actualizar AI-Furina de forma automática**

```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget && wget -O - https://raw.githubusercontent.com/DevAlexJs/SakuraBot-MD/master/termux.sh | bash 
```
**✰ Volverte owner del Bot**

*Si después de instalar el bot e iniciar la sesión (deseas poner tu número es la lista de owner pon este comando:*

```bash
cd && cd AI-Furina && nano settings.js
```
#### Para que no pierda su progreso en Ai Furina, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> *Estos comandos solo funcionan para TERMUX, REPLIT, LINUX*
</details>

---

### **`PROPIETARIO`**
<a
href="https://github.com/Lc-Novikov"><img src="https://github.com/Lc-Novikov.png" width="130" height="130" alt="Xplorazzy-Tech"/></a>