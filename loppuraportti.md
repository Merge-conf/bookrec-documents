Loppuraportti
===

Merge conflictin kolmen viikon mittaiseen miniprojektiin kuului ylä- ja alamäkiä. Tässä raportissa käymme läpi projektin elinkaaren läpi sprintti kerrallaan samalla nostaen esiin asioita siitä mikä onnistui ja siitä missä jäi parantamisen varaan. Toteutimme projektin fullstack-kurssilta tutuilta teknologioilla. Tässä on kokemame.

### Sprint 1

Ensimmäisessä sprintissä aloittaminen vei aikaa. Osittain se johtui siitä, että aluksi emme tienneet, mistä olisi viisasta lähteä liikkeelle. Johtuen siitä, että kaikki asiat olivat vielä epäselviä keskustelu polveili ja hyppi. Kun pääsimme liikkeelle, konfiguraatioiden kohdalla huomasimme autorisaatio-ongelman, joka johti siihen, että loimme erillisen gitHub-käyttäjän hoitamaan pelkästään deployment pipelinen julkaisuvaiheen toteutuksen. Kun alun ongelmat saatiin ratkaistua, keskustelu ja työnjako selkeytyi huomattavasti. 

Iloksemme huomasimme, että kaikilla on suhteellisen sama mielipide käytettävästä stackista, joka helpotti toimintaa. Myös yleisesti alkuperäisen suunnitelman luominen meni vaivattomasti, sillä kykenimme neuvottelemaan kaikkia miellyttävät ratkaisut toiminnallisuuksien toteuttamiseen. Työnjako alkoi myös selvitä, ja äkkiä huomattiin jokaisen omat mielenkiinnon kohteet sekä osaamisen pääalueet.

Sprintin aikana toteutettujen toiminnallisuuksien määrä oli vähäinen alun konfiguroinnin, suunnittelun ja yhteistyön opettelun takia, mutta saimme lähes kaiken toimimaan. Ainoa mainittava puute oli applikaation palvelimella oleva versio. Emme ehtineet muuttaa frontendiä production-versioon, sen sijaan Herokussa pyörivä versio jäi development-versioksi. Aiemmin mainittu autorisaatio-ongelma johtui siitä, että deployaavan gitHub-käyttäjän omiin Heroku-projekteihin pääsi käsiksi kaikki organisaation jäsenet. Tästä syystä koimme, että erillinen käyttäjä olisi tarpeellinen.

### Sprint 2

Toisen sprintin suurin ongelma oli informaatiokatkokset. Kaikki ryhmän jäsenet eivät päässeet ensimmäiseen asiakastapaamiseen, jossa päätettiin ottaa sprinttiin toteutettavaksi toiminnallisuuksia, joista vain yhdellä ryhmän jäsenistä oli ennestään kokemusta, ja juuri hän ei päässyt suunnitteluun mukaan sairastumisen vuoksi. Ennen kun päätimme toteuttaa äänitiedostojen tallennukseen tarvittavan file hosting microservicen kuten yksi ryhmän jäsen oli jo aikaisemmin omassa projektissaan tehnyt, aikaa kului hukkaan erilaisten valmiiden ratkaisujen löytämiseen verkosta, mistä suurin osa oli maksullisia.

Microservicen toteuttaminen siiloutui lopulta vain yhdelle ryhmän jäsenelle, jolloin ketterän ohjelmistokehityksen cross-functional teams -periaate rikkoutui. Muu ryhmä joutui odottamaan oleellista toiminnallisuutta, jotta projekti pääsisi eteenpäin. UX jätti paljon toivomisen varaan tässä vaiheessa projektin etenemistä, mistä saimme palautetta asiakastapaamisessa. Siitä ei toisaalta oltu määritelty vielä tässä vaiheessa mitään, joten UX:n tönkköys oli tietyssä mielessä oikeutettua.

Lopulta erinäiset informaatiokatkokset johtivat siihen, että moni user story jäi puolitiehen, vaikka osa ryhmästä luuli niiden olevan jo valmiina. Toinen sprintti meni siis koko ryhmän mielestä selvästi heikoiten, kun tarkastellaan projektia kokonaisuudessaan. Kaikista vaikeuksista huolimatta projekti kuitenkin eteni kohtuullista vauhtia ja kolmanteen sprinttiin ei jäänyt ajallisesti paljoakaan korjattavaa toisen sprintin toiminnallisuuksista. Ymmärsimme ryhmänä aikataulutuksen tärkeyden.

### Sprint 3
- Osasimme ottaa sopivan määrän töitä
- Iso osan projektin toiminnalisuudesta jouduttiin uusia
- Tiimityö alkoi rullaamaan paremmin
- Legacy koodia jäi githubiin iso kasa. 
- Taskien jako sujui aika hyvin  

