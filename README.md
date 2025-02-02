# Site Oficial de Pokémon

Este é o repositório do site oficial de Pokémon, criado como parte do trabalho para cumprir a **Missão 7 - Curso 4: CSS Modificando Elementos HTML**. O projeto teve como objetivo praticar e aplicar conhecimentos de HTML e CSS, bem como a integração com frameworks e bibliotecas (como Bootstrap e Lightbox) para melhorar a responsividade e a usabilidade do site.

## Sumário

- [Visão Geral](#visão-geral)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Funcionalidades](#funcionalidades)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como Executar](#como-executar)
- [Conclusão](#conclusão)
- [Créditos](#créditos)

## Visão Geral

O site foi desenvolvido com uma estrutura semântica em HTML e estilos avançados em CSS. Ele apresenta diversas seções:

- **Header (Cabeçalho e Menu de Navegação):** Um menu fixo no topo com logo e opções de navegação que se adaptam à versão mobile por meio de um menu colapsado (hamburger).
- **Imagem de Capa:** Uma imagem de capa que apresenta o tema do site.
- **Seção Sobre:** Uma breve introdução sobre a franquia Pokémon e sua história.
- **Seção Pokémons (Cards):** Cards interativos exibindo informações e imagens dos principais personagens da primeira temporada.
- **Seção Galeria de Imagens:** Uma galeria de imagens dos Pokémons, com a funcionalidade de Lightbox para ampliar as imagens.
- **Rodapé:** Informações de copyright e links adicionais.

## Tecnologias Utilizadas

- **HTML5:** Estrutura semântica e organização do conteúdo.
- **CSS3:** Estilização e responsividade, com uso de variáveis, media queries e técnicas avançadas como `scroll-margin-top` para melhorar a usabilidade.
- **Bootstrap 4:** Utilizado para garantir a responsividade e a criação de um menu colapsado (hamburger) na versão mobile.
- **Lightbox2:** Biblioteca para exibir a galeria de imagens de forma interativa e com efeito modal.

## Funcionalidades

- **Menu Responsivo:** O menu do header é fixo e adaptável, transformando-se em um menu "hamburger" em dispositivos móveis.
- **Cards Interativos:** Cada card dos Pokémons exibe informações detalhadas e possui efeitos de hover, além de um layout responsivo que se adapta à visualização em diferentes dispositivos.
- **Galeria de Imagens:** A galeria permite a visualização ampliada das imagens utilizando o Lightbox, melhorando a experiência do usuário.
- **Scroll Margin:** Uso da propriedade `scroll-margin-top` para evitar que as seções fiquem ocultas atrás do header fixo ao navegar pelas âncoras.

## Estrutura do Projeto

```
├── index.html         # Página principal do site
├── README.md          # Este arquivo de documentação
├── estiloct.css       # Arquivo CSS com os estilos personalizados
├── img/               # Pasta com as imagens utilizadas (logo, capa, cards, etc.)
└── LICENSE            # Arquivo com os termos da licença MIT para o projeto
```

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/rennanferraz/rennanferraz_site_pokemon.git
2. Abra o arquivo index.html no seu navegador ou execute um servidor local para visualização.
3. Navegue pelo site e explore as diferentes seções.

## Conclusão
Este projeto permitiu a aplicação prática de conceitos avançados de HTML e CSS, demonstrando como modificar e estilizar elementos de forma responsiva e interativa. A integração com o Bootstrap e o Lightbox facilitou a criação de uma interface moderna e amigável para os usuários.

## Créditos
- **Desenvolvedor:** Renan Ferraz
- **Curso:** Missão 7 - Curso 4: CSS Modificando Elementos HTML
- **Frameworks/Bibliotecas:** [Bootstrap](https://getbootstrap.com/) e [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/)
