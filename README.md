README: Projeto Cartão Animado (Card Animado)

Este repositório contém o código-fonte para um projeto web simples que demonstra cartões interativos com um efeito de "flip" (virar) em 3D, utilizando HTML e CSS puro.

🚀 Funcionalidades Principais

Efeito Flip 3D: Os cartões viram suavemente para revelar o conteúdo do verso quando o mouse passa por cima (:hover).
Layout Responsivo: Utiliza Flexbox para organizar os cartões e garantir que se ajustem à largura da tela.
Design Moderno: Fundo gradiente vibrante (radial-gradient), cabeçalho fixo com backdrop-filter (efeito blur) e sombras sutis.
Conteúdo Front-End/Back-End: Cartões de exemplo para áreas de desenvolvimento de software.

🛠️ Tecnologias Utilizadas

O projeto é construído exclusivamente com tecnologias front-end básicas:
HTML5: Estrutura semântica da página e definição dos elementos dos cartões.
CSS3: Estilização, layout Flexbox/Grid, transições 3D (transform, perspective), e backface-visibility.

📁 Estrutura de Arquivos

A estrutura do projeto segue um padrão básico:
/card-animado/
├── index.html
├── style.css
└── /img/
    ├── (Imagens de preview usadas no verso dos cartões)
    
📖 Como Usar

Para visualizar o projeto, basta abrir o arquivo index.html em qualquer navegador web moderno. Não há necessidade de servidor web ou instalação de dependências.
Detalhes de Implementação
Centralização e Layout: O body e o main utilizam display: flex para centralizar o conteúdo vertical e horizontalmente e permitir que os cartões se organizem com gap e flex-wrap.
Efeito 3D: A propriedade perspective: 1000px; no contêiner .card é crucial para criar a profundidade 3D, enquanto transform-style: preserve-3d; no .card-inner permite que os elementos filhos herdem o contexto 3D.
Transições: A animação de virar é controlada pela propriedade transform no .card-inner na interação :hover.

🖼️ Fontes das Imagens de Preview
 
As imagens utilizadas no verso dos cartões são links externos usados apenas para demonstração visual dentro do HTML (index.html):
Card Front-End (Card 1):
URL: https://minasvisual-api-master.s3.amazonaws.com (p. 1)
Card Back-End (Card 2):
URL: https://blog.ebaconline.com.br (p. 1)
Card Projeto Gamma (Card 3):
URL: http://huntit.com.br (p. 2)
© Créditos e Licença
Desenvolvedor: Eduardo Luz
Este projeto é fornecido como código de demonstração.
