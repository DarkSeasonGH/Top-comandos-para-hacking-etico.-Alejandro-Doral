# Top-comandos-para-hacking-etico.-Alejandro-Doral

Top 25 comandos para hacking etico:

1.macchanger
con macchanger puedes cambiar la direccion mac temporalmente de tu dispositivo.
macchanger -r wlan1

2.proxychains
proxychains sirve para hacer una cadena de proxys por la que la informacion pasa y hacerlo mas seguro la conexion
proxychains nmap 74.124.12.12 -v -T4


3.traceroute
traceroute es un diagnostico de red y sirve para visualizar todos los paquetes que circulan a una web.
traceroute google.com

4.whatweb
whatweb nos da informacion de la web que le indiquemos, sobre todo de como se creo la web y lenguaje de programacion
whatweb hola.com

5.whois
whois es como whatweb pero para obtner informacion de dominios y bases de datos
whois hola.com

6.nmap
nmap es una herramienta para escanear puertos de una red
nmap kali.org --script vuln

7.dirb
dirb es una herramienta para encontrar directorios y archivos ocultos de paginas web, para usar esta herramienta necesitamos wordlist
y las wordlist las podemos encontrar en /usr/share/dirb/wordlists/
dirb http://www.sitio.com ejemplowordlist

8.nikto
nikto es una herramienta para encontrar vulnerabilidades de un sistema del host que le indiquemos

9.SQLiv
SQLiv es una herramienta para encontrar vulnerabilidades de inyeccion SQL a paginas web
sqliv -t hola.com
