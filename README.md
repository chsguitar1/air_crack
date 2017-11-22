# air_crack
ifconfig // verificar placa de rede
airmon-ng start wlan0 // placa de rede wlan0 modo de escuta
airodump-ng mon0 --write nome_do_arquivo_de_captura
aircrack-ng nome_do_arquivo_de_captura.cap 
