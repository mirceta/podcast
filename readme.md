## Kako dela internet (za stare ljudi)

### Cilj

Cilj seminarske naloge je starejšim občanom predstaviti ISO/OSI model interneta s top-down pristopom. Predpostavka je, da učenec zna uporabljati spletni brskalnik za enostavna opravila kot je obiskovanje spletnih strani in brskanje. Zato razlago gradim iz te predpostavke - začnem na vrhu in nadaljujem proti nižjim plastem modela interneta.

### Ciljna skupina

Ciljna skupina so starejši občani, ki znajo uporabljati internet, vsaj do te mere, da znajo obiskovati spletne strani v poljubnem brskalniku in navigirati po njih. Na primer kaj poiskati v googlovem iskalniku, pogledati kaj je novega na 24ur.com ali brskati po facebooku in ga uporabljati.

V mislih sem imel natanko svoje stare starše. Zanimivo je, da vsi redno brskajo po spletnih straneh, dva stara starša imata tudi svoj facebook račun in sta na njemu aktivna. Nihče od njih pa pravzaprav ne razume kaj se dogaja v ozadju in kako vse skupaj sploh obratuje. Dedek mi je celo povedal, da ga zelo zanima, vendar verjame, da ob nobeni razlagi na svetu tega ne bo mogel razumeti.

### Podroben opis

#### Podcast 1: Frontend

#### Podcast 2: Backend

#### Podcast 3: Internet - Pošta slovenije


# Content

## Podcast 1 - Frontend

Računalnik je v večih pogledih zelo zakomplicirana stvar, kompleksnost interneta pa vse skupaj le še potencira. Enostavno je stvar razložiti tako, da je za laika preveč komplicirano ali pa je razlaga tako poenostavljena, da nam pravzaprav pove premalo in imamo na koncu še zmeraj očutek, da nimamo pojma za kaj se gre. Vodilo tega projekta bo to, da internet razložim na enostaven način, kjer poslušalec dobi široko sliko o delovanju interneta, vendar tak, da poslušalca ozavestimo česa ne ve in ga opremim vsaj s pravimi vprašanji za raziskovanje podrobnosti, če ga bo že to zanimalo.

Predpostavim, da poslušalec zna uporabljati osnovne funkcionalnosti v spletnem brskalniku.

- Zna obiskati spletno stran
- Mogoče kliknit na kakšen gumb

In za nadaljevalce:

- Zna uporabljati spletno aplikacijo kot je facebook.

Začnimo na mestu, ki ga poznamo, to je spletni brskalnik. Spletni brskalnik je program, s katerim dostopamo do spletnih strani in spletnih aplikacij. Večina od nas uporablja Internet Explorer, Chrome, Firefox ali katere druge.

Ne glede na to kateri spletni brskalnik uporabljate, vsi si v glavnem delijo isto osnovno nalogo, izpolniti cilj: Ko vpišem katero stran hočem in pritisnem Enter, hočem videti to stran. Ta posnetek je namenjen razlagi, kako spletni brskalnik dejansko to naredi.

Ko v brskalnik vpišemo naslov spletne strani, ki jo želimo, brskalnik 
iz interneta dobi to spletno stran. Spletna stran v nekem smislu pride kot ničle in enice po kablu na naš računalnik. Naj vas to ne zmede. 

Namesto, da se trudimo te ničle in enice razumeti, si na tem nivoju stvar predstavljamo na enostaven način. Recimo, da gremo na kanarske otoke na morje in ne znamo špansko vendar znamo angleško. Čeprav pridemo na morje in smo tam tujec in rabimo določene usluge od domačinov, se zanašamo na to, da domačini poznajo angleščino in da lahko z njimi komuniciramo tako. S tem vmesnim jezikom - angleščino, je bariera med nami in domačini razdrta. 

Podobna situacija je z nami in računalniki. Tudi ko gremo na splet, se v resnici pogovarjamo z našim računalnikom v nekem skupnem jeziku in mu naročamo kaj naj zahteva ali pošilja v internet. Če se navežemo na prejšnjo analogijo, je računalnik španec na morju s katerim želimo komunicirati, ničle in enice so španščina, mi pa smo prišli na morje.
V tej razlagi nam manjka le še del, kaj je naša angleščina, naš skupni jezik takrat, ko se pogovarjamo z računalnikom.

