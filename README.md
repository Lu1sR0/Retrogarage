<div align="center">

# Retro Garage

Site de uma loja fictícia de carros clássicos, com vídeo de fundo, catálogo e modelos 3D interativos.

[![Ver site](https://img.shields.io/badge/VER_SITE-0D0D0D?style=for-the-badge&logo=netlify&logoColor=FF003C)](https://retrogarage.netlify.app)

![HTML5](https://img.shields.io/badge/HTML5-0D0D0D?style=for-the-badge&logo=html5&logoColor=FF003C)
![CSS](https://img.shields.io/badge/CSS-0D0D0D?style=for-the-badge&logo=css&logoColor=FF003C)
![JavaScript](https://img.shields.io/badge/JavaScript-0D0D0D?style=for-the-badge&logo=javascript&logoColor=FF003C)
![Sketchfab](https://img.shields.io/badge/Sketchfab-0D0D0D?style=for-the-badge&logo=sketchfab&logoColor=FF003C)
![Git LFS](https://img.shields.io/badge/Git_LFS-0D0D0D?style=for-the-badge&logo=gitlfs&logoColor=FF003C)

</div>

## Sobre

Loja de carros retrô criada por mim para um trabalho da **ETEC Professor Basilides de Godoy**. No contexto do curso, a Retro Garage é apresentada como projeto de portfólio da [Disquetech](https://github.com/Lu1sR0/Disquetech), empresa fictícia de desenvolvimento criada pelo grupo — por isso o rodapé traz os contatos da Disquetech.

Preços, avaliações e textos são fictícios, criados para o exercício.

## Funcionalidades

- **Tela de carregamento** que some quando a página termina de carregar.
- **Header fixo** com menu hambúrguer no mobile, que fecha automaticamente ao rolar a página.
- **Hero com vídeo de fundo** em loop, sem som, com a chamada da loja.
- **Catálogo** com seis clássicos — Porsche 911, Chevrolet Impala, Ferrari 250 California, Jaguar E-Type, Fusca e Ford Mustang Boss 429 — com preço à vista e parcela mensal.
- **Carros em 3D**: três modelos interativos incorporados do Sketchfab (Fusca, Mustang e Impala).
- **Sobre nós** com uma imagem de Fusca clicável que toca uma buzina.
- **Avaliações** bem-humoradas de personagens como Dean Winchester e Herbie.
- **Rodapé** com navegação, endereço no Google Maps e redes da Disquetech.
- **Animações de entrada** com ScrollReveal e layout responsivo (breakpoints de 991 px a 350 px).

## Tecnologias

- **HTML5, CSS e JavaScript** puros.
- **ScrollReveal** — animações ao rolar a página.
- **Boxicons** e **Font Awesome** — ícones.
- **Google Fonts** — Titan One, Changa One e Bungee Shade.
- **Sketchfab** — visualizador 3D incorporado.
- **Git LFS** — versionamento do vídeo de fundo (`fordfundo.mp4`).
- **Netlify** — hospedagem.

## Estrutura

```
Retrogarage/
├── index.html      # página única com todas as seções
├── style.css       # estilos e media queries
├── main.js         # menu mobile, ScrollReveal, buzina e loader
├── fordfundo.mp4   # vídeo do hero (Git LFS)
├── car_horn.mp3    # som da buzina
└── img/            # fotos dos carros, logo e avatares das avaliações
```

## Como rodar localmente

O vídeo de fundo é armazenado com Git LFS. Instale o [Git LFS](https://git-lfs.com/) antes de clonar para baixar o arquivo real:

```bash
git lfs install
git clone https://github.com/Lu1sR0/Retrogarage.git
cd Retrogarage
```

Depois, abra o `index.html` no navegador ou use a extensão **Live Server** do VS Code. Os modelos 3D e as bibliotecas externas precisam de conexão com a internet.

---

<div align="center">
Desenvolvido por <a href="https://github.com/Lu1sR0">Luis Roberto</a> · <a href="https://outframe.dev">Outframe</a>
</div>
