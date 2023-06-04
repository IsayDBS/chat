# Chat 

Applicación parecida a Whatsapp, envía mensaje entre varios usuarios.
- Permite registrar
- Permite ingresar/salir
- Permite acceder a salas

Tecnologías utilizadas:
- Django == 4.2.1
- Channels == 3.0.5

Se utiliza sqlite para guardar los mensajes y puedan presentarse en un momento futuro.

Para correr la aplicación con tu computadora como server:

```
python3 manage.py <ip de tu máquina:8080>
```