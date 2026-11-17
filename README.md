# TRAMA — Educação e Geografia · V3

Versão demonstrativa do aplicativo de planejamento do professor César.

## Como publicar no GitHub Pages
1. Crie/abra um repositório público, envie `index.html`, `manifest.webmanifest`, as pastas `icons` e `assets` e o arquivo `.nojekyll` para a raiz.
2. Em **Settings > Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/(root)`.
3. Acesse o endereço gerado pelo GitHub Pages.

## Funcionalidades V3
- Identidade verde/neutral Apple Glass, logotipo com TRAMA em destaque.
- Saudação dinâmica Bom dia/Boa tarde/Boa noite, conforme relógio do dispositivo.
- Informações Institucionais: calendário 2027 (Resolução SEE nº 5.328/2026), eventos editáveis e inclusão de novas datas.
- Home com horários semanais de aulas, editáveis.
- Páginas por turma com importação de listagem CSV, TXT ou XLSX, visualização e edição dos nomes.
- Portal do aluno com globo terrestre ilustrativo e link que abre Google Earth, além de visualização e download de atividades.

## Limitações e privacidade
- **Demonstração local**: os dados são salvos via `localStorage` neste navegador. Publicar no GitHub Pages **não** faz as alterações do professor aparecerem nos aparelhos dos alunos.
- **Não carregue listas reais de menores neste protótipo hospedado em computador compartilhado.** Não há autenticação. Listagens são exibidas somente na área do professor, mas todo o app é demonstrativo e o armazenamento no navegador não substitui uma solução segura.
- O Google Earth não permite incorporar sua interface integral em `iframe` de terceiros; a janela exibe um globo com mapa NASA Blue Marble e link externo para `https://earth.google.com/web/`.
- Imagem da Terra: NASA Blue Marble Next Generation, de domínio público, distribuída no pacote para funcionamento sem conexão.
- A agenda de 2027 foi semeada conforme Resolução SEE/MG nº 5.328/2026. Personalizações não alteram o calendário homologado da escola.
- A importação XLSX utiliza recursos nativos de navegadores modernos (`DecompressionStream`). Caso a importação falhe, exporte como CSV.
- Conteúdos curriculares da biblioteca ainda são ilustrativos, pendente integração de habilidades oficiais.
- Para a publicação compartilhada das atividades e sincronização, será necessário adicionar autenticação e backend, conforme etapa futura do projeto.
