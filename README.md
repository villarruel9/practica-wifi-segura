# practica-wifi-segura

## PARTE 1: Ingresamos en la página http://neverssl.com y abrimos las herramientas de desarrollador y observamos:

<img width="1590" height="657" alt="1" src="https://github.com/user-attachments/assets/69ddb8c1-002f-459f-9b52-43bc617ff455" />


### URL SOLICITADA :
<img width="352" height="36" alt="2" src="https://github.com/user-attachments/assets/3d6de15b-3f43-4123-b3a7-b80763773aad" />


### MÉTODO HTTP:
<img width="232" height="23" alt="3" src="https://github.com/user-attachments/assets/82024f4b-eb8d-439d-a634-c393d0377464" />


### HOST:
<img width="336" height="42" alt="4" src="https://github.com/user-attachments/assets/8053f2e7-fc3c-4111-8eaa-37e6c41cf70e" />


### PROTOCOLO UTILIZADO: HTTP
### HEADERS ENVIADOS:

<img width="345" height="486" alt="5" src="https://github.com/user-attachments/assets/c4bc39f6-96d5-48b5-b410-a8e93c7fe8bb" />


## PARTE 2: Análisis
## ¿Que protocolo utiliza el sitio? 
Utiliza HTTP

## ¿Qué información puede observarse durante la solicitud?
Como vemos en las capturas podemos ver el Host, La url, el método GET, Los headers y el user agent:
<img width="349" height="116" alt="6" src="https://github.com/user-attachments/assets/d1dd4c83-077f-48e9-b084-d95b3abdaa68" />


## ¿Qué riesgos existen al navegar mediante HTTP desde una red Wi-Fi pública?
Al navegar mediante HTTP desde una red Wi-Fi pública, existen varios riesgos porque la información que se envía no está cifrada. Esto puede permitir que otras personas conectadas a la misma red intercepten datos, como contraseñas, mensajes o información personal. También existe el riesgo de conectarse a redes falsas creadas para robar información. Por eso, es más seguro utilizar sitios que tengan HTTPS y evitar ingresar datos sensibles cuando se está conectado a una red Wi-Fi pública.

## ¿Cómo cambiaría este escenario utilizando una VPN?
Si estamos usando una red pública y navegamos por HTTP, una VPN nos ayudaría a estar más protegidos porque:

**Cifrado:**

la VPN cifra la información que enviamos y recibimos, por lo que otras personas conectadas a la misma red no pueden ver fácilmente nuestros datos.

**Túnel seguro:**

la VPN crea una especie de túnel entre nuestro dispositivo y el servidor VPN. La información pasa por ese túnel de forma protegida.

**Protección del tráfico:**

aunque estemos usando HTTP, la información que viaja desde nuestro dispositivo hasta la VPN está protegida y es más difícil que alguien pueda interceptarla.

**Privacidad:** 

la VPN también oculta nuestra dirección IP real y hace que los sitios vean la IP del servidor VPN en lugar de la nuestra.

En conclusión, usar una VPN en una red pública hace que nuestra conexión sea más segura y privada, especialmente frente a otras personas que estén conectadas a la misma red.

## 3 REGLAS DE ORO

1- No ingresar datos sensibles: evitar poner contraseñas, datos bancarios, tarjetas, etc.

2- No conectarse a sitios HTTP para cosas importantes: preferir siempre HTTPS, que cifra la comunicación.

3- Usar una VPN: si tenés que usar una red pública, la VPN ayuda a proteger el tráfico y dificulta que otras personas de la misma red puedan interceptarlo.
