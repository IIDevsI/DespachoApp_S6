# ⚙️ Requisitos Funcionales

1. La aplicación debe permitir **registrar y autenticar usuarios** mediante Firebase Authentication.  
2. La aplicación debe contar con una **pantalla de menú** para ingresar el valor de la compra y seleccionar la distancia con un slider.  
3. La aplicación debe **calcular automáticamente el costo de despacho** según las reglas de negocio:  
   - Gratis si compra ≥ $50.000 y distancia ≤ 20 km.  
   - $150/km si compra está entre $25.000 y $49.999.  
   - $300/km en otros casos.  
4. La aplicación debe permitir **guardar la ubicación GPS** del usuario en Firebase Realtime Database.  
5. La aplicación debe **guardar un pedido en Firebase** al presionar el botón “Pagar”.  
6. La aplicación debe mostrar al usuario un **resumen con subtotal, distancia, costo de despacho y total**.  

---
