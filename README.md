# 🎬 Meu Portal de Entretenimento Digital

> Projeto desenvolvido para a **Agenda 13** do componente curricular **Desenvolvimento de Sistemas I (DS I)** do curso Técnico em Desenvolvimento de Sistemas da **ETEC / CPS**.

![Status](https://img.shields.io/badge/Status-Concluído-success)
![HTML5](https://img.shields.io/badge/HTML5-Semântico-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Flexbox-1572B6?logo=css3&logoColor=white)
![Design](https://img.shields.io/badge/Design-Editorial%20Indie-d97706)

---

## 📖 Sobre o Projeto

O **Meu Portal de Entretenimento Digital** é uma página web temática que reúne conteúdos sobre produções cinematográficas, áudio e streaming, e cultura gamer & tecnologia. O projeto foi construído explorando a fundo os conceitos de **arquitetura CSS**, padronização com **Classes e IDs**, organização de layout com **Flexbox**, **CSS Reset (Eric Meyer)** e a integração de código de script para interfaces web modernas.

A página adota a identidade visual **"Editorial Quente & Indie"** (inspirada em portais conceituados como *Letterboxd* e *Pitchfork*), combinando tons terrosos, café espresso escuro, superfícies quentes e toques de terracota, mostarda e sálvia.

---

## 🚀 Funcionalidades & Destaques

- **Layout Flexbox de Três Colunas:** As 3 seções temáticas (*Filmes e Séries*, *Música e Podcasts*, *Games e Tecnologia*) são dispostas lado a lado de forma ajustável e totalmente responsiva.
- **Smart Navbar (Menu Inteligente):** 
  - Fixação inteligente no topo (`position: sticky`) com efeito translúcido de vidro fosco (`backdrop-filter: blur(12px)`).
  - Ocultamento automático ao rolar para baixo e reaparecimento suave ao rolar para cima (via JavaScript atendendo à **Habilidade 3.2**).
- **Navegação Suave por Âncoras:** Transições de rolagem fluidas com `scroll-behavior: smooth` e margens de respiro com `scroll-margin-top`.
- **Hierarquia Semântica Rigorosa:** Estruturado com tags HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<footer>`).
- **Acessibilidade e Padronização:** Todas as 9 imagens contêm descrições alternativas (`alt`) e fontes padronizadas pela classe `.fonte-imagem`.

---

## 🛠️ Requisitos Técnicos Atendidos

| Requisito | Como foi aplicado no projeto |
| :--- | :--- |
| **CSS Reset (Eric Meyer)** | Arquivo `reset.css` vinculado no `<head>` antes da folha principal para padronizar estilos cross-browser. |
| **CSS Externo** | Arquivo `estilo.css` com 100% das regras de layout, tipografia, Flexbox, media queries e variáveis CSS `:root`. |
| **CSS Interno** | Tag `<style>` no `<head>` do `portal.html` para estilizar o badge `.tag-destaque-interno` e efeitos de hover. |
| **CSS Inline** | Atributo `style=""` aplicado diretamente no rodapé (`<footer>`) para cumprir a especificação do enunciado. |
| **Classes e IDs** | IDs únicos para cada temática (`#filmes-series`, `#musica-podcasts`, `#games-tecnologia`) e classes reutilizáveis (`.secao-coluna`, `.imagem-portal`, `.fonte-imagem`). |
| **Flexbox** | Aplicado no `#conteiner-secoes` (`display: flex; gap: 1.75rem; flex-wrap: wrap;`) e nos filhos com `flex: 1 1 340px;`. |
| **Comentários no CSS** | Cada seção do `estilo.css` e do `reset.css` possui cabeçalhos e comentários pedagógicos explicativos. |
| **Interação com a IA** | Registro textual completo das 3 etapas obrigatórias + rodadas complementares de refatoração no `Registro_Interacao_IA.md`. |

---

## 📂 Estrutura de Arquivos

```bash
GabrielMoraisMarcondes_Ag13_DS_I_REC/
├── index.html                  # Arquivo principal / Raiz para GitHub Pages
├── portal.html                 # Arquivo HTML oficial exigido no enunciado
├── estilo.css                  # Folha de estilo externa com Flexbox e variáveis
├── reset.css                   # CSS Reset baseado no modelo de Eric Meyer (v2.0)
├── Registro_Interacao_IA.md    # Relatório detalhado das interações com a IA mentora
├── README.md                   # Documentação completa do projeto
└── imagens/                    # Galeria local de imagens ilustrativas
    ├── cinema.jpg
    ├── series.jpg
    ├── claquete.jpg
    ├── musica.jpg
    ├── podcast.jpg
    ├── show.jpg
    ├── games.jpg
    ├── setup.jpg
    └── vr.jpg
```

---

## 💻 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/gmmdev671/etec-ag13-DS1.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd etec-ag13-DS1
   ```
3. Abra o arquivo `portal.html` ou `index.html` em qualquer navegador web (Google Chrome, Microsoft Edge, Mozilla Firefox).

---

## 👨‍💻 Autor

- **Aluno:** Gabriel Morais Marcondes  
- **Curso:** Técnico em Desenvolvimento de Sistemas  
- **Instituição:** ETEC / Centro Paula Souza (CPS)  
- **Componente:** Desenvolvimento de Sistemas I (DS I) &bull; Agenda 13  
