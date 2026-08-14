# Mural Infinito

Um mural público onde uma pessoa deixa uma nota e outra pessoa pode encontrá-la depois.

## Arquivos

- `index.html` interface
- `styles.css` visual
- `app.js` lógica, feed infinito e modo local
- `config.js` configuração do Supabase
- `schema.sql` tabela e políticas do banco

## Compartilhamento entre computadores

O GitHub Pages hospeda o frontend, mas não é banco de dados. Para que as notas sejam realmente compartilhadas entre computadores, crie um projeto Supabase, execute `schema.sql` no SQL Editor e coloque a URL e a chave anon pública em `config.js`.

Sem configuração, o site funciona em modo local para testar a interface.
