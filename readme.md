## Passo a passo para criar um fake api rest:

**1º** - Crie uma pasta no seu diretório de sua preferência com o seguinte nome: "jsonserver" ;<br/>
<br/>**2º** - Acesse o seguinte link do GitHub: https://github.com/typicode/json-server/tree/v0 e cole no navegador de sua preferência;<br/>
<br/>**3º** - Desça até achar o seguinte comando: "npm install -g json-server" ;<br/>
<br/>**4º** - Abra o terminal de sua preferência dentro da pasta que você criou no passo 1º, e cole o comando do passo 3º no terminal
5º - após baixar todas as dependências, crie um arquivo de texto dentro da pasta "jsonserver" com o nome: "db.json" e adicione dentro do arquivo, cole a seguinte documentação:<br/>
<br/>{
"id": "1",
"nome": "Fabiano",
"endereco": "Rua de Tal"
} <br/>
<br/>**6º** - Após colar essa documentação, salve o documento e no terminal execute o seguinte comando: json-server --watch db.json ;<br/>
<br/>**7º** - Feito isso, vai ser carregado algumas informações no terminal, dentre elas um endpoint com o seguinte caminho: http://localhost:3000/pessoas ;<br/>
<br/>**8º** - Abra um programa chamado "Postman" ou qualquer outro de sua preferência, desde que você consiga testar o funcionamento da api ;<br/>
<br/>**9º** - Após isso, copie e cole esse caminho http://localhost:3000/pessoas usando o método GET e clique no botão "send" ;<br/>
<br/>**10º** - Feito isso, será exibido os dados que você colocou dentro do documento "db.json"

### Pronto, sua fake api REST já estará em funcionamento ;)
