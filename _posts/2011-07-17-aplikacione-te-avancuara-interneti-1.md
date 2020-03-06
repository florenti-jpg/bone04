---
layout: post
title: Aplikacione të avancuara interneti (Rich Internet Applications) - 1
date: 2011-07-17 13:01
author: betim
comments: true
categories: []
tags: [albanian, shqip, aplikacione, rich internet applications]
---

<h1>Hyrje</h1>
Me shtrirjen e internetit, evoluimin e teknologjisë nga dita në ditë edhe kërkesat e përdoruesve janë rritur, zgjeruar dhe ndryshuar me kalimin e kohës. Sot (si përdorues) kur nuk kemi problem me lidhjen e internetit dhe shpejtësinë e tij, ne dëshirojmë që shumicën e punëve ditore ti kemi në një vend të vetëm, të centralizuar por të qasshëm nga vendi në vend (nga kompjuteri personal, i punës, i shtëpisë, i kafeterisë ku mund të kalojmë një kohë të shkurtër, telefoni mobil madje, e gjetiu). Prej kohës është parë që uebi është një shans i mirë për zhvilluesit softuerik që të mund të japin një alternativë për zgjidhjen e këtij “problemi”. <!--more-->Mirëpo duke u nisë nga dëshira, e ndoshta më shumë edhe nga nevoja për kryerjen e disa detyrave komplekse (siç mund të jetë ngarkimi i të dhënave vizuale nga kamera e instaluar në kompjuter, apo printimi i përshtatur, po ashtu në printerin e instaluar lokalist apo në rrjetën lokale), është parë që aplikacionet  e “pastra” uebi nuk mund ta marrin barrën e plotë të zgjidhjes së kësaj problematike. Me këtë rast u desh një qasje pak më ndryshe apo më e zgjeruar (se sa vetëm një teknologji prezantuese siç është HTML), duke e sjellë në skenë një koncept, që edhe vetë ka ndryshuar nga dita në ditë, prej ideve të para e deri më sot – Aplikacionet e avancuara interneti (Rich internet applications). Nëse mund të bazohemi në shkrimet e Wikipedia-s termin “<em>rich internet application</em>” e hasim për herë të parë në një shkrim, në mars të vitit 2002 nga Macromedia (tash e bashkuar me Adobe), megjithëse si koncept ka ekzistuar ndër vite (edhe shumë kohë më parë madje) por me emërime tjera si: “<em>remote scripting</em>” nga Microsoft (rreth vitit 1999), “<em>X Internet</em>” nga  Forrester Research (tetor 2000), “<em>rich (web) clients</em>” dhe “<em>rich web application</em>”. Por në të vërtetë çka është një “aplikacion i avancuar interneti”, çka e veçon atë, si mund ti qasemi atij, cilat janë konceptet që e përbëjnë atë, cilat teknologji na mundësojnë të zhvillojmë diçka të tillë, si është përhapja e këtyre teknologjive, cili është raporti i tyre me standardet e hapura, ku është statusi i tyre, cili është mendimi im personal në raport me kahun dhe zhvillimet që duhet të merr ky koncept dhe tema tjera do të trajtojmë në këtë seri të shkrimeve.

[caption id="attachment_27" align="aligncenter" width="300" caption="Rich Internet Application Frameworks"]<a href="http://blog.betimdrenica.com/wp-content/uploads/2011/07/ria-1.png"><img class="size-medium wp-image-27" title="ria-1" src="http://blog.betimdrenica.com/wp-content/uploads/2011/07/ria-1.png?w=300" alt="rich internet application frameworks (flash, html5, silverlight)" width="300" height="65" /></a>[/caption]

<h1>Definicioni dhe ndërtimi (nga një pamje e lartë)</h1>
Aplikacion i avancuar interneti (<em>rich internet application</em>, më poshtë referuar si Ria aplikacion) është një ueb aplikacion (në thelb, i pastër) që ndërtohet për të liferuar tipare, mundësi dhe funksione normalisht, i  shoqëruar me një desktop aplikacion (“standalone”, shtojcë apo komponentë). Ria aplikacioni sipërfaqësisht, gjithë procesimin e të dhënave, qasjeve, manipulimeve dhe operacioneve tjera përcjellëse e realizon përmes internetit / rrjetit duke u shërbyer nga një ndërfaqe e përdoruesit (user interface) e cila shërben si klient dhe një shërbim (apo një mori shërbimesh) i cili vepron në anën e server aplikacionit (aplikacioneve).

Një Ria aplikacion normalisht ekzekutohet nga shfletuesi (<em>web browser</em>), dhe (shpesh) nuk kërkon instalime tjera përcjellëse për të punuar (hiq shtojcat e caktuara, për të cilat do të flasim më gjerë). Por, disa Ria aplikacione shpesh mund të punojnë vetëm me një seri të caktuar shfletuesish (jo me të gjithë që janë në përdorim), kështu, duke e përdorë mekanizmin e shtojcave (<em>add-ins</em>).

Për qëllime sigurie, pothuajse të gjithë Ria aplikacionet kanë qasje tejet të kufizuar në sistem operativ, duke e ngushtuar fushën e veprimit (të drejtat) vetëm në një hapësirë të vogël e cila quhet “sandbox”, e që është totalisht e izoluar nga pjesët tjera, koncept ky, i cili shmang shumë probleme të mundshme sigurie, probleme me virus dhe softuer dashakeq, etj. Por me tërë këto “limitime” një Ria aplikacion edhe në këtë hapësirë mund të funksionoj për mrekulli, duke mos u limituar në funksionalitete ose në atë që ofron për përdoruesin e fundit (<em>end-user</em>). Hapësira e lejuar, siç e thamë edhe më lartë, është e izoluar dhe shumë e vogël (zakonisht nis me 1 MB), por me aprovimin e përdoruesit (dijeninë e tij të plotë) kjo hapësirë edhe mund të rritet (programatikisht), nëse i nevojitet aplikacionit (dhe përdoruesi e aprovon një kërkesë të tillë). Kjo hapësirë përdoret për të ruajtur informacione të caktuara për aplikacionin, përdoruesin, sistemin apo edhe vetë komponentet e aplikacionit. Zakonisht programerët e përdorin këtë hapësirë edhe për baza lokale të të dhënave të cilat në shumicën e rasteve shërbejnë memorizim të përkohshëm (cache).

Në pjesët tjera do të vazhdojmë të flasim për teknologjitë e caktuara, përparësitë dhe mangësitë e tyre, shtrirjen apo përhapjen dhe informacione tjera interesante.

*Për të lexuar pjesën e dytë të shkrimit, kliko <a title="Aplikacione të avancuara interneti (Rich Internet Applications) – 2" href="http://betimdrenica.wordpress.com/2011/07/17/aplikacione-te-avancuara-interneti-2/" target="_blank">këtu</a>.
*Për të lexuar pjesën e tretë të shkrimit, kliko <a title="Aplikacione të avancuara interneti (Rich Internet Applications) – 3" href="http://betimdrenica.wordpress.com/2011/07/17/aplikacione-te-avancuara-interneti-3/" target="_blank">këtu</a>.

<em>\*Artikulli është botuar në <a title="CIO Albanian" href="http://www.cio.al" target="_blank">CIO Albanian</a></em>