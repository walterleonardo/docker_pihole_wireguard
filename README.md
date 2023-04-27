# Docker install 

sudo apt update
sudo apt upgrade -y
sudo apt install docker docker-compose


# docker_pihole_wireguard

Un reposito que incluye un docker-compose.yaml que puede ayudarte a crear una VPN en tu red privada con WIREGUARD, incluyendo un filtro de URLs muy efectivo con PIHOLE, todo corriendo con docker lo cual nos permite ejecutarlo en cualquier sistema operativo, windows, linux, apple, inclusive Raspberry PI, y como en mi caso en un simple OrangePiZero.

Solo hay que tener instalado docker en el equipo donde ejecutaremos esto.



La unica modificación del código, es copiar o cambiar el nombre al archivo .env_example a .env y configurar la clave de acceso a vuestra administración de PIHOLE.

# WireGuard
Esta aplicación es un servidor de VPN el cual hace una tarea muy sensilla, permitiendonos acceder a nuestra red privada desde cualquier punto del mundo, y con total tranquilidad ya que el trafico se encuentra completamente cifrado.
Funcionando perfectamente en cualquier sistema operativo, inclusive Android y IOs.


# PIHOLE
Un servidor DNS con infinidad de posibilidades de filtro de URL, o partes de nombres de dominio, por ejemplo palabras obsenas o referencias a actos ilegales. 
Recordemos que PIHOLE solo posee administración y por defecto no hay redirecciones, entonces para acceder a esta hay que poner en nuestro navegador http://ip_servidor_pihole/admin




