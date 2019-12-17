Loppuraportti
===

### Sprint 1

Ensimmäisessä sprintissä aloittaminen vei aikaa. Osittain se johtui siitä, että aluksi emme tienneet,
mistä olisi viisasta lähteä liikkeelle. Johtuen siitä, että kaikki asiat olivat vielä epäselviä
keskustelu polveili ja hyppi. Kun pääsimme liikkeelle, configuraatioiden kohdalla huomasimme
autorisaatio-ongelman, joka johti siihen, että loimme erillisen gitHub-käyttäjän hoitamaan
pelkästään deployment pipelinen julkaisuvaiheen toteutuksen. Kun alun ongelmat saatiin ratkaistua,
keskustelu ja työnjako selkeytyi huomattavasti. 

Iloksemme huomasimme, että kaikilla on suhteellisen sama mielipide käytettävästä stackista, joka
helpotti toimintaa. Myös yleisesti alkuperäisen suunnitelman luominen meni vaivattomasti, sillä
kykenimme neuvottelemaan kaikkia miellyttävät ratkaisut toiminnallisuuksien toteuttamiseen. Työnjako
alkoi myös selvitä, ja äkkiä huomattiin jokaisen omat mielenkiinnon kohteet sekä osaamisen pääalueet.

Sprintin aikana toteutettujen toiminnallisuuksien määrä oli vähäinen alun konfiguroinnin, suunnittelun
ja yhteistyön opettelun takia, mutta saimme lähes kaiken toimimaan. Ainoa mainittava puute oli
applikaation palvelimella oleva versio. Emme ehtineet muuttaa frontendiä production-versioon,
sen sijaan Herokussa pyörivä versio jäi development-versioksi. Aiemmin mainittu autorisaatio-ongelma
johtui siitä, että deployaavan gitHub-käyttäjän omiin Heroku-projekteihin pääsi käsiksi kaikki
organisaation jäsenet. Tästä syystä koimme, että erillinen käyttäjä olisi tarpeellinen.

### Sprint 2
- Otimme liikaa työtä tähän sprinttiin. Iso osa user storyista jäi puolitiehen
- Todella paljon aikaa kului file-hostauksen keksimisessä.
- Kommunikaatio meni pieleen tällä viikolla. Paljon yksin työskentelyä eikä tieto uusista muutoksista ei kulkenut.
- File-hostauksen luominen jäi yhdelle henkilölle. Vain hän tietää miten se toimii.
- Cross-functional perjaate rikkoitui.
- UX oli tönkköä. Se olisi kuitenkin jossain määrin tärkeää.
- Vaikeuksista ja työn määrästä huolimatta lopputulos oli suhteellisen hyvä

### Sprint 3
- Osasimme ottaa sopivan määrän töitä
- Iso osan projektin toiminnalisuudesta jouduttiin uusia
- Tiimityö alkoi rullaamaan paremmin
- Legacy koodia jäi githubiin iso kasa. 
- Taskien jako sujui aika hyvin  

Kolmas sprintti alkoi rajulla todellisuudella. Asiakkaan testatessa aikaansaannostamme selvisi, että iso osa ohjelman toiminnallisuudesta ei toiminutkaan kuten oletimme. Lisäksi UX ei asiakkaalta varsinaisia kehuja saanut. Ensimmäinen toive asiakkaalta olikin, että toteuttaisimme kirjavinkkien näyttämisen taulukkona eikä listana, minkä seurauksena jouduimme kirjoittamaan ison osan frontendistä uudelleen. 

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
