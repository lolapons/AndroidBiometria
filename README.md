# AndroidBiometria

# Descripción del Proyecto AndroidBiometria

Este proyecto frontend se encarga de mostrar datos en tiempo real sobre los niveles de ozono y la temperatura, recuperados de una API. El diseño es simple y está estructurado en HTML, CSS y JavaScript, permitiendo que la información se actualice automáticamente cada 5 segundos.

## Archivos y Funcionalidades

### `MainActivity`
Esta es la clase principal de la aplicación Android. Aquí se gestiona la interfaz de usuario y las interacciones del usuario. Al iniciar la actividad, se configuran los componentes visuales y se inicia el proceso de escaneo Bluetooth para detectar beacons y obtener datos sobre los sensores. 

### `TramaIBeacon`
Esta clase se encarga de gestionar la trama del beacon, que incluye los datos que se transmiten desde el dispositivo beacon. Aquí se procesan los datos recibidos, se extraen los valores relevantes de ozono y temperatura, y se preparan para ser mostrados en la interfaz de usuario. Además, se pueden implementar métodos para validar la información recibida.

### `Utilidades`
La clase Utilidades contiene métodos y funciones que son utilizados en todo el proyecto. Aquí se pueden definir funciones auxiliares, como formatear datos, validar entradas, o realizar conversiones necesarias entre diferentes unidades. Esto ayuda a mantener el código más limpio y modular.

---

*Lola Pons Bargues*
