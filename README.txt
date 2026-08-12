AUDENS COMPANY — Landing Page V4 ("Operação em Ascensão")
=========================================================
Estrutura:
  index.html        → página (código limpo, tokens CSS, sem base64)
  images/           → imagens externas otimizadas (WebP)

Como abrir: abra index.html mantendo a pasta images/ ao lado.
Publicação: suba os dois juntos (mesma pasta relativa ./images/).

PENDÊNCIAS marcadas no código (buscar "[" ):
  - Foto real dentro da operação (seção Operadores) — hoje placeholder.
  - Nome público + cidade da operação do case.
  - Autorização dos clientes nos prints (nomes/telefones podem ser ocultados).
  - Forma final do número "+R$50 mi" (validar apresentação, sem causalidade).
  - Política de fidelidade (FAQ) e Política de Privacidade (LGPD).
  - Logo oficial em SVG (hoje usamos um símbolo-montanha placeholder inline).

CONFIGURAÇÃO TÉCNICA (buscar no <script>):
  - CONFIGURE_CRM_ENDPOINT_HERE  → endpoint do CRM/webhook do formulário.
  - META_PIXEL_ID / GA4_ID / GTM_ID → IDs de tracking (dataLayer já preparado).
  Eventos: lp_view, hero_cta_click, method_cta_click, case_view, offer_view,
           form_start, form_step_1_complete, lead_submit, qualified_lead.

Obs.: a foto dos fundadores está espelhada no arquivo original (logo/tatuagem
invertidos). Substituir por versão não espelhada quando possível.
