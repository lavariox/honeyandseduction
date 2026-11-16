# Fuentes dispersas — información reutilizable para Honey

**Propósito:** todo lo que ya existe en otros proyectos, correos o archivos y que sirve para Honey, reunido aquí para **no construir desde cero**. Antes de tomar acción en Honey, revisar este archivo y el `README.md` de esta carpeta.

> Regla: los originales se quedan donde están (no se duplican archivos). Aquí van los **extractos y los apuntadores**. Si algo de aquí se vuelve material de trabajo de Honey, se copia a su carpeta correspondiente y se anota la fecha.

## 1. Precios reales de Andrea (verificados 2026-10-21)

- Vela 3 mechas BBW: **L650** (promo **L550**).
- Mist/splash 236 ml: **L390**. Body cream 236 ml: **L390**.
- Entrega a domicilio **L80 por pedido, la paga la clienta APARTE** (traslado, no costo de Andrea).
- Entregas de **8:00 a. m. a 6:00 p. m.**
- Políticas: sin devoluciones por cambio de gusto, sin reembolsos en efectivo, saldo a favor solo canjeable por otro producto disponible; producto equivocado o dañado se reporta con fotos y se revisa caso por caso.
- Fuente: mensajes de Andrea 2026-11-16; documento `~/workspace/user/files/Honey_Seduction_Proceso_de_Compra_y_Politicas_de_Entrega.docx` (también en Drive).

## 2. Rentabilidad (escenario 2026-10-21, con los precios de Andrea)

- Vela L650: costo aterrizado L516 → margen **L134 (20,6%)**.
- Mist L390: margen **L67 (17,2%)**. Cream L390: margen **L74 (19,0%)**.
- Canasta ejemplo (3 velas + 3 mists + 2 cremas): L3.900 → ganancia **L748 (19,2%)**.
- **Alerta:** a L550 la vela deja solo ~L34 de margen. Piso de promo sano propuesto: **L600** (no aprobado por Andrea todavía). Mist ~L40 por debajo del mercado (~L430); sugerido **L420** (tampoco aprobado).
- Comprar solo en promo USA (50% off) es todo el negocio; a precio regular se pierde.
- Fuente: `~/workspace/honey-seduction/escenario-precios/escenario-bbw-2026-10-21.md` (ojo: ese archivo es anterior a los precios reales de Andrea y a la corrección de entrega — actualizar antes de reutilizarlo tal cual).

## 3. Flete EEX (de Encomiendas Express, reutilizable para el costo aterrizado)

- Tarifario Público 2027: Honduras, caja 60" "La Chiqui" **$180** → base derivada **$2,57/lb**.
- Pesos asumidos: vela 1,9 lb; mist 0,7 lb; cream 0,6 lb.
- Radio de 30 millas de recolecta/entrega gratis (oficial); fuera del radio $1,00/milla ida y vuelta hasta 150 millas.
- Fuente: `~/workspace/eex-whatsapp-agent/kb/TARIFARIO_PUBLICO_2027.md` (proyecto EEX).

## 4. Cobros — Square (de EEX, aplicable a Honey)

- **Square es el sistema oficial de todos los pagos de EEX** y Honey puede ser su **segunda DBA**: opción recomendada, una "Location" de Honey dentro de la cuenta Square existente de Harold (catálogo, inventario y reportes separados; Andrea con acceso de empleada limitado a esa ubicación).
- Límite honesto: una cuenta Square = una entidad fiscal, el 1099-K combina EEX + Honey.
- Comisión Square en línea: **3,3% + $0,30** (sobre el bruto; en un producto de 8% de margen se come más de un tercio de la ganancia — el fee de tarjeta lo paga la clienta aparte, regla EEX).
- Práctica actual (puente temporal, no permanente): la mayoría paga por transferencia directa al banco de Andrea en Honduras; los pocos que pagan con tarjeta son compras grandes ($100–$200) y Harold crea un link de Square bajo Encomiendas Express. No es viable a largo plazo (riesgo para la cuenta de EEX).
- Facturas Square a Andrea Elvir (EEX, en Hotmail): #000292 $320 (nov 2026, pagada en efectivo), #000257 $170 y #000253 $170 (jun 2026). Coinciden con los PDF en Drive.

## 5. Cobros en Honduras — PixelPay (investigado 2026-10-21, sin ejecutar)

