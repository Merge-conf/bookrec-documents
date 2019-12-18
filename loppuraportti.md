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
