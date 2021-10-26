# jdbc-odb
Conexão jdbc com ODB. Exemplo de insert, delete, select.
Passos:

Criar base "odb" no libre office com tabelas, coloar algum registro pra teste e o que quiser;
Fechar a base e mudar a extençao do arquivo como ".zip"; Exemplo: "baseteste.odb" para "baseteste.zip";
Extrair o arquivo zip, localizar os arquivos data, log, properties, script e renomear eles para "baseteste.data", "baseteste.log", "baseteste.properties", "baseteste.script";
Colocar esses 4 arquivos na raiz do projeto ou em alguma pasta para apontar o endereço da base no codigo do projeto;
Baixe o "hsqldb.jar" e adicione a biblioteca do projeto, ou utilize a que ja esta aqui.
