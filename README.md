# ExamenNGINX

### Ejercicio 1
#### WEB 1 - Acceso correcto
<img width="540" height="213" alt="image" src="https://github.com/user-attachments/assets/6ca996a6-28e4-4c47-8076-6e6867ae300e" />
<img width="549" height="172" alt="image" src="https://github.com/user-attachments/assets/b2d9e5f5-df2c-43c3-85aa-98550d97f476" />
Se configura Web1 para que tenga acceso por HTTPS mediante certificados SSL. Se añade el return 301 para que automáticamente se redirijan todas las búsquedas por HTTP hacia HTTPS, como se ve en la captura del comando curl.


#### WEB 2 - Redirigida a la web de mantenimiento
<img width="509" height="202" alt="image" src="https://github.com/user-attachments/assets/288e90b9-4ac1-47ce-acb1-3634cfd4aa02" />
<img width="550" height="196" alt="image" src="https://github.com/user-attachments/assets/2a86e3d8-bb0b-4d22-af46-ab1324f11d01" />
Se configura Web2 para que todas las búsquedas a www.web2.org se redirijan automáticamente hacia la web que creamos de mantenimiento.

### EJERCICIO 2
#### Configuración logs
<img width="316" height="225" alt="image" src="https://github.com/user-attachments/assets/ca37b681-f1d8-4f12-afb1-900a6cbd47ef" />
Se soluciona un fallo de sintaxis que aparecía al ejecutar "nginx -t". Se crean las rutas para los logs de errores y se configura la web1 para enviar accesos fallidos hacia donde queremos, pero no se logra llevar a cabo.
<img width="1284" height="139" alt="image" src="https://github.com/user-attachments/assets/aef73dcf-c3ae-4c2d-a0f1-f0451744cebb" />




