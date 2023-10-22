**Serviço remoto** 

`Biblioteca`
 + [ ] Inserção de livros 
    - in 
      1. nome_livro
      2. autor_livro
      3. genero_livro
      4. data_livro
    - out
      1. retorna o objeto formatado com uma mensagem de sucesso
    - exceções
      1. time out
      2. param invalidos
      3. mesmo livro cadastrado
 + [ ] Remoção
    - in
      1. qualquer identificador que possa fazer match com o livro buscado
    - out
      1. retorna uma mensagem de sucesso ao excluir
    - exceções
      1. caso não ache o livro retorna uma mensagem do tipo *remoção invalida*
 + [ ] Método de busca nas prateleiras da biblioteca
    - in
      1. qualquer identificador nome/data/autor/genero
    - out
      1. mostrar resultados da busca (retornar o objeto)
    - exceções
      1. não achar o objeto em questão

> [!NOTE]
> Ainda vou adicionar mais funções em questão como possivelmente um web-view
