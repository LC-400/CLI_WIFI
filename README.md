Tested successfully on Raspberry PI Zero.

Connects, disconnects and reconnects onto a WIFI-network with the CLI. 
Suitable for headless setups or NON-GUI environments.

Config-file: /etc/wpa_supplicant/wpa_supplicant.conf

Raspi_config allows setting ssid and unencrypted passphrase for a network.

Encrypt the passhprase with: wpa_passphrase ssid passphrase.
Delete the unencrypted passphrase from the config-file.

Files:
wpa_initial_connect 
wpa_reconnect
wpa_disconnect
