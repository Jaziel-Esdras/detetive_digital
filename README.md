# Detetive Digital — O caso da imagem suspeita

Aplicação web educativa responsiva, sem backend, cadastro ou coleta de dados pessoais.

## Executar localmente
1. Extraia o ZIP.
2. Abra `index.html` em um navegador moderno. Para testar a experiência mobile, use as ferramentas de dispositivo do navegador ou envie a pasta para uma hospedagem estática.
3. O jogo usa ilustrações SVG incorporadas no próprio HTML, então não depende de arquivos de imagem externos. A fonte Google Fonts é opcional; se estiver offline, o navegador usa fontes sans-serif locais.

## Publicar e gerar QR Code
Publique `index.html` em um serviço de hospedagem estática (por exemplo, GitHub Pages, Netlify ou Cloudflare Pages) e copie a URL pública. Gere o QR Code usando essa URL final. Não gere o QR Code apontando para `file://` ou para o computador local.

## Conteúdo e rigor educativo
As cinco imagens são ilustrações sintéticas feitas em SVG para este jogo e estão identificadas como sintéticas. Os contextos são fictícios. O jogo não tenta detectar automaticamente imagens de IA. As conclusões enfatizam a necessidade de verificar procedência, contexto e fontes independentes.

## Funcionalidades incluídas
- Tela inicial, briefing, tutorial, seleção de casos, investigação, feedback, resultado final e revisão.
- Cinco casos com imagens próprias incorporadas.
- Marcadores interativos de pistas (+25 pontos por pista nova).
- Zoom e restauração de visualização.
- Uma resposta por caso, feedback e avanço manual.
- Pontuação, progresso, categorias finais e revisão das respostas.
- Compartilhamento nativo ou cópia do resultado.
- Layout responsivo e respeito à preferência de redução de movimento.

## Limitações honestas
O projeto foi gerado como um pacote estático; não foi publicado na internet nem testado em uma variedade real de celulares. A interação básica foi implementada em JavaScript, mas a publicação e os testes físicos devem ser feitos pelo organizador antes da feira. O zoom é por botões (não gesto de pinça) e os marcadores são regiões predefinidas.
