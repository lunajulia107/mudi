# 💜 Mudi

**Protótipo visual da Mudi**, uma plataforma de networking e aceleração profissional de mulheres. A Mudi conecta mulheres do design digital a oportunidades reais no mercado de trabalho, com **feed de projetos, vagas, mentoria e comunidade** num só lugar.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap Icons](https://img.shields.io/badge/Bootstrap_Icons-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-green?style=flat-square)

[Ver online](https://lunajulia107.github.io/mudi/) · [Sobre](#-sobre-o-projeto) · [Funcionalidades](#-funcionalidades) · [Tecnologias](#-tecnologias-utilizadas) · [Como executar](#%EF%B8%8F-como-executar-o-projeto) · [Créditos](#-créditos-do-projeto)

---

## Em resumo

| | |
| --- | --- |
| **O que é** | Protótipo navegável de um app para mulheres do design digital |
| **Onde ver** | [lunajulia107.github.io/mudi](https://lunajulia107.github.io/mudi/) |
| **Telas** | Onboarding, Feed, Vagas, Mentoria, Comunidade e Perfil |
| **Formato** | App mobile exibido dentro de um mockup de celular |
| **Tecnologias** | HTML, Sass e JavaScript puro |
| **Instalação** | Nenhuma, roda direto no navegador |

---

## 📸 Demonstração

<!-- Quando o GIF estiver pronto, salve em images/demo.gif e descomente a linha abaixo -->
<!-- <img src="./images/demo.gif" alt="Demonstração das funcionalidades da Mudi" width="400px"> -->

🎬 GIF com todas as funcionalidades em breve.

👉 [Visite o protótipo online](https://lunajulia107.github.io/mudi/)

---

## 📌 Sobre o projeto

A Mudi nasceu para ajudar mulheres do design digital a darem os próximos passos na carreira. O protótipo simula a experiência completa do app: do primeiro acesso até a candidatura a uma vaga, passando por mentoria, cursos e conversa com a comunidade.

| Pilar | Como aparece no app |
| --- | --- |
| **Visibilidade** | Feed para compartilhar projetos e perfil com portfólio |
| **Oportunidade** | Vagas de design com detalhes completos e candidatura pelo Mudi |
| **Aprendizado** | Mentoras, sessões de mentoria e cursos |
| **Comunidade** | Canais temáticos e mensagens diretas |

> [!NOTE]
> É um protótipo visual. Pessoas, empresas, vagas e publicações são fictícias e servem só para ilustrar a experiência.

---

## 🚀 Funcionalidades

### 👋 Onboarding e acesso · `index.html`

- Abertura com animação do logo
- Apresentação em 3 telas, com opção de pular
- Login e cadastro em abas, com área de atuação, nível de experiência e cidade
- Opção de continuar com Google ou Apple (visual)

### 📰 Feed · `feed.html`

- Stories das usuárias
- Publicações com carrossel de imagens, curtidas e comentários
- Detalhe do projeto com habilidades e ferramentas
- Nova publicação com tipo, até 5 imagens, título, descrição, habilidades, ferramentas e link
- Carregar mais publicações

### 💼 Vagas · `vagas.html`

- Busca e filtros por área, modelo de trabalho, nível e contrato
- Salvar vagas
- Detalhe da vaga com faixa salarial, sobre a empresa, atividades, requisitos, diferenciais, benefícios, crescimento e processo seletivo
- Contato da recrutadora e candidatura pelo Mudi

### 🎓 Mentoria · `mentoria.html`

- Mentora do mês e outras mentoras, com avaliação e especialidades
- Controle de sessões e cursos usados no mês
- Solicitação de sessão e pedido de orientação para a comunidade
- Cursos em andamento e disponíveis por plano
- Planos **Mudi Pro** e **Mudi Pro+**, com tela de upgrade

### 💬 Comunidade · `chat.html`

- Busca de canais
- Canais temáticos, como `#ui-design`, `#portfólio`, `#vagas`, `#carreira` e `#ia-no-design`
- Mensagens diretas com mentoras e outras usuárias
- Envio de mensagens

### 👩 Perfil · `perfil.html`

- Capa, foto, seguidores e projetos
- Sobre, links em destaque e habilidades (hard skills, soft skills e ferramentas)
- Experiência, formação e voluntariado
- Portfólio e recomendações
- Menu de configurações e plano atual

### 🌗 Em todo o app

- Modo claro e escuro em todas as telas
- Navegação inferior entre Feed, Vagas, Mentoria e Perfil, depois do login
- Modais e avisos rápidos de confirmação

---

## 🛠 Tecnologias utilizadas

| Tecnologia | Para que serve |
| --- | --- |
| **HTML** | Estrutura das telas |
| **Sass** | Estilos organizados em módulos, com design tokens de cor, tipografia e formas |
| **JavaScript** | Interações: onboarding, filtros, modais, curtidas, chat e troca de tema |
| **Google Fonts** | Fonte Poppins |
| **Bootstrap Icons** | Ícones da interface |
| **GitHub Pages** | Publicação do protótipo |

---

## 🎨 Design system

Os estilos ficam em `sass/` e partem de **design tokens** definidos em `_tokens.scss`:

| Token | Exemplos |
| --- | --- |
| Cores da marca | Roxo `#8B53FE`, verde `#8EFF01`, rosa `#EA196B`, amarelo `#FCF52B`, azul `#4A6CF7` |
| Formas | Ações `999px`, cards `16px`, inputs `12px`, superfícies `20px` |
| Tipografia | Poppins |
| Temas | Claro e escuro, trocados pelo atributo `data-theme` |

---

## ⚙️ Como executar o projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/lunajulia107/mudi.git
```

### 2️⃣ Abrir no navegador

Dê dois cliques no arquivo `index.html`. Pronto! 🎉

### 3️⃣ Editar os estilos (opcional)

O CSS final é gerado a partir do Sass. Depois de mudar algum arquivo `.scss`, compile com:

```bash
sass sass/main.scss sass/main.css
```

> [!TIP]
> No VS Code, a extensão **Live Sass Compiler** compila automaticamente toda vez que você salva.

---

## 📁 Estrutura do projeto

```
mudi/
├── index.html        → onboarding, login e cadastro
├── feed.html         → feed de projetos
├── vagas.html        → vagas
├── mentoria.html     → mentoras, cursos e planos
├── chat.html         → comunidade e mensagens
├── perfil.html       → perfil da usuária
├── images/
│   ├── brand/        → logos da Mudi
│   ├── geral/        → imagens de feed, cursos, vagas, perfil e usuárias
│   └── mockup.png    → moldura do celular
└── sass/
    ├── main.scss     → arquivo principal que junta os módulos
    ├── main.css      → CSS compilado usado nas páginas
    ├── _tokens.scss  → design tokens
    └── _*.scss       → componentes e estilos de cada tela
```

---

## 🤝 Créditos do projeto

Desenvolvido por **Julia Rodrigues**.

---

## 📄 Licença

Este projeto está sob a licença **MIT**.
