




/* Copyright 2008 Google. */ (function() { /*

Copyright The Closure Library Authors.
SPDX-License-Identifier: Apache-2.0
*/
(function(){function e(g){this.t={};this.tick=function(h,k,f){this.t[h]=[void 0!=f?f:(new Date).getTime(),k];if(void 0==f)try{window.console.timeStamp("CSI/"+h)}catch(m){}};this.getStartTickTime=function(){return this.t.start[0]};this.tick("start",null,g)}var a;if(window.performance)var d=(a=window.performance.timing)&&a.responseStart;var l=0<d?new e(d):new e;window.jstiming={Timer:e,load:l};if(a){var b=a.navigationStart;0<b&&d>=b&&(window.jstiming.srt=d-b)}if(a){var c=window.jstiming.load;0<b&&d>=
b&&(c.tick("\_wtsrt",void 0,b),c.tick("wtsrt\_","\_wtsrt",d),c.tick("tbsd\_","wtsrt\_"))}try{a=null,window.chrome&&window.chrome.csi&&(a=Math.floor(window.chrome.csi().pageT),c&&0<b&&(c.tick("\_tbnd",void 0,window.chrome.csi().startE),c.tick("tbnd\_","\_tbnd",b))),null==a&&window.gtbExternal&&(a=window.gtbExternal.pageT()),null==a&&window.external&&(a=window.external.pageT,c&&0<b&&(c.tick("\_tbnd",void 0,window.external.startE),c.tick("tbnd\_","\_tbnd",b))),a&&(window.jstiming.pt=a)}catch(g){}})(); })()



