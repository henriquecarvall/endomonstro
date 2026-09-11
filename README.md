# Endomonstro — Lucas C Prot

Página de vendas responsiva e biblioteca de vídeos. HTML, CSS e JavaScript sem dependências.

## Rodar localmente

Requer Node.js 20 ou superior. Execute `npm start` e abra http://127.0.0.1:4173.

`npm run build` valida os arquivos estáticos, âncoras, JavaScript e regras do quiz. O diretório publicável é `dist/`.

## Páginas

- `dist/index.html`: página de vendas, quiz, WhatsApp e oferta após 60 segundos.
- `dist/conteudos.html`: biblioteca com filtros e vídeos do Instagram carregados sob demanda.
- `dist/videos.json`: catálogo dos seis vídeos selecionados da base fornecida. É uma seleção editorial, não sincronização automática do Instagram.

Avisos no canto (página de vendas): seis frases fixas com emoji sobre curso, comunidade, preço, vida social, quiz e consultoria, uma por vez a partir de 15 s. Não simulam compras nem pessoas; ao fechar um aviso, os outros param nessa sessão. Notificações de compra só com dados reais da Hotmart.

O pop-up aparece uma vez por sessão, somente na página de vendas. Aguarda se outra janela estiver aberta ou se a aba estiver oculta. Não há contagem regressiva ou desconto fictício.

WhatsApp configurado exatamente como fornecido: +55 67 9249-6064. Confirmar que o número recebe mensagens antes de campanhas; não foi enviada mensagem de teste.

Preço conferido no checkout em 11/09/2026: 10 × R$ 35,69, total R$ 356,90 com acréscimo; R$ 297 à vista. Conferir novamente ao mudar condições na Hotmart.

## O que depende de ativação comercial

- Materiais de entrada estão em breve. Confirmar preços, entregas e checkouts antes de vender.
- Consultoria recebe contato por WhatsApp; as condições são informadas na conversa.
- O pop-up destaca curso e comunidade já incluída. Cupons e bônus adicionais exigem uma oferta real.
- Não há Pixel, CRM, formulários, automação de mensagens ou processamento de pagamentos neste código.
- Discussões acontecem nos comentários originais dos posts e na comunidade anunciada no curso. O site não simula usuários nem comentários.
- Embeds dependem das permissões de cada post e do Instagram; existe link direto como alternativa.

## Fontes e copy

Fotografias originais recuperadas da página pública do Lucas. A copy usa primeira pessoa e fatos da história já fornecida. Os desejos de confiança, presença e vida social são aspirações; não há promessa de renda ou de relacionamento.

Referências de estrutura: [Hook, Story, Offer, no podcast de Russell Brunson](https://podcasts.apple.com/us/podcast/mastering-the-hook-story-offer-framework-the-key/id1315130618?i=1000671533225), [Sexy Canvas, André Diamand](https://www.andrediamand.com/). Aplicação: identificação, história pessoal, desejo, pertencimento e oferta clara. Não há reprodução literal de copy desses autores.

Hospedagem privada Sites identificada em `.openai/hosting.json`. Não há tokens no repositório.
