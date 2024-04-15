Decisão da Arquitetura Utilizada
O projeto utiliza uma arquitetura de cliente-servidor, onde o frontend é desenvolvido em Vue.js e Vuetify para a interface do usuário e o backend é construído com Node.js e Express.js para a lógica de negócios e integração com o banco de dados MySQL.

A escolha dessa arquitetura permite uma separação clara de responsabilidades entre o frontend e o backend, facilitando a manutenção, escalabilidade e reutilização de código. Além disso, o uso do Vue.js no frontend proporciona uma experiência de usuário fluida e responsiva, enquanto o Node.js no backend permite uma implementação rápida e eficiente da API RESTful.

Lista de Bibliotecas de Terceiros Utilizadas
Backend:
bcryptjs: Utilizada para a criptografia de senhas armazenadas no banco de dados.
cors: Middleware utilizado para habilitar o acesso de origens cruzadas (CORS) na API.
dotenv: Utilizada para carregar variáveis de ambiente a partir de um arquivo .env.
express: Framework web utilizado para construir a API RESTful.
jsonwebtoken: Utilizada para gerar e verificar tokens de autenticação JWT.
mysql e mysql2: Drivers de banco de dados MySQL utilizados para se conectar e interagir com o banco de dados.
sequelize: ORM utilizado para mapear objetos JavaScript para modelos de banco de dados e facilitar operações CRUD.
sequelize-cli: Utilizado para criar e gerenciar migrações e seeds no banco de dados.
vuetify: Utilizada para criar uma interface de usuário elegante e responsiva no frontend.
Frontend:
@mdi/js e @mdi/font: Conjunto de ícones Material Design utilizados pelo Vuetify.
axios: Cliente HTTP utilizado para fazer requisições AJAX para o backend.
core-js: Biblioteca de polyfills para garantir compatibilidade com navegadores mais antigos.
vue: Framework JavaScript utilizado para construir a interface de usuário reativa.
vue-router: Utilizado para navegação entre as páginas da aplicação frontend.
vuetify: Framework de componentes Vue.js utilizado para criar uma IU consistente e bonita.
vuex: Utilizado para gerenciamento de estado centralizado na aplicação Vue.js.
O que Melhoraria se Tivesse Mais Tempo
Com mais tempo, algumas melhorias poderiam ser implementadas:

Implementar Testes Mais Abrangentes: Expandir a cobertura de testes automatizados tanto no frontend quanto no backend, Vue Test Utils para garantir a qualidade e estabilidade do código, por priorizar outras partes do código os testes ficaram um pouco rasos passando somente a lógica que deve conter a função.

Melhorar o Design da Interface do Usuário: Refinar o layout e as validações exibidas.

Implementar Cache de Dados: Adicionar uma camada de cache de dados na API backend para reduzir o tempo de resposta e minimizar o impacto em casos de alta carga.

Implementar coluna para criador admin de cada usuário e relacionar as tabelas.

Implementar Logging e Monitoramento: Adicionar logs detalhados e implementar ferramentas de monitoramento para rastrear e diagnosticar problemas em tempo real, garantindo uma operação contínua e confiável do sistema.

Implementar Docker para usar como container.
