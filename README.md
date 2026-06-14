DEFENCE HUB CZECHINVEST — web pro WordPress
============================================

Obsah složky (4 samostatné offline soubory, vše vložené — fonty, loga, animace):

  index.html            — Homepage (CZ)
  nato-diana.html       — NATO DIANA 2027 (CZ)
  index-en.html         — Homepage (EN)
  nato-diana-en.html    — NATO DIANA 2027 (EN)

Prokliky mezi stránkami i přepínač jazyka CZ/EN fungují,
pokud jsou VŠECHNY ČTYŘI soubory ve STEJNÉ složce.


JAK VLOŽIT DO WORDPRESSU
------------------------

Možnost A — vlastní URL (nejčistší)
1. Nahrajte celou tuto složku přes FTP / Správce souborů na server,
   např. do:  /public_html/defence-hub/
2. Web pak běží na adrese:  https://vasedomena.cz/defence-hub/
3. V menu WordPressu přidejte „Vlastní odkaz" na tuto adresu.

Možnost B — iframe uvnitř WordPress stránky
1. Nahrajte složku přes FTP, např. do:
   /wp-content/uploads/defence-hub/
2. Vytvořte novou stránku → blok „Vlastní HTML" → vložte:

   <iframe src="/wp-content/uploads/defence-hub/index.html"
           style="width:100%;height:100vh;border:0" loading="lazy"></iframe>

Možnost C — plugin
   Použijte plugin pro vkládání HTML (např. „WP Coder" nebo
   „HTML Snippets") a vložte obsah index.html.


POZNÁMKY
--------
- Formuláře (Konzultace, Přidat řešení, Registrace DIANA) vedou na
  externí odkazy (MS Forms, dnb.com, diana.tech) — fungují samostatně.
- Odpočet do uzávěrky 3. 7. 2026 běží automaticky.
- Soubory neupravujte ručně — jsou to zabalené (inlined) verze.
  Pro změny se ozvěte a upravíme zdrojové soubory.
