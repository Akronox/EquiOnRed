# Herramienta echa en bash para identificar equipos activos conectados en una red

*Sustituir las 2 ip de dentro del comando por la del rooter elegido sin poner el ultimo o ultimos numeros acabandolo con un .  (ej-192.168.1.)(en mi caso es el 16 le dejo sin poner)

*Uso= Darle los permisos: chmod +x EquiOnRed.sh

*Ejecutar con tu ip del rooter: ./EquiOnRed.sh 192.168.1.16

El resultado arrojara los equipos conectados a tu red:
└──╼ #./EquiOnRed.sh 192.168.1.16
Host 192.168.1.132 - Activo
Host 192.168.1.144 - Activo
Host 192.168.1.130 - Activo
Host 192.168.1.151 - Activo
Host 192.168.1.135 - Activo
Host 192.168.1.128 - Activo
