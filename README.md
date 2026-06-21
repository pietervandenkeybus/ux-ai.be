# ux-ai.be — UX & AI (contentsite)

Een echte inhoudelijke site over het praktisch inzetten van AI in UX-werk, met Pieter Van den Keybus
als auteur. Geen naam-landingspagina, maar content met een eigen onderwerp en zoekintentie — dat is
wat 'm op eigen kracht laat ranken (en jou geloofwaardig vermeldt).

## Inhoud
`index.html`, `robots.txt`, `sitemap.xml`, `CNAME`, `.nojekyll`, `vercel.json`

## Deployen (GitHub → Vercel)
1. Push de inhoud van deze map naar een nieuwe repo.
2. Importeer de repo in Vercel.
3. Voeg het domein `ux-ai.be` toe (Project → Settings → Domains) en volg de DNS-instructie van Vercel.
4. Vercel serveert HTTPS automatisch. (Het `CNAME`-bestand is voor GitHub Pages; op Vercel stel je het
   domein in de UI in — het bestand stoort niet.)

## SEO na deploy
- Maak een property aan in Google Search Console voor `ux-ai.be` en dien `sitemap.xml` in.
- De structured data bevat een `Article` met jou als `author`, en `sameAs` naar al je profielen/domeinen.

## Inhoudelijk uitbreiden = sterker ranken
Deze site wordt krachtiger naarmate je er echte artikels aan toevoegt. Begin eventueel met losse
pagina's per onderwerp (bv. `/ai-in-gebruikersonderzoek`, `/ai-prototyping`) en voeg ze toe aan de sitemap.