Kolmas sprintti alkoi rajulla todellisuudella. Asiakkaan testatessa aikaansaannostamme selvisi, että iso osa ohjelman toiminnallisuudesta ei toiminutkaan kuten oletimme. Lisäksi edellämainittu UX:än tönkköys ei asiakkaalta varsinaisia kehuja saanut. Ensimmäinen toive asiakkaalta olikin, että toteuttaisimme kirjavinkkien näyttämisen taulukkona eikä listana, minkä seurauksena jouduimme kirjoittamaan ison osan frontendistä uudelleen. 

Sprintti meni kuitenkin kaikin puolin paremmin kuin kaksi ensimmäistä. Emme tehneet samaa virhettä kuin toisessa sprintissä, vaan otimme sprinttiin sopivan määrän työtä. Työmäärää myös helpotti se, että iso osa kolmannen sprintin toiminnallisuudesta oli jo pohjustettu toisessa sprintissä. Sopivan työmäärän lisäksi ryhmän tiimityö ja taskien jako alkoi rullaamaan paremmin. Aikaa jäi jopa parantaa ohjelman tyylikkyyttä ja valmistautua loppudemoon. 

Vaikka viimeinen sprintti sujui hyvin, oli siinä kuitenkin myös parantamisen varaa. Ohjelmiston puolella frontendin uudelleenkirjoittamisen jälkeen projektiin jäi paljon turhaa ja käyttämätöntä koodia, jota kukaan ei uskaltanut poistaa. Tiimityöskennellyn puolella taas olisi voinut olla enemmän tiimitapaamisia.  

### Mitä parannetaan
- Tehdään töitä yhdessä paikassa
- Jonkinlainen vakio-aika tapaamiselle olisi hyvä.
- Tehdään töitä isommissa pätkissä
- Reviewaus oli hoidettu huonosti. Ei välttämättä tiennyt mitä tarkalleen olisi pitänyt reviewata.
- Reviewaus voitaisi hoitaa ehkä pull-requestina
- Testauksen olisi pitänyt kattavampaa

### Mikä sujui hyvin
- Koko tiimi tunsi toisensa ennen projektin alkua muka helpotti yhteistyötä
- Toisen sprintin aikana järkeistimme user pointien jakoa

### Mitä opimme
- Uusia teknologioita
- Käytännön scrum
- Miksi scrum on parempi kuin esim. vesiputous
- Aikataulutus on tärkeää
- Lukemaan toisen koodia
- Integroimaan omaa koodia muiteen koodiin
- Opimme pariohjelmoinnin hyödyistä

### Turhauttavaa
- Projektia sai tehdä vain hyvin vähän aikaa. Ei  päässy kunnolla rytmiin.
- Ajan puutteen takia jouduimme miettimään esim. pidetäänkö retro yms.
- Testausvaatimukset olivat epäselviä
- Reviewaus ei tuntunut merkitykselliseltä.

Mitä projektissa jäi yleisesti parantamisen varaan on parempi kommunikaatio ja pyrkimys tehdä töitä yhdessä sovitussa paikassa tiettyyn aikaan. Heikko kommunikaatio johti osittain siihen, että osa töistä joutui odottamaan, koska ei ollut riittävää tietoa tehdä päätöstä yksin tai saatettiin aloittaa jo toisen user storyn tekemistä, vaikka joku muu oli jo sen tekemisen aloittanut. Nämä ongelmat olisi saanut ratkaistua helposti, jos oltaisiin pystytty sopia tietty aika ja paikka tekemiselle, jolloin tiedon välityksessä ei olisi ollut ongelmia ja kaikki olisivat tietoisia, missä vaiheessa projekti on. Tavallisesti heikko kommunikaatio johtui siitä, että henkilö ei ollut kyseisellä ajanhetkellä tavoitteavissa.

Toinen parannettava seikka on, miten koodin reviewaus oli toteutettu. Päätimme ensimmäisestä viikosta lähtien käyttää Kanban -tyylistä lappu systeemiä trellossa kuitenkaan ilman mitään WIP -rajoitteita, joka johti siihen, että review -palkki oli lopulta täynnä reviewausta odottavia taskeja. Tämä myös johti siihen, että henkilö joutui etsimään koodista ne kohdat, joita oli muokattu taskin suorittamisen aikana. Tämä vei henkilöltä aikaa ja joskus henkilö ei ymmärtänyt, minkä takia jotain kohtia on muutettu koodissa. Tällöin henkilön täytyi varmistaa koodin muokannneelta henkilöltä, minkä takia muutos on tehty, joka taas vei aikaa. Oli myös tilanteita, joissa henkilö oli reviewannut koodin, mutta jälkikäteen oli huomaatu, että taskin toiminnallisuus ei toimikaan, jolloin laput olivat vuorotellen  done ja review tilassa. Jälkikäteen ryhmässä mietimme, että githubin PR:ät olisivat auttaneet tässä. Tällöin ei olisi tarvinnut henkilöiden etsiä muutettuja koodin pätkiä ja kokonaisuus olisi ollut helpompi arvioida.

