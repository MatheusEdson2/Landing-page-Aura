# Studio Aura

Landing page conceitual para o Studio Aura, um estúdio de arquitetura e design de interiores de alto padrão. O projeto explora a estética do luxo discreto com uma interface escura, detalhes dourados, tipografia editorial e imagens de interiores.

<img width="1917" height="975" alt="Captura de tela 2026-10-19 200824" src="https://github.com/user-attachments/assets/fe05aa9a-256c-460d-b5e3-c0db0726466e" />


## Sobre o projeto

A página apresenta a identidade do Studio Aura em uma experiência visual inspirada em galerias de arte e hotéis boutique, com foco no portfólio e nos serviços do estúdio.

## Funcionalidades

- Abertura com vídeo de fundo e chamadas para ação.
- Processo de trabalho apresentado em três etapas, com animação vinculada à rolagem.
- Galeria dinâmica de projetos.
- Seção sobre o estúdio e sua filosofia.
- Depoimentos em apresentação rotativa.
- Formulário com validação básica dos campos.
- Link de contato via WhatsApp.
- Navegação adaptada para dispositivos móveis.
- Animações de entrada durante a rolagem da página.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- [GSAP](https://gsap.com/) e ScrollTrigger
- Google Fonts: Bodoni Moda e Hanken Grotesk

## Executar localmente

O projeto não requer instalação de dependências nem etapa de compilação.

1. Clone o repositório:

   ```bash
   https://github.com/MatheusEdson2/Landing-page-Aura.git
   ```

2. Abra a pasta do projeto no VS Code.
3. Abra o arquivo **index.html** no navegador ou use a extensão Live Server.

GSAP e as fontes são carregados de serviços externos. É necessária uma conexão com a internet para carregá-los.

## Estrutura do projeto

```text
.
├── index.html
├── script.js
├── styles.css
├── screen.png
├── DESIGN.md
├── prd_studio_aura.md
└── src/
    └── assets/
        ├── interior-dark-video.mp4
        ├── video-camadas.mp4
        ├── projeto-banheiro.png
        ├── projeto-biblioteca.png
        ├── projeto-cozinha.png
        ├── projeto-quarto.png
        ├── projeto-sala.png
        ├── projeto-sala-2.png
        └── projeto-terracota.png
```

## Observações

- O formulário valida os campos e exibe uma confirmação visual, mas ainda não envia os dados para um servidor ou serviço de e-mail.
- Antes de publicar, substitua o número demonstrativo do WhatsApp e os links sociais pelos contatos reais.
- Textos, nomes e depoimentos são conteúdo demonstrativo.

## Licença

Nenhuma licença foi especificada para este projeto.
