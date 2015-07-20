** PageHandlerFactory é utilizado para carregar e configurar a injeção de dependência. Localiza a página apropriada para a utilização em uma requicição HTTP. A não utilização teria que injetar manualmente as configurações de injeção de dependência.

** WebServiceHandlerFactory é utilizado para publicar facilmente os serviços da web.

** LogRoutesHandler é emitir as rotas para o browser. Configuração de rotas.

** A tag httpModules definide que agora conterá mais um módulo raiz que corresponderá às configurações web exclusivas do Spring.net.

----------

Tipos de escopos:

* Aplication: Cria uma unica instância do objeto durante a aplicação;
* Session: Cria uma unica instancia do HttpSession. Ideal para perfil de usuários.
* Request: Cria uma unica instância por solicitação HTTP.
