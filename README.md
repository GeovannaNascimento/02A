# 02A

$ apt update
$ apt upgrade

(instalar nodejs caso não esteja instalado)

$ cd nodejs
(Encontrar onde foi colocado, o ambiente "virtual" do nodejs)

$ source <pasta_do_node>/bin/activate
(Se funcionar o comando o prompt terá o nome da pasta ativada)

$ node --version
(Testar)

$ sudo chown aluno:aluno index.js
(Permissão)

$ nano index.js

"var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World!');
}).listen(5000);"

(Alterar código de acordo com as requisições e CTRL+X para salvar + S-sim + ENTER)

$ node index.js
