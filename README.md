<h1 align=center>DESAFIO 03 - CORRIGINDO O CODIGO NODEJS</h1>

<p align=center>
<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fad01ee79-762a-4775-bbb6-354f2f42879a%2Fcover-node.js.png?table=block&id=59ccb235-aecd-43a6-a06b-f09a24e7ede8&width=2560&userId=7137382c-021e-467b-a53b-07178c390223&cache=v2" alt="drawing" width="700"/>
</p>


**SOBRE O DESAFIO**

O Desafio consiste em corrigir os erros em uma aplicação feita com nodejs.

**DETALHES DA APLICAÇÃO**

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

A estrutura de um repositório ao ser criado é a seguinte: 

{
  id: uuid(),
  title,
  url,
  techs,
  likes: 0
}

Descrição de cada propriedade:

- **id** deve ser um uuid válido;
- **title** é o título do repositório (por exemplo "unform");
- **url** é a URL que aponta para o repositório (por exemplo "[https://github.com/unform/unform](https://github.com/unform/unform)");
- **techs** é um array onde cada elemento deve ser uma string com o nome de uma tecnologia relacionada ao repositório (por exemplo: ["react", "react-native", "form"]);
- **likes** é a quantidade de likes que o repositório recebeu (e que vai ser incrementada de 1 em 1 a cada chamada na rota de likes).

Note que a quantidade de likes deve sempre ser zero no momento de criação.
