# FUNCIONAMIENTO DE WIREGUARD EN LINUX.

Para instalar e iniciar Wireguard en tú ordenador sigue los siguientes pasos:


1. Para instalarlo con el comando "`sudo apt-get install wireguard`"
<br>
<br>

2. Una vez instalado el Wireguard debes  mover el archivo de configuración descargado a la carpeta de Wireguard en la ruta ``/etc/wireguard``, se puede mover ejecutando el comando: `mv wg-client.conf /etc/wireguard/`
<br>
<br>

3. Ya con el archivo en la carpeta de wireguard debemos activarlos, para ello tenemos dos opciones:

    - Ejecutamdo el comando ``wg-quick up``
    - ``systemctl start wg-quick@wg-client ``
<br>
<br>

4. Y para activarlo con el arranque del sistema  debemos ejecutar el comando: ``systemctl enable wg-quick@wg-client ``

A continuación puedes ver un gif con el paso a paso de lo anteriorment explicado:


