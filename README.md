# GoldNews AI (APK)
Calendario USD de alto impacto + sesgo IA + señales XAUUSD, con planes Standard/Pro/Ultimate.

## Generar el APK (sin instalar nada)
1. Crea un repo en GitHub y sube TODO este contenido (incluida la carpeta .github).
2. Pestaña Actions → "Build APK" → Run workflow (corre solo en cada push).
3. Descarga el artefacto `GoldNewsAI-apk` → instala app-debug.apk en tu Android.

## Local
npm install && npx cap add android && npx cap sync && cd android && ./gradlew assembleDebug

## Datos
- Calendario: feed público semanal de Forex Factory (faireconomy.media).
- Precio: api.gold-api.com. IA: tu clave de Anthropic (opcional).
- Cobros reales: integrar Google Play Billing o RevenueCat en setPlan().
