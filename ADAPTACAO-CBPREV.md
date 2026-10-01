# Adaptação CBPREV — 1 de outubro de 2026

## Alterações

- dist/index.html: nome institucional, título e descrição; hero; quatro cards de atuação; apresentação de Carla Berenice; atendimento; seção institucional no lugar de avaliações; CTA e rodapé.
- dist/assets/site.css: regenerado com as classes utilizadas, sem alterar configuração, fontes ou tamanhos.
- Este relatório documenta as verificações e pendências.

Todos os contatos apontam para https://www.instagram.com/cbprev_/, fornecido pelo usuário. Foram removidos telefone, WhatsApp, endereço, CNPJ, nota, quantidade de avaliações, depoimentos e links do escritório anterior. Os cards de avaliações mantêm a estrutura e a animação, com textos institucionais e sem simular depoimentos. Os serviços se limitam a aposentadorias e benefícios do INSS; os outros dois cards apresentam orientação individual e atendimento nacional.

O título foi encurtado para “Orientação para o INSS / com atenção e estratégia.” para caber em 320 pixels sem alterar o CSS. O acolhimento permanece na apresentação institucional.

## Identidade e contatos pendentes

Não foi possível confirmar a grafia visual da marca, a paleta, o e-mail ou o endereço nos canais oficiais. O Instagram não estava acessível nas consultas; a página https://cbadvocaciaprev.com/bpc-loas-negado/ apresentou erro de certificado TLS. Não foram incluídos e-mail nem endereço sem confirmação. WhatsApp continua pendente.

A paleta azul escuro/dourado é a do modelo anterior, não uma paleta oficial atribuída à CBPREV. O botão flutuante usa o dourado já existente, substituindo a referência verde ao WhatsApp por um ícone genérico de contato, preservando suas dimensões e efeito.

Os arquivos da logo, do retrato e do favicon do modelo anterior foram preservados para a etapa de substituição autorizada. Os textos alternativos identificam logo e retrato como materiais do modelo cuja substituição está pendente; o retrato não foi atribuído a Carla Berenice. Esses materiais precisam ser substituídos antes de publicar esta adaptação como site oficial.

## Verificações

- npm run build: passou; apenas aviso de base Browserslist antiga.
- git diff --check: passou.
- Scripts inline e estilos inline: idênticos ao modelo anterior; sintaxe JavaScript válida.
- Mesmas seis seções e vinte elementos article; vídeo, sources, poster e atributos intactos.
- Chrome: celular de 390 pixels, tablet de 768 pixels e desktop de 1440 pixels sem rolagem horizontal; teste adicional de 320 pixels com o título ajustado.
- Navegação por todas as seções, carregamento de imagens, vídeo e links de contato verificados. Sem erros JavaScript no navegador.

As alterações permanecem locais. Não foi enviada esta versão ao GitHub nem acionada publicação automática, pois identidade e materiais oficiais ainda estão pendentes.

Logo: aplicada a versão PNG transparente da imagem fornecida pelo usuário na abertura, cabeçalho, rodapé e favicon. Foto e demais confirmações seguem pendentes.

Foto: aplicada na seção Sobre a imagem original Foto cbprev.png fornecida pelo usuário, sem edição, mantendo o container e object-fit existentes.

Avaliações: oito autores e trechos literais fornecidos em prints pelo usuário. Nota 5,0 e 268 avaliações conforme os prints, sem atualização automática. Grupos duplicados preservados para o loop de animação. Botão aponta ao perfil do Google Maps confirmado em consulta anterior.

WhatsApp confirmado pelo usuário: +55 86 98113-1819. Aplicado aos cinco links de contato; Instagram preservado no rodapé.