- **PixelPay** (hondureño, recomendado): liquida directo al banco del comerciante en 24–48 h, integra facturación CAI/SAR con ISV 15%, tiene API (`POST /v2/payments`, monto + moneda HNL). **No tiene API de catálogo**: el catálogo vive en la base de Honey y solo el total va a PixelPay.
- Afiliación como comerciante individual: permiso de operación vigente, RTN e ID, cuenta bancaria hn a nombre del comerciante. Contacto: info@pixel.hn, WhatsApp de ventas +504 9440-2425.
- **Comisión no publicada en ningún lado**: hay que exigir por escrito % tarjeta local, % débito, % tarjeta internacional, cargo fijo por transacción, mensualidad y costos de reembolso/contracargo antes de firmar.
- Respaldo: BAC Credomatic Compra Click (link de pago por WhatsApp). Descartado: Pagadito (5% + $0,25).
- Pendiente de verificar: que el permiso de comerciante individual de Honey esté vigente y que el nombre coincida exacto en permiso + RTN + cuenta bancaria.

## 6. Afiliados (investigado 2026-10-21, sin registrar nada)

- Top 5 verificados: Ulta (Rakuten, 2–6%, cookie 30 días), Sephora (Rakuten, 5–10%, cookie 24 h), Victoria's Secret (Rakuten/Admitad, ~3,6–5%), Walmart (Impact, 1–4% belleza ~3–4%, cookie 3 días), JCPenney (CJ, ~2,4–3%, cookie 7 días). Solo 3 cuentas de red cubren los 5: Rakuten, Impact, CJ.
- **BBW no tiene programa de afiliados público activo** (2026): la ganancia ahí es ahorro por cupones + margen de reventa. TJ Maxx sin programa de afiliados; Ross sin tienda en línea.
- Regla: comprar por el propio link de afiliado está prohibido en la mayoría de programas.
- Fuente: `~/workspace/honey-seduction/afiliados/checklist-registro-redes.md`

## 7. Cuentas y correos (revisión 2026-11-16)

- GitHub: cuenta **lavariox** (registrada con lavariox@hotmail.com). Repo único de Honey: **lavariox/honeyandseduction** — solo README + `index.html` placeholder de abril 2026. Sin duplicados en todo GitHub.
- Gmail **proyectosxhn@gmail.com**: sin correos del negocio Honey (solo ruido: Popeyes, Indeed, PayPal Honey). Esa cuenta NO es la de GitHub.
- Outlook **lavariox@hotmail.com**: sin correos del proyecto web/bot; solo facturas Square a Andrea y alertas de Google.
- **Cuenta Google alternativa de H&S (uso interno):** existe y está registrada en el documento general interno. No se publica aquí (repo público).

## 8. Marca y materiales ya hechos (reutilizables, no rehacer)

- Paleta real del logo: rosa blush #F6A8C6, lila #C9B8E3, dorado #C9A24B, crema #FAF3EE, texto ciruela #5A2A3A.
- Contacto: honeyseduction2023@gmail.com, WhatsApp +504 8945-3659, IG @honey_seduction (418 seguidores, 93 posts, última publicación mayo 2025, dormida ~6 meses).
- Imágenes de producto y branding: `~/workspace/honey-seduction/web-images/` y `~/workspace/honey-seduction/branding/` (ojo: son imágenes generadas por IA para demo — reemplazar con fotos reales de Andrea antes de salir en vivo).
- Config de marca: `~/workspace/honey-seduction/brand-pipeline/brand_config.py`.
- Regla de marca: SIEMPRE logo + WhatsApp en todo material publicitario de H&S.

## 9. Herramientas IA — dashboard de Conect AI (para H&S y T-PINK)

- Artefacto `herramientas-y-utilidades-ia`: "Herramientas y Utilidades IA, by CONECT-AI" — Top 10 (ChatGPT, Claude, Gemini, DeepSeek, Perplexity, Canva, Midjourney, Notion AI, Copilot, Grok), roadmap de 5 fases desde cero con cursos gratis de Cisco NetAcad en español, 5 videos de YouTube y prompts listos.
- Limitación conocida: el progreso del roadmap es solo de la sesión (no se guarda entre visitas). Si se quiere progreso guardado por persona, hay que pasarlo a versión con almacenamiento — Harold no ha contestado todavía.
- Brief: `~/workspace/research_notes/conectai-herramientas-ia/report.md`

## 10. Dominios (verificado por RDAP 2026-11-16)

- **honeyandseduction.com LIBRE**, honey-seduction.com LIBRE, honeyandseductionhn.com LIBRE. honeyseduction.com OCUPADO (Namecheap, vence 2027-01-16).
- Recomendación: honeyandseduction.com en Porkbun (~$11,81/año) o Cloudflare (~$11,17/año, solo transferencias). Hosting $0 en GitHub Pages o Cloudflare Pages. **Dominio NO comprado todavía.**
