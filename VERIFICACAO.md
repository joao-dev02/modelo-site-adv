# Verificação do site

Revisão realizada em 1 de outubro de 2026, com Chrome automatizado e servidor HTTP local.

## Resultados

- Geração do CSS com Tailwind: concluída.
- Sintaxe dos dois scripts inline: válida.
- Dez referências a arquivos locais: todos presentes.
- Desktop (1440 × 900) e celular (390 × 844): navegação pelas seis seções sem rolagem horizontal; contato alcançado.
- Menu móvel: abre e fecha após a seleção.
- Imagens: carregadas após percorrer o site, incluindo o retrato com carregamento tardio.
- Vídeo: carregado e reproduzido no modo normal.
- Execução normal: sem erros de JavaScript ou mensagens de erro no console.
- GSAP bloqueado na rede: conteúdo visível, cards visíveis e rolagem liberada.
- JavaScript desativado: conteúdo visível, tela de abertura oculta e rolagem liberada.
- Movimento reduzido: conteúdo visível sem tela de abertura e vídeo pausado.

## Correções

- CSS do Tailwind gerado localmente, substituindo o script CDN.
- Recuperação da tela de abertura quando bibliotecas de animação não estão disponíveis.
- Exibição do conteúdo sem JavaScript.
- Vídeo não reinicia com movimento reduzido.
- Foco visível para links e botões e margem de navegação para o cabeçalho fixo.

## Escopo

Os links de WhatsApp, Instagram e Google Maps foram conferidos no código; não foram enviadas mensagens. O site não contém backend nem formulário. As avaliações, dados do escritório e informações institucionais foram preservados, sem validação externa de autoria ou conteúdo.

Verificação adicional: tela de 320 × 740 sem rolagem horizontal, com e sem animações. Corrigida a quebra de palavras longas nos títulos.
