# SunoProject em Postman - Testes para API TheMovieDB.org
Esta collection do Postman foi feita com base em testes da API de TheMovieDB.org contendo requests essenciais de acordo com critérios definidos por mim.

## Pré-condição
* Ter o [Postman](https://www.postman.com) instalado em sua máquina

## Como fazer a importação

### Método 
1. Efetue o download do arquivo `sunoproject.postman_collection.json`
2. Abra o Postman
3. Selecione o menu *File -> Import*
4. Selecione a aba *File*
5. Clique no botão *Upload Files*
6. Navegue até o diretório onde você salvou o arquivo e selecione-o
7. Clique no botão *Import*

# Observações
Por praticidade, você poderá utilizar a ferramenta built-in Runner presente no Postman, basta clicar no ícone Runner no canto inferior direito da tela, arrastar a collection SunoProject para o centro da tela, selecionar a caixa Save responses (desativada por padrão) e clicar em Start Run.

Acredito que o endpoint presente na request DeleteExistingList necessitava de ajustes no momento em que o teste foi realizado, pois mesmo executando a ação projetada, o retorno era status 500. Os testes de retorno foram comentados no código.

Muito obrigado, e boa avaliação!
