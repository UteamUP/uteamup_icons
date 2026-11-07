UteamUP — Fólk í starfi / People at Work
1.200 ný SVG-tákn • 300 störf • 20 atvinnusvið • 12 lotur af 100

INNIHALD OG NOTKUN
Öll 1.200 SVG-táknin eru í þessari einu möppu, UteamUP_People.
Afritaðu *.svg í sameiginlegu táknamöppuna þína. Engar MDI-skrár.
Opnaðu index.html til að leita eftir íslensku eða ensku starfsheiti,
sía eftir atvinnusviði, útfærslu og lotu og velja forskoðunarstærð.
Yfirlitið og táknin virka án nettengingar.

300 STÖRF, FJÓRAR MANNESKJUÚTFÆRSLUR
Þetta eru 300 starfsheiti, hvert með fjórum teiknuðum manneskjum:
01 — kona; 02 — karlmaður; 03 — kynsegin manneskja;
04 — hinsegin manneskja með ótilgreint kyn.

Allt fólkið er skáldað. Sjálfsmynd er höfundarskráning, ekki ályktun
út frá hári, fötum eða útliti. Hárgreiðslur, andlitsform og líkamsstaða
dreifast óháð þessum útfærslum. Hinsegin sjálfsmynd er aðgreind frá
kyni í lýsigögnum; null merkir ótilgreint, ekki að viðkomandi tilheyri
ekki þeim hópi. Sama starfsmerki og viðeigandi vinnufatnaður fylgja
öllum fjórum manneskjuútfærslunum fyrir hvert starf.

NÖFN OG LOTUR
people-project-manager-01.svg
people-project-manager-02.svg
people-project-manager-03.svg
people-project-manager-04.svg

Hvert starfsheiti hefur stöðugt enskubundið skráarheiti og íslenskt
heiti í yfirliti og lýsigögnum. 25 störf × 4 útfærslur = 100 tákn í lotu.
Allar 12 loturnar eru í pakkanum. batches.json skráir nákvæma skiptingu.
Engin flokkun í undirmöppur er nauðsynleg fyrir notkun táknanna.

STÍLL
Teikniflötur: viewBox="0 0 32 32"; sjálfgefin birting 24 × 24 px.
Lína: stroke-width="1.2" á 32 eininga fleti, jafngildi 0,9 px við 24 px.
Litur: #1655A6. Gagnsær bakgrunnur, fill="none", ávalir línuendar.
Sama línuþykkt er á fólki, fatnaði, hjálmum og starfsmerkjum.
Táknin eru raunveruleg vektorgögn. Engar rastermyndir, táknaletur,
ytri leturskrár eða tengingar á önnur tákn eru innfelldar.
Við smáa birtingu er gagnlegt að hafa starfsheitið með tákninu.

LÝSINGAR OG ATHUGASEMDIR Í SVG
Hver skrá inniheldur:
<title> — starfsheiti og manneskjuútfærslu.
<desc> — lýsingu á manneskjunni, vinnufatnaði og sýnilegu starfsmerki.
<!-- ... --> — athugasemd um starfið, útfærsluna og starfsmerkið.
<metadata> — JSON með íslensku/ensku starfsheiti, flokki, sjálfsmynd,
útlitslýsingu og hönnunarstillingum.

title og desc eru ekki sýnilegar línur í teikningunni. Þau geyma heiti
og myndlýsingu; ARIA-vísanir eru á SVG-rótinni. Athugasemdir eru
ætlaðar þeim sem lesa kóðann. metadata nýtist við innlestur í kerfi.
Lýsingar eru á ensku; íslensk starfsheiti eru einnig í JSON og CSV.

Dæmi um SVG-lýsingu:
<title>Project manager — Woman</title>
<desc>A fictional woman working as project manager, wearing a
tailored jacket. Visible work cue: a project timeline with staggered
task bars.</desc>
<!-- Occupation: project-manager; person variant 01. -->

VEFNOTKUN
<img src="/icons/people-project-manager-01.svg"
     width="24" height="24" alt="Verkefnastjóri">

Notaðu alt á HTML img eftir samhengi. Fyrir skrautlegt tákn með
sýnilegu heiti við hliðina má hafa alt="". Innfelld SVG hefur title,
desc og role="img"; séu sömu SVG-gögn innfelld oftar en einu sinni
þarf hvert eintak sín einstöku id og samsvarandi ARIA-vísanir.
Yfirlitið index.html sér um það fyrir eigin forskoðanir.

Til að lita innfellt SVG með CSS má skipta stroke="#1655A6" út fyrir
stroke="currentColor" og stilla color á foreldri. Hægt er að breyta
width og height eftir birtingarstærð án þess að breyta viewBox.
Til að fá enn léttari línur má t.d. lækka stroke-width á rótinni úr
1.2 í 1.0; það jafngildir 0,75 px í 24 px birtingu.

YFIRLIT OG GÆÐAYFIRFERÐ
preview-people-overview.png sýnir 20 dæmi úr safninu.
preview-category-XX-YY.png sýnir hvert tákn í 96 og 24 px.
icon-list.csv tengir skráarheiti, íslensk/ensk starfsheiti og lýsingar.
manifest.json inniheldur lýsigögn allra 1.200 táknanna.
review.json tengir einstaklingsbundna sjónræna yfirferð við skráarhash.
validation.json geymir byggingar-, jaðar- og tvítekningarprófanir.

Fjórar manneskjur með sama starfsmerki eru meðvitaðar útfærslur
sama starfs. Mismunandi starfsheiti fá sitt eigið merki. Ekki er
notuð almenn staðgengilsmynd þegar starfsmerki vantar.

HEIMILDIR UM SVG
W3C, SVG 2 Document Structure: https://www.w3.org/TR/SVG/struct.html
W3C, XML Comments: https://www.w3.org/TR/xml/#sec-comments
Upprunalegar vektorteikningar búnar til fyrir þetta safn.
