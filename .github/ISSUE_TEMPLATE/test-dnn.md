---
name: DEV-BE - PAGE template issue HOME PAGE
about: Composizione e configurazione moduli della home
title: "[DEV-BE][PAGE] - HOME PAGE"
labels: 'layer: be, ready for: Development'
assignees: ''

---

**PRIMOPIANO**
- [ ] Modulo EDN 
_Titolo modulo:_ Primo Piano Standard
_Container:_ NoTitle
_Modulo Condiviso:_ sì
_Indicizzazione:_ no

> **Configurazioni EDN**
> 2 - Display principale: 
> _nr art.:_ 4; 
> _Selezionare istanza modulo:_ seleziona istanza (es. Primo Piano)
> _Control Bar:_ disabilita Display in article list
> 4 - Filtra articoli: 
> Ordina per: Data Publicazione , Discendente
> Filtro categoria: Primo Piano
> _Articoli in evidenza:_ abilita Mantenere in cima
> 6 - Template e tema
> _Template Listing:_ List_Article_PrimoPiano
> _Template dettaglio:_ Details_Article_Default



**S0_col_8**
- [ ] Modulo EDN 
_Titolo modulo:_ [nome] (es. Dai Territori)
_Container:_ H2_Basic
_Modulo Condiviso:_ sì
_Indicizzazione:_ no

> **Configurazioni EDN**
> 2 - Display principale
> _nr art.:_ 4; 
> _Selezionare istanza modulo:_ seleziona istanza (es. Dai Territori)
> _Control Bar:_ disabilita Display in article list
> 4 - Filtra articoli 
> _Ordina per:_ Data Publicazione , Discendente
> _Filtro categoria:_ [nome categoria]
> _Articoli in evidenza:_ abilita Mantenere in cima
> 6 - Template e tema
> _Template Listing:_ List_Article_gridDueColonne
> _Template dettaglio:_ Details_Article_Default
> 14 - Formattazione dei contenuti:
> _Limitare larghezza titolo:_ 100
> _Limitare larghezza sommario:_ 140


**S0_col_4**
- [ ] Modulo HTML
_Titolo modulo:_ Social widgets
_Container:_ CCI_Unioni-SocialWidget
_Modulo Condiviso:_ sì
_Indicizzazione:_ no
_Intestazione:_ 
```
<!-- WIDGET FACEBOOK-->
<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/it_IT/sdk.js#xfbml=1&version=v9.0&appId=947908932327396&autoLogAppEvents=1" nonce="xcTpm2OE"></script>
```
_Contenuto:_
```
<div class="tab-content" id="widget-tabs">
<!-- WIDGET TWITTER -->
<div class="tab-pane fade show active" id="twitter"><a class="twitter-timeline text-center d-block p-4" data-height="900" href="https://twitter.com/Confcoop_ER?ref_src=twsrc%5Etfw"><span class="unableToLoad">
        <i class="fab fa-twitter text-blue"></i><br>
        <span class="text-smaller">I tweet non possono essere visualizzati sul browser che stai utilizzando. <br> Aggiorna il tuo browser o visualizza i post su Twitter.</span> </a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></div>
<!-- WIDGET FACEBOOK -->
<div class="tab-pane fade" id="facebook">
<div class="fb-page" data-adapt-container-width="true" data-height="900" data-hide-cover="false" data-href="https://www.facebook.com/ConfcooperativeEmiliaRomagna" data-show-facepile="false" data-small-header="true" data-tabs="timeline" data-width="">
<blockquote cite="https://www.facebook.com/ConfcooperativeEmiliaRomagna" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/ConfcooperativeEmiliaRomagna">Confcooperative Emilia Romagna</a></blockquote>
</div>
</div>
</div>
```

**S3_0_col_8**
- [ ] Modulo EDN Calendar
_Titolo modulo:_ Appuntamenti
_Container:_ NoTitle_Calendar
_Modulo Condiviso:_ sì
_Indicizzazione:_ no

> **Configurazioni EDN**
> Abilita: Mostra calendario, Mostra archivio
> Apri dettaglio articoli: Appuntamenti 
> Nr. eventi: 3
> Tema: CCI_Unioni


**S3_0_col_4**
- [ ] Modulo EDN
_Titolo modulo:_ L.A. ti consigliamo
_Container:_ H2_Basic
_Modulo Condiviso:_ sì
_Indicizzazione:_ no

> **Configurazioni EDN**
> 2 - Display principale
> _nr art.:_ 3; 
> _Selezionare istanza modulo:_ seleziona istanza
> _Control Bar:_ disabilita Display in article list
> 4 - Filtra articoli 
> _Ordina per:_ Data Publicazione , Discendente
> _Filtro categoria:_ [nome categorie]
> 6 - Template e tema
> _Template Listing:_ List_Article_TiConsigliamo_2
> _Template dettaglio:_ Details_Article_Cards


**S4_col_12**
- [ ] Modulo EDN
_Titolo modulo:_ I nostri partners
_Container:_ H2_Basic_Centered
_Modulo Condiviso:_ sì
_Indicizzazione:_ sì

> **Configurazioni EDN**
> _nr art.:_ []; 
> 4 - Filtra articoli 
> _Ordina per:_ Data Publicazione , Discendente
> _Filtro categoria:_ [nome categoria]
> 6 - Template e tema
> _Template Listing:_ List_Article_MultiItemCarouselHome
> _Template dettaglio:_ Details_Article_Cards


**FOOTER_col_12**
- [ ] Modulo HTML
_Titolo modulo:_ Footer Contatti
_Container:_ NoTitle_Padding
_Modulo Condiviso:_ no
_Indicizzazione:_ no
_Visualizza Il Modulo su Tutte le Pagine:_ Sì


**MENUBOTTOM_col_12**
- [ ] Modulo DDR Menu
_Titolo modulo:_ Footer Menu
_Container:_ NoTitle_noPadding
_Modulo Condiviso:_ no
_Indicizzazione:_ no
_Visualizza Il Modulo su Tutte le Pagine:_ Sì
> Menu impostazioni
> _Menu Style:_ Menus/FooterMenu
> _Nodes to include:_ Privacy, Note legali, Credits, Mappa del sito
> _Include hidden nodes:_ sì

