[README.md](https://github.com/user-attachments/files/26258398/README.md)
# 🎓 Revisão 5º Ano

Plataforma interativa de quizzes e revisão de conteúdos do 5º Ano do Ensino Fundamental do Colégio Santa Catarina de Sena, Belém/PA.

🔗 **URL pública:** https://hesketh-lucas.github.io/quiz-5ano

---

## 💡 Como surgiu

Este projeto nasceu de um pai que queria ajudar a filha a estudar de uma maneira mais leve e criativa — e que esse esforço pudesse também alcançar as amigas dela. O que começou como uma ferramenta para uma criança acabou se tornando uma plataforma aberta para qualquer aluno do 5º Ano.

---

## 📚 Matérias e quizzes disponíveis (AC2 — 1º Bimestre)

| Matéria | Quizzes | Status |
|---|---|---|
| 📖 História | Unidade 1 (15q) + Unidade 2 (11q) | ✅ Disponível |
| 🌍 Geografia | Cap. 1 (15q) + Cap. 3 (15q) | ✅ Disponível |
| ✏️ Língua Portuguesa | Cap. 1 (15q) + Cap. 2 (15q) | ✅ Disponível |
| 🔢 Matemática | Cap. 2 — Adição/Subtração (15q) + Cap. 3 — Multiplicação/Divisão (15q) | ✅ Disponível |
| 🔬 Ciências | Cap. 1 (15q) + Cap. 2 (15q) + Cap. 3 (15q) | ✅ Disponível |

> Os quizzes de Matemática têm 3 questões-problema ao final com **5 minutos** de tempo cada.

---

## 🗂️ Funcionalidades

- **Modo Quiz** — escolha AC → matéria → capítulo → responda com cronômetro
- **Modo Estudar** — resumos, chips de palavras-chave, mapas mentais e dicas por capítulo
- **Placar Global** — compartilhado entre todos os usuários em tempo real (via Firebase)
- **Histórico Pessoal** — últimas 3 tentativas por quiz, salvas no aparelho
- **Agenda Escolar** — eventos do calendário letivo 2026 com filtros por categoria
- **Conteúdo Programático** — roteiro completo por matéria e capítulo
- **Compartilhar resultado** — via WhatsApp ou copiar texto

---

## 📖 Livros de referência

| Matéria | Livro | Editora |
|---|---|---|
| História | Ligamundo | Saraiva |
| Geografia | Aprender Juntos | SM |
| Língua Portuguesa | Projeto Presente | Moderna |
| Matemática | Aprender Juntos | SM |
| Ciências | Buriti Mais Ciências | Moderna |

---

## 🛠️ Tecnologia

- **Frontend:** HTML + CSS + JavaScript puro — tudo em um único arquivo `index.html`
- **Hospedagem:** GitHub Pages (gratuito)
- **Banco de dados (placar global):** Serviço de banco de dados em tempo real na nuvem (Google)
- **Armazenamento local:** localStorage do browser (histórico pessoal de cada jogador)
- **Analytics:** Google Analytics 4

> O banco de dados na nuvem permite que o placar seja compartilhado entre todos os dispositivos em tempo real. O histórico pessoal continua salvo apenas no aparelho de cada jogador.

---

## ⚙️ Painel Administrativo

Acesso oculto — **5 cliques no ícone 🎓** da tela inicial.

Opções disponíveis:
- Zerar placar geral
- Zerar tudo (placar + históricos)
- Zerar contadores de visitas/quizzes

---

## 📊 Analytics e Monitoramento

- **Google Analytics 4** — rastreia visitas, quizzes iniciados e concluídos, matérias acessadas e compartilhamentos
- **Firebase Console** — mostra o placar em tempo real em `Realtime Database → Dados → placar`
- **Barra de stats na home** — exibe visitas, quizzes feitos e matéria mais acessada

---

## 🔒 Segurança do banco de dados

As regras do banco permitem leitura e escrita pública apenas no nó `/placar`, sem expiração.
Não há dados sensíveis armazenados — apenas apelidos e pontuações dos quizzes.

---

## 🗓️ Próximos passos pendentes

- [ ] Desbloquear AC3 e AC4 quando houver material
- [ ] Adicionar quizzes dos bimestres seguintes conforme calendário escolar
- [ ] Avaliar PWA (app instalável) para acesso offline

---

## 📅 Calendário de avaliações — 1º Bimestre 2026

| Data | Disciplina | Avaliação |
|---|---|---|
| 23/02 | História | AC1 |
| 24/02 | Geografia | AC1 |
| 25/02 | Língua Portuguesa | AC1 |
| 26/02 | Ciências | AC1 |
| 27/02 | Matemática | AC1 |
| 20/03 | Língua Inglesa | AC2 |
| 23/03 | História | AC2 |
| 24/03 | Geografia | AC2 |
| 25/03 | Língua Portuguesa | AC2 |
| 26/03 | Ciências | AC2 |
| 27/03 | Matemática | AC2 |

---

Feito com 💚 por **Lucas Hesketh** · Colégio Santa Catarina de Sena · Belém/PA
