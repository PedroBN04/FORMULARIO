# Formulário e Perfil de Usuário

Este projeto consiste em um sistema de cadastro e exibição de perfil de usuário, desenvolvido utilizando **HTML, CSS e JavaScript**. Ele permite que o usuário preencha um formulário com suas informações pessoais, valide os dados e visualize o perfil na página seguinte.

## Tecnologias Utilizadas
- **HTML5**: Estrutura das páginas.
- **CSS3**: Estilização, responsividade e temas claro/escuro.
- **JavaScript (ES6+)**: Manipulação do DOM, validação de formulário e armazenamento de dados no sessionStorage.

## Funcionalidades
- **Cadastro de usuário**: Nome, e-mail e idade são inseridos e validados.
- **Validação dinâmica**: Campos obrigatórios e regras para preenchimento correto.
- **Armazenamento temporário**: Dados mantidos enquanto a sessão está ativa.
- **Exibição de perfil**: Dados cadastrados são carregados automaticamente.
- **Modo claro/escuro**: Alternância de tema para melhor experiência do usuário.
- **Redirecionamento automático**: Se não houver dados no sessionStorage, o usuário é redirecionado ao formulário.
- **Botão de sair**: Permite limpar os dados da sessão e retornar ao formulário.

## Estrutura do Projeto
```
/
├── index.html        # Página do formulário
├── perfil.html       # Página do perfil do usuário
├── css/
│   ├── design.css    # Estilização do formulário
│   ├── user.css      # Estilização da página de perfil
├── js/
│   ├── test.js       # Validação do formulário e armazenamento dos dados
│   ├── usuario.js    # Carregamento e exibição dos dados do perfil
├── img/              # Pasta para imagens
└── README.md         # Documentação do projeto
```

## Como Executar o Projeto
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd nome-do-repositorio
   ```
3. Abra o arquivo `index.html` no navegador.

## Melhorias Futuras
- Implementação de armazenamento persistente com LocalStorage ou banco de dados.
- Adição de um sistema de autenticação com login e senha.
- Melhoria na acessibilidade e suporte para dispositivos móveis.

## Autor
**Pedro Humberto Bitencourt Nascimento**
- [GitHub](https://github.com/seu-usuario)
- [LinkedIn](https://www.linkedin.com/in/seu-perfil)

## Licença
Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

