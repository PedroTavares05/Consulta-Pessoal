# Orçamento Pessoal

Este é um projeto simples de gerenciamento de despesas pessoais, desenvolvido com HTML, CSS, JavaScript e Bootstrap. Ele permite o cadastro, consulta e exclusão de despesas armazenadas no `localStorage` do navegador.

## Estrutura do Projeto

O projeto possui a seguinte estrutura de arquivos:

### Arquivos

- **[index.html](index.html)**  
  Página principal do projeto, onde é possível cadastrar novas despesas. Contém um formulário para entrada de dados como ano, mês, dia, tipo, descrição e valor da despesa.

- **[consulta.html](consulta.html)**  
  Página para consulta de despesas cadastradas. Permite filtrar despesas por ano, mês, dia, tipo, descrição e valor. Também possibilita a exclusão de despesas.

- **[app.js](app.js)**  
  Arquivo JavaScript que contém a lógica do projeto. Ele implementa as classes `Despesa` e `Bd` para manipulação de dados, além de funções para cadastro, consulta e exclusão de despesas.

- **logo.png**  
  Imagem utilizada como logotipo no cabeçalho das páginas.

## Funcionalidades

1. **Cadastro de Despesas**  
   - Preencha os campos no formulário da página inicial ([index.html](index.html)) e clique no botão de adicionar para cadastrar uma nova despesa.

2. **Consulta de Despesas**  
   - Acesse a página de consulta ([consulta.html](consulta.html)) para visualizar todas as despesas cadastradas.
   - Utilize os filtros para buscar despesas específicas.

3. **Exclusão de Despesas**  
   - Na página de consulta, clique no botão de exclusão (ícone de "X") para remover uma despesa.

## Tecnologias Utilizadas

- **HTML**: Estrutura das páginas.
- **CSS**: Estilização com Bootstrap.
- **JavaScript**: Lógica de negócio e manipulação do DOM.
- **Bootstrap**: Framework CSS para estilização e responsividade.
- **Font Awesome**: Ícones utilizados nos botões.
- **localStorage**: Armazenamento de dados no navegador.

## Como Executar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador para acessar a página inicial.
3. Navegue entre as páginas `index.html` e `consulta.html` para utilizar as funcionalidades do projeto.

## Capturas de Tela

### Página de Cadastro
![Página de Cadastro](logo.png)

### Página de Consulta
![Página de Consulta](logo.png)

## Autor

Este projeto foi desenvolvido como um exemplo de aplicação prática de HTML, CSS e JavaScript.
