> Instrucciones para agentes de IA que trabajan en este proyecto de documentación.

# Proof by Nilho - Documentación para Marcas

## Sobre este proyecto

- Documentación para **Proof**, la infraestructura de Nilho que conecta recomendaciones con ventas.
- Sitio construido con [Mintlify](https://mintlify.com).
- Páginas en formato MDX con frontmatter YAML.
- Configuración en `docs.json`.
- Ejecutar `mint dev` para vista previa local.
- Ejecutar `mint broken-links` para verificar enlaces.

## Audiencia

- **Marcas** que se integran con Proof.
- Escribir directamente a la marca usando "tú" (colombiano informal pero profesional).

## Terminología

| Término en Proof | No usar | Notas |
|---|---|---|
| Marca | Advertiser, Anunciante, Comercio | Así se refiere Proof a sus clientes |
| Creador | Partner, Afiliado | Persona que recomienda productos |
| Recomendación | Referido | Así llama Proof a las acciones de los creadores |
| Offer (Oferta) | Campaña | "Oferta" es el término de la plataforma |
| Tracking link | Enlace de seguimiento | Preferir "tracking link" |
| Conversión | Venta (a menos que sea específicamente una venta) | Conversión es más genérico |
| Postback | Callback | Usar "postback" o "postback S2S" |
| Click ID / Transaction ID | - | Usar `_ef_transaction_id` en código |
| Order ID | - | Usar `adv_event_id` en código |
| Verification Token | API Key | Término específico de Proof |

## Preferencias de estilo

- Idioma: **Español (Colombia)**, usar "tú" informal profesional
- Voz activa, segunda persona
- Oraciones concisas, una idea por oración
- **No usar em dash (—)** en la documentación
- Títulos en sentence case
- Negrita para elementos de UI: Haz clic en **Configuración**
- Formato de código para nombres de archivos, comandos, rutas y referencias de código
- Incluir ejemplos de código reales (JavaScript, HTML, cURL)
- Usar componentes de Mintlify: `<Card>`, `<Steps>`, `<Tabs>`, `<Accordion>`, `<Warning>`, `<Info>`, `<Tip>`

## Archivo de referencia

- `everflow-reference.md` en la raíz del repo contiene la referencia técnica interna en inglés.
- Consultarlo para mantener precisión técnica.
- Este archivo está en `.mintignore` y no se publica.
- **Nunca mencionar Everflow en la documentación pública.**

## Límites del contenido

- Solo documentar funcionalidad relevante para marcas.
- No documentar funciones administrativas internas de Nilho.
- No documentar la interfaz de Creadores (eso es otro sitio de docs).
- Las integraciones de VTEX son documentación propia de Proof.
