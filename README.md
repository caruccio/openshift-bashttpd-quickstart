Bash HTTP server quickstart for OpenShift
=========================================
Quickstart [bashttpd](https://github.com/avleen/bashttpd) para a plataforma Getup Cloud OpenShift.

Para criar sua aplicação, primeiro vcê precisa registrar-se na Getup.
Acesse http://getupcloud.com/#/sign-up e faça seu cadastro.
Você recebe gratuitamente 750hs para testar a plataforma.

Utilizando o comando `rhc` crie uma app DIY usando este quickstart:

    $ rhc app-create bashttpd diy --from-code https://github.com/caruccio/openshift-bashttpd-quickstart.git

Sua aplicação está disponível na URL http://bashttpd-$namespace.getup.io

Edite o arquivo `bashttpd.conf` para incluir novas diretivas.

Para mais informações, leia o artigo em [nosso blog](http://getupcloud.com/blog/bashttpd-servidor-http-em-shell-script).
