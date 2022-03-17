# LoRa
## _Análisis de documentación de módulos RAK3172 y RAK5146 de RAKwireless_
#### INtroducción 
La compañia RAKwireless, proveedor líder de soluciones de IoT, que fabrica y ofrece productos de Internet de las cosas (IoT), es considerada para la migración de la tecnología de comunicación de Xbee a LoRa en BlueSensor. Se considera los módulos RAK3172 y RAK5146 para este cambio, en este presente informe se resume los aspectos relevantes de este cambio considerando como fundamental motivo , evitar el desbordamiento o pérdida de datos en la topología de red malla.
#### RAK3172
[![3172.png](https://i.postimg.cc/br4W6Bhq/3172.png)](https://postimg.cc/GTJXtztf)

#### Descripción del producto
RAK3172 es un módulo transceptor de largo alcance y baja potencia que se basa en el chip STM32WLE5CC. Proporciona una solución fácil de usar, de tamaño pequeño y de bajo consumo para aplicaciones de datos inalámbricos de largo alcance. Este módulo cumple con especificaciones de clase A, B y C de LoRaWAN 1.0.3. Se puede conectar fácilmente a diferentes plataformas de servidor LoRaWAN como TheThingsNetwork (TTN), Chirpstack, Actility, etc. También es compatible con la comunicación LoRa Point-to-Point (P2P) modo que lo ayuda a implementar rápidamente su propia red LoRa personalizada de largo alcance.
Puede configurar el modo y el funcionamiento del módulo mediante comandos AT a través de una interfaz UART. RAK3172 también ofrece características de baja potencia que son muy adecuadas para aplicaciones alimentadas por batería.

Las tres categorías de dispositivos LoRaWAN se definen como:
- dispositivos finales bidireccionales (Clase A)
- dispositivos finales bidireccionales con ranuras de recepción programadas (Clase B)
- dispositivos finales bidireccionales con ranuras de recepción máximas (Clase C)


Cada uno de los cuales permite disminución de la latencia a costa de mayores requisitos de energía.
> La latencia, en términos informáticos la podemos definir como el tiempo que transcurre entre una orden y la respuesta que se produce a esa orden >concreta. Entonces, como podremos suponer la latencia se mide en unidad de tiempo, concretamente en milisegundos o microsegundos, ya que el segundo sería >una medida demasiado alta como para aplicarla a sistemas microinformáticos. Con la latencia estamos midiendo el tiempo que estamos esperando desde que >damos una orden hasta que recibimos la respuesta que esperamos.


