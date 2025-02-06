# Consulta de Usuários GitHub

Este projeto tem como objetivo fornecer uma interface simples e eficiente para consultar e exibir informações de usuários do GitHub, como repositórios, estatísticas e perfis. Ele foi construído utilizando **React**, **JavaScript (ES6+)**, **HTML**, **CSS** e outras tecnologias modernas.

## Funcionalidades

- **Consulta de Usuários GitHub**: O usuário pode inserir o nome de um usuário GitHub e consultar informações sobre ele.
- **Exibição de Dados**: Exibe dados como o nome, bio, número de repositórios, seguidores e outros detalhes do perfil.
- **Listagem de Repositórios**: Lista os repositórios públicos do usuário consultado.
- **Estatísticas do Usuário**: Exibe estatísticas básicas como número de seguidores, repositórios e contribuições.

## Tecnologias Utilizadas

- **Front-end**: 
  - React
  - JavaScript (ES6+)
  - HTML
  - CSS (Flexbox, Grid)
  
- **Estilização**: 
  - CSS
  - TailwindCSS
  - Styled Components
  
- **Controle de Versão**: 
  - Git
  - GitHub
  
- **Consumo de APIs**: 
  - Axios (para consumo da API pública do GitHub)

## Como Rodar o Projeto

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/Cesar-AMS/Consulta-de-Usuarios-GitHub.git





**Consulta-de-Usuarios-GitHub/
├── public/
│   ├── index.html          # Arquivo HTML principal
│   ├── favicon.ico         # Ícone da aplicação
│   └── manifest.json       # Informações sobre o app, como ícones e temas
├── src/
│   ├── assets/             # Imagens, fontes e outros recursos estáticos
│   ├── components/         # Componentes reutilizáveis da aplicação
│   │   ├── Header.js       # Componente do cabeçalho
│   │   ├── UserProfile.js  # Componente para exibir as informações do usuário
│   │   ├── RepoList.js     # Componente para listar os repositórios
│   │   └── Stats.js        # Componente para exibir as estatísticas do usuário
│   ├── services/           # Arquivo para integrar com APIs externas
│   │   └── githubApi.js    # Funções para fazer chamadas para a API do GitHub
│   ├── App.js              # Componente principal da aplicação
│   ├── index.js            # Ponto de entrada do React
│   ├── App.css             # Estilos globais da aplicação
│   └── index.css           # Estilos globais da aplicação
├── .gitignore              # Arquivo que define o que deve ser ignorado pelo git
├── package.json            # Definições do projeto, dependências e scripts
├── README.md               # Documentação do projeto
└── package-lock.json       # Registro das dependências do projeto
**