V splošnem je skupni jezik, programski jezik, ki ga govorita programer in računalnik. Ko programer želi, da računalnik naredi nekaj zanj, mu bo to naročil v nekem programskem jeziku. Za nas je pomemben le kontekst internetnega brskalnika, kjer sta relevantna le dva jezika, vsak s svojim namenom.

Imenovali ju bomo jezik za opis strani - **OPIS** (HTML) in jezik za opis stvari, ki se dogajajo na strani - **LOGIKA** (Javascript). V resnici, ko "gremo na neko spletno stran", iz interneta zahtevamo opis in logiko. Naš spletni brskalnik pa zna opis in logiko prevesti v lepe in odzivne spletne strani, ki jih mi potem uporabljamo. Pomembno je, da razumemo, da ne glede na to katero spletno stran gledamo, smo v resnici zahtevali njen opis in logiko. Iz interneta je to vedno edina stvar, ki jo zahtevamo in edina stvar, ki se prenaša.

V nadaljevanju bomo poskusili na kratko razložiti, kako sploh izgledata opis in logika.

Opis je načeloma dokument, v katerem so navodila za spletni brskalnik, kako za nas narediti pravilen prikaz dane spletne strani. Če za primer vzamemo stran google (in jo še rahlo poenostavimo), potem v opisu verjetno piše nekako takole:

- na sredino strani sliko kjer piše Google
- pod njo naj bo tekstovno polje
- pod tem tekstovnim poljem pa naj bo še gumb na katerem piše "iskanje Google"

Seveda, je to sporočilo napisano v jeziku za opis strani. Ima pa konec koncev identičen pomen. Kot smo povedali, če se pogovarjamo s tujcem v angleščini, se v resnici pogovarjamo iste stvari, le na prilagojen način, da se lahko razumemo.

Logika je načeloma dokument, v katerem so navodila o tem kakšni naj bodo odzivi na to da klikamo na gumbe, vpisujemo kaj v tekstovna polja, morda kako naj se kakšna slika spreminja s časom (animira), in podobno.

Recimo za stran google, morda v logiki piše, da naj ob tam, da miško premaknemo na gumb, postane gumb povdarjen (ima bolj izražene barve). Piše tudi, da naj bo tem, da nekaj vpišemo v tekstovno polje, brskalnik ponudi možnosti za dopolnitev tega kar iščemo. Naj takrat ko pritisnemo na gumb, brskalnik zopet pridobi iz interneta rezultat našega iskanja. Ta rezultat bo seveda zopet samo opis strani, ki vsebuje rezultat in pripadajoča logika.

V prvem podcastu smo spoznali, da ob uporabi interneta vseskozi komuniciramo s spletnim brskalnikom, ki mu v resnici naročamo, kaj naj pridobi iz interneta. Iz interneta za vsako stran, ki jo želimo, brskalnik dobi njen opis in logiko, ki sta dokumenta, napisana v nekem jeziku za opis strani in jeziku za opis stvari, ki se dogajajo na strani. Računalnik z internetom komunicira v ničlah in enicah, vendar nas ta jezik ne zanima, saj zna računalnik to prevesti tudi v jezik za opis stvari in jezik za logiko, ki ga programerji že razumejo. To kar mi vidimo, na koncu na ekranu, je rezultat tega da brskalnik sledi navodilom zapisanim v opisu in logiki strani.

## Podcast 2 - Backend

V prejšnem podcastu smo spoznali, kaj se zgodi po tem, ko prejmemo opis in logiko iz interneta. Izpustili pa smo to, da ne vemo kaj dejansko je internet. Povedali smo, da gre naš brskalnik zahtevati od interneta neko spletno stran, nismo pa povedali od kje v internetu potem dejansko pride naš odgovor.

Predstavljajmo si internet kot super hitro Pošto Slovenije. Takoj ko pošto oddamo v nabiralnik, se v našem nabiralniku magično že pojavi odgovor nanjo.