/* Copyright 2008 Google. */ (function() { function d(a){return document.getElementById(a)}window.byId=d;function g(a){return a.replace(/^\s+|\s+$/g,"")}window.trim=g;var h=[],k=0;window.JOT\_addListener=function(a,b,c){var f=new String(k++);a={eventName:a,handler:b,compId:c,key:f};h.push(a);return f};window.JOT\_removeListenerByKey=function(a){for(var b=0;b<h.length;b++)if(h[b].key==a){h.splice(b,1);break}};window.JOT\_removeAllListenersForName=function(a){for(var b=0;b<h.length;b++)h[b].eventName==a&&h.splice(b,1)};
window.JOT\_postEvent=function(a,b,c){var f={eventName:a,eventSrc:b||{},payload:c||{}};if(window.JOT\_fullyLoaded)for(b=h.length,c=0;c<b&&c<h.length;c++){var e=h[c];e&&e.eventName==a&&(f.listenerCompId=e.compId||"",(e="function"==typeof e.handler?e.handler:window[e.handler])&&e(f))}else window.JOT\_delayedEvents.push({eventName:a,eventSrc:b,payload:c})};window.JOT\_delayedEvents=[];window.JOT\_fullyLoaded=!1;
window.JOT\_formatRelativeToNow=function(a,b){a=((new Date).getTime()-a)/6E4;if(1440<=a||0>a)return null;var c=0;60<=a&&(a/=60,c=2);2<=a&&c++;return b?window.JOT\_siteRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a)):window.JOT\_userRelTimeStrs[c].replace("\_\_duration\_\_",Math.floor(a))}; })()



 

 var breadcrumbs = [{"path":"/project","deleted":false,"title":"\u0420\u041e\u0411\u041e\u0422\u0418/WORKS selection","dir":"ltr"},{"path":"/project/misce-place","deleted":false,"title":"\u041c\u0456\u0441\u0446\u0435/Place","dir":"ltr"},{"path":"/project/misce-place/nikita-kadan-ein-ort-des-zweifels","deleted":false,"title":"\u003ENikita Kadan \"EIN ORT DES ZWEIFELS\"","dir":"ltr"}];
 var JOT\_clearDotPath = 'http://www.gstatic.com/sites/p/f560b7/system/app/images/cleardot.gif';

 
 var JOT\_userRelTimeStrs = ["a minute ago","\_\_duration\_\_ minutes ago","an hour ago","\_\_duration\_\_ hours ago"];

 
 

 

 var webspace = {"gvizGstaticVersion":"current","enableAnalytics":false,"pageSharingId":"jotspot\_page","codeembeds":{"outerIframeSrc":"https://www.gstatic.com/jotspot/embeds/code/0f08d42392f2000e7e3f3daf5b427a43/outer\_iframe.html","innerIframeSrc":"https://1640754583-jotspot-embeds.googleusercontent.com/code/8d87fa64604b2a11fae2ed06104c58d3/inner\_iframe.html"},"enableUniversalAnalytics":false,"sharingPolicy":"OPENED\_WITH\_INDICATOR","siteTitle":"ladanakonechna.com","experiments":{"enableSubpagesGadgetInTakeout":true,"overrideDisableDomainEditing":false,"DisableSiteEditingFeature\_\_disable\_site\_editing":true,"disableDomainEditing":false},"jot2atari":{"eligibility":"INELIGIBLE"},"onepickUrl":"https://docs.google.com/picker","adsensePublisherId":null,"features":{"moreMobileStyleImprovements":null,"subscriptionDataMigrationInProgress":null,"plusBadge":false},"configProperties":{"disableSiteEditing":null},"isPublic":true,"newSitesBaseUrl":"https://sites.google.com","isConsumer":false,"serverFlags":{"jot2AtariLearnMoreUrl":"https://support.google.com/sites/answer/7035197"},"domainAnalyticsAccountId":"","plusPageId":"","signInUrl":"https://accounts.google.com/AccountChooser?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/project/misce-place/nikita-kadan-ein-ort-des-zweifels&service=jotspot","analyticsAccountId":"","scottyUrl":"/\_/upload","homePath":"/","siteNoticeUrlEnabled":null,"plusPageUrl":"","adsensePromoClickedOrSiteIneligible":true,"csiReportUri":"http://csi.gstatic.com/csi","sharingId":"jotspot","termsUrl":"//www.google.com/intl/en/policies/terms/","gvizVersion":1,"editorResources":{"sitelayout":["http://www.gstatic.com/sites/p/f560b7/system/app/css/sitelayouteditor.css"],"text":["http://www.gstatic.com/sites/p/f560b7/system/js/codemirror.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/codemirror\_css.css","http://www.gstatic.com/sites/p/f560b7/system/js/trog\_edit\_\_en.js","http://www.gstatic.com/sites/p/f560b7/system/app/css/trogedit.css","/\_/rsrc/1638433988000/system/app/css/editor.css","http://www.gstatic.com/sites/p/f560b7/system/app/css/codeeditor.css","/\_/rsrc/1638433988000/system/app/css/camelot/editor-jfk.css"]},"sharingUrlPrefix":"/\_/sharing","isAdsenseEnabled":true,"domain":"ladanakonechna.com","baseUri":"","name":"ladanakonechna-com","siteTemplateId":false,"siteNoticeRevision":null,"siteNoticeUrlAddress":null,"siteNoticeMessage":null,"page":{"isRtlLocale":false,"canDeleteWebspace":null,"isPageDraft":null,"parentPath":"/project/misce-place","parentWuid":"wuid:gx:47c1d80fbdef656f","siteLocale":"uk","timeZone":"America/Los\_Angeles","type":"text","title":"\u003ENikita Kadan \"EIN ORT DES ZWEIFELS\"","locale":"en","wuid":"wuid:gx:3ac1b244449530b6","revision":11,"path":"/project/misce-place/nikita-kadan-ein-ort-des-zweifels","isSiteRtlLocale":false,"pageInheritsPermissions":null,"name":"nikita-kadan-ein-ort-des-zweifels","canChangePath":true,"state":"","properties":{},"bidiEnabled":false,"currentTemplate":{"path":"/system/app/pagetemplates/text","title":"Web Page"}},"canPublishScriptToAnyone":true,"user":{"keyboardShortcuts":true,"sessionIndex":"","guest\_":true,"displayNameOrEmail":"guest","userName":"guest","uid":"","renderMobile":false,"domain":"","namespace":"","hasWriteAccess":false,"namespaceUser":false,"primaryEmail":"guest","hasAdminAccess":false,"isGoogleAdmin":false},"gadgets":{"baseUri":"/system/app/pages/gadgets"}};
 webspace.page.breadcrumbs = breadcrumbs;

 
 var JOT\_siteRelTimeStrs = ["\u0445\u0432\u0438\u043b\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0445\u0432\u0438\u043b\u0438\u043d \u0442\u043e\u043c\u0443","\u0433\u043e\u0434\u0438\u043d\u0443 \u0442\u043e\u043c\u0443","\_\_duration\_\_ \u0433\u043e\u0434\u0438\u043d \u0442\u043e\u043c\u0443"];



 window.jstiming.load.tick('scl');
 









