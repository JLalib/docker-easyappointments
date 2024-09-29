# Easy!Appointments
Easy!Appointments | Sistema de gestión de citas y reservas.

![image](https://github.com/user-attachments/assets/22a1c161-4b42-4266-afba-efd91bb1a983)

## Configuración envío mails (SMTP)
Después de cambiar la configuración, reiniciar el contenedor.
### Comandos usados:

Copiar fichero email.php del container a local

genbyte@docker:~/docker/eassyappointments$ docker cp easy-appointments:/var/www/html/application/config/email.php .

backup email.php

genbyte@docker:~/docker/eassyappointments$ cp email.php email.php-old

Copiar fichero email.php de local a container

genbyte@docker:~/docker/eassyappointments$ docker cp email.php easy-appointments:/var/www/html/application/config/email.php