Recimo, da želimo nekemu podjetju Pohištvo d.o.o poslati pošto, v pošti pa sprašujemo po njihovi ponudbi glede stolov. Ne vemo kaj je naslov poslovalnice tega podjetja. Ker imamo super hitro Pošto Slovenije, se odločimo poslati pismo na AJPES, katerega naslov poznamo, kjer sprašujemo kaj je naslov poslovalnice tega podjetja. Pogledamo v naš nabiralnik in že nas čaka odgovor: Nekijeva ulica 5, soba 13. Zdaj imamo vse potrebno in napišemo pismo namenjeno Pohištvu d.o.o, na Nekijevo ulico 5. V trenutku v naš nabiralnik dobimo odgovor - katalog stolov vseh vrst.

Internet v resnici deluje podobno kot super hitra Pošta Slovenije. Pravzaprav ko vpišemo v brskalnik da bi radi šli na google (www.google.com), brskalnik najprej od nekakšnega internet AJPESa (DNS) dobi googlov naslov. Brskalnik že sam po sebi pozna naslov AJPESa. Ko mu DNS naslov vrne, gre na ta naslov zahtevati spletno stran. Kaj pa je na tem naslovu? 

Na tem končnem naslovu je pravzaprav še en računalnik. Vbistvu je to program na temu računalniku. Kot se vsi zavedamo, je računalnik sistem v katerem "živijo" programi. V resnici mi komuniciramo z nekim programom, ki se nahaja na računalniku. Analogija na Nekijevo ulico 5, sobo 13 je tole: Računalnik je zgradba, katere naslov je Nekijeva ulica 5, program pa živi v sobi 13.

Torej, ko zahtevamo spletno stran, celoten proces njenega pridobivanja zgleda takole:

- Brskalnik pošlje pošto na DNS in sprašuje kaj je naslov kjer lahko dobimo spletno stran www.google.com.
- DNS nam pove da je to 34.123.54.112, soba 8080.
- Brskalnik tedaj pošlje pošto na naslov 34.123.54.112, v sobo 8080.
- Program, ki živi v sobi 8080 na tem naslovu, dobi to pošto in nam na nas pripravi še eno pismo. V pismo doda opis in logiko spletne strani, potem pa jo pošlje po Internetu.
- Naš brskalnik prejme programov odgovor, prebere opis in logiko, potem pa po navodilih v opisu in logiki pripravi končen izgled spletne strani za nas, in to izriše na naš ekran.

Kako pa program na drugi strani, ki nam pošlje nazaj opis strani in logiko sploh pripravi sporočilo za nas?

Čeprav sta brskalnik in ta zaledni program, ki pripravlja odgovore oba programa, v resnici delujeta drugače. Zaledni program mora poznati vse detajle poslastva spletne strani, da lahko vrača pravilne odgovore.

## Podcast 3 - Internet

V prejšnjem podcastu smo spoznali od kje sploh pride neko sporočilo, ki ga iz brskalnika zahtevamo. Spoznali smo, da je na drugi strani še en računalnik, oziroma program, ki se izvaja na računalniku, ali kot smo rekli po analogiji, "živi v neki sobi v računalniku". Namen tega podcasta bo podrobnejši pogled vmesne poti med brskalnikom na našem računalniku in programom na računalniku od katerega pridobimo spletno stran.

Vsak zahtevek in odgovor, programi opremijo z dodatnimi podatki, ki jih vsi vmesni členi v spletu interneta potrebujejo, da prenesejo naše sporočilo od enega do drugega programa. V nadaljevanju bomo poenostavljeno pogledali najbolj razširjeno razlago tega, kako se neko sporočilo prenese iz enega konca na drug konec. Pravimo mu OSI model, mi se ga bomo lotili z enostavnimi analogijami.

OSI model je sestavljen iz večih plasti. Vsaka plast doda neke dodatne informacije našemu sporočilu, ki na njegovi poti do ciljnega računalnika služijo različnim namenom. Najprej si bomo pogledali nam, uporabnikom, najbližjo plast, ki je tudi edina do katere imamo kot uporabniki brskalnika dostop.

### Aplikacijska plast

