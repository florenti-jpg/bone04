---
layout: post
title: Aplikacione të avancuara interneti (Rich Internet Applications) - 3
date: 2011-07-17 13:47
author: betim
comments: true
categories: []
tags: [albanian, shqip, aplikacione, rich internet applications]
---

*Për të lexuar pjesën e parë të shkrimit, kliko <a title="Aplikacione të avancuara interneti (Rich Internet Applications) – 1" href="http://betimdrenica.wordpress.com/2011/07/17/aplikacione-te-avancuara-interneti-1/" target="_blank">këtu</a>.
*Për të lexuar pjesën e dytë të shkrimit, kliko <a style="color:#0066cc;font-family:Georgia, 'Bitstream Charter', serif;line-height:1.5;" title="Aplikacione të avancuara interneti (Rich Internet Applications) – 2" href="http://betimdrenica.wordpress.com/2011/07/17/aplikacione-te-avancuara-interneti-2/" target="_blank">këtu</a>.

Në pjesën e fundit të kësaj serie të shkrimeve për aplikacionet e avancuara të internetit kemi folur për pjesën e konceptimit të aplikacioneve dhe për ambientin e integruar të zhvillimit, por duke ju përgjigjur edhe profilit të revistës dhe të lexuesve (potencial) të saj nuk jemi futur në detale, siç do ta bëjmë edhe në këtë pjesë, ku do të vazhdojmë të flasim për idenë se çka duhet të ofroj një Ria platformë zhvillimi për pjesën e përkrahjes pë zhvillimin e ndërfaqeve (user interfaces), për pjesën e gjuhëve programuese dhe fare pak do të përmendim se si është qasja e ndaj bazave të të dhënave nga persepktiva e këtij tipi të aplikacioneve.<!--more-->

<h1>Zhvillimi i ndërfaqeve</h1>
Një Ria platformë zhvillimi të pashmangshme në bërthamën e saj e ka pjesën e zhvillimit të ndërfaqeve (<em>user interfaces</em>) me të cilat përdoruesi interakton me zgjidhjen, e vlerëson atë, i lehtësohen proceset e punës së tij dhe në fund kryen funksionin që i takon (zgjidhjes). Prej shumë kohësh është bërë përpjekje nga shumë kompani, institute a trupa të ndryshëm (madje të bërë enkas për këtë problematikë) që të unifikohet platforma e zhvillimi të ndërfaqeve, mirëpo deri më sot kjo ka qenë e pamundur. Trupat rregullativ të standardeve shpeshë (për të mos thënë gjithmonë) janë treguar të ngathët dhe të ngadalshëm në specifikimin e teknikave dhe dokumenteve të nevojshme, duke quar kështu kompanitë tek ideja e zhvillimit të pjesëve të caktuara (shtojcave për shfletues) për të arritur zgjidhjen e plotë të problemeve. Në vitet e mëhershme ishte evidente paaftësia e HTML për të plotësuar nevojat e një Ria aplikacioni, dhe mu për këtë kemi daljen në skenë të “<em>teknologjive</em>” të bazuara në shtojca për shfletues (si flash, javafx e silverlight) të cilët i dhanë një dimension tjetër kësaj problematike. Përpos shtrirjes së gjerë e të pakontestueshme (siç është rasti me flash dhe silverlight) këto platforma zhvillimi i ofrojnë zhvilluesit një gamë të gjerë mundësishë dhe alternativash për të zgjidhur probleme dhe për të ofruar zgjidhje inovative për klientët. Por së bashku me benefitet janë evidente edhe konsekuencat e daljes së “gjuhëve të reja programuese” për zhvillimin e ndërfaqeve, duke i nxjerrë “telashe shtesë” zhvilluesve softuerik, dhe në të njejtën kohë duke u larguar nga standardet (pasi që çdo platformë ka logjikën dhe mënyrën e vetë të qasjes ndaj problemeve, që është edhe e natyrshme). Nuk duhet harruar që të gjitha këto platforma (cila më shumë e cila më pak) njëkohësisht lehtësuan tejmase punën për zhvilluesit softuerik duke sjellë konceptin e RAD (<em>rapid application development</em>) në qendër të tyre, dhe mu për këtë sot ne kemi vegla zhvillimi shumë të përparuara (shembulli i Visual Studio nga Microsoft, Flash Builder nga Adobe, apo Netbeans dhe Eclipse). Tani së fundi me përhapjen e paimagjinueshme të platformave mobile (që njëkohësisht kanë hapur edhe spektrin e shtrijes së Ria aplikacioneve), duke ruajtur me fanatizëm gjithsecila idenë e vetë të eksperiencës së përdoruesit, që nuk do të lejonin futjen e konceptit të shtojcave në to, është ngritur një nevojë e madhe për standardizimin e teknologjisë së zhvillimit të ndërfaqeve, dhe kjo më së shumti i ka kontribuar të shumëpërfolurës teknologji në kohët e fundit HTML5 (e cila në të njejtën kohë është kombinim edhe i metodologjive dhe teknologjive përcjellëse si CSS dhe të tjera). Neve tani nuk do të flasim shumë për HTML5 për ti lënë vendin një shkrimi apo serie shkrimesh ku do të mund të elaboronim më gjerë dhe gjatë pse kjo është e ardhmja, pse kjo është një investim me mend dhe cilat janë pikat e forta dhe të dobëta të saj.
<h1>Zhvillimi i logjikës së aplikacionit (kodi burimor)</h1>
Tek çdo Ria aplikacion është i pashmangshëm “koncepti i kodit burimor” apo thënë më thjeshtë nevoja për logjikë të caktuar të veprimit të aplikacionit. Për këtë çdo platformë zhvilluese Ria duhet të ofroj një funksionalitet të tillë, qoftë me komponenten skriptuese të saj apo me gjuhën/t programuese. Shembull Flash ofron ActionScript, Silverlight ofron tërë gamën e gjuhëve programuese brenda .Net (me një fokus të madh në C# dhe Visual Basic), JavaFx ofron Java etj. Kjo i kontribon në të njejtën kohë idesë së bashkimit të madh të zhvilluesve “të pastër” softuerik dhe të dizajnuesve grafik të softuerëve, por që më e rëndësishmja është se një Ria aplikacioni i japin fuqinë e gjuhës që përkrahin dhe përkrahjen për koncepte të ndryshme, si interaktimi me baza të të dhënave, arkitektura të fuqishme të dizajnimit (arkitektural), ofrimin e përvojave dhe zgjidhjeve të bëra më herët (në gjuhë të caktuara programuese), interaktimin edhe më të pastër me sistemet operative (duke dhënë qasje në API të ndryshëm), gamë të gjerë kontrollash, interaktim me shërbime të ndryshme webi etj.

Pra, siç edhe shihet kompanitë e ndryshme që merren me vegla për zhvilluesit kanë dhënë një kontribut të pakontestueshëm në zhvillimin e kësaj teknologjie por njëkohësisht e kanë vënë trupën e standardeve para një sfide të madhe me pyetjen më të thjeshtë, a mundet një platformë standarde (të marrim trendin HTML5) të jap tërë atë që japin sot këto vegla (<em>jo-standarde</em>)?! Pyetje kjo që mbetet të  marrë përgjigjje në kohët që po vijnë. Ne (zhvilluesit softuerik dhe arkitektët e zgjidhjeve softuerike) mendojmë se <em>duhet</em>, a mundet, <em>po presim</em>!

<em>\*Artikulli është botuar në <a title="CIO Albanian" href="http://www.cio.al" target="_blank">CIO Albanian</a></em>