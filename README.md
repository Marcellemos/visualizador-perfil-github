# 🔍 Visualizador de Perfil do GitHub

Uma aplicação web simples e elegante que permite aos usuários pesquisar e visualizar informações detalhadas de perfis do GitHub, utilizando a API oficial da plataforma.

## 🚀 Funcionalidades

- **Busca Dinâmica:** Encontre qualquer usuário do GitHub apenas digitando o seu login.
- **Informações do Perfil:** Visualização de avatar, nome, biografia e contadores de seguidores e seguindo.
- **Listagem de Repositórios:** Exibe os 10 repositórios mais recentes do usuário.
- **Detalhes dos Repositórios:** Informações sobre estrelas, forks, visualizações (watchers) e linguagem principal de cada repositório.
- **Design Responsivo:** Interface adaptável para diferentes tamanhos de tela (desktop, tablet e mobile).
- **Interatividade:** Feedback de carregamento e tratamento de erros (usuário não encontrado).

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica do conteúdo.
- **CSS3:** Estilização moderna com foco em responsividade e animações.
- **JavaScript (ES6+):** Lógica da aplicação utilizando Módulos, Fetch API e manipulação assíncrona.
- **GitHub API:** Consumo de dados reais da plataforma.
- **DevIcons:** Ícones estilizados para a interface.

## 📁 Estrutura do Projeto

```text
├── index.html          # Ponto de entrada da aplicação
└── src/
    ├── css/            # Estilos organizados por módulos
    │   ├── animations.css
    │   ├── reset.css
    │   ├── responsive.css
    │   └── styles.css
    └── js/             # Lógica da aplicação
        ├── githubApi.js   # Comunicação com a API
        ├── index.js       # Orquestração e eventos
        └── profileView.js # Renderização dos dados na tela
```

## 💻 Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/visualizador-perfil-github.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd visualizador-perfil-github
   ```
3. Abra o arquivo `index.html` no seu navegador de preferência ou utilize uma extensão como a **Live Server** no VS Code.

## 👤 Autor

Desenvolvido por **Marcel Melo**.

---
Projeto desenvolvido como parte do aprendizado de consumo de APIs e manipulação do DOM.
