# FileCloud

Ahora puedes acceder al portal de administración de FileCloud en:

http://<IP:8400>/ui/admin/index.html

El nombre de usuario es admin y la contraseña es password.


Puedes acceder al portal de usuario de FileCloud en: 

http://<IP:8400>/ui/core/index.html

Comandos posteriores:

docker exec -it filecloud.solr bash

cp -R /var/www/html/thirdparty/overrides/solarium/Solarium/fcskel/* /var/solr/data/fccore/
