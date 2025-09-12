<h1 align="center">Taller 1</h1>

<h2>Instalación y configuración inicial</h2>
<ul>
  <li>La Raspberry Pi 3 requiere una tarjeta microSD (32 GB recomendada), fuente de alimentación microUSB, salida HDMI, teclado y mouse.</li>
  <li>La memoria se prepara con <a href="https://www.raspberrypi.com/software/">Raspberry Pi Imager</a>, seleccionando:
    <ul>
      <li>Dispositivo: Raspberry Pi 3</li>
      <li>Sistema operativo: Raspberry Pi OS 32-bit</li>
      <li>Almacenamiento: tarjeta SD</li>
    </ul>
  </li>
  <li>Durante la instalación se recomienda activar <strong>SSH</strong> para control remoto.</li>
  <li>Tras la primera inicialización, el proceso puede tardar y mostrar mensajes en pantalla.</li>
</ul>

<h2>Comandos básicos</h2>
<ul>
  <li><code>sudo apt full-upgrade -y</code>: actualizar el sistema operativo.</li>
  <li><code>sudo apt install &lt;paquete&gt;</code>: instalar programas.</li>
  <li><code>sudo systemctl status cron</code>: verificar el servicio <em>cron</em>.</li>
  <li><code>crontab -e</code>: programar tareas automáticas.</li>
  <li><code>crontab -l</code>: listar tareas programadas.</li>
  <li><code>chmod +x archivo.sh</code>: dar permisos de ejecución.</li>
  <li><code>pwd</code>: mostrar directorio actual.</li>
  <li><code>nano archivo.sh</code>: crear o editar un script.</li>
  <li><code>bash archivo.sh</code>: ejecutar un script.</li>
  <li><code>cat archivo.sh</code>: mostrar contenido de un archivo.</li>
</ul>

<h2>Automatización con cron</h2>
<ul>
  <li>Se pueden crear rutinas en archivos <code>.sh</code> y programarlas con <code>crontab</code>.</li>
  <li>Es importante dar permisos de ejecución con <code>chmod +x</code>.</li>
  <li>Ejemplo: ejecutar un script todos los días de forma automática.</li>
</ul>

<h2>Exploración de red</h2>
<ul>
  <li><code>ifconfig</code>: visualizar la dirección IP y máscara de red.</li>
  <li><code>nmap</code>: escanear dispositivos en la red local (requiere instalación, aunque en este taller presentó errores).</li>
</ul>

<h2>Conclusiones</h2>
<p>El taller mostró los pasos esenciales para:</p>
<ul>
  <li>Instalar y configurar Raspberry Pi 3 con Raspberry Pi OS.</li>
  <li>Usar <code>cron</code> para la automatización de tareas mediante scripts.</li>
  <li>Explorar la red local obteniendo la IP y detectando vecinos con <code>nmap</code>.</li>
</ul>
