SISAU

Sistema de Ausência e Urgência - Contrôle de Ausência da guarnição e plano de chamada para OMs do EB

By Felipe Pedrosa

Esta versão utiliza:

-Apache 2.0.61

-PHP Version 5.3.10-1ubuntu3.13

-Mysql 5.0.45

-PhpMyAdmin 2.11.2.2

Alteração necessária:

Edite o arquivo php.ini do seu servidor e altere o valor da variável abaixo para On:

Caso essa linha não exista deve ser acrescentada

register_globals = On

As Configurações de conexão com o banco de dados são feitas no arquivo base.php

Usuário padrão: admin

Senha: admin