Z aplikacijsko plastjo se ukvarja naš brskalnik. Najbolj smo se v prejšnjih podcastih ukvarjali s to plastjo. Ta plast specificira najrazličnejše protokole na nivoju aplikacij, kar se zdi precej komplicirano. Nas v resnici to ne zanima. Poenostavljeno, aplikacijska plast v resnici določi nekakšen sporazum med našim brskalnikom in programom, ki nam bo dostavil spletno stran, o tem kako se bosta pogovarjala. Na tem nivoju naš brskalnik dobi sposobnost, da izve, če je z dobljeno spletno stranjo vse v redu, ali je bilo kaj narobe. Lahko, da se je v oddaljenem programu kaj zalomilo in nam je sporočil, da enostavno ni mogel vrniti spletne strani. Morda nam sporoči, da nima stvari, ki jo mi želimo imeti. Morda pa našemu brskalniku le zagotovi, da je vse poteklo tako kot smo pričakovali. Iz naše strani pa aplikacijska plast zagotovi, da lahko oddaljenemu programu povemo, če od njega le želimo neko spletno stran, ali bi želeli da si morda kaj shrani. Morda želimo, da nekaj izbriše iz svojega spomina. Primer tega bi bil morda to, da na Facebooku hranimo svoje slike, zdaj pa jih želimo izbrisati. Glede na to, da te slike niso na našem računalniku, ampak jih hrani oddaljeni program, ga moramo zaprositi da jih izbriše. 

Torej aplikacijska plast zagotovi, da obe strani razumeta specificiranje tega kar sporočamo. Tu gre le za to, da povemo natančno, da nekaj želimo, da nam oddaljeni program nekaj pošlje, nekaj izbriše iz svojega spomina, morda kaj spremeni v svojem spominu. Iz druge strani, pa da nam zna oddaljeni program povedati, če je šlo vse v redu.

Nam ljudem je zelo naravno razumeti, da nam nekdo ne more dati nečesa kar si želimo, ali, da je odziv na neko našo željo drugačen od pričakovanega, vendar računalnik potrebuje točna navodila, da se lahko odzove na nepričakovane stvari tako kot bi hoteli.

### Sejna plast

S sejno plastjo se poskrbi, da se na nek način ustvari kontekst pogovora med brskalnikom in oddaljenim programom. Predstavljajmo si situacijo, ko kogarkoli srečamo. Nekako vemo, da ne moremo kar oditi iz našega pogovora, preden je pogovor končan. Mi imamo nekakšen protokol olike, bontona, manir ali kakorkoli že hočete. Ta protokol lahko seveda kršimo, vendar bo vsaj iz ene strani nastopila zmedenost. Lahko bi rekli, da v pogovoru obstaja nek kontekst, neka seja, kjer se stvari povezujejo med seboj.

Na podoben način se, ko se pogovarjata dva programa ustvari seja, ki je nekakšen kontekst njunega pogovora. Praktično nikoli si brskalnik in oddaljen program ne izmenjata le enega zahtevka in odgovora, ampak je vpletenih več zaporednih sporočil. Običajna praksa je tudi to, da se neko veliko sporočilo razbije na več kosov, kjer mora vsak udeleženec razumeti, katera sporočila sodijo skupaj in jim slediti, da lahko razume celoten pogovor. Vse to je stvar seje.

Za primer, kjer seja pride do izraza lahko pomislimo na Facebook. Preden lahko pogledamo svoj profil se moramo v Facebook vpisati. Takšen proces bi lahko izgledal takole:

- Brskalnik: Želim priti do svojega profila.
- Facebook: Kdo pa si sploh ti?
- Brskalnik: Jaz sem ta in ta, moje geslo je tole.
- Facebook: OK, izvoli in vstopi. Izvoli svojo karto, kadarkoli rabiš kaj od mene mi jo pošlji nazaj.
- Brskalnik: Želim videti svoje slike.
- Facebook: Izvoli.
- in tako dalje.

### Transportna plast

V transportni plasti se brskalnik in oddaljen program dogovorita za že bolj specifične stvari v komunikaciji, kot je na primer kako veliki naj bodo kosi sporočil, ki si jih med seboj pošiljata, ali raven zanesljivosti komunikacije med njima.

Vzemimo primer spletne strani. Če moramo spletno stran prejeti v več kosih, potem si ne moremo privoščiti, da katerega koščka ne bi dobili, saj potem morda celotna stran ne bo delovala pravilno. Tako se programa med seboj dogovorita, da bosta ob neprispelem koščku, le tega izmenjala še enkrat, vse dokler ne bo prispel.

