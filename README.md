# comandosUnix
Comandos de soporte para unix. Solo Apuntes.
ps x ///  para ver todos los demonios programados.
ps aux /// para ver todo lo que esta corriendo incluido los demonios
ps -el // para otros propositos.
ls -a //

#Para apagar unix de forma segura

shutdown // cuidado que no corra sync y fsck . 

#--------------------------------------------
#Unix no tiene control de versiones
#GNU Emacs para hacer backups
#Si borras algo es para siempre,Solo se recupera atraves de backups.
#-------------------- Estructura
for x in `cat`
do
...handle $x
done
#--------------------haciendo loop con multiples variables.
for file in prog1 prog2 prog3
do
...process $file
done
