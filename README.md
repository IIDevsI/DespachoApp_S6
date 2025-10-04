# DespachoApp_S6

Aplicación móvil Android desarrollada en Kotlin para la gestión de pedidos y cálculo de despacho en tiempo real, usando Firebase Authentication y Firebase Realtime Database.

## Funcionalidades
- **Login y Registro** de usuarios mediante Firebase Authentication.
- **Menú principal** con ingreso de valor de compra y slider de distancia (km).
- **Cálculo de costo de despacho**:
  - Gratis si compra >= $50.000 y distancia <= 20 km.
  - $150/km si la compra está entre $25.000 y $49.999.
  - $300/km en otros casos.
- **Botón Guardar ubicación (GPS)** que almacena latitud/longitud en Firebase Realtime Database.
- **Botón Pagar** que registra un pedido en Firebase con subtotal, km, costo de despacho y total.

## Tecnologías usadas
- Android Studio (Kotlin)
- Firebase Authentication
- Firebase Realtime Database
- Google Play Services Location

## Ejecución
1. Clonar este repositorio.
2. Abrir el proyecto en Android Studio.
3. Agregar el archivo `google-services.json` de Firebase.
4. Compilar y ejecutar en un dispositivo Android físico o emulador.

## Autores
- [Héctor Corante] 
