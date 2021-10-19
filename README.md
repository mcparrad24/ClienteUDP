# ClienteUDP

Instrucciones de uso:

Para el desarrollo de esta aplicación se utilizó un socket TCP y un socket UDP. 

Para utilizar el cliente, asegúrese de que la aplicación del servidor este corriendo primero y que la IP del servidor (ipServ) y el puerto sean los indicados para el socket TCP (que se encuentra en la función createSocket, dentro de socket.create_connection). Si por alguna razón, utilizando 'localhost' no funciona, modifique la IP del cliente (ipCli) por la IP de su máquina o '0.0.0.0'. No modifique el puerto que será utilizado para el socket UDP (puerto2). 

Una vez ejecute la aplicación, por consola llegará un mensaje preguntando cuantos clientes recibirán el archivo. Ingrese el mismo número que le envío por consola previamente al servidor cuando hizo la misma pregunta. En el momento en el que envíe el número, la aplicación empezará a recibir el archivo para cada cliente.
