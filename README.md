<div align="center">

# Conceptos de producto

**7 paneles de producto SaaS diseñados como concepto:** CRM con WhatsApp e IA, inbox con agentes, analítica de ganancia, gimnasio, mayorista B2B, nutricionistas y app de turnos.

<sub>Product concepts: 7 SaaS dashboards with invented brands and sample data.</sub>

[![Ver la galería](https://img.shields.io/badge/Ver_la_galer%C3%ADa-en_vivo-7C5CFF?style=for-the-badge)](https://orbitalnestdev.github.io/saas-concepts/)
![HTML](https://img.shields.io/badge/HTML-0F0F12?style=for-the-badge&logo=html5&logoColor=E34F26)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F0F12?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![Chart.js](https://img.shields.io/badge/Chart.js-0F0F12?style=for-the-badge&logo=chartdotjs&logoColor=FF6384)

</div>

> [!NOTE]
> **Son conceptos, no trabajos para clientes.** Las marcas, las personas y los datos son inventados. Muestran cómo encaro un panel de producto: qué información va primero, cómo se lee de un vistazo y qué hace la IA en cada caso.

## Los paneles

<table>
<tr>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/leadnest.html"><img src="screenshots/leadnest.jpg" alt="Panel de Leadnest"></a><br><b>Leadnest</b> · CRM de ventas con WhatsApp e IA<br><sub>Pipeline kanban con canal y puntaje de IA en cada oportunidad, gráficos de ingresos y conversión, y un resumen de cada conversación con la intención, el presupuesto y el próximo paso.</sub><br><sub><i>Stack previsto: Next.js · PostgreSQL · OpenAI</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/leadnest.html">Ver panel →</a></td>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/replyo.html"><img src="screenshots/replyo.jpg" alt="Panel de Replyo"></a><br><b>Replyo</b> · Inbox de WhatsApp con agentes de IA<br><sub>El agente responde desde una base de conocimiento, agenda turnos y pasa la consulta a una persona con todo el contexto. Bandeja compartida, panel del cliente, constructor visual de agentes al estilo n8n y métricas de respuestas IA vs. humanas.</sub><br><sub><i>Stack previsto: Next.js · n8n · WhatsApp Cloud API</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/replyo.html">Ver panel →</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/marginly.html"><img src="screenshots/marginly.jpg" alt="Panel de Marginly"></a><br><b>Marginly</b> · Analítica de ganancia para tiendas online<br><sub>Ganancia neta real después de costo, envío, comisiones y publicidad para Shopify, WooCommerce y Tiendanube: ROAS por día, cascada de ganancia, productos que pierden plata e ideas de la IA con su impacto estimado.</sub><br><sub><i>Stack previsto: Next.js · Shopify API · Meta Ads · GA4</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/marginly.html">Ver panel →</a></td>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/kinetik.html"><img src="screenshots/kinetik.jpg" alt="Panel de Kinetik"></a><br><b>Kinetik</b> · Sistema de gestión para gimnasios<br><sub>Socios y membresías, grilla semanal de clases con cupos, ingresos por hora, pagos y una lista de socios en riesgo que dejaron de ir, con recordatorio por WhatsApp en un clic.</sub><br><sub><i>Stack previsto: Next.js · Prisma · Stripe</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/kinetik.html">Ver panel →</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/bulkly.html"><img src="screenshots/bulkly.jpg" alt="Panel de Bulkly"></a><br><b>Bulkly</b> · Portal de pedidos mayoristas (B2B)<br><sub>El cliente hace pedidos rápidos por SKU con su lista de precios, mínimos por bulto y crédito disponible; el equipo maneja listas por segmento, stock por depósito y cada pedido desde la preparación hasta la factura.</sub><br><sub><i>Stack previsto: Next.js · Node.js · PostgreSQL</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/bulkly.html">Ver panel →</a></td>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/nutrio.html"><img src="screenshots/nutrio.jpg" alt="Panel de Nutrio"></a><br><b>Nutrio</b> · Panel para nutricionistas con planes de IA<br><sub>Fichas de pacientes con evolución de peso y grasa corporal, macros del día, armado del plan semanal con IA y registro de comidas por foto analizado por IA.</sub><br><sub><i>Stack previsto: Next.js · Supabase · OpenAI</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/nutrio.html">Ver panel →</a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://orbitalnestdev.github.io/saas-concepts/turnly.html"><img src="screenshots/turnly.jpg" alt="Panel de Turnly"></a><br><b>Turnly</b> · App de turnos para iOS<br><sub>Para clínicas y salones: el cliente elige servicio, profesional y horario, paga una seña y recibe recordatorios; el negocio tiene un back office web con la agenda del día, la ocupación y los ingresos.</sub><br><sub><i>Stack previsto: React Native · Expo · Supabase</i></sub><br><a href="https://orbitalnestdev.github.io/saas-concepts/turnly.html">Ver panel →</a></td>
<td width="50%"></td>
</tr>
</table>

## Cómo están hechos

- Cada panel es un solo archivo HTML: Tailwind por CDN, Chart.js para los gráficos e íconos SVG en línea. Sin build ni dependencias.
- Diseñados a 1440 px de ancho, con datos de ejemplo de octubre de 2026.
- El stack de cada ficha es el que usaría para construir el producto real.
- Diseño y especificación propios; el maquetado se hizo con asistencia de IA.

## Verlos en tu compu

Cloná el repo y abrí `index.html` en el navegador. No hace falta instalar nada.

---

<div align="center"><sub>Hecho por <a href="https://github.com/orbitalnestdev">Eliana Azcurra</a> · desarrolladora full stack freelance · <a href="https://www.linkedin.com/in/eliazdev">LinkedIn</a> · <a href="https://www.fiverr.com/elyazcurra90">Fiverr</a></sub></div>
