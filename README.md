# Portfólio Pessoal

Este é o código do meu **portfólio pessoal**, que apresenta meu trabalho como **desenvolvedor Front-end** com foco em **React, HTML e CSS**. O objetivo é mostrar minhas habilidades e facilitar o contato com potenciais clientes e colaboradores.

## Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **Google Fonts**: Fontes utilizadas (`Krona One` e `Montserrat`).
- **Design Responsivo**: A página foi projetada para se adaptar a diferentes tamanhos de tela, utilizando a tag meta `viewport` para garantir a responsividade.

## Estrutura do Projeto

### Arquivos Principais:

- `index.html`: Página principal do portfólio.
- `style.css`: Arquivo de estilos utilizado para estilizar a página.

### Estilização (CSS)

O arquivo `style.css` foi projetado para fornecer uma aparência moderna e responsiva ao portfólio. Abaixo estão alguns detalhes sobre os principais estilos aplicados:

- **Fonte**: Utiliza as fontes **Krona One** (para títulos) e **Montserrat** (para parágrafos e links), ambas carregadas do Google Fonts.
  
  ```css
  @import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
  ```

- **Cor de Fundo e Texto**:
  
  O fundo da página é preto (`#000000`), e o texto é branco (`#f6f6f6`) para proporcionar um forte contraste, com destaque em azul (`#22D4FD`) para certos elementos como o título principal e os botões.

  ```css
  body {
      background-color:#000000;
      color: #f6f6f6;
  }

  .titulo-negrito-azul {
      color: #22D4FD;
  }
  ```

- **Apresentação e Layout**:
  
  A seção de apresentação utiliza **Flexbox** para alinhar o conteúdo e a imagem lado a lado, com espaçamento adequado entre eles. O conteúdo textual é organizado em colunas e possui espaçamento uniforme.

  ```css
  .apresentacao {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin: 10% 17%;
  }

  .apresentacao__conteudo {
      width: 615px;
      display: flex;
      flex-direction: column;
      gap: 40px;
  }

  .apresentacao__conteudo__titulo {
      font-size: 36px;
      font-family: "Krona One", sans-serif;
  }

  .apresentacao__conteudo__paragrafo {
      font-size: 24px;
      font-family: "Montserrat", sans-serif;
      font-weight: 400;
  }
  ```

- **Links de Redes Sociais**:
  
  Os links para redes sociais são estilizados como botões com bordas arredondadas e mudanças de cor ao passar o mouse (hover effect). Eles têm um fundo azul (`#22D4FD`), que muda ligeiramente de tom ao interagir com o mouse.

  ```css
  .apresentacao__links__link {
      background-color: #22D4FD;
      width: 280px;
      border-radius: 16px;
      font-family: "Montserrat", sans-serif;
      font-size: 24px;
      font-weight: 600;
      color: #000000;
      text-align: center;
      padding: 21.5px 0;
      text-decoration: none;
  }

  .apresentacao__links__link:hover {
      background-color: #22c4ec;
  }
  ```

- **Imagem**:
  
  A imagem exibida ao lado do texto tem bordas arredondadas para um visual mais suave, com dimensões predefinidas.

  ```css
  .imagem {
      width: 488px;
      height: 550px;
      border-radius: 16px;
  }
  ```

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/LuisFNascimento/portfolio.git
   ```

2. Abra o arquivo `index.html` em qualquer navegador para visualizar o portfólio.

## Personalização

Você pode personalizar o conteúdo do portfólio para incluir suas próprias informações, alterar estilos no arquivo `style.css`, ou adicionar novas seções conforme necessário.

## Exemplo de Layout

Abaixo está uma visualização da estrutura da página de portfólio:

```
+-----------------------------+
|         Cabeçalho            |
| Eleve seu negócio digital... |
| Sou Luís Fernando...         |
| [Instagram] [GitHub]         |
|                             |
|         [Imagem]             |
+-----------------------------+
```

## Contato

Se você está interessado em colaborar ou saber mais sobre meus projetos, sinta-se à vontade para me contatar via redes sociais ou GitHub.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
```

Este README agora inclui uma explicação detalhada sobre os estilos CSS utilizados no projeto, junto com as informações anteriores sobre o HTML e o propósito do portfólio.
