# Do dado repetido ao banco organizado — 1FN à Desnormalização

Artigo técnico acadêmico sobre normalização de banco de dados (da primeira à quinta forma normal) e desnormalização controlada, escrito com uma abordagem introdutória e acessível, acompanhado de exemplos práticos em PostgreSQL e vídeos educacionais selecionados.

## 👥 Autores
- João Victor Guimarães Gomes
- Matheus Augusto Antunes Pentogennis
- Gustavo Gabriel Naves Ferreira
- Lucas Siqueira Teles
- Lucas da Graça Leandro
- Gabriel Gonçalves Lima

*(Revisado em: 16/10/2026)*

## 🌐 Página Publicada e Repositório
- **URL pública (Deploy):** [Inserir link do GitHub Pages após ativar]
- **Repositório GitHub:** [Inserir link do repositório público]

## 📂 Estrutura do Projeto
- `index.html`: Arquivo principal contendo todo o conteúdo estruturado do artigo.
- `estilos/style.css`: Folha de estilos moderna, limpa, totalmente responsiva e acessível (altamente legível para todos os públicos).
- `imagens/normalizacao.svg`: Diagrama vetorial original criado especificamente para ilustrar as etapas de normalização.
- `sql/`: Pasta reservada para os scripts DDL e DML com exemplos e consultas utilizando dados puramente fictícios.
- `ROTEIRO_5_MINUTOS.md`: Roteiro cronometrado para a apresentação presencial da equipe.

## ⚙️ Como Executar os Scripts SQL Localmente
1. Certifique-se de possuir o **PostgreSQL (versão 15 ou superior)** e uma ferramenta de gerenciamento (como o *pgAdmin 4*) instalados.
2. Crie um **banco de dados de testes totalmente vazio** (nunca execute scripts de exemplo em ambientes de produção ou com dados reais).
3. Abra a ferramenta de consulta (*Query Tool*), cole ou abra os scripts da pasta `sql/` e execute os comandos para visualizar a criação das tabelas e as consultas com `JOIN`.

## 🚀 Como Publicar no GitHub Pages
1. Crie um repositório público no GitHub contendo todos os arquivos organizados nas pastas descritas acima.
2. Acesse a aba **Settings** do repositório e clique em **Pages**.
3. Na seção *Build and deployment*, escolha a opção **Deploy from a branch**.
4. Selecione a branch `main` e a pasta raiz (`/ (root)`), em seguida clique em **Save**.
5. Aguarde alguns instantes, copie a URL gerada e teste-a diretamente em outro dispositivo ou no navegador do seu celular.

## 🧠 Decisões do Grupo
1. **Recorte do tema:** Escolhemos utilizar um cenário prático e intuitivo de perguntas de um *quiz* tecnológico para ilustrar as redundâncias de dados e anomalias.
2. **Formato do artigo:** Consolidamos todo o conteúdo em uma única página fluida, rica em títulos bem estruturados, tabelas comparativas e pílulas de conhecimento em vídeo incorporadas de forma segura.
3. **Padrão tecnológico:** Adotamos o PostgreSQL como SGBD padrão para demonstrar o uso correto de chaves primárias e estrangeiras.
4. **O que decidimos não fazer:** Optamos por não aprofundar implementações complexas da 5FN com exemplos extensos devido à sua raridade em cenários cotidianos, focando o núcleo prático até a BCNF e a desnormalização analítica.

## 🛡️ Privacidade, Autoria e Isenção de Responsabilidade
> **Aviso importante:** Todos os dados, nomes de empresas, produtos e registros utilizados nos códigos SQL e nas tabelas deste projeto são puramente fictícios e de uso exclusivamente acadêmico, não representando nenhuma entidade ou pessoa real. De acordo com as diretrizes de privacidade, **nenhum** telefone, e-mail pessoal, endereço residencial ou perfil privado é divulgado neste repositório. As opiniões, escolhas técnicas e análises expressas no artigo pertencem exclusivamente aos autores.

## 📚 Referências Consultadas
- CODD, E. F. A relational model of data for large shared data banks. *Communications of the ACM*, v. 13, n. 6, 1970.
- FAGIN, R. Multivalued dependencies and a new normal form for relational databases. *ACM Transactions on Database Systems*, v. 2, n. 3, 1977.
- PostgreSQL Global Development Group. [PostgreSQL Documentation: DDL Constraints](https://www.postgresql.org/docs/current/ddl-constraints.html).
- PostgreSQL Global Development Group. [PostgreSQL Documentation: Materialized Views](https://www.postgresql.org/docs/current/rules-materializedviews.html).

## 📊 Métricas de Desempenho (Lighthouse / PageSpeed Insights)
*(Preencha os dados abaixo somente após rodar a auditoria técnica na página publicada)*
- **Desempenho:** [preencher após auditoria]
- **Acessibilidade:** [preencher após auditoria]
- **Boas Práticas:** [preencher após auditoria]
- **SEO:** [preencher após auditoria]