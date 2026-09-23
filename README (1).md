# LabRed · Simulador de redes para el aula

Creado por **Juan Luis Torralbo Muñoz**.

Simulador de redes pensado para 1º de Bachillerato. Todo funciona en el navegador, en un único archivo `index.html`, sin servidor, sin instalar nada y sin conexión a Internet una vez cargado.

## Publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `labred`).
2. Sube `index.html` (y este README) a la raíz del repositorio.
3. En el repositorio: **Settings → Pages → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
4. En uno o dos minutos estará en `https://TU-USUARIO.github.io/labred/`.

También funciona abriendo `index.html` directamente con doble clic, o copiándolo a un pendrive.

## Qué se puede hacer

- Montar redes con PC, servidores, switches, hubs y routers, y conectarlos con cables.
- Configurar IP, máscara, puerta de enlace y DNS; avisos automáticos de errores típicos (IP repetida, puerta de enlace fuera de la red, dirección de red o broadcast asignada…).
- Consola en cada equipo: `ipconfig`, `ping`, `tracert`, `arp`, `nslookup`, `route print`, `curl`, y en routers `show ip route`.
- Protocolos simulados paso a paso: Ethernet, ARP, IPv4 con TTL, ICMP, DHCP (DISCOVER/OFFER/REQUEST/ACK), DNS, TCP (saludo en tres pasos) y HTTP.
- Routers con rutas conectadas y estáticas (incluida la ruta por defecto).
- Servidores con DHCP, DNS y web (página HTML editable) y un navegador en cada PC.
- Captura de tráfico tipo Wireshark: cada paquete con sus capas y una explicación en castellano.
- Calculadora IP con los bits de red y de equipo resaltados.
- Ejemplos con misiones y retos con fallos escondidos.
- Guardado automático, descarga/apertura en `.json` y **enlace para compartir** que contiene la red y el enunciado de la misión.

## Preparar un ejercicio

1. Monta la red (puedes dejar fallos a propósito).
2. Sin nada seleccionado, escribe el enunciado en el panel derecho («Enunciado de la misión»).
3. Pulsa **Compartir enlace** y pega ese enlace en Classroom, Moodle o donde prefieras.
