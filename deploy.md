# curl --location --output virtualenv-16.6.2.tar.gz https://github.com/pypa/virtualenv/tarball/16.6.2 - instala o virtualenv
# tar xvzf virtualenv-16.6.2.tar.gz - extraí virtualenv
# python pypa-virtualenv-fa40003/virtualenv.py .virtualenv || python2.7 pypa-virtualenv-fa40003/virtualenv.py .virtualenv - Cria um ambiente virtual com o venv.
# Ativa o venv
# A partir desse momento é possível instalar as coisas com o pip.
# Colocar essas linhas no topo do arquivo principal
  import os
  import sys
  sys.path.insert(0, '/home/<username>/public_html/cgi-bin/myenv/lib/python2.7/site-packages')
# O comando 'pwd' fornece o path do diretório, se usado no terminal (util para modificar o .htaccess)

# Fontes: 
   https://medium.com/@mohdejazsiddiqui/deploy-flask-app-in-apache-shared-hosting-5b3c82c8fd5e 
   https://suporte.hostgator.com.br/hc/pt-br/articles/115000388754-Como-instalar-o-Django-em-ambientes-compartilhados-
   https://medium.com/@sergioyahni/deploy-a-flask-app-on-apache-shared-hosting-with-mysql-4dc5340611b7
   https://medium.datadriveninvestor.com/installing-python-3-10-and-flask-on-godaddy-updated-ebe764ab78a7
