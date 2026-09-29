# LIRA NOTES

MVP de notas do Grupo Lira, inspirado na experiência do Apple/iCloud Notas.

## MVP

- Navegação em três colunas: pastas → notas → conteúdo completo
- Login por Magic Link via Supabase Auth
- Notas e pastas persistidas no Supabase
- Auto-save
- Favoritos, recentes, pesquisa e lixeira
- RLS por usuário
- Tema claro/escuro
- PWA básica

## Arquitetura

Frontend estático + Supabase (Auth/Postgres/RLS) + Vercel.

O `SUPABASE_PUBLISHABLE_KEY` em `config.js` é uma chave pública destinada a aplicações de navegador. Nenhuma chave secreta é versionada no repositório.