Onnistunut asia oli, että ensimmäisen sprintin jälkeen järjestimme taskien jaon selkeämmäksi. Ensimmäisessä sprintissä taskit olivat vain listattuna ilman minkäänlaista priorisointia tai tietoa, mihin user storyyn taski littyi. Toisen sprintin alussa päätimme priorisoida taskit user storyen mukaan ja numeroimme taskit, jolloin oli selvää mihin storyyn taski kuului. Tämä selkeytti työskentelyä ja taskien jakoa merkittävästi.

Projektissa opimme myös paljon uusia teknologioita ja käytänteitä. Ehkä suurin oppi projektissa oli, miten Scrum -malli toimii käytännössä ja miten ryhmä toimii sen kanssa. Miniprojekti selkeytti myös, minkä takia Scrumin kaltaisia inkrementaalisia malleja suositaan nykyään käytettävän vesiputousmalleista. Scrum -mallin lisäksi opimme myös perustavien käytänteiden merkitystä, joista mainittakoon aikataulutus.

Projektin aikana opimme myös lukemaan toisen kirjoittamaa koodia paremmin. Yliopistolla toisen henkilön kirjoittaman koodin lukemista on ollut jonkin verran, mutta tässä projektissa oli jopa mielekästä lukea toisen henkilön kirjoittamaa koodia. Tällöin näkyi hyvin miten ajatukset vaihtelevat per henkilö toteutustavoista. Varsinkin, jos koodia on muutetu kohdista, johon koodia lukeva henkilö on myös kirjoittanut. Tämä nosti keskustelua esiin, jossa molemmat osapuolet useimmiten oppivat jotain uutta.

Mitä hyvää projektissa myös oli, että kaikki ryhmät jäsenet tunsivat toisensa entuudestaan jostain aikaisemmista kursseista tai taphtumista, joka edesauttoi merkittävästi ryhmähengen muodostumisessa. Alusta lähtien kaikilla oli helppo kysyä toiselta apua, mielipidettä tai selitystä johonkin projektiin liittyvästä asiasta.
Opimme myös yleisesti toimimaan ryhmässä, kun tavoitteena oli saada tuotettua toimivaa ohjelmistoa. Erityisesti opimme integroimaan omaa koodiamme toisen muun kirjoittamaan koodiin. Opimme myös, kuinka tehokasta on koodata pariohjelmoinnilla. Opimme, kuinka paljon se nopeuttaa tekemistä ja vähentää koodiin syntyviä bugeja, kun toinen henkilö pystyy antamaan heti oman mielipiteensä, miten asia tulisi koodata, tai toinen huomaa mahdollisesti syntyvän bugin. Pariohjelmoitaessa on myös helpompi löytää vika, jos koodi aiheuttaa virheen.

Mitä turhauttavaa kurssiin liittyi oli esimerkiksi, että henkilö ei saanut käyttää projektiin viikossa enemmän aikaa kun 6 tuntia. Tämä aiheutti hieman harmaita hiuksia, koska ryhmäläiset suurimmalti osalti ovat henkilöitä, jotka saisivat 6 tuntia käyettyä yhden päivän aikana. Vähäisestä ajasta johtuen jouduimme myös miettimään, että pidetäänkö viikottain retro vai ei. 

Toinen turhauttava seikka oli myös, että ei ollut täysin selvää, miten ja millä tasolla testaus olisi tullut suorittaa. Koska teknologiat, joita ryhmämme käytti projektissa olivat eroavat siitä, mitä kurssilla suositeltiin, niin testaukäytänteet myös erosivat. Tämä johti siihen, että piti selvittää, miten testit suoritamme, mitä testejä luomme ja kuinka kattavasti. Yksi esimerkki tästä oli, että kuinka kattavasti teemmeyksikkötestejä, kun cypressin suorittamat E2E -testit käytännössä kattasivat yksittäisten komponenttien testaamisenkin.

Yleisellä tasolla projekti tuntui ryhmäläisille onnistuneelta. Vaikka projektin aikana olikin paljon avoimia kysymyksiä ja teknisiä ongelmia, niin nämä kuitenkin saatiin ratkaistua kommunikoinnin ja ryhmätyön avulla. Lisäksi kaikki ryhmäläiset oppivat jotain uutta projektia tehdessä, joko teknologioita, toteutustapoja tai toimintamalleja. Lisäksi kaikki oppivat virheistä ja pystyvät tarvittaessa parantamaan näistä seuraavaan projektiin.