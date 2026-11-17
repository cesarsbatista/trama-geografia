# TRAMA V5 — Educação e Geografia

## Instalação no GitHub Pages
Envie **todo o conteúdo deste ZIP**, mantendo as pastas `icons/` e `assets/`, para a **raiz** do repositório no GitHub. Configure **Settings → Pages → Deploy from a branch → main → /(root)**. Se já há uma V4 publicada, substitua os arquivos antigos por estes.

## Correções V5
1. Indicadores das turmas agora em **verde-sálvia**, sem azul.
2. A lista de estudantes possui botões de **editar** e **remover** junto a cada nome; edição exige confirmação, impede duplicatas e salva localmente.
3. Importação de PDF revisada: o seletor é nativo, com leitor local para PDFs padrão (texto selecionável; filtros Flate/ASCII85), leitor PDF.js alternativo quando necessário e com internet, prévia editável antes de importar e alertas de erro. Não há OCR de PDFs digitalizados.
4. Pop-up do calendário ganhou margens, preenchimento e espaçamento para desktop e celular.

## Limitações
É um **protótipo local sem autenticação**, banco de dados ou sincronização. PDFs são lidos no próprio navegador: não há upload remoto. O leitor local funciona nos navegadores recentes e não interpreta todos os tipos de PDF; PDFs complexos podem exigir conexão para biblioteca PDF.js ou revisão manual. **Não use nomes reais de estudantes em uma publicação pública sem implementar antes autenticação e controles de privacidade**.

Os dados do navegador da V4 são tentativamente copiados para a nova chave `trama-geografia-v5`; a chave V4 permanece preservada. A simulação do portal do aluno nesta versão não publica atividades em outros dispositivos.

Os conteúdos curriculares e as turmas iniciais são apenas demonstrativos.
