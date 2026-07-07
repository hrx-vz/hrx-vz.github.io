# ⬢ CeroCloud Portal Web
[![🔒 Privacidad Total](https://img.shields.io/badge/Proyecto-Privacidad%20Total-00ffff?style=for-the-badge)](https://github.com/hrx-vz/cerocloud)
![🟢 Sistema Funcionando](https://img.shields.io/badge/Fase-Sistema%20Funcionando-00ff00?style=for-the-badge)

> **Privacidad Absoluta.** Transforma tus propios dispositivos (PC, Laptop, Tablet o Celular Android) en búnkers reales de almacenamiento privado, seguro y 100% bajo tu control, sin depender jamás de nubes de terceros.

---

## 🌎 El Portal Visual del Ecosistema

Este repositorio alberga la interfaz gráfica y el cliente de acceso web oficial (`hrx-vz.github.io`). Está diseñado exclusivamente para operar como una **PWA (Progressive Web App)** ultra ligera que interactúa directamente con tu infraestructura privada.

⚠️ **INFORMACIÓN CRUCIAL:** Este portal web por sí solo no almacena datos ni realiza tareas de servidor. Para que tu nube funcione, necesitas desplegar el backend en tu hardware.

🚀 **[IR AL REPOSITORIO CENTRAL (CEROCLOUD CORE) ➔](https://github.com/hrx-vz/cerocloud)**  
*Allí encontrarás el script de instalación (`install.sh`), el núcleo (`server.js`) y las instrucciones detalladas de despliegue.*

---

## ⚡ Características Clave

*   **🛡️ Soberanía Total:** No es una cuenta en la nube ajena; tú eres el dueño físico, legal y técnico de los discos donde viaja tu información.
*   **🌐 Acceso Híbrido Inteligente:** Conexión local en casa a la velocidad máxima de tu router (sin consumir internet) o enlace global cifrado mediante túneles para acceder desde cualquier parte del mundo.
*   **📱 Cliente PWA (MiNube):** Se instala en segundos en tu pantalla de inicio desde el navegador, comportándose como una aplicación nativa, fluida y sin desbordamientos de diseño.
*   **🔒 Protocolo de Invisibilidad:** Seguridad perimetral silenciosa. Si alguien intenta ingresar con credenciales erróneas, el sistema no muestra alertas; genera un espacio aislado y vacío para despistar intrusos.

---

## 📦 Arquitectura del Ecosistema

Para entender cómo se conectan tus repositorios, mira este esquema de comunicación:

```text
  📱 DISPOSITIVO (Cliente)          🏠 TU HARDWARE (Servidor Local)
┌──────────────────────────┐       ┌───────────────────────────┐
│  PWA MiNube (Este Repo)  │ ───>  │  Core CeroCloud (Backend) │
│  Interface Gráfica Web   │ <───  │  Node.js + server.js      │
└──────────────────────────┘       └───────────────────────────┘
             │                                   │
             └───────── Túnel Cloudflare ────────┘
                    (Acceso Seguro Global)

```
## 📥 Guía Rápida de Despliegue

¡Todo listo para tomar el control! Solo necesitas seguir estos dos pasos clave para sincronizar tu sistema:

### ⚙️ PASO 1: Iniciar tu Servidor (Backend)
No necesitas configuraciones complejas. Visita nuestro repositorio central, donde encontrarás el **comando único de instalación** diseñado tanto para Android (Termux) como para sistemas Linux (Ubuntu/Debian). Solo copia, pega y ejecuta.

🚀 **[OBTENER COMANDO DE INSTALACIÓN AQUÍ ➔](https://github.com/hrx-vz/cerocloud)**

---

### 📱 PASO 2: Instalar la Interfaz Visual (Frontend)
Una vez que tu servidor esté activo, vincula tu interfaz de usuario:

1. **Entra al Portal:** Abre en tu móvil: [https://hrx-vz.github.io](https://hrx-vz.github.io)
2. **Instala la App:** Toca los 3 puntos (⋮) de tu navegador y selecciona **"Instalar aplicación o agregar a pantalla"**.
3. **Sincroniza:** Abre **MiNube** desde tu cajón de aplicaciones, toca **"¿Primera vez?"** y pega tu enlace de acceso, crea tu usuario y contraseña. ¡Eso es todo!

---

> 🪐 **Tu Nube, Tus Reglas.** Tecnología descentralizada para quienes buscan soberanía total sobre sus archivos. El control absoluto ha vuelto a tus manos.

## 🕹️ El Arcade Digital: Despliegues de Concienciación Táctica

Para entender el comportamiento de las redes, la evasión de sistemas y el monitoreo global, hemos diseñado una suite interactiva de simulación y entornos arcade directamente en la web. 

Baja hasta los paneles de control de abajo, elige tu entorno y experimenta el flujo del mundo digital en tiempo real.

<br />

<div align="center">

### ⚡ PROYECTO: NEXUS
**[ 🎮 JUGAR AHORA ](https://hrx-vz.github.io/games/nexus.html)**

*60 segundos. Cero margen de error.*
Un arcade de supervivencia crítica contra el reloj. Administra la temperatura de tu núcleo, despliega señuelos dinámicos para confundir a los rastreadores y recolectar refrigerantes antes de que tu sistema sufra un sobrecalentamiento crítico. Incluye síntesis de audio integrada nativa.
</div>

---

<div align="center">

### 📡 OPERACIÓN FANTASMA
**[ 🎮 JUGAR AHORA ](https://hrx-vz.github.io/games/fantasma.html)**

*El arte de la invisibilidad digital.*
Un simulador táctico de sigilo y evasión en dos dimensiones. Tu misión es extraer paquetes de datos críticos esquivando ondas expansivas de radar en tiempo real. Sincroniza tu módulo *Ghost* para desmaterializarte justo en el instante del impacto. Si tu barra de exposición llega al 100%, la operación ha fallado.
</div>

---

<div align="center">

### 🗺️ NET-HUNTER
**[ 🎮 JUGAR AHORA ](https://hrx-vz.github.io/games/nethunter.html)**

*Estrategia global a gran escala.*
Elige tu rol: Infiltrado, Destructor o Centinela. Un RPG táctico interactivo que te pone al mando de una terminal de asalto. Coordina ataques a nodos estratégicos en un mapa esférico simulado, gestiona flujos de energía e invoca inteligencia aliada autónoma mediante comandos S.O.S de emergencia.
</div>

---

<div align="center">

### 💻 CYBERMUNDO: SIMULADOR DIGITAL
**[ 👁️ ENTRAR AL SIMULADOR ](https://hrx-vz.github.io/games/cybermundo.html)**

*No es un juego. Es una ventana a la matriz.*
Un espacio puramente contemplativo e inmersivo diseñado para visualizar la densidad de la red. Monitorea flujos de datos globales, analiza la telemetría de coordenadas tridimensionales flotantes y observa cómo interactúan los sistemas automatizados en un entorno abstracto de partículas. Ideal como panel de monitoreo estético ambiental.
</div>

---

## 🛠️ Especificaciones de Arquitectura

*   **Núcleo:** Despliegue optimizado de bajo consumo para nodos distribuidos.
*   **Seguridad:** Cifrado de punto a punto y políticas estrictas de cero logs de terceros.
*   **Diseño Visual:** Interfases híbridas optimizadas para terminales virtuales y navegadores móviles.
---

## 🛰️ Desafío Táctico: Hackeo de Objetivos Reales (Net-Hunter)

En el mapa global 3D de **Net-Hunter**, no estás atacando al azar. El sistema despliega las ubicaciones de agencias de inteligencia reales en tiempo real. Si quieres interceptar sus servidores, búscalos usando el radar visual en base a su latitud ($X$) y longitud ($Y$):

*   **El Pentágono (EE. UU.):** Ubicado en el eje de coordenadas aproximado ($X: 38.87$, $Y: -77.05$). Un nodo de alta seguridad informática.
*   **El Kremlin (Rusia):** Ubicado en el eje de coordenadas aproximado ($X: 55.75$, $Y: 37.61$). Tráfico de datos encriptado y hostil.

**¿Cómo seguir la ruta de ataque?:** 
Mueve el joystick virtual para rotar el globo terráqueo e interceptar las coordenadas en pantalla. Cuando tu laptop (`💻`) se alinee visualmente en la misma trayectoria $X$ / $Y$ del objetivo, el enlace de red se establecerá automáticamente para iniciar la infiltración.

Si te ves superado por los cortafuegos enemigos, recuerda activar tu comando **S.O.S** para desplegar compañeros autónomos en esa posición.

---

## 📞 CONTACTO

¿necesitas soporte de despliegue para tu infraestructura privada o quieres contactar directamente al desarrollador de este ecosistema? Establece una sesión directa:

*   **Telegram:** [@HRI_VL](https://t.me/HRI_VL) 🌐

