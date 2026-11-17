# TRAMA V4 — Educação e Geografia

## Publicação no GitHub Pages
Extraia o pacote e envie todo o conteúdo (incluindo pastas `icons` e `assets`) à raiz do repositório GitHub. Em **Settings → Pages**, selecione a branch `main` e pasta `/(root)`.

## Mudanças na V4
1. Importação de listagens de estudantes exclusivamente por PDF, com extração de texto via PDF.js, revisão e salvamento manual da lista.
2. Indicadores do painel transferidos para o Planejamento.
3. No celular, agenda diária em lugar do quadro semanal; computador mantém semana completa.
4. Ícone com área verde até as bordas, sem moldura branca pré-desenhada.
5. Calendário mensal clicável com pop-up para compromissos e aulas do dia.
6. Gerenciamento simultâneo de escolas, filtros, vínculo por turma/horário e eventos escolares.
7. Planejamento em um trimestre por vez, com conteúdo completo e setas superiores.

## Funcionamento do PDF
A leitura de PDF usa a biblioteca PDF.js servida por CDN (`cdnjs.cloudflare.com`). É necessária conexão à internet para importar PDF. PDFs com texto selecionável são suportados; arquivos digitalizados sem texto pesquisável **não possuem OCR** nesta versão. Os nomes extraídos devem ser revisados antes de salvar.

## Aviso sobre dados e privacidade
**O TRAMA V4 continua sendo um protótipo local.** Não há autenticação, banco de dados nem sincronização entre dispositivos. O GitHub Pages publica a interface, mas as edições feitas no aparelho do professor não aparecem automaticamente nos aparelhos dos alunos.

**Não insira dados reais de estudantes menores de idade na versão pública compartilhada ou em dispositivos compartilhados.** A navegação local não constitui proteção de acesso. O ambiente definitivo exigirá autenticação do professor, políticas de autorização e servidor seguro.

## Atualização da V3
A primeira abertura em um navegador com dados da V3 tenta importar os registros V3 para a nova chave `trama-geografia-v4`. A V3 não é apagada. Para um teste seguro, experimente primeiro em um navegador particular, sem dados reais.

## Conteúdos
O exemplo de currículo continua ilustrativo e não substitui os planos de curso oficiais SEE-MG. O calendário de 2027 segue as datas previamente fornecidas pelo professor.
