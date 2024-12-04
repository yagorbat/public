---
description: >-
  Обновленный в 2024 году файл правильного robots.txt, который учитывает
  особенности Битрикс последних версий, а также особенности robots.txt для
  популярных решений Aspro Next, Сотбит, Deluxe, Nextype
icon: code
---

# Готовый robots.txt для bitrix

```
User-Agent: *
Disallow: */index.php$
Disallow: /bitrix/
Disallow: /personal/
Disallow: */cgi-bin/
Disallow: /local/
Disallow: /test/
Disallow: /*show_include_exec_time=
Disallow: /*show_page_exec_time=
Disallow: /*show_sql_stat=
Disallow: /*bitrix_include_areas=
Disallow: /*clear_cache=
Disallow: /*clear_cache_session=
Disallow: /*ADD_TO_COMPARE_LIST
Disallow: /*ORDER_BY
Disallow: /*?print=
Disallow: /*?list_style=
Disallow: /*?sort=
Disallow: /*sort_by=
Disallow: /*?set_filter=
Disallow: /*?arrFilter=
Disallow: /*?order=
Disallow: /*&print=
Disallow: /*print_course=
Disallow: /*?action=
Disallow: /*&action=
Disallow: /*register=
Disallow: /*forgot_password=
Disallow: /*change_password=
Disallow: /*login=
Disallow: /*logout=
Disallow: /*auth=
Disallow: */auth/
Disallow: /*backurl=
Disallow: /*back_url=
Disallow: /*BACKURL=
Disallow: /*BACK_URL=
Disallow: /*back_url_admin*
Disallow: /*?utm_source=
Disallow: */order/
Disallow: /*download
Disallow: /test.php
Disallow: */filter/*/apply/
Disallow: /*setreg=
Disallow: /*logout
Disallow: */filter/
Disallow: /*sphrase_id
Disallow: */search/
Disallow: /*type=
Disallow: /*?product_id=
Disallow: /*?display=
Disallow: /*?view_mode=
Disallow: /*view=
Disallow: /*min_price=
Disallow: /*max_price=
Disallow: /*&page=
Disallow: /*?path=
Disallow: /*?route=
Disallow: /*?products_on_page=
Disallow: /*?PAGEN_1=1$
Disallow: /*?PAGEN_1=1/$
Disallow: /*?new=
Disallow: /*?edit=
Disallow: /*?preview=
Disallow: /*SHOWALL=
Disallow: /*SHOW_ALL=
Disallow: /*SHOWBY=
Disallow: /*SPHRASE_ID=
Disallow: /*TYPE=
Disallow: /*?utm*=
Disallow: /*&utm*=
Disallow: /*?VIEW=
Disallow: /*?SORT_TO=
Disallow: /*?SORT_FIELD=
Disallow: /*set_filter=
Disallow: */auth.php
Disallow: /*?alfaction=
Disallow: /*?oid=
Disallow: /*?name=
Disallow: /*?form_id=
Disallow: /*&form_id=
Disallow: /*?bxajaxid=
Disallow: /*&bxajaxid=
Disallow: /*?view_result=
Disallow: /*&view_result=
Disallow: */resize_cache/
Disallow: /*?linerow=
Disallow: /bitrix/panel/
Disallow: *?sort_ord=
Disallow: *?sort_dir=
Disallow: *?category_id=
Disallow: *?item_id=
Disallow: *?pn_pr=
Disallow: *?page=
Disallow: *?tab=
Disallow: *?display=
Disallow: *?linerow=
Disallow: *?year=
Disallow: *?oid=
Disallow: */filter/
Disallow: *showElements*
Disallow: *PAGEN_2*
Disallow: *?ORDER_ID=
Disallow: *how=*
Disallow: */form/?name=
Disallow: *?name=
Disallow: /*gclid*
Disallow: /*yclid*
Disallow: /*ymclid*
Disallow: /test*
Disallow: /404.php
Disallow: /api/*
Disallow: /*?RID*
Disallow: *?preview=
Disallow: *bitrix_*=
Disallow: *auth=
Disallow: /*?tag
Disallow: /*set_filter*
Disallow: /*?showElements=
Disallow: /*?tid*
Disallow: /*&tid*
Disallow: *?FILTER*=
Disallow: *?ei=
Disallow: *?p=
Disallow: *?q=
Disallow: *?tags=
Disallow: *B_ORDER=
Disallow: *BRAND=
Disallow: *CLEAR_CACHE=
Disallow: *SECTION_ID=
Disallow: *section_id=
Disallow: *SECTION[*]=
Disallow: *SHOW_ALL=
Disallow: *SHOWBY=
Disallow: *SORT=
Disallow: *SPHRASE_ID=
Disallow: *TYPE=
Disallow: /*?from*
Disallow: /*&from*
Disallow: /*block=*
Disallow: *r1=
Disallow: */?_ym_debug
Disallow: */apply/*
Disallow: *&by*
Disallow: *?by*
Disallow: *?id=*
Disallow: *?a=*
Disallow: *?amp*
Disallow: *IBLOCK_ID=*
Disallow: *RESULT_ID=*
Disallow: *PROPERTY=*
Disallow: *IN_STOCK=*
Disallow: *SECTION_CODE=*
Disallow: *SIZE=*
Disallow: *added=*
Disallow: *position=*
Disallow: *callibri=*
Disallow: *gtm_debug=*
Disallow: *placement=*
Disallow: *source=*
Disallow: *&adv=*
Disallow: *?adv=*
Disallow: *option=*
Disallow: *?hhtmFrom=*
Disallow: *?_r=*
Disallow: *sort_order=*
Disallow: *lang=*
Disallow: *etext=*
Disallow: *s=*
Disallow: *?ref=
Disallow: *?vk*
Disallow: *?fbclid=
Disallow: *?ORDER_ID=
Disallow: *?search_string=
Disallow: *?utm_referrer=
Disallow: *?orderby=
Disallow: *?start=
Disallow: *?roistat=
Disallow: *?roistat_pos=
Disallow: *?roistat_referrer=
Disallow: *?roistat_visit=
Disallow: *?iswebp=
Disallow: *?rb_clickid=
Disallow: *?erid=
Disallow: *?rrcid=
Disallow: *?target=
Allow: /upload/*
Allow: /bitrix/components/
Allow: /bitrix/cache/
Allow: /bitrix/js/
Allow: /bitrix/templates/
Allow: /bitrix/*.js
Allow: /bitrix/*.css
Allow: /local/components/
Allow: /local/cache/
Allow: /local/js/
Allow: /local/templates/
Allow: /local/*.js
Allow: /local/*.css
Allow: /local/*.jpg
Allow: /local/*.jpeg
Allow: /local/*.png
Allow: /local/*.gif
Crawl-delay: 30
Sitemap: https://ВАШДОМЕН/sitemap.xml

User-Agent: Yandex
Disallow: */index.php$
Disallow: /bitrix/
Disallow: /personal/
Disallow: */cgi-bin/
Disallow: /local/
Disallow: /test/
Disallow: /*show_include_exec_time=
Disallow: /*show_page_exec_time=
Disallow: /*show_sql_stat=
Disallow: /*bitrix_include_areas=
Disallow: /*clear_cache=
Disallow: /*clear_cache_session=
Disallow: /*ADD_TO_COMPARE_LIST
Disallow: /*ORDER_BY
Disallow: /*?print=
Disallow: /*?list_style=
Disallow: /*?sort=
Disallow: /*sort_by=
Disallow: /*?set_filter=
Disallow: /*?arrFilter=
Disallow: /*?order=
Disallow: /*&print=
Disallow: /*print_course=
Disallow: /*?action=
Disallow: /*&action=
Disallow: /*register=
Disallow: /*forgot_password=
Disallow: /*change_password=
Disallow: /*login=
Disallow: /*logout=
Disallow: /*auth=
Disallow: */auth/
Disallow: /*backurl=
Disallow: /*back_url=
Disallow: /*BACKURL=
Disallow: /*BACK_URL=
Disallow: /*back_url_admin*
Disallow: /*?utm_source=
Disallow: */order/
Disallow: /*download
Disallow: /test.php
Disallow: */filter/*/apply/
Disallow: /*setreg=
Disallow: /*logout
Disallow: */filter/
Disallow: /*sphrase_id
Disallow: */search/
Disallow: /*type=
Disallow: /*?product_id=
Disallow: /*?display=
Disallow: /*?view_mode=
Disallow: /*view=
Disallow: /*min_price=
Disallow: /*max_price=
Disallow: /*&page=
Disallow: /*?path=
Disallow: /*?route=
Disallow: /*?products_on_page=
Disallow: /*?PAGEN_1=1$
Disallow: /*?PAGEN_1=1/$
Disallow: /*?new=
Disallow: /*?edit=
Disallow: /*?preview=
Disallow: /*SHOWALL=
Disallow: /*SHOW_ALL=
Disallow: /*SHOWBY=
Disallow: /*SPHRASE_ID=
Disallow: /*TYPE=
Disallow: /*?utm*=
Disallow: /*&utm*=
Disallow: /*?VIEW=
Disallow: /*?SORT_TO=
Disallow: /*?SORT_FIELD=
Disallow: /*set_filter=
Disallow: */auth.php
Disallow: /*?alfaction=
Disallow: /*?oid=
Disallow: /*?name=
Disallow: /*?form_id=
Disallow: /*&form_id=
Disallow: /*?bxajaxid=
Disallow: /*&bxajaxid=
Disallow: /*?view_result=
Disallow: /*&view_result=
Disallow: */resize_cache/
Disallow: /*?linerow=
Disallow: /bitrix/panel/
Disallow: *?sort_ord=
Disallow: *?sort_dir=
Disallow: *?category_id=
Disallow: *?item_id=
Disallow: *?pn_pr=
Disallow: *?page=
Disallow: *?tab=
Disallow: *?display=
Disallow: *?linerow=
Disallow: *?year=
Disallow: *?oid=
Disallow: */filter/
Disallow: *showElements*
Disallow: *PAGEN_2*
Disallow: *?ORDER_ID=
Disallow: *how=*
Disallow: */form/?name=
Disallow: *?name=
Disallow: /*gclid*
Disallow: /*yclid*
Disallow: /*ymclid*
Disallow: /test*
Disallow: /404.php
Disallow: /api/*
Disallow: /*?RID*
Disallow: *?preview=
Disallow: *bitrix_*=
Disallow: *auth=
Disallow: /*?tag
Disallow: /*set_filter*
Disallow: /*?showElements=
Disallow: /*?tid*
Disallow: /*&tid*
Disallow: *?FILTER*=
Disallow: *?ei=
Disallow: *?p=
Disallow: *?q=
Disallow: *?tags=
Disallow: *B_ORDER=
Disallow: *BRAND=
Disallow: *CLEAR_CACHE=
Disallow: *SECTION_ID=
Disallow: *section_id=
Disallow: *SECTION[*]=
Disallow: *SHOW_ALL=
Disallow: *SHOWBY=
Disallow: *SORT=
Disallow: *SPHRASE_ID=
Disallow: *TYPE=
Disallow: /*?from*
Disallow: /*&from*
Disallow: /*block=*
Disallow: *r1=
Disallow: */?_ym_debug
Disallow: */apply/*
Disallow: *&by*
Disallow: *?by*
Disallow: *?id=*
Disallow: *?a=*
Disallow: *?amp*
Disallow: *IBLOCK_ID=*
Disallow: *RESULT_ID=*
Disallow: *PROPERTY=*
Disallow: *IN_STOCK=*
Disallow: *SECTION_CODE=*
Disallow: *SIZE=*
Disallow: *added=*
Disallow: *position=*
Disallow: *callibri=*
Disallow: *gtm_debug=*
Disallow: *placement=*
Disallow: *source=*
Disallow: *&adv=*
Disallow: *?adv=*
Disallow: *option=*
Disallow: *?hhtmFrom=*
Disallow: *?_r=*
Disallow: *sort_order=*
Disallow: *lang=*
Disallow: *etext=*
Disallow: *s=*
Disallow: *?ref=
Disallow: *?vk*
Disallow: *?fbclid=
Disallow: *?ORDER_ID=
Disallow: *?search_string=
Disallow: *?utm_referrer=
Disallow: *?orderby=
Disallow: *?start=
Disallow: *?roistat=
Disallow: *?roistat_pos=
Disallow: *?roistat_referrer=
Disallow: *?roistat_visit=
Disallow: *?iswebp=
Disallow: *?rb_clickid=
Disallow: *?erid=
Disallow: *?rrcid=
Disallow: *?target=
Allow: /upload/*
Allow: /bitrix/components/
Allow: /bitrix/cache/
Allow: /bitrix/js/
Allow: /bitrix/templates/
Allow: /bitrix/*.js
Allow: /bitrix/*.css
Allow: /local/components/
Allow: /local/cache/
Allow: /local/js/
Allow: /local/templates/
Allow: /local/*.js
Allow: /local/*.css
Allow: /local/*.jpg
Allow: /local/*.jpeg
Allow: /local/*.png
Allow: /local/*.gif

Clean-param: lang&etext&source&setreg&back_url_admin&logout&sphrase_id&action&utm_source&openstat&sort&sort_by&arrFilter&display&bxajaxid&view_mode&set_filter&alfaction&SORT_TO&SORT_FIELD&VIEW&bitrix_include_areas&clear_cache&part_id&q&start&orderby&error

Clean-param: etext&show_include_exec_time&show_page_exec_time&show_sql_stat&bitrix_include_areas&clear_cache&clear_cache_session&ADD_TO_COMPARE_LIST&ORDER_BY&print&list_style&sort&sort_by&set_filter&arrFilter

Clean-param: order&print_course&action®ister&forgot_password&change_password&login&logout&auth&backurl&back_url&BACKURL&BACK_URL&back_url_admin&utm_source&download&setreg&logout&sphrase_id&type&product_id

Clean-param: display&view_mode&view&min_price&max_price&page&path&route&products_on_page&PAGEN_1=1&new&edit&preview&SHOWALL&SHOW_ALL&SHOWBY&SPHRASE_ID&TYPE&utm&VIEW&SORT_TO&SORT_FIELD&set_filter&alfaction

Clean-param: oid&name&form_id&bxajaxid&bxajaxid&view_result&view_result&resize_cache&linerow&sort_ord&sort_dir&category_id&item_id&pn_pr&page&tab&display&linerow&year&oid&showElements&PAGEN_2&ORDER_ID&how

Clean-param: name&gclid&yclid&ymclid&RID&preview&bitrix_&auth&tag&set_filter&showElements&tid&FILTER&ei&p&q&tags&B_ORDER&BRAND&CLEAR_CACHE&SECTION_ID§ion_id&SHOW_ALL&SHOWBY&SORT&SPHRASE_ID&TYPE&from&block

Clean-param: gtm_debug&r1&_ym_debug&by&id&a&IBLOCK_ID&RESULT_ID&PROPERTY&IN_STOCK&SECTION_CODE&sort_order&_r&option&adv&source&placement&callibri&position&added&SIZE&search_string&bx_sender_conversion_id

Clean-param: ref&vk&fbclid&s&ORDER_ID&search_string&utm_referrer&orderby&start&roistat&roistat_pos&roistat_referrer&roistat_visit&page&iswebp&rb_clickid&erid&rrcid&target

	
User-Agent: Googlebot
Disallow: */index.php$
Disallow: /bitrix/
Disallow: /personal/
Disallow: */cgi-bin/
Disallow: /local/
Disallow: /test/
Disallow: /*show_include_exec_time=
Disallow: /*show_page_exec_time=
Disallow: /*show_sql_stat=
Disallow: /*bitrix_include_areas=
Disallow: /*clear_cache=
Disallow: /*clear_cache_session=
Disallow: /*ADD_TO_COMPARE_LIST
Disallow: /*ORDER_BY
Disallow: /*?print=
Disallow: /*?list_style=
Disallow: /*?sort=
Disallow: /*sort_by=
Disallow: /*?set_filter=
Disallow: /*?arrFilter=
Disallow: /*?order=
Disallow: /*&print=
Disallow: /*print_course=
Disallow: /*?action=
Disallow: /*&action=
Disallow: /*register=
Disallow: /*forgot_password=
Disallow: /*change_password=
Disallow: /*login=
Disallow: /*logout=
Disallow: /*auth=
Disallow: */auth/
Disallow: /*backurl=
Disallow: /*back_url=
Disallow: /*BACKURL=
Disallow: /*BACK_URL=
Disallow: /*back_url_admin*
Disallow: /*?utm_source=
Disallow: */order/
Disallow: /*download
Disallow: /test.php
Disallow: */filter/*/apply/
Disallow: /*setreg=
Disallow: /*logout
Disallow: */filter/
Disallow: /*sphrase_id
Disallow: */search/
Disallow: /*type=
Disallow: /*?product_id=
Disallow: /*?display=
Disallow: /*?view_mode=
Disallow: /*view=
Disallow: /*min_price=
Disallow: /*max_price=
Disallow: /*&page=
Disallow: /*?path=
Disallow: /*?route=
Disallow: /*?products_on_page=
Disallow: /*?PAGEN_1=1$
Disallow: /*?PAGEN_1=1/$
Disallow: /*?new=
Disallow: /*?edit=
Disallow: /*?preview=
Disallow: /*SHOWALL=
Disallow: /*SHOW_ALL=
Disallow: /*SHOWBY=
Disallow: /*SPHRASE_ID=
Disallow: /*TYPE=
Disallow: /*?utm*=
Disallow: /*&utm*=
Disallow: /*?VIEW=
Disallow: /*?SORT_TO=
Disallow: /*?SORT_FIELD=
Disallow: /*set_filter=
Disallow: */auth.php
Disallow: /*?alfaction=
Disallow: /*?oid=
Disallow: /*?name=
Disallow: /*?form_id=
Disallow: /*&form_id=
Disallow: /*?bxajaxid=
Disallow: /*&bxajaxid=
Disallow: /*?view_result=
Disallow: /*&view_result=
Disallow: */resize_cache/
Disallow: /*?linerow=
Disallow: /bitrix/panel/
Disallow: *?sort_ord=
Disallow: *?sort_dir=
Disallow: *?category_id=
Disallow: *?item_id=
Disallow: *?pn_pr=
Disallow: *?page=
Disallow: *?tab=
Disallow: *?display=
Disallow: *?linerow=
Disallow: *?year=
Disallow: *?oid=
Disallow: */filter/
Disallow: *showElements*
Disallow: *PAGEN_2*
Disallow: *?ORDER_ID=
Disallow: *how=*
Disallow: */form/?name=
Disallow: *?name=
Disallow: /*gclid*
Disallow: /*yclid*
Disallow: /*ymclid*
Disallow: /test*
Disallow: /404.php
Disallow: /api/*
Disallow: /*?RID*
Disallow: *?preview=
Disallow: *bitrix_*=
Disallow: *auth=
Disallow: /*?tag
Disallow: /*set_filter*
Disallow: /*?showElements=
Disallow: /*?tid*
Disallow: /*&tid*
Disallow: *?FILTER*=
Disallow: *?ei=
Disallow: *?p=
Disallow: *?q=
Disallow: *?tags=
Disallow: *B_ORDER=
Disallow: *BRAND=
Disallow: *CLEAR_CACHE=
Disallow: *SECTION_ID=
Disallow: *section_id=
Disallow: *SECTION[*]=
Disallow: *SHOW_ALL=
Disallow: *SHOWBY=
Disallow: *SORT=
Disallow: *SPHRASE_ID=
Disallow: *TYPE=
Disallow: /*?from*
Disallow: /*&from*
Disallow: /*block=*
Disallow: *r1=
Disallow: */?_ym_debug
Disallow: */apply/*
Disallow: *&by*
Disallow: *?by*
Disallow: *?id=*
Disallow: *?a=*
Disallow: *?amp*
Disallow: *IBLOCK_ID=*
Disallow: *RESULT_ID=*
Disallow: *PROPERTY=*
Disallow: *IN_STOCK=*
Disallow: *SECTION_CODE=*
Disallow: *SIZE=*
Disallow: *added=*
Disallow: *position=*
Disallow: *callibri=*
Disallow: *gtm_debug=*
Disallow: *placement=*
Disallow: *source=*
Disallow: *&adv=*
Disallow: *?adv=*
Disallow: *option=*
Disallow: *?hhtmFrom=*
Disallow: *?_r=*
Disallow: *sort_order=*
Disallow: *lang=*
Disallow: *etext=*
Disallow: *s=*
Disallow: *?ref=
Disallow: *?vk*
Disallow: *?fbclid=
Disallow: *?ORDER_ID=
Disallow: *?search_string=
Disallow: *?utm_referrer=
Disallow: *?orderby=
Disallow: *?start=
Disallow: *?roistat=
Disallow: *?roistat_pos=
Disallow: *?roistat_referrer=
Disallow: *?roistat_visit=
Disallow: *?iswebp=
Disallow: *?rb_clickid=
Disallow: *?erid=
Disallow: *?rrcid=
Disallow: *?target=
Allow: /upload/*
Allow: /bitrix/components/
Allow: /bitrix/cache/
Allow: /bitrix/js/
Allow: /bitrix/templates/
Allow: /bitrix/*.js
Allow: /bitrix/*.css
Allow: /local/components/
Allow: /local/cache/
Allow: /local/js/
Allow: /local/templates/
Allow: /local/*.js
Allow: /local/*.css
Allow: /local/*.jpg
Allow: /local/*.jpeg
Allow: /local/*.png
Allow: /local/*.gif
 
User-Agent: SemrushBot
Disallow: /
 
User-Agent: MJ12bot
Disallow: /
 
User-Agent: AhrefsBot
Disallow: /
 
User-Agent: gigabot
Disallow: /
 
User-Agent: Gigabot/2.0
Disallow: /
 
User-Agent: msnbot
Disallow: /
 
User-Agent: msnbot/1.0
Disallow: /
 
User-Agent: ia_archiver
Disallow: /
 
User-Agent: libwww-perl
Disallow: /
 
User-Agent: NetStat.Ru Agent
Disallow: /
User-Agent: WebAlta Crawler/1.3.25
Disallow: /
 
User-Agent: Yahoo!-MMCrawler/3.x
Disallow: /
 
User-Agent: MMCrawler/3.x
Disallow: /
 
User-Agent: NG/2.0
Disallow: /
 
User-Agent: slurp
Disallow: /
 
User-Agent: aipbot
Disallow: /
 
User-Agent: Alexibot
Disallow: /
 
User-Agent: GameSpyHTTP/1.0
Disallow: /
 
User-Agent: Aqua_Products
Disallow: /
 
User-Agent: asterias
Disallow: /
 
User-Agent: b2w/0.1
Disallow: /
 
User-Agent: BackDoorBot/1.0
Disallow: /
 
User-Agent: becomebot
Disallow: /
 
User-Agent: BlowFish/1.0
Disallow: /
 
User-Agent: Bookmark search tool
Disallow: /
 
User-Agent: BotALot
Disallow: /
 
User-Agent: BotRightHere
Disallow: /
 
User-Agent: BuiltBotTough
Disallow: /
 
User-Agent: Bullseye/1.0
Disallow: /
 
User-Agent: BunnySlippers
Disallow: /
 
User-Agent: CheeseBot
Disallow: /
 
User-Agent: CherryPicker
Disallow: /
 
User-Agent: CherryPickerElite/1.0
Disallow: /
 
User-Agent: CherryPickerSE/1.0
Disallow: /
 
User-Agent: Copernic
Disallow: /
 
User-Agent: CopyRightCheck
Disallow: /
 
User-Agent: cosmos
Disallow: /
 
User-Agent: Crescent
Disallow: /
 
User-Agent: Crescent Internet ToolPak HTTP OLE Control v.1.0
Disallow: /
 
User-Agent: DittoSpyder
Disallow: /
 
User-Agent: EmailCollector
Disallow: /
 
User-Agent: EmailSiphon
Disallow: /
 
User-Agent: EmailWolf
Disallow: /
 
User-Agent: EroCrawler
Disallow: /
 
User-Agent: ExtractorPro
Disallow: /
 
User-Agent: FairAd Client
Disallow: /
 
User-Agent: Fasterfox
Disallow: /
 
User-Agent: Flaming AttackBot
Disallow: /
 
User-Agent: Foobot
Disallow: /
 
User-Agent: Gaisbot
Disallow: /
 
User-Agent: GetRight/4.2
Disallow: /
 
User-Agent: Harvest/1.5
Disallow: /
 
User-Agent: hloader
Disallow: /
 
User-Agent: httplib
Disallow: /
 
User-Agent: HTTrack 3.0
Disallow: /
 
User-Agent: humanlinks
Disallow: /
 
User-Agent: IconSurf
Disallow: /
 
User-Agent: InfoNaviRobot
Disallow: /
 
User-Agent: Iron33/1.0.2
Disallow: /
 
User-Agent: JennyBot
Disallow: /
 
User-Agent: Kenjin Spider
Disallow: /
 
User-Agent: Keyword Density/0.9
Disallow: /
 
User-Agent: larbin
Disallow: /
 
User-Agent: LexiBot
Disallow: /
 
User-Agent: libWeb/clsHTTP
Disallow: /
 
User-Agent: LinkextractorPro
Disallow: /
 
User-Agent: LinkScan/8.1a Unix
Disallow: /
 
User-Agent: LinkWalker
Disallow: /
 
User-Agent: LNSpiderguy
Disallow: /
 
User-Agent: lwp-trivial
Disallow: /
 
User-Agent: lwp-trivial/1.34
Disallow: /
 
User-Agent: Mata Hari
Disallow: /
 
User-Agent: Microsoft URL Control
Disallow: /
 
User-Agent: Microsoft URL Control - 5.01.4511
Disallow: /
 
User-Agent: Microsoft URL Control - 6.00.8169
Disallow: /
 
User-Agent: MIIxpc
Disallow: /
 
User-Agent: MIIxpc/4.2
Disallow: /
 
User-Agent: Mister PiX
Disallow: /
 
User-Agent: moget
Disallow: /
 
User-Agent: moget/2.1
Disallow: /
 
User-Agent: MSIECrawler
Disallow: /
 
User-Agent: NetAnts
Disallow: /
 
User-Agent: NICErsPRO
Disallow: /
 
User-Agent: Offline Explorer
Disallow: /
 
User-Agent: Openbot
Disallow: /

User-Agent: Openfind
Disallow: /
 
User-Agent: Openfind data gatherer
Disallow: /
 
User-Agent: Oracle Ultra Search
Disallow: /
 
User-Agent: PerMan
Disallow: /
 
User-Agent: ProPowerBot/2.14
Disallow: /
 
User-Agent: ProWebWalker
Disallow: /
 
User-Agent: psbot
Disallow: /
 
User-Agent: Python-urllib
Disallow: /
 
User-Agent: QueryN Metasearch
Disallow: /
 
User-Agent: Radiation Retriever 1.1
Disallow: /
 
User-Agent: RepoMonkey
Disallow: /
 
User-Agent: RepoMonkey Bait & Tackle/v1.01
Disallow: /
 
User-Agent: RMA
Disallow: /
 
User-Agent: searchpreview
Disallow: /
 
User-Agent: SiteSnagger
Disallow: /
 
User-Agent: SpankBot
Disallow: /
 
User-Agent: spanner
Disallow: /
 
User-Agent: SurveyBot
Disallow: /
 
User-Agent: suzuran
Disallow: /
 
User-Agent: Szukacz/1.4
Disallow: /
 
User-Agent: Teleport
Disallow: /
 
User-Agent: TeleportPro
Disallow: /
 
User-Agent: Telesoft
Disallow: /
 
User-Agent: The Intraformant
Disallow: /
 
User-Agent: TheNomad
Disallow: /
 
User-Agent: TightTwatBot
Disallow: /
 
User-Agent: toCrawl/UrlDispatcher
Disallow: /
 
User-Agent: True_Robot
Disallow: /
 
User-Agent: True_Robot/1.0
Disallow: /
 
User-Agent: turingos
Disallow: /
 
User-Agent: TurnitinBot
Disallow: /
 
User-Agent: TurnitinBot/1.5
Disallow: /
 
User-Agent: URL Control
Disallow: /
 
User-Agent: URL_Spider_Pro
Disallow: /
 
User-Agent: URLy Warning
Disallow: /
 
User-Agent: VCI
Disallow: /
 
User-Agent: VCI WebViewer VCI WebViewer Win32
Disallow: /
 
User-Agent: Web Image Collector
Disallow: /
 
User-Agent: WebAuto
Disallow: /
 
User-Agent: WebBandit
Disallow: /
 
User-Agent: WebBandit/3.50
Disallow: /
 
User-Agent: WebCapture 2.0
Disallow: /
 
User-Agent: WebCopier
Disallow: /
 
User-Agent: WebCopier v.2.2
Disallow: /
 
User-Agent: WebCopier v3.2a
Disallow: /
 
User-Agent: WebEnhancer
Disallow: /
 
User-Agent: WebSauger
Disallow: /
 
User-Agent: Website Quester
Disallow: /
 
User-Agent: Webster Pro
Disallow: /
 
User-Agent: WebStripper
Disallow: /
 
User-Agent: WebZip
Disallow: /
 
User-Agent: WebZip
Disallow: /
 
User-Agent: WebZip/4.0
Disallow: /
 
User-Agent: WebZIP/4.21
Disallow: /
 
User-Agent: WebZIP/5.0
Disallow: /
 
User-Agent: Wget
Disallow: /
 
User-Agent: wget
Disallow: /
 
User-Agent: Wget/1.5.3
Disallow: /
 
User-Agent: Wget/1.6
Disallow: /
 
User-Agent: WWW-Collector-E
Disallow: /
 
User-Agent: Xenu's
Disallow: /
 
User-Agent: Xenu's Link Sleuth 1.1c
Disallow: /
 
User-Agent: Zeus
Disallow: /
 
User-Agent: Zeus 32297 Webster Pro V2.9 Win32
Disallow: /
 
User-Agent: Zeus Link Scout
Disallow: /
 
User-Agent: EmailSiphon
Disallow: /
 
User-Agent: EmailCollector
Disallow: /
 
User-Agent: teoma
Disallow: /
 
User-Agent: NjuiceBot
Disallow: /
 
User-Agent: Scrapy
Disallow: /
 
User-Agent: Baiduspider
Disallow: /

User-Agent: SeznamBot
Disallow: /
 
User-Agent: crawler
Disallow: /
 
User-Agent: JS-Kit
Disallow: /
 
User-Agent: HybridBot
Disallow: /
 
User-Agent: Voyager
Disallow: /
 
User-Agent: PostRank
Disallow: /
 
User-Agent: DomainCrawler
Disallow: /
 
User-Agent: MegaIndex.ru
Disallow: /
 
User-Agent: ltx71
Disallow: /
 
User-Agent: Exabot
Disallow: /
 
User-Agent: CCBot
Disallow: /
 
User-Agent: DotBot
Disallow: /
 
User-Agent: GetIntent\ Crawler
Disallow: /
 
User-Agent: Butterfly
Disallow: /
 
User-Agent: libwww
Disallow: /
 
User-Agent: SWeb
Disallow: /
 
User-Agent: LinkExchanger
Disallow: /
 
User-Agent: Soup
Disallow: /
 
User-Agent: GrapeshotCrawler
Disallow: /
 
User-Agent: DnyzBot
Disallow: /
 
User-Agent: spbot
Disallow: /
 
User-Agent: DeuSu
Disallow: /
 
User-Agent: MLBot
Disallow: /
 
User-Agent: InternetSeer
Disallow: /
 
User-Agent: BUbiNG
Disallow: /
 
User-Agent: FairShare
Disallow: /
 
User-Agent: Yeti
Disallow: /
 
User-Agent: Birubot
Disallow: /
 
User-Agent: YottosBot
Disallow: /
 
User-Agent: gold\ crawler
Disallow: /
 
User-Agent: Linguee
Disallow: /
 
User-Agent: Ezooms
Disallow: /
 
User-Agent: Purebot
Disallow: /
 
User-Agent: kmSearchBot
Disallow: /
 
User-Agent: SiteBot
Disallow: /
 
User-Agent: CamontSpider
Disallow: /
 
User-Agent: ptd-crawler
Disallow: /
 
User-Agent: HTTrack
Disallow: /
 
User-Agent: suggybot
Disallow: /
 
User-Agent: ttCrawler
Disallow: /
 
User-Agent: Nutch
Disallow: /
 
User-Agent: msnbot-media
Disallow: /
 
User-Agent: Abonti
Disallow: /
 
User-Agent: aggregator
Disallow: /
 
User-Agent: BDCbot
Disallow: /
 
User-Agent: BLEXBot
Disallow: /
 
User-Agent: Bullseye
Disallow: /
 
User-Agent: ca\-crawler
Disallow: /
 
User-Agent: Cegbfeieh
Disallow: /
 
User-Agent: coccoc
Disallow: /
 
User-Agent: CyotekWebCopy/1\.7
Disallow: /
 
User-Agent: CyotekHTTP/2\.0
Disallow: /
 
User-Agent: discobot
Disallow: /
 
User-Agent: Download Ninja
Disallow: /
 
User-Agent: EasouSpider
Disallow: /
 
User-Agent: FeedBooster
Disallow: /
 
User-Agent: Genieo
Disallow: /
 
User-Agent: grub\-client
Disallow: /
 
User-Agent: Harvest
Disallow: /
 
User-Agent: ieautodiscovery
Disallow: /
 
User-Agent: Incutio
Disallow: /
 
User-Agent: IstellaBot
Disallow: /
 
User-Agent: JamesBOT
Disallow: /
 
User-Agent: k2spider
Disallow: /
 
User-Agent: Keyword Density/0\.9
Disallow: /
 
User-Agent: libWeb
Disallow: /
 
User-Agent: linko
Disallow: /
 
User-Agent: LinkScan/8\.1a Unix
Disallow: /
 
User-Agent: lmspider
Disallow: /
 
User-Agent: lwp\-trivial
Disallow: /
 
User-Agent: magpie
Disallow: /
 
User-Agent: MaxPointCrawler
Disallow: /
 
User-Agent: MegaIndex
Disallow: /
 
User-Agent: memoryBot
Disallow: /
 
User-Agent: Mippin
Disallow: /
 
User-Agent: Missigua Locator
Disallow: /
 
User-Agent: Niki\-Bot
Disallow: /
 
User-Agent: NPBot
Disallow: /
 
User-Agent: OLEcrawler
Disallow: /
 
User-Agent: panscient\.com
Disallow: /
 
User-Agent: ProPowerBot/2\.14
Disallow: /
 
User-Agent: Python\-urllib
Disallow: /
 
User-Agent: Riddler
Disallow: /
 
User-Agent: serf
Disallow: /
 
User-Agent: SISTRIX
Disallow: /
 
User-Agent: sitecheck\.Internetseer\.com
Disallow: /
 
User-Agent: Serpstat
Disallow: /
 
User-Agent: SnapPreviewBot
Disallow: /
 
User-Agent: Sogou
Disallow: /
 
User-Agent: Spinn3r
Disallow: /
 
User-Agent: SpyFu
Disallow: /
 
User-Agent: Szukacz/1\.4
Disallow: /
 
User-Agent: Titan
Disallow: /
 
User-Agent: UbiCrawler
Disallow: /
 
User-Agent: UnisterBot
Disallow: /
 
User-Agent: Unknown
Disallow: /
 
User-Agent: uptime files
Disallow: /
 
User-Agent: User-Agent
Disallow: /
 
User-Agent: Vedma
Disallow: /
 
User-Agent: WBSearchBot
Disallow: /
 
User-Agent: Web Downloader/6\.9
Disallow: /
 
User-Agent: WebmasterWorldForumBot
Disallow: /
 
User-Agent: WebReaper
Disallow: /
 
User-Agent: Wotbox
Disallow: /
 
User-Agent: wsr\-agent
Disallow: /
 
User-Agent: WWW\-Collector\-E
Disallow: /
 
User-Agent: Zao
Disallow: /
 
User-Agent: ZyBORG
Disallow: /
 
User-Agent: ahrefs
Disallow: /
 
User-Agent: qwantify
Disallow: /
 
User-Agent: qwant
Disallow: /
 
User-Agent: semrush
Disallow: /
 
User-Agent: Detectify
Disallow: /
 
User-Agent: LinkpadBot
Disallow: /
 
User-Agent: FlipboardProxy
Disallow: /
 
User-Agent: aiHitBot
Disallow: /
 
User-Agent: trovitBot
Disallow: /
```
