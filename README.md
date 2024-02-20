# Ciselniky DLP nove v Dockeru

## Balicky
git,docker pro CENTOS na RHEL

# Instalace 
v /opt/ git clone  https://github.com/suklorg/cisDLPDocker.git\
nebo pouze update v adresari /opt/cisDLPDocker\
git pull \
dale pak build a spusteni\
docker compose -f {file dle prostredi} build\
docker compose -f {file dle prostredi} up -d

# appka
hostname:8753/cissuklapi/v1/lecivepripravky/1
