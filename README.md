# Barradas Feitosa Advocacia

Site institucional responsivo, em português, para apresentação do escritório, áreas de atuação, atendimento e contato pelo WhatsApp.

## Executar localmente

Requer Node.js 22 ou superior e npm.

```sh
npm ci
npm run build
npm start
```

Abra http://127.0.0.1:4173. O servidor é destinado à conferência local.

## Editar e publicar

- Conteúdo, layout e animações: `dist/index.html`.
- Imagens, vídeos e CSS gerado: `dist/assets/`.
- Configuração do Tailwind: `tailwind.config.cjs`.
- Entrada do CSS: `styles/input.css`.

Após alterar classes ou configuração, execute `npm run build` e inclua o CSS atualizado no commit. Para hospedagem estática, publique a pasta `dist` (diretório de saída). O site funciona também em subdiretórios, pois os arquivos locais usam caminhos relativos.

Não há backend nem formulário: os botões de atendimento abrem o WhatsApp. Google Fonts, GSAP e Lenis são carregados de serviços externos. Se as bibliotecas de animação falharem, o conteúdo e a navegação continuam disponíveis; sem JavaScript, o conteúdo também permanece visível.

O envio ao GitHub armazena os arquivos do projeto. A hospedagem pública deve ser configurada separadamente no serviço escolhido.

## Vercel

A configuração em vercel.json define o build como npm run build e a pasta de publicação como dist. Importe o repositório mantendo a raiz do projeto na pasta principal. Novos commits em main acionam o deploy quando a integração Git está habilitada.
