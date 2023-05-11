# FUNCIONAMIENTO DE WIREGUARD EN LINUX.

Para instalar e iniciar Wireguard en tú ordenador sigue los siguientes pasos:
<br>

1. Para instalarlo con el comando: "`sudo apt-get install wireguard`"

<br>

2. Una vez instalado el Wireguard debes  mover el archivo de configuración descargado a la carpeta de Wireguard en la ruta ``/etc/wireguard``, se puede mover ejecutando el comando: `mv wg-client.conf /etc/wireguard/`

<br>

3. Ya con el archivo en la carpeta de wireguard debemos activarlos, para ello tenemos dos opciones:

    - Ejecutando el comando: ``wg-quick up`` o ``systemctl start wg-quick@wg-client ``, ambos tienen la misma finalidad.
<br>

4. Para activarlo con el arranque del sistema debemos ejecutar el comando: ``systemctl enable wg-quick@wg-client ``, de esta manera aplicaremos la configuración del archivo descargado.

<br>
A continuación puedes ver un gif con el paso a paso de lo anteriorment explicado:


