# django ci/cd

apt install apache2-utils

echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g ^C

default password: user password
