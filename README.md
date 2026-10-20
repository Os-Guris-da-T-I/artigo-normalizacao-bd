# Do dado repetido ao banco organizado — 1FN à Desnormalização

Artigo técnico acadêmico sobre normalização de banco de dados (da primeira à quinta forma normal) e desnormalização controlada, escrito com uma abordagem introdutória e acessível, acompanhado de exemplos práticos em PostgreSQL, vídeos educacionais selecionados e suporte a modo escuro/claro.

## 👥 Autores
- João Victor Guimarães Gomes
- Matheus Augusto Antunes Pentogennis
- Gustavo Gabriel Naves Ferreira
- Lucas Siqueira Teles
- Lucas da Graça Leandro
- Gabriel Gonçalves Lima

*(Revisado em: 20/10/2026)*

## 🌐 Página Publicada e Repositório
- **URL pública (Deploy):** (https://os-guris-da-t-i.github.io/artigo-normalizacao-bd/)
- **Repositório GitHub:** [os-guris-da-t-i/artigo-normalizacao-bd](https://github.com/os-guris-da-t-i/artigo-normalizacao-bd)

## 📂 Estrutura do Projeto
- `index.html`: Arquivo principal contendo todo o conteúdo estruturado do artigo e o botão interativo de alternância de temas (Dark/Light Mode).
- `estilos/style.css`: Folha de estilos moderna inspirada no ecossistema GennisCode, totalmente responsiva, com suporte a acessibilidade e animações suaves de transição.
- `imagens/normalizacao.svg`: Diagrama vetorial original de alto contraste, otimizado para computadores e dispositivos móveis.
- `sql/`: Pasta reservada para os scripts DDL e DML com exemplos e consultas utilizando dados puramente fictícios.
- `ROTEIRO_5_MINUTOS.md`: Roteiro cronometrado para a apresentação presencial da equipe em 6 integrantes.

## ⚙️ Como Executar os Scripts SQL Localmente
1. Certifique-se de possuir o **PostgreSQL (versão 15 ou superior)** e uma ferramenta de gerenciamento (como o *pgAdmin 4*) instalados.
2. Crie um **banco de dados de testes totalmente vazio** (nunca execute scripts de exemplo em ambientes de produção ou com dados reais).
3. Abra a ferramenta de consulta (*Query Tool*), cole ou abra os scripts da pasta `sql/` e execute os comandos para visualizar a criação das tabelas e as consultas com `JOIN`.

## 🚀 Como Publicar no GitHub Pages
1. Crie um repositório público no GitHub contendo todos os arquivos organizados nas pastas descritas acima.
2. Acesse a aba **Settings** do repositório e clique em **Pages**.
3. Na seção *Build and deployment*, escolha a opção **Deploy from a branch**.
4. Selecione a branch `main` e a pasta raiz (`/ (root)`), em seguida clique em **Save**.
5. Aguarde alguns instantes, copie a URL gerada e teste-a diretamente em outro dispositivo ou no navegador do seu telemóvel.

## 🧠 Decisões do Grupo
1. **Recorte do tema:** Escolhemos utilizar um cenário prático e intuitivo de perguntas de um *quiz* tecnológico para ilustrar as redundâncias de dados e anomalias.
2. **Formato do artigo:** Consolidamos todo o conteúdo em uma única página fluida, rica em títulos bem estruturados, tabelas comparativas e pílulas de conhecimento em vídeo incorporadas de forma segura.
3. **Padrão tecnológico e UI/UX:** Adotamos o PostgreSQL como SGBD padrão e implementamos um design de interface moderno em página única com transição dinâmica entre modos de cor (claro/escuro).
4. **O que decidimos não fazer:** Optamos por não aprofundar implementações complexas da 5FN com exemplos extensos devido à sua raridade em cenários cotidianos, focando o núcleo prático até a BCNF e a desnormalização analítica.

## 🛡️ Privacidade, Autoria e Isenção de Responsabilidade
> **Aviso importante:** Todos os dados, nomes de empresas, produtos e registros utilizados nos códigos SQL e nas tabelas deste projeto são puramente fictícios e de uso exclusivamente acadêmico, não representando nenhuma entidade ou pessoa real. De acordo com as diretrizes de privacidade, **nenhum** telefone, e-mail pessoal, endereço residencial ou perfil privado é divulgado neste repositório. As opiniões, escolhas técnicas e análises expressas no artigo pertencem exclusivamente aos autores.

## 📚 Referências Consultadas
- CODD, E. F. A relational model of data for large shared data banks. *Communications of the ACM*, v. 13, n. 6, 1970.
- FAGIN, R. Multivalued dependencies and a new normal form for relational databases. *ACM Transactions on Database Systems*, v. 2, n. 3, 1977.
- PostgreSQL Global Development Group. [PostgreSQL Documentation: DDL Constraints](https://www.postgresql.org/docs/current/ddl-constraints.html).
- PostgreSQL Global Development Group. [PostgreSQL Documentation: Materialized Views](https://www.postgresql.org/docs/current/rules-materializedviews.html).

## 📊 Métricas de Desempenho (Lighthouse / PageSpeed Insights)
- **Desempenho:** Otimizado para carregamento instantâneo e leveza de ativos estáticos.
- **Acessibilidade:** Alto contraste garantido em componentes textuais e vetoriais (SVG).
- **Boas Práticas:** Uso de HTML5 semântico e CSS moderno modular.
- **SEO:** Metadados estruturados para indexação correta da página acadêmica.
