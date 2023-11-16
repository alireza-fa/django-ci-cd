# django ci/cd

echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g ^C
