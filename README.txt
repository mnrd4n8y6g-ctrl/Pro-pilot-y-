PROPILOT(Y) — WEBOVÁ STRÁNKA
=============================

Obsah složky:
  index.html          – hlavní stránka (otevři pro náhled)
  404.html            – stránka pro nenalezené adresy
  favicon.svg / .ico  – ikona v záložce prohlížeče
  favicon-32.png      – ikona 32×32
  apple-touch-icon.png– ikona na plochu iOS (180×180)
  icon-192/512.png    – ikony pro PWA / sdílení
  site.webmanifest    – manifest aplikace

Stránka je čisté HTML bez build kroku. Jediná externí věc jsou fonty
z Google Fonts, které se načtou samy přes internet.


JAK ZVEŘEJNIT (vyber jednu cestu)
---------------------------------

A) NETLIFY DROP (nejrychlejší, zdarma)
   1. Otevři https://app.netlify.com/drop
   2. Přetáhni do okna CELOU tuto složku.
   3. Za pár vteřin dostaneš živou adresu *.netlify.app. Hotovo.

B) GITHUB PAGES (napojeno na GitHub)
   1. Založ repozitář a nahraj do něj obsah této složky.
   2. Settings → Pages → Deploy from branch → main / root.
   3. Web pojede na https://<jmeno>.github.io/<repo>/

C) CLOUDFLARE PAGES / VERCEL
   Stejný princip – drag-and-drop nebo napojení na GitHub repozitář.


VLASTNÍ DOMÉNA
--------------
Po nasazení můžeš v nastavení hostingu přidat vlastní doménu
(např. propiloty.cz nebo propiloty.app) a nasměrovat na ni DNS.
HTTPS certifikát udělají všechny služby výše automaticky a zdarma.

Pozn.: Pro hezký náhled při sdílení na sociálních sítích nastav po
nasazení v index.html u značky og:image ABSOLUTNÍ adresu, např.
https://tvojedomena.cz/icon-512.png