>Nikita Kadan "EIN ORT DES ZWEIFELS" - ladanakonechna.com



 window.jstiming.load.tick('cl');
 



 








|  |  |
| --- | --- |
| [ladanakonechna.com](../../index.html) |  |
|  |







|  |  |  |
| --- | --- | --- |
| MENU* [????????????/NEWS](../../home/news)
* [????????????/WORKS selection](../../project)
	+ [2021](../2021)
		- [???????????????????????????? ??????????????/ Disciplined Vision](../2021/disciplinovane-bacenna-disciplined-vision)
	+ [2020](../2020)
		- [Images from abroad](../2020/images-from-abroad)
		- [Bodies in the distance](../2020/bodies-in-a-distance)
		- [???? ???????????????????? ?? ????????????????????/We shall be confronted with the possibility](../2020/mi-zitknemosa-z-mozlivistu)
		- [????????????????/Photozone](../2020/photozone)
		- [?? ?????????? ???? ?? ???????????? (??????????????????????)/In foliage and in stone (self-portrait)](../2020/u-listi-ta-v-kameni-avtoportret-in-foliage-and-in-stone-self-portrait)
		- [?????? ?????????? (???????????????????? ??????????????????)/ Untitled (dedicated to exhibitions)](../2020/bez-nazvi-prisvaceno-vistavkam-untitled-dedicated-to-exhibitions)
		- [??????????????/Package](../2020/pakunok-package)
		- [The search of a proper sign for the monument to the Polish protests](../2020/posuk-naleznoie-viviski-dla-pam-atnika-polskim-protestam-the-search-of-a-proper-sign-for-the-monument-to-the-polish-protests)
	+ [2019](../2019)
		- [??????????????/Flags](../flags)
		- [Historical pictures of the contemporary ruins](../2019/historical-pictures-of-the-contemporary-ruins)
	+ [2018](../2018)
		- [Background mode](../background-mode)
		- [Demonstration](../demonstration)
		- [Some examples from the field of management](../some-examples-from-the-field-of-management)
	+ [2017](../2017)
		- [??????????????/Teacher](../ucitel-teacher)
	+ [2016](../2016)
		- [????????????????/The exhibition](../the-exhibition)
		- [The music stops. The guests are embarrassed. Pause](../the-music-stops-the-guests-are-embarrassed-pause)
		- [???????????? ????????/Black Box](../cornij-asik-black-box)
		- [artists` motto](../artists-motto)
	+ [2015](../2015)
		- [Merge Visible](../merge-visible)
		- [????????/Hail (Grad)](../grad-hail)
		- [?????? ??????????/The so-called](../tak-zvani-the-so-called)
		- [War in Ukraine](../war-in-ukraine)
		- [?????????? ??????????????????/The deception of distance](../obman-distanciie-the-deception-of-distance)
	+ [2014](../2014)
		- [???????????????? ???????????????????? ????????????/Mobile portable model](../mobilna-portativna-model-mobile-portable-model)
		- [???????????????????????? ???????????? ?????????????????????? ????????????/Unstarted dialogue of unnamed characters](../---unstarted-dialogue-of-unnamed-characters)
		- [???????? ??????????????????????/Negotiating table](../stil-peregovoriv-negotiation-table)
		- [???????????????????? ?? ???????? ??????????????. ??????????????????????'??, 1973/Photos from my album. Transnistria, 1973](../photos-from-my-album-transnistria-1973)
		- [??????????????????????????/Reserved](../reserved)
		- [?????????? ??????????????/From left to right](../from-left-to-right)
	+ [2013](../2013)
		- [?????????????? ?????????????? ???????? ????????????/Object lesson of my participation](../naocnij-priklad-moeie-ucasti-object-lesson-of-my-partisipation)
	+ [2012](../2012)
		- [Bad face of Ukraine](../bad-face-of-ukraine)
		- [Drinking a bottle of vodka alone in the park surrounding the CCA Ujazdowski Castle, opposite to the pavilion of Rikrit Tiravanija, during summer festival "Green Jazd??w"](../drinking-alone)
		- [?????????? ?????? ????????/Almost the same](../majze-tez-same-almost-the-same)
		- [Welcome* if you can fit in](../welcome)
	+ [2011](../2011)
		- [???????????????????????? ??????/Personal shield](../personalnij-sit-personal-shield-1)
		- [???? ???????? ????????/One More Day](../se-odin-den-one-more-day)
		- [??????????????????/Enthusiasm](../entuziazm-enthusiasm)
		- [???????? ?? ????????/While I can see](../poki-a-bacu-while-i-can-see)
		- [???????? ???? ?????????????????? ??????????????/ Disciples and the illuminated plane](../-ucni-ta-osvitlena-plosina-disciples-and-the-illuminated-plane)
		- [???????????????? ?????? ????????/Monument for 2](../monument-dla-dvoh-monument-for-2)
		- [????????/Sea](../more-sea)
	+ [2010](../2010)
		- [????????????????/Cards](../listivki-cards)
		- [??????????????????????/Perspective](../perspektiva-perspective)
	+ [2009](../2009)
		- [??????????/Place](../misce-place)
		- [?????????????????????? ???????????? ??????????????????????/Investigation of manipulation mechanisms](../doslidzenna-sistem-manipuliciie-investigation-of-mechanisms-of-manipulation)
		- [????????????. ??????????. ????????/Before. Now. Further](../ranise-teper-dali-before-now-further)
		- [?????? ?????????? ???????? ???? ?????????????? ???????? ???? ?????? ???????????????????? ???????? ????????????????/Three points of view on common field and three possibilities to own it](../tri-tocki-zoru-na-spilne-pole-ta-tri-mozlivosti-jogo-pridbati-three-points-of-view-on-common-field-and-three-possibilities-to-own-it)
* [????????????????????/PUBLICATIONS](../../texts)
* [????????????????????/INFO](../../info)

LINKS* [>> Metod Fund](http://www.methodfund.org)
* [>> ?????????????????????? ????'?????????????? ??????????????/??uratorial Union HUDRADA](http://www.hudrada.tumblr.com)
* [>> Course of Art](http://courseofcontemporaryart.tumblr.com/)
* [>> -ICTM](http://istmkyiv.wordpress.com/)
* [>>PROSTORY](http://prostory.net.ua/)
* [R.E.P. group](../../r-e-p)
	+ [R.E.P. CV](../../r-e-p/r-e-p-cv)
	+ [R.E.P. Projects](../../r-e-p/r-e-p-projects)
 | 
 

[????????????/WORKS selection](../../project)??? > ???[??????????/Place](../misce-place)??? > ???
 

>Nikita Kadan "EIN ORT DES ZWEIFELS"





| 
EIN ORT DES ZWEIFELSNikita Kadan ??K??nstler, Mitglied der Gruppe R.E.P., Redakteur (mit Inga Zimprich und S??nke Hallmann) der Online-Kunstzeitschrift "Zombie"***Lada Nakonetschna,******DER ORT, Stiftung Zentrum******f??r zeitgen??ssische******Kunst, Kiew, 03.03.2009******Lada Nakonetschnas neue Arbeit balanciert zwischen der Offensichtlichkeit des Gezeigten und der Komplexit??t der Bedeutung. Dieses Konnotat ist wie aus einzelnen St??cken zusammengesetzt und funktioniert wie eine Maschine, die Fragen produziert.******Zwei Wochen lang hatte die K??nstlerin vertikale Bleistiftstriche an die W??nde eines******ger??umigen Saales im Fl??gel der Alten Akademie an der Nationalen Universit??t (Kiewer Mogyla-Akademie)******aufgetragen. Dieser Saal wird von acht von der Decke h??ngenden Strahlern ungleichm????ig ausgeleuchtet. Wo die Strahler helle Flecken an die Wand werfen, sind die Bleistiftstriche kraftvoller; an den dunkleren Stellen sind die Striche heller und zarter. Dort, wo Einrichtungsgegenst??nde oder Einbauten Schatten werfen, sind keine Striche gezogen. Auf diese Weise ???beseitigt??? Lada Nakonetschna visuell, sie ebnet die Unterschiede zwischen den Schatten und Lichtpartien ein und nimmt dem Betrachter die optische Orientierung.******Man wird von einem mittelgrauen Trugbild empfangen, das die Unterschiede zwischen den Ecken und den W??nden verwischt, die Kr??mmungen des Gew??lbes und die Stufe der Bodenleisten ausgleicht. Zugleich sieht man vor sich Abertausende einzelner Striche, deren Unterschiede in der Strichst??rke und im Aufdruck nur ganz aus der N??he und schwer zu erkennen sind. Der Akt der Angleichung heller und dunkler Stellen mit ungleichm????en Strichen f??hrt zu einem Spiel mit der Wahrnehmung des Betrachters, fast zum Entgleiten, Verschwinden. Aber diese unz??hligen Bewegungen des Bleistifts, die ???Quantit??t der Arbeit???, pr??sentieren sich in einer entmutigenden Appelllosigkeit. Das in dem Werk Dargestellte wird immer weniger greifbar, immer zweifelhafter. Was aber ist das pr??sentierte Werk, oder vielmehr was sagt es aus?**Es ist eine einf??rmige ???Handarbeit???, wie sie in der globalisierten Welt immer mehr diskriminiert wird.***
***Solche Handarbeit erweist sichals die Schattenseite des Waren??berflusses und muss von schlecht bezahlten und rechtlosen***
***Arbeitern erledigt werden. So ist der direkte Verweis auf die Arbeit, die an St??ckzahlen gemessen wird, zun??chst nur ein direkter***
***Hinweis auf die Kehrseite der kapitalistischen Gl??ckseligkeit.***

***Diese Tatsache, dass sich zur Erstellung von ???Der Ort??? geleistete/verschwendete Arbeit als qualifizierte erweist***
***(die K??nstlerin beherrscht die tonale Modellierung der Zeichnung), bleibt in der Offensichtlichkeit des Gezeigten verborgen:***
***mit der pr??sentierten ??bersteigerung einer in der Wiederholung untergehenden einzelnen Handbewegung.***
***Die scheinbare Offensichtlichkeit wird noch dadurch unterstrichen, dass die Intention dieser Arbeit ganz und gar nicht in der blo??en***
***Betrachtung liegt. Nur die intensivierte Wahrnehmung, die Analyse ???wie es gemacht ist???, l??sst ??berhaupt verstehen***
***???was man sieht???. Die Aktivierung des Bewu??tseins des Betrachters aber differenziert die Kunst als kritische Methode von***
***der spekulativen k??nstlerischen Unterhaltung.***

***Diese Arbeit von Lada Nakonetschna ist in dieser Hinsicht besonders symptomatisch, und das ist klar erkennbar:***
***Die K??nstlerin schafft ein Bild eines ???Ortes allgemein??? und zwar gerade an einem Ort, der derzeit eine Krise der***
***Selbstbestimmung erlebt.***

***Zugleich wird offenkundig ???Der Ort??? thematisiert, an dem diese Arbeit realisiert wurde. Die tonale Modellierung in der Zeichnung, mit der ??blicherweise eine Raumillusion in der Ebene erzeugt wird, dient hier als Mittel, reales Volumen eines Interieurs zu verbergen. Auf diese Weise wird der Saal, der lange Jahre als Ausstellungsraum des Zentrum f??r zeitgen??ssische Kunst der Nationalen Universit??t (Mogyla-Akademie) in Kiew diente, teilweise der Wiedererkennung entzogen. Ein solcher Versuch, die visuellen Charakteristika eines Raumes zu verwischen, bezieht sich auch auf dessen heutige unbestimmte Funktion. Seit 1995 hatte das Zentrum f??r zeitgen??ssische Kunst diese R??ume bespielt, aber im Dezember 2008 seine Schlie??ung verk??ndet. Nach den ??blichen Ritualen des Abschieds ergab sich jedoch bald ein Aufschub: Noch ein weiteres Jahr kann die Stiftung ???Zentrum f??r zeitgen??ssische Kunst??? - nicht im vollen Umfang und nicht eigenst??ndig, aber immerhin - die R??umlichkeiten im Fl??gel der Alten Akademie nutzen. Dieses Stadium ???kurz vor dem Tod??? zeichnet sich durch Begrenztheit seiner M??glichkeiten (das Zentrum kann nicht selbst ??ber die Nutzung seiner ehemaligen Ausstellungsr??ume entscheiden) und unklare Perspektiven aus. Die k??nftige Funktion des Raums, in dem diese Arbeit realisiert wurde, wird derzeit noch diskutiert. Er k??nnte im Rahmen der Stiftung weiter Ausstellungsraum bleiben, dem k??rzlich gegr??ndeten Zentrum visueller Forschung oder der Akademie selbst zugeschlagen werden - oder Teil der neuen R??ume der Bibliothek der Nationalen Mogyla-Akademie werden. Das ungekl??rte Schicksal, die unausger??umten Zweifel charakterisieren diesen Raum heute.******Zugleich sind diese Zweifel auch produktiv. Die Situation des Raumes verweist auf ???andere Orte??? der Kunst, oder - genauer gesagt - auf die Ungew??hnlichkeit solcher Orte. Die Zeit des Zentrums f??r zeitgen??ssiche Kunst an der Akademie, das lange eine wichtige Bastion nicht-kommerzieller Kunst in der ukrainischen Szene war, ist abgelaufen. Die lokale K??nstlergemeinschaft steht vor der Wahl: Entweder kann sie nur noch im Rahmen privater Unternehmen existieren (was heute zumindest auf den ersten Blick als alternativlos erscheint), oder sie schafft neue Formen der Institutionalisierung und Pr??sentation von Kunst. Wie diese Formen aussehen, h??ngt von den Ergebnissen der Diskussion ab, die allerdings bislang nur in einem kleinen Kreis junger K??nstler und Theoretiker gef??hrt wird. Vielleicht kommt dabei eine Art mobiler Mini-Institutionen heraus, die als Partner der unbeweglichen Schwergewichte der offiziellen Institutionen auftreten. Oder eher Netzwerke, die selbst zur Realisierung dieser und jeder Projekte in der Lage sind - oder beide Varianten zugleich. So oder so ist die Schlie??ung des Zentrums f??r zeitgen??ssische Kunst Ausl??ser f??r diese Diskussion. Und die derzeitige ???Galgenfrist??? bietet die M??glichkeit, diese Diskussion r??umlich zu fassen.*Ein weiteres Element kommt in Lada Nakonetschnas Arbeit zu den Themen Arbeit und Ort hinzu: die Zeit. Der lange Prozess der Entstehung dieses aufwendigen Werks m??ndet in einen einzigen Abend, an dem es pr??sentiert wird - danach werden die W??nde ??bermalt. Die Investion dieser Arbeitsleistung diente nicht der Erschaffung eines Gegenstandes. Vielmehr ist die k??nstlerische Arbeit das Erreichte - als Mittel der Demonstration von Arbeit und Zeitabl??ufen; zugleich kann ein spezieller Ort dem Zweifel und den Fragen anheimgestellt werden, die sich aus der Anwesenheit der Betrachter im Raumkunstwerk erst ergeben.
***ht*tp**://**www**.**zombie**.**ccc**-**k**.**net**/**>[??????????/Place](../misce-place)** |





 



 |







  







[Sign in](https://accounts.google.com/ServiceLogin?continue=http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/project/misce-place/nikita-kadan-ein-ort-des-zweifels&service=jotspot)|[Report Abuse](http://sites.google.com/a/ladanakonechna.com/ladanakonechna-com/system/app/pages/reportAbuse)|[Print Page](javascript:;)|Powered By **[Google Sites](http://sites.google.com/site)**






 window.jstiming.load.tick('sjl');
 


 window.jstiming.load.tick('jl');
 

 gsites.HoverPopupMenu.createSiteDropdownMenus('sites-header-nav-dropdown', false);
 

 JOT\_setupNav("2bd", "MENU", false);
 JOT\_addListener('titleChange', 'JOT\_NAVIGATION\_titleChange', 'COMP\_2bd');
 

 JOT\_setupNav("5938840112648904", "LINKS", false);
 JOT\_addListener('titleChange', 'JOT\_NAVIGATION\_titleChange', 'COMP\_5938840112648904');
 

 setTimeout(function() {
 var fingerprint = gsites.date.TimeZone.getFingerprint([1109635200000, 1128902400000, 1130657000000, 1143333000000, 1143806400000, 1145000000000, 1146380000000, 1152489600000, 1159800000000, 1159500000000, 1162095000000, 1162075000000, 1162105500000]);
 gsites.Xhr.send('http://www.ladanakonechna.com/\_/tz', null, null, 'GET', null, null, { afjstz: fingerprint });
 }, 500);


 window.onload = function() {
 if (false) {
 JOT\_setMobilePreview();
 }
 var loadTimer = window.jstiming.load;
 loadTimer.tick("ol");
 loadTimer["name"] = "load," + webspace.page.type + ",user\_page";
 window.jstiming.report(loadTimer, {}, 'http://csi.gstatic.com/csi');
 }
 

 JOT\_insertAnalyticsCode(false,
 false);
 

 var maestroRunner = new gsites.pages.view.SitesMaestroRunner(
 webspace, "uk");
 maestroRunner.initListeners();
 maestroRunner.installEditRender();
 

 JOT\_insertTranslateCode('en', 'uk');
 

 //<![CDATA[
 // Decorate any fastUI buttons on the page with a class of 'goog-button'.
 if (webspace.user.hasWriteAccess) {
 JOT\_decorateButtons();
 }

 // Fires delayed events.
 (function() {
 JOT\_fullyLoaded = true;
 var delayedEvents = JOT\_delayedEvents;
 for (var x = 0; x < delayedEvents.length; x++) {
 var event = delayedEvents[x];
 JOT\_postEvent(event.eventName, event.eventSrc, event.payload);
 }
 JOT\_delayedEvents = null;
 JOT\_postEvent('pageLoaded');
 })();
 //]]>


 JOT\_postEvent('decorateGvizCharts');
 

 JOT\_setupPostRenderingManager();
 

 JOT\_postEvent('renderPlus', null, 'sites-chrome-main');
 

 sites.codeembed.init();
 
 

 window.jstiming.load.tick('render');
 JOT\_postEvent('usercontentrendered', this);
 


