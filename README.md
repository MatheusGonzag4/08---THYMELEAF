# Cadastro de Produtos com Thymeleaf

Projeto baseado na estrutura da aula `Cadastro de Produtos — Spring Boot + Thymeleaf`.

## Estrutura

- `model/Produto.java`: representa nome, preço e categoria.
- `controller/ProdutoController.java`: controla cadastro e listagem.
- `templates/cadastrar.html`: formulário de cadastro.
- `templates/lista.html`: tabela de produtos.
- Os produtos ficam em uma lista em memória e são perdidos ao reiniciar a aplicação.

## Como executar na IntelliJ

1. Extraia o arquivo ZIP.
2. Abra a pasta `cadastro-produtos` na IntelliJ IDEA.
3. Aguarde o Maven carregar as dependências.
4. Execute `CadastroProdutosApplication`.
5. Acesse `http://localhost:8080`.

## Fluxo esperado

- `/` redireciona para `/cadastrar`.
- `/cadastrar` mostra o formulário.
- Após cadastrar, a aplicação redireciona para `/lista`.
- `/lista` mostra os produtos cadastrados ou a mensagem de lista vazia.