Drugačno situacijo pa imamo, ko se pogovarjamo po telefonu. Dostikrat slišimo rahlo šumenje, ko se s kom pogovarjamo. Slišimo ga zaradi tega, ker so se neki kosi sporočil vmes izgubili, ali pa so bili pokvarjeni. Programa na telefonih sta se dogovorila, da je to v redu, saj le tako lahko kosi sporočil prihajajo dovolj hitro, da jih slišimo kot zvezen pogovor. Tako se lahko z nekom pogovarjamo tako kot bi se v resnici, če bi stal pred nami.

### Omrežna plast

Pri vsem pa ostane še en velik problem. Kako pa sploh potem računalnika komunicirata, če ni direktne žice med njima? Očitno so tu neki vmesni računalniki, ki morajo sporočilo prenesti. Temu smo prej rekli hitra Pošta Slovenije in tu lahko spoznamo kaj se dogaja v njej. Tudi to bomo poenostavili. Predstavljajmo si zelo enostaven način tega kako bi mi kot ljudje prenesli neko sporočilo iz enega konca sveta na drug konec.

Recimo, da smo na nekem vzporedni verziji sveta, kjer nimamo telefonov, nimamo pošte, skratka nobenih firm, ki bi bile sposobne za nas prenašati sporočila. Vse kar imamo so poznanstva z drugimi ljudmi. Živimo v Ljubljani, našega sina, ki živi na Havajih pa želimo vprašati če nas pogreša. Naše sporočilo napišemo na list papirja in začnemo premlevati kako bi lahko sporočilo prišlo do Havajev. 

Enostavna ideja je, da naše prijatelje vprašamo, če poznajo koga s Havajev. Morda ima neka naša prijateljica sina, za katerega ve, da ima punco v New Yorku. Sporočilo predate prijateljici, ki vam obljubi da ga bo dala svojemu sinu z napotki kam mora sporočilo priti.

Po parih tednih vam prijateljica prinese nazaj odgovor od vašega sina. Od vaše prijateljice naprej sicer ne veste kaj se je zgodilo s sporočilom, vendar nekako je vseeno prispelo na svoj cilj, in celo nekaj ste dobili nazaj. Le to vas zanima. Vmes se je lahko zgodila cela gora stvari:

- Prijateljica je sporočilo predala sinu.
- Sin je potoval k punci, ki je poznala nekoga iz druge strani amerike in je šla ravno k njemu na obisk naslednji teden. 
- Ta je poznal še nekoga, ki je bližje Havajem, in je ob obisku pri njemu predal sporočilo. 
- Eventualno je sporočilo prišlo na Havaje, kjer so našli nekoga, ki pozna nekoga, ki pozna vašega sina.

Morda je bilo na nek način v vaši smeri enako. Sicer se zdi ta metoda zelo neumna in ima veliko točk odpovedi, vendar je enostaven protokol za prenos sporočila. Edino pravilo je, da naj gre sporočilo vedno bolj proti cilju.

V komunikaciji računalnikov je precej podobno. Ko vaš brskalnik pošlje zahtevek oddaljenemu programu, je verjetno vmes še veliko drugih računalnikov, ki tako kot ljudje v naši zgodbi, znajo sporočilo prenesti vsaj malce bližje cilju. Eventualno, po večih prenosih med udeleženci, sporočilo pride to naslovnika, ki se odzove na isti način. 

### Povezovalna in fizična plast

Sedaj, ko vemo, kako se sporočilo prenaša po dejanskem internetu, s tem, da vsak vmesni računalnik pošlje sporočilo malce bližje njegovemu cilju, nam manjka le še podatek o tem, kako sporočilo dejansko pošljemo po mediju, ki je povezava med računalniki. To je lahko na primer kabel ali brezžični medij. Na tem nivoju gre za še nadaljnje pakiranje sporočila v nekaj čemur rečemo okno. Tu se zagotovi tudi, da se znajo vmesni računalniki odzivati na napake v sporočilu in naše sporočilo se dejansko zakodira v ničle in enice. To je seveda za nas neznan jezik, pomembno pa nam je le, da se ga da pretvoriti nazaj v nekaj razumljivega.

Ničle in enice v resnici predstavljajo napetost na žici. Če je v nekem trenutku na žici visoka napetost, potem pomeni da je to enica, če pa je nizka pomeni da je ničla, lahko pa je tudi ravno obratno. 

Ko ničle in enice pridejo do vmesnega računalnika, jih ta prebere, jih razume kot originalno sporočilo in se odloči kam bo to naprej poslal.