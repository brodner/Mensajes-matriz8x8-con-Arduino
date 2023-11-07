# Proyecto de Arduino - Mensajes en Matriz de LEDs

Este repositorio contiene el código y los recursos para un proyecto de Arduino que muestra mensajes en una matriz de LEDs. El proyecto utiliza la biblioteca MD_MAX72xx para controlar la matriz y permite mostrar mensajes personalizados en la pantalla.

## Contenido

- [Descripción del proyecto](#descripción-del-proyecto)
- [Materiales necesarios](#materiales-necesarios)
- [Configuración](#configuración)
- [Instrucciones de uso](#instrucciones-de-uso)
- [Licencia](#licencia)

## Descripción del proyecto

Este proyecto de Arduino te permite mostrar mensajes personalizados en una matriz de LEDs. Puedes controlar el desplazamiento de los mensajes y ajustar la velocidad de desplazamiento. Es una forma divertida de experimentar con la programación de Arduino y la visualización de texto en una matriz de LEDs.

## Materiales necesarios

Asegúrate de tener los siguientes materiales antes de comenzar:

- Placa Arduino
- Matriz de LEDs compatible con la biblioteca MD_MAX72xx
- Pines y cables de conexión
- Cable USB para la programación de la placa Arduino

## Configuración

1. Conecta la matriz de LEDs a tu placa Arduino siguiendo las instrucciones de conexión adecuadas. Asegúrate de conectar los pines de datos, reloj y selección (CS) a los pines correspondientes de tu placa Arduino.

2. Abre el archivo de código fuente del proyecto en el entorno de desarrollo de Arduino.

3. Asegúrate de que tu entorno de desarrollo esté configurado con la velocidad de transmisión adecuada. En el archivo de código fuente, la velocidad de transmisión está configurada de la siguiente manera:

   ```cpp
   Serial.begin(57600);
   ```
Asegúrate de que la configuración de velocidad de transmisión en tu monitor serie coincida con este valor.

Carga el código en tu placa Arduino utilizando el cable USB.
## Instrucciones de uso
Abre el monitor serie en el entorno de desarrollo de Arduino.

En el monitor serie, puedes escribir mensajes que deseas mostrar en la matriz de LEDs. Termina cada mensaje con un retorno de carro o una nueva línea.

Ejemplo:

```cpp
Este es un mensaje de prueba
¡Hola, Arduino!;
```
Los mensajes que ingreses se mostrarán en la matriz de LEDs y se desplazarán a medida que se ingresen nuevos mensajes.

Puedes ajustar la velocidad de desplazamiento del mensaje utilizando un potenciómetro (si está configurado) o modificando la velocidad en el código.

Diviértete experimentando con diferentes mensajes y observa cómo se muestran en la matriz de LEDs.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más detalles sobre los términos de la licencia.

Si tienes alguna pregunta o problema, no dudes en abrir un informe de problemas (issue) en este repositorio o ponerte en contacto conmigo a través de brodner.rocael.m.a@gmail.com.

