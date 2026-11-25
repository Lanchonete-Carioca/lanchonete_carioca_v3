### LANCHONETE CARIOCA



## 🤝 Como Contribuir


A Lanchonete Carioca utiliza um fluxo baseado em GitHub Issues, Pull Requests e revisões de código para garantir qualidade e rastreabilidade.

### Fluxo de Desenvolvimento

1. Crie ou selecione uma Issue existente.
2. Crie uma branch a partir da `main`.
3. Desenvolva a funcionalidade ou correção.
4. Execute os testes disponíveis.
5. Abra um Pull Request vinculado à Issue.
6. Realize a revisão do código.
7. Faça o merge após aprovação.

### Nomeação de Branches

Utilize os seguintes padrões:

```text
feature/nome-da-funcionalidade
fix/nome-da-correcao
refactor/nome-da-melhoria

Exemplos:
feature/products-api
feature/login-jwt
fix/cart-mobile
refactor/products-service

Padrão de Commits

Seguimos o padrão Conventional Commits:

Plain Text
feat: nova funcionalidade
fix: correção de erro
refactor: melhoria interna
test: criação ou ajuste de testes
docs: atualização de documentação

Exemplos:

Plain Text
feat: adiciona rota GET /api/products
fix: corrige cálculo do carrinho
refactor: reorganiza estrutura do backend
Vinculando Issues

Sempre relacione o Pull Request à Issue correspondente:

Plain Text
Closes #20
Fixes #21
Resolves #22

O GitHub fechará a Issue automaticamente após o merge.

Requisitos para Aprovação
Código sem erros de lint
Testes executando com sucesso
Funcionalidade validada manualmente
Documentação atualizada quando necessário
Estrutura do Projeto

Frontend:

React
Vite
React Router

Backend:

Node.js
Express
JWT Authentication
Jest e Supertest
Versionamento

O projeto segue o planejamento por versões:

v2.5.x → Frontend e experiência do usuário
v2.6.0 → Backend REST API e autenticação JWT
v2.7.0 → Pedidos e persistência de dados

Essa seção deixa claro para qualquer colaborador, inclusive o GitHub Copilot, qual é o processo oficial do projeto **Lanchonete Carioca**. Ela também combina bem com seu roadmap atual da versão **2.6.0 (Produtos, Usuários, JWT, Testes e Integração Frontend ↔ Backend)**.

Onde a comunidade procura primeiro?

Normalmente nesta ordem:

README.md ⭐ (principal porta de entrada)
Wiki do GitHub (se você habilitar)
Docs/ dentro do repositório
Plain Text
docs/
├── roadmap.md
├── backend-api.md
├── frontend.md
└── release-notes.md
GitHub Projects
Issues e Discussions
Estrutura recomendada para seu projeto
Plain Text
app_lanchonete_v3/
│
├── README.md
├── CONTRIBUTING.md
├── CHANGELOG.md
│
├── docs/
│ ├── roadmap.md
│ ├── arquitetura.md
│ ├── backend-api.md
│ └── releases/
│
└── .github/
├── copilot-instructions.md
└── pull_request_template.md

Assim, quando alguém entrar no seu repositório, o README aponta para toda a documentação e a comunidade consegue encontrar facilmente o roadmap, as regras de contribuição e o planejamento das versões da Lanchonete Carioca.

☕ Curiosidades
O que a equipe come no café da manhã?
Café carioca bem forte ☕
Pão na chapa 🥖
Biscoito Globo 🏖️
Suco natural 🍊
E, claro, muito código antes do almoço!

😄 Fun Facts
O projeto nasceu para simular o funcionamento de uma lanchonete moderna.
A inspiração veio das tradicionais lanchonetes do Rio de Janeiro.
Boa parte do desenvolvimento foi realizada com apoio do GitHub Copilot.
Café é considerado uma dependência crítica do projeto ☕.

⚡ Sinta o Poder do Markdown
O README da Lanchonete Carioca utiliza Markdown para tornar a documentação mais organizada e agradável de ler.

Texto
Negrito

Itálico

Riscado

Lista de Tarefas
Frontend React
Catálogo de Produtos
API REST
Autenticação JWT
Integração Completa
Código
const pedido = {
  cliente: "Maria",
  item: "X-Burger",
  quantidade: 2
};

console.log(pedido);
Tabela
Recurso	Status
Frontend	✅
Backend	🚧
JWT	🚧
Testes	🚧
Citação
"Uma boa documentação vale tanto quanto um bom código."

Links
https://github.com/Regina1973/app_lanchonete_v3/issues
https://github.com/Regina1973/app_lanchonete_v3/pulls
Emojis
🍔 🌭 🥤 🍟 ☕ 🚀

Obrigado por visitar a Lanchonete Carioca!
