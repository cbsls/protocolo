ARQUIVOS GERADOS

1) index.html
- App principal de Entrada de Documentos
- Mantém layout estilo WhatsApp
- Já aponta para a tabela Supabase: public.documentos_entrada

2) manifest.json
- Manifesto PWA

3) sw.js
- Service Worker para cache offline

4) supabase_documentos_entrada.sql
- Script para criar a tabela no Supabase

PASSOS RÁPIDOS

1. No Supabase, abra SQL Editor
2. Cole o conteúdo do arquivo supabase_documentos_entrada.sql e execute
3. No GitHub Pages, substitua:
   - index.html
   - manifest.json
   - sw.js
4. Mantenha o arquivo icon.png na raiz do projeto
5. Faça commit
6. Abra o app e teste

OBSERVAÇÃO
- Senha admin atual no index: 123456
- Tabela usada pelo sistema: documentos_entrada
- Se quiser, no próximo passo eu posso gerar uma versão com:
  - numeração automática de protocolo
  - exportação PDF
  - filtro por data
  - setor fixo B4
  - campo despacho
