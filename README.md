# TRAMA V5.1 — Educação e Geografia

## Instalação no GitHub Pages
Envie **todo o conteúdo deste ZIP**, mantendo as pastas `icons/` e `assets/`, para a **raiz** do repositório no GitHub. Configure **Settings → Pages → Deploy from a branch → main → /(root)**. Se já há uma V4 publicada, substitua os arquivos antigos por estes.

## Correções V5
1. Indicadores das turmas agora em **verde-sálvia**, sem azul.
2. A lista de estudantes possui botões de **editar** e **remover** junto a cada nome; edição exige confirmação, impede duplicatas e salva localmente.
3. Importação de PDF revisada: o seletor funciona sem reiniciar a tela; PDF.js é carregado do próprio site, com prévia editável antes de importar e alertas de erro. Não há OCR de PDFs digitalizados.
4. Pop-up do calendário ganhou margens, preenchimento e espaçamento para desktop e celular.

## Limitações
É um **protótipo local sem autenticação**, banco de dados ou sincronização. PDFs são lidos no próprio navegador: não há upload remoto. O leitor PDF.js fica incluído no aplicativo, mas PDFs protegidos, digitalizados ou com layout incomum ainda podem exigir revisão manual. **Não use nomes reais de estudantes em uma publicação pública sem implementar antes autenticação e controles de privacidade**.

Os dados do navegador da V4 são tentativamente copiados para a nova chave `trama-geografia-v5`; a chave V4 permanece preservada. A simulação do portal do aluno nesta versão não publica atividades em outros dispositivos.

Os conteúdos curriculares e as turmas iniciais são apenas demonstrativos.


## Correções V5.1 — Listas da SEE-MG
- Seletor PDF corrigido (o clique não aciona indevidamente a troca de tema).
- Leitor PDF.js 2.8.335 com worker disponibilizados localmente em `assets/`, sem dependência de CDN.
- Identificação de registros numerados no padrão `ordem código_de_matrícula nome`, removendo ordem e matrícula da lista de nomes.
- Revisão obrigatória dos nomes antes de adicionar à turma; PDFs escaneados sem texto não são reconhecidos automaticamente.
- O PDF e as matrículas não são enviados a serviços externos pelo importador.

### Direitos de terceiros
`assets/pdf.min.js` e `assets/pdf.worker.min.js` são componentes PDF.js do projeto Mozilla, distribuídos sob Apache License 2.0. Consulte `assets/LICENSE.pdfjs.txt`.
