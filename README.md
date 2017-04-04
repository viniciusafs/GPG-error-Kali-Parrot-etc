# Ajuda com erro de chaves PGP, ao adicionar repositórios.

apt-key adv --keyserver hkp://keys.gnupg.net --recv-keys 7D8D0BF6

#Adicionado apenas os oito digitos da chave inteira.
#Segundo método
#Apagar o arquivo lists

rm -rf /var/lib/apt/lists
apt-get update 
apt-get install kali-archive-keyring
