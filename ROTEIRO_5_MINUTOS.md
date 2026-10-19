# ⏱️ Roteiro de Apresentação — 5 Minutos (6 Integrantes)

> **Regra de Ouro:** Abertura do site ao vivo no navegador em tela cheia (`F11`) antes de iniciar. A navegação deve acompanhar a fala de cada integrante.

---

### 1. Abertura, Identidade & Contexto (0:00 – 0:50) — **João Victor**
* **Ação na tela:** Manter no topo da página (*Hero Section*), destacando a marca **"Os Guri da T.I."** e o título principal.
* **Falar:**
  > *"Olá, professor e colegas! Nós somos 'Os Guri da T.I.', grupo formado por mim, pelo Gustavo, Lucas Siqueira, Matheus, Lucas Leandro e Gabriel. Hoje apresentamos nosso artigo técnico 'Do dado repetido ao banco organizado'. Nosso objetivo foi unir o rigor acadêmico exigido em Banco de Dados a uma navegação fluida em página única, demonstrando a evolução das Formas Normais até o código SQL prático."*

---

### 2. O Problema e as Anomalias (0:50 – 1:40) — **Gustavo Gabriel**
* **Ação na tela:** Rolar até a **Seção 01 (O Problema)**, passando o cursor pela **Tabela Desnormalizada** e pelos cartões de anomalias.
* **Falar:**
  > *"Para ilustrar o problema real, utilizamos o domínio de um Quiz de Tecnologia. Em uma tabela única e desnormalizada, dados de categorias e fontes se repetem em cada linha. Essa redundância gera três anomalias graves: a de Inserção, quando não podemos cadastrar uma fonte sem uma pergunta; a de Alteração, onde mudar um nome exige atualizar dezenas de linhas; e a de Exclusão, onde apagar uma pergunta apaga também a fonte."*

---

### 3. As Decisões de Projeto do Grupo (1:40 – 2:20) — **Lucas Siqueira**
* **Ação na tela:** Rolar levemente até a **Seção 05 (Decisões Acadêmicas)** do artigo.
* **Falar:**
  > *"Com base nisso, tomamos três decisões técnicas principais: 
  > 1. Adotar o modelo de Quiz por ser didático e prático; 
  > 2. Desenvolver o projeto em arquitetura single-page responsiva com tema escuro/claro e links de apoio; 
  > 3. Implementar a estrutura em PostgreSQL 15 com restrições rígidas. 
  > Como decisão do que não fazer, optamos por tratar a 5FN apenas na teoria, por ser um cenário atípico no cotidiano do desenvolvimento."*

---

### 4. A Solução: 1FN à 3FN e o Diagrama (2:20 – 3:10) — **Matheus Augusto**
* **Ação na tela:** Rolar até a **Seção 02 (Formas Normais)**, destacando a **Figura 1 (Diagrama do Fluxo de Normalização)**.
* **Falar:**
  > *"Para eliminar as anomalias, aplicamos o processo de normalização: a 1FN garante que cada célula contenha valores atômicos; a 2FN remove dependências parciais da chave primária; e a 3FN elimina dependências transitivas. Criamos este diagrama original que resume a decomposição do banco em tabelas independentes de `perguntas`, `categorias` e `fontes` conectadas por chaves estrangeiras."*

---

### 5. Código SQL Prático & Desnormalização (3:10 – 4:10) — **Lucas da Graça**
* **Ação na tela:** Rolar para a **Seção 06 (SQL na Prática)** destacando o código `CREATE TABLE` e o `JOIN`, e passar rapidamente pela **Seção 04 (Materialized Views)**.
* **Falar:**
  > *"Traduzimos essa modelagem em scripts PostgreSQL reais. Como podem ver no código, isolamos as colunas e estabelecemos a integridade referencial com `FOREIGN KEY`. E quando precisamos consultar os dados consolidados, usamos o operador `JOIN`. Também abordamos a Desnormalização com Visões Materializadas, técnica usada para acelerar consultas analíticas sem comprometer a estrutura do banco."*

---

### 6. Autoria, Privacidade e Deploy (4:10 – 5:00) — **Gabriel Gonçalves**
* **Ação na tela:** Rolar até o **Rodapé**, mostrando a grade com os **6 Cartões de Autores** (com fotos, bios e links).
* **Falar:**
  > *"Por fim, publicamos nossa aplicação no GitHub Pages com HTTPS ativo e total responsividade móvel. Cumprimos 100% dos requisitos de privacidade e autoria com fotos, mini-bios e links profissionais públicos do GitHub e LinkedIn de todos os seis membros. Agradecemos pela atenção e estamos abertos a dúvidas!"*

---

## 🛑 Checklist do Grupo para o Dia da Apresentação
- [x] Fotos de todos os 6 integrantes com uploads concluídos na pasta `imagens/autores/`.
- [ ] Testar o link final do GitHub Pages no celular e no computador da apresentação.
- [ ] Treinar a passagem da fala com um cronômetro na mão (cada pessoa fala entre 45 e 50 segundos).
- [ ] Deixar a aba do artigo aberta em tela cheia (`F11`) antes de ser chamado.
