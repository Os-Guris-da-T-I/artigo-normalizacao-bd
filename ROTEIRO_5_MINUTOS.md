# ⏱️ Roteiro de Apresentação — 5 Minutos (6 Integrantes)

**Regra de ouro:** Tenham a página publicada aberta ao vivo no navegador antes de começar. Como são 6 pessoas, cada uma deve falar de forma direta, clara e com o cronômetro treinado.

---

## 🕒 1. Abertura e Tema (0:00 – 0:50) — Integrante 1

* **O que falar:**
  > "Olá, professor e colegas! O nosso grupo apresenta o artigo 'Do dado repetido ao banco organizado'. O foco do trabalho foi mostrar como estruturar um banco de dados relacional, passando pelas formas normais e entendendo o impacto da redundância. Somos formados por [Nome do Integrante 1], [Nome do Integrante 2], [Nome do Integrante 3], [Nome do Integrante 4], [Nome do Integrante 5] e [Nome do Integrante 6]."

---

## 🕒 2. O Problema e as Anomalias (0:50 – 1:40) — Integrante 2

* **O que falar:**
  > "Para ilustrar o problema, usamos um cenário prático de perguntas de um quiz. Em uma tabela única e desnormalizada, dados de categorias e fontes se repetem a cada linha. Isso gera três grandes problemas conhecidos: as anomalias de atualização, inserção e exclusão, onde uma alteração simples em um dado duplicado pode corromper a consistência do sistema."

---

## 🕒 3. As Decisões do Grupo (1:40 – 2:20) — Integrante 3

* **O que falar:**
  > "Tomamos três decisões principais no projeto:
  > 1. Focar em um exemplo lúdico de quiz, facilitando a visualização técnica;
  > 2. Desenvolver um artigo em página única, com design moderno inspirado no ecossistema GennisCode, incluindo suporte a alternância de tema (modo escuro e claro) para total acessibilidade visual;
  > 3. Utilizar scripts em PostgreSQL focando em integridade referencial. Como o que escolhemos não fazer, optamos por não nos estender na 5FN por ser um cenário raro na prática cotidiana."

---

## 🕒 4. A Solução e a Figura (2:20 – 3:10) — Integrante 4

* *Ação: Mostrar brevemente o diagrama na tela*
* **O que falar:**
  > "Para resolver as anomalias, aplicamos a normalização dividindo as informações em tabelas independentes ligadas por chaves estrangeiras. Criamos um diagrama vetorial original e otimizado para acessibilidade que resume visualmente essa evolução: a 1FN garante valores atômicos, a 2FN remove dependências parciais e a 3FN elimina dependências transitivas."

---

## 🕒 5. O Código SQL e a Consulta (3:10 – 4:10) — Integrante 5

* *Ação: Mostrar rapidamente o trecho de código SQL ou a tabela na página*
* **O que falar:**
  > "Mostrando a página ao vivo, aqui no nosso código SQL na seção prática, a tabela de perguntas aponta para categorias e fontes usando chaves estrangeiras. Quando precisamos exibir os dados reunidos, utilizamos o comando JOIN. A normalização não esconde a informação; ela a organiza de forma segura e inteligente para o banco de dados."

---

## 🕒 6. O Deploy e Fechamento (4:10 – 5:00) — Integrante 6

* **O que falar:**
  > "Por fim, realizamos o deploy da nossa página pública utilizando o GitHub Pages, garantindo compatibilidade, responsividade e navegação fluida. O projeto cumpre rigorosamente todas as normas de privacidade, autoria e dados acadêmicos fictícios. Agradecemos muito a atenção de todos e abrimos para perguntas!"
---

## 🛑 Checklist Prático para a Equipe
- [ ] Substituir os nomes dos 6 integrantes nos locais indicados.
- [ ] Garantir que o repositório público do GitHub e o GitHub Pages estejam funcionando.
- [ ] Ensaiar com o cronômetro para que cada um fale exatamente por cerca de 45 a 50 segundos.
- [ ] Verificar se todos os 6 integrantes possuem commits próprios registrados no histórico do repositório.
