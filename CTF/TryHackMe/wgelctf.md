# [Task 1] Wgel CTF 26/10/2019
Have fun with this easy box.
### Antes de nada scaneo
```
$ nmap -Pn -sT -p- -O -sC -sV -T5
```
<p>
Es scaner nos indica la existencia de dos puertos, 22 y 80. Abrimos navegador y nos vamos al servidor http. La conexión solo muestra la página de información de apache, pero si vemos el código fuente nos desvela la existencia del comentario:


### #1	User flag<p>
### Solución:
`codigo`
Answer format: ********************************


### #2	Root flag
 
Answer format: ********************************

