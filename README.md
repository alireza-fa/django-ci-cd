# traefik / nexus

apt install apache2-utils

echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
