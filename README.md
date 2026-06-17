# 📚 Atena - IA Especialista em Escrita de Livros

Atena é uma IA avançada especializada em escrita de livros para públicos adolescente e jovem adulto. Ela "fura a bolha" de criatividade, desenvolve capítulos automaticamente, aprende sobre seus personagens e mantém todo o histórico da sua obra.

## ✨ Features

- 🤖 IA especialista em escrita adolescente/YA
- 📖 Desenvolvimento automático de capítulos
- 💾 Armazenamento de conversas anteriores
- 📝 Sistema de rascunhos com edição e exclusão
- ⭐ Fixar rascunho como versão final do capítulo
- ✏️ Editar versões finais
- 👥 Especialização em personagens (conhece melhor que ninguém)
- 🎵 Integração Spotify (música para inspiração)
- 🎨 Interface moderna com abas (Conversa, Rascunhos, Versões Finais)
- 🪟 Atena em aba separada

## 🛠️ Tech Stack

### Backend
- Node.js + Express + TypeScript
- OpenAI/Anthropic API
- MongoDB
- JWT (autenticação)

### Frontend
- React 18+ + TypeScript
- Tailwind CSS
- Axios
- React Router

## 🚀 Como Começar

### Backend
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm start
```

### Com Docker
```bash
docker-compose up
```

## 📝 Features Detalhadas

### 1. Chat com Atena
Conversa contínua armazenada para referência futura. Atena aprende o contexto do seu livro e personagens.

### 2. Editor de Capítulos
- Múltiplos rascunhos por capítulo
- Versão final fixada
- Edição de versões finais
- Apagar rascunhos

### 3. Gerenciador de Personagens
- Armazenar personalidade, backstory, motivações
- Relacionamentos entre personagens
- Atena aprende e referencia automaticamente

### 4. Integração Spotify
- Conectar conta do Spotify
- Criar playlists por capítulo/mood
- Sugestões de música por scene

## 📖 Roadmap

- [ ] Sistema de análise de sentimentos dos capítulos
- [ ] Sugestões de plottwist automáticas
- [ ] Integração com Google Drive para backup
- [ ] Sistema de feedback da comunidade
- [ ] Geração de covers
- [ ] Exportação em múltiplos formatos (PDF, EPUB, etc)
- [ ] Modo colaborativo (múltiplos autores)

## 🔐 Variáveis de Ambiente

Veja `.env.example` em `backend/` para mais detalhes.

```
OPENAI_API_KEY=
MONGODB_URI=
JWT_SECRET=
SPOTIFY_CLIENT_ID=
SPOTIFY_CLIENT_SECRET=
```

## 📞 Suporte

Encontrou um bug? Abra uma [issue](https://github.com/Ella-projectss/atena-book-ai/issues)!

---

Feito com ❤️ para escritores criadores de histórias incríveis
