# Lead: Clínica Ortotrauma (Brumado - BA)

Prévia de site para abordagem comercial. HTML estático, sem build.

- Instagram: https://www.instagram.com/ortotrauma_clinica/
- WhatsApp: (77) 99908-8800 · Rua Placídia Rizério, 28 · Centro
- Google: nota 2,9 (14 avaliações). Reclamações principais: ninguém atende telefone/WhatsApp, precisa ir até a clínica para marcar exame.
  Gancho de venda: site com agendamento direto por exame (mensagem pronta) + agenda dos médicos visível.

## Rodar
    npx serve public -l 4180

## Publicar (Cloudflare, conta usewebverse@gmail.com)
    npx wrangler deploy

Só a pasta `public/` vai pro ar.
URL: https://webverse-ortotrauma.usewebverse.workers.dev

Fotos originais (panorâmicas 360, 4000px) ficam em `_bruto/`, fora do git.

## Fontes dos dados
- Médicos, dias, exames, convênios: posts do Instagram (jul-set/2026)
- Horários, endereço, fotos: Google Maps (panorâmicas 360 reprojetadas; originais em `_bruto/`)

## A confirmar com o cliente
- CRM da Dra. Ana Paola Palles; lista completa de convênios; fotos reais dos médicos
- Logo vetorial oficial (o do site é recriação simplificada)
