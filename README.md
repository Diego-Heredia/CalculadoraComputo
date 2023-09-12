# Calculadora Distribuida

Este proyecto consiste en una calculadora distribuida que utiliza un middleware para gestionar las comunicaciones entre el cliente y el servidor.

## Estructura del Proyecto

- **Middleware**: Se encarga de recibir paquetes del cliente y reenviarlos a los servidores.
- **Servidor**: Realiza las operaciones solicitadas y devuelve los resultados al cliente a través del middleware.
- **Cliente**: Interfaz de usuario donde se pueden introducir operaciones para ser procesadas por el servidor.



## Instrucciones de Uso

1. **Iniciar el Middleware**:
    - Navega al directorio donde se encuentra el archivo ejecutable o el código fuente del middleware.
    - Ejecuta el middleware. Esto abrirá una ventana que mostrará los registros de las operaciones.

2. **Iniciar el Servidor**:
    - Una vez que el middleware esté en funcionamiento, navega al directorio del servidor.
    - Ejecuta el servidor. Deberías ver un mensaje indicando que el servidor está esperando operaciones.

3. **Iniciar el Cliente**:
    - Finalmente, navega al directorio del cliente.
    - Ejecuta el cliente. Esto abrirá la interfaz de usuario donde puedes introducir operaciones para ser procesadas.
    - Introduce una operación y observa cómo se procesa y se devuelve el resultado.

## Notas

- Es esencial iniciar los componentes en el orden especificado: primero el middleware, luego el servidor y finalmente el cliente. De lo contrario, es posible que no se establezca la comunicación correctamente.

