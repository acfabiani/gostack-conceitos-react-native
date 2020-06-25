## :rocket: Sobre o desafio
Simples app com uma lista de *Repositories* recuperados da *API*, com funcionalidade para curtie um item da listagem.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes}` curtidas, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**:Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

## :blue_book: Principais conceitos
* Todos os containers serão uma *`View`*, não existem divs, footer, header, aside, section...
* Todos os textos serão *`Text`*, não existem p, span, strong, h1...

* Os elementos não herdam estilos, toda estilização é feita para o componente expecífico através do *`StyleSheet`*, e todos os componentes tem por padrão *display: flex*.

## :carousel_horse: Como usar
## Pré requisitos
- API back-end [gostack-conceitos-nodejs](https://github.com/acfabiani/gostack-conceitos-nodejs)
## Iniciando o projeto
- Clone o repositório
- Baixe as dependências
    ```bash
    $ yarn
    ```
- Rode o aplicativo
    ```bash
    $ yarn android
    ```
    ou
    ```bash
    $ yarn ios
    ```
- Para rodar os testes
    ```bash
    $ yarn test
    ```    
---
Feito com :hearts: by acfabiani :unicorn: