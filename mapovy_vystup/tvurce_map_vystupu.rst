Tvůrce mapového výstupu (Map composer)
======================================

Systém QGIS dokáže pracovat s různými formáty a zobrazovat je v
mapovém okně (viz :num:`#map-window`). Obsah mapového okna lze
jednoduše vyexportovat do obrázku. V případě, že je zapotřebí mapový
výstup určený pro tisk, který zachová nastavení zobrazování vrstev,
tak je nutné využít samostatný nástroj *Map Composer (Tvůrce mapového
výstupu)*. Důvodem je, že všechna nastavení (reference na vrstvy,
stylování, popisky a další) se sice ukládají do *.qgs* projektu, ale
ten je přenositelný pouze do QGIS systému.

.. todo:: nerozumim posledni vete (ML), composer prejima nastaveni z
          projektu anebo ne?

.. _map-window:
          
.. figure:: images/map_window.png
   :class: large
   :scale-latex: 80
 
   Mapové okno zobrazující vrstvy dle jejich stylování
       
.. figure:: images/composer_output.png
   :class: large
   :scale-latex: 80
 
   Ukázka výstupu

Map Composer umožňuje vytvořit z dat výstup v běžně používaných
formátech, jakými jsou např. PDF, PNG, JPEG a další. Takovýmto
způsobem je možné prezentovat jednotlivá data, jejich kombinaci nebo
výsledky různých analýz i bez potřeby speciálních kartografických
systémů.


Správce torby mapy
------------------

Systém QGIS umožňuje vytvářet víc než jeden mapový výstup na daný
projekt. Zpravování jednotlivých mapových výstupů umožňuje *Správce 
tvorby mapy* dostupný z menu :menuselection:`Projekt --> Správce 
tvůrců mapy`.

.. figure:: images/composer_manager.png
   :class: large
   :scale-latex: 80
 
   Otevření Správce tvorby mapy z menu.

Zde se nachází okno, kde jsou uvedeny všechny vytvořené mapové
výstupy. Pokud není doposud žádný vytvořený, tak je seznam prázdný a
pomocí tlačítka :item:`Přidat` se dá vytvořit nový.

.. figure:: images/add_new_composer.png
   :class: small
   :scale-latex: 30
 
   Zakládání nového mapového výstupu.

Vyskočí okno pro zadání názvu nově vytvářeného mapového výstupu. Po
zadání názvu a potvrzení tlačítkem :item:`OK` se tento vytvoří a
následně se otevře okno pro editaci a úpravu samotného mapového
výstupu.
        
        
.. tip:: Existující mapový výstup lze zkopírovat pomocí tlačítka
         :item:`Duplikovat`. Mapový výstup ke zkopírování se označí
         a pak se stiskne zmíněné tlačítko. V otevřeném okně se
         pak nastaví nový název mapového výstupu.

Pokud chcete otevřít existující mapový výstup, tak jej v seznamu
*Správce rvorby mapy* vyberte a tlačítkem :item:`Zobrazit` otevřete.
Všechny existující mapové výstupy jsou přístupné také z menu
:menuselection:`Projekt --> Tvorba map`.

Nastavení pracovní plochy
-------------------------

Jako první je nutné nastavit vlastnosti pracovní plochy. Toto
nastavení najdeme v pravé části v záložce :item:`Kompozice` část
:item:`Papír a kvalita`.

.. figure:: images/composer_plain.png
   :class: large
   :scale-latex: 80
 
   Okno nového mapového výstupu.

.. figure:: images/paper_settings.png
   :class: small
               
   Zakládání nového mapového výstupu - vlastnosti podkladu

Zde se nastaví velikost "papíru", jeho orientace, barva pozadí a
rozlišení v DPI při exportu. Tyto hodnoty lze přenastavit i v průběhu
práce. Do takto nastavené pracovní plochy lze začít přidávat
jednotlivé prvky.

.. tip:: Při tvorbě profesionálních mapových výstupů se doporučuje
         používat 400 DPI. Pro běžné použití je vhodné ponechat
         původní nastavení 300 DPI.
    
         V některých případech je nutné najít vhodnou kombinaci měřítka
         zobrazovaného mapového výřezu, velikosti podkladového papíru a
         příslušného DPI.

         DPI je zkratka pro *Dots per inch*, více informací na
         :wikipedia:`Wikipedii <DPI>`.
    
