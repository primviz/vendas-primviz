# Primviz • Página de vendas • V1.5

Projeto estático em HTML, CSS e JavaScript puro, sem instalação ou build. Extraia o ZIP e abra index.html. Publique a pasta que contém index.html no GitHub/Cloudflare Pages, sem comando de build.

## Integrações
- Checkout: https://pay.hotmart.com/E107558886P
- WhatsApp: 55 71 98349-9101, somente no bloco final de dúvidas.
- Meta Pixel: 1395824749322064, PageView e eventos personalizados ClickCheckout / ClickWhatsApp.
- GA4: G-XXPLRF9T9N, page_view, click_checkout (product_name e button_position) e lead_whatsapp.
- Os eventos de clique medem ações na página. Não confirmam compra, início efetivo de checkout ou envio de mensagem. Purchase e InitiateCheckout precisam de configuração e validação na Hotmart.
- Os parâmetros utm_source, utm_medium, utm_campaign, utm_content, utm_term, src e sck são preservados nos links para checkout.

## Atualização V1.5
Substituição dos materiais de postagens por mockups completos: Tiago Neves, Madu Miranda, Ferrer, Party Truck e Carrinhos Gourmet. Hero com a composição de três celulares enviada. Copy comercial, checkout, WhatsApp e scripts de rastreamento preservados.

## Conteúdo e materiais
A copy final enviada foi aplicada. As imagens do portfólio são os mockups frontais completos do novo envio, otimizados em WebP com transparência preservada. Foram retiradas somente margens transparentes externas. O conteúdo do celular não foi recortado. Não foram criados depoimentos, números de clientes ou páginas fictícias. A comparação usa uma representação conceitual genérica de lista de links.

A seção de produto usa mockup real estático. Para incluir uma gravação de navegação, será necessário enviar o vídeo real. Depoimentos poderão ser incluídos após o envio. Não existem placeholders visíveis ao visitante.

## URL de publicação e SEO
A URL canônica e o sitemap usam https://primviz.com.br/ como endereço padrão da marca. Se esta página for publicada em outro domínio ou subdiretório, atualize a URL em index.html, robots.txt e sitemap.xml antes da publicação. A criação deste ZIP não publica nem configura domínio.

## Verificação
- JavaScript passou na verificação de sintaxe do Node.
- Arquivos locais referenciados, IDs e âncoras do HTML foram conferidos.
- Nove perguntas do FAQ e links comerciais foram verificados.
- Eventos e encaminhamento de parâmetros foram testados localmente com chamadas monitoradas.
- Os testes visuais em navegador não puderam ser executados: o ambiente não disponibiliza um executável do Chromium. Validar mobile (320, 390 e 430 px), tablet e desktop antes de ativar o tráfego.
- GA4 Realtime e recebimento do Meta Pixel não foram confirmados: exigem a página publicada e acesso às propriedades. Conferir o recebimento dos eventos no GA4 e no Gerenciador de Eventos antes de rodar anúncios.
- O destino Hotmart não foi testado com pagamento. Conferir produto, recorrência, garantia e direcionamento de boas-vindas na conta Hotmart.

## Arquivos
index.html • assets/style.css • assets/script.js • assets/images/ • favicon.png • robots.txt • sitemap.xml

## V1.5 • Menos repetição
Novos mockups Palivo Tattoo e Denice Silva na personalização. Tiago aparece na apresentação de produto; Carrinhos Gourmet na comparação; Madu, Ferrer e Party Truck no carrossel de profissões. O bloco de prova real apresenta um índice com links para esses exemplos na própria página, sem duplicar as imagens. A composição do hero foi preservada.

## Atualização V1.5
Mockup Carrinhos Gourmet Larissa Pais substituído pela versão corrigida do arquivo 12.png. Inclusão de Farmácia 2 de Julho, Clínica Mãe e Dra. Enyla Cerqueira no carrossel de profissões e no índice de prova real, sem repetição dos mockups individuais. Somente margens transparentes removidas; celulares e telas preservados.

## Atualização V1.5
Links reais recebidos na planilha aplicados aos dez exemplos. Mockups e índice do portfólio abrem em nova aba, com botões ABRIR PÁGINA sem setinhas. Os destinos foram transcritos do material do usuário; disponibilidade dos sites externos não foi verificada. Para Palivo Tattoo, usado o endereço palivo.primviz.com.br, correspondente ao mockup da landing page. Os links comerciais, WhatsApp e rastreamento foram preservados.

## Atualização V1.5 • Página interna de obrigado
Página adicionada em obrigado/index.html, acessível em /obrigado (redirecionamento para /obrigado/ no Cloudflare Pages). Configure na Hotmart a URL completa usando o domínio em que este projeto for publicado. Se usar o endereço informado venda.primviz.com.br, o destino será https://www.venda.primviz.com.br/obrigado.

A página não tem links de entrada no menu ou na página de vendas, não aparece no sitemap e possui noindex/nofollow tanto no HTML quanto em _headers. Isso reduz descoberta, mas não constitui controle de acesso: qualquer pessoa com a URL pode abri-la.

Orientações, prazo de primeira versão e WhatsApp estão incluídos. O briefing será orientado pela equipe, pois não foi fornecido um link específico. O evento lead_whatsapp tem categoria onboarding. Purchase não é disparado nesta URL pública; configure a confirmação de vendas pela integração com Hotmart. GA4 e Meta Pixel foram preservados nas duas páginas.
