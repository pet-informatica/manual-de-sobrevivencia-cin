# Manual de Sobrevivência

O Manual de Sobrevivência é um projeto criado e mantido pelo PET-Informática e tem como objetivo juntar em um só lugar as informações essenciais para a vida do aluno no Centro de Informática.

O projeto utiliza o [Docsify](https://github.com/docsifyjs/docsify) para construir o site. As páginas são escritas em [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/) e renderizadas pelo Docsify no lado do cliente.

## Contribuindo

### Editando uma página

Todas as páginas estão disponíveis na pasta `/manual`. Para editar uma página, basta alterar o conteúdo do seu respectivo arquivo `.md`.

### Adicionando uma nova página

Para adicionar uma nova página, você precisa criar um novo arquivo e adicioná-lo na barra lateral. Para isto:

- Crie um novo arquivo `.md` na pasta `/manual` com o conteúdo da sua nova página. 

- Adicione a seguinte linha ao arquivo `_sidebar.md`:

        * [<span class="iconify" data-icon="mdi-NOME_DO_ICONE"></span> TITULO_DA_PAGINA](/manual/ARQUIVO_DA_PAGINA.md)

`NOME-DO-ICONE`: Nome do ícone que acompanhará o link na barra lateral. Você pode consultar os ícones disponíveis no [site do Material Design Icons](https://materialdesignicons.com/).  
`TITULO-DA-PAGINA`: Título da página na barra lateral.  
`ARQUIVO-DA-PAGINA`: Nome do arquivo da página correspondente.

### Editando a página inicial

Para editar o conteúdo da página inicial, basta alterar o conteúdo do arquivo `_coverpage.md`.

## Executando localmente

Para executar localmente, você precisará da versão LTS do [Node.js](https://nodejs.org) mais recente.

Primeiro, instale a interface de linha de comando do Docsify executando o seguinte comando no terminal:

        npm install -g docsify-cli

Depois, no diretório raiz do projeto, execute:

        docsify serve

No navegador da sua preferência, acesse `https://localhost:3000` para visualizar o site.