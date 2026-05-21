# Projeto Biblioteca Virtual:
### Tema 1 - Biblioteca Pessoal
### integrantes: Samuel Costa Domingues - Ciência da computação

## Explicações:
### 1 - Fila é um sistema de listagem, onde, aquele que entra primeiro, tambêm sai primeiro
#### exemplo no codigo: "for i, livro in enumerate(livros, start=1): ..."Onde, aqui conta do primeiro ao ultimo.
### 2 - Pilha é quase o contrario da fila, onde aquele por ultimo, sai primeiro
#### exemplo no codigo: "for posicao, livro in enumerate(reversed(lidos), start=1): ..."Por outro lado, neste, o "reversed" faz inverter a ordem, fazendo A contagem ir do mais recente ao mais antigo.
### 3 - O dicionario, foi utilizado para gravar as informações do livro, como autor, titulo
#### exemplo no código: dic_livros = {
####        "id": len(livros) + 1,
####        "tituloz": titulos,
####        "autor": autor,
####        "Ano_de_publicação": ano,
####        "genero": genero,
####        "prioridade": prioridades,
####        "status": status[0]
### 4 - A principal diferença entre listas e tuplas, é como elas são escritas, e como funcionam, ambas guardam dados, porém a lista é escrita com couchetes, e os dados dentro são mutaveis, como por exemplo, adicionar o nome do autor/data, etc , enquanto as tuplas são feitas com parenteses, e são imutaveies, como por exemplo, status tipo a ler,lendo e lido.
### 5 - modularização é a divisão do projeto em partes menores, como o que foi feito nesse projeto, dividindo em 4 arquivos.

## Como executar o projeto:
### A versão de python necessaria é a 3.10+
### Para executar o arquivo utilize o comando python main.py
### Não são necessárias bibliotecas externas
## Funcionalidades:
### As funcionalidades entregues são
## adicionar livros;
### listar livros;
### atualizar status;
### livros a ler;
### livros concluidos;
### procurar livro;
### Sair;
## Dificuldades e aprendizados:
### Começando com as dificuldades, o que eu achei mais dificil durante a produção do trabalho, foi a implementação do sistema de procura de livros, poís foi a que mais me levou tempo, e a mais "diferente", dentre as funcionalidades, já sobre o aprendizado, entre o que eu aprendi durante o desenvolvimento do projeto, inclui, a utilização de dicionarios, listas, tuplas, e suas diferenças, o que é a modularização, pegar dados de outros arquivos utilizando from, try e except e lower/higher case.
