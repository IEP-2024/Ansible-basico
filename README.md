Para ejecutar:

`ansible-playbook -i inventario archivo.yml -k -K`

-k: para que pida password de SSH
-K: para que pida password de sudo



Para usar docker (en cmd):

`docker run -ti --rm -v %cd%:/ansible ggmartinez/ansible:9.1.0`