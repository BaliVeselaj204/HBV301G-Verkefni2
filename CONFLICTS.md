# Árekstrar milli hagsmunaaðila

## Nákvæmni skráningar gegn tekjum af sektum


- **Árekstur:** Kerfið er hannað til að útrýma sektum sem stafa af gleymdri greiðslu (sjá [BREQ-1](../Verkefni1/business_requirements.md#breq-1)) og til að skrá stæðistíma með mikilli nákvæmni (sjá [QA-1](../Verkefni1/quality_attribute.md#qa-1)). Fyrir rekstraraðilann eru sektir hins vegar umtalsverður hluti tekna af stæðarekstri. Því betur sem kerfið virkar fyrir ökumanninn, því minni verða sektartekjurnar — krafan um þægindi notandans vinnur beinlínis gegn núverandi tekjumódeli rekstraraðilans.

- **Hagsmunaaðilar:** Ökumenn (notendur) annars vegar og rekstraraðili stæðis (viðskiptavinur) hins vegar. Sveitarfélagið kemur einnig við sögu þar sem það setur reglur um bæði gjaldskrá og sektir.

- **Orsök:** Aðilarnir mæla árangur kerfisins á ólíkan hátt. Ökumenn meta það út frá því hversu áreynslulaust og fyrirsjáanlegt það er, en rekstraraðilinn metur það út frá heildartekjum á hvert stæði. Þegar kerfið er keypt er gert ráð fyrir að sjálfvirk innheimta auki tekjur með því að ná til þeirra sem áður greiddu ekki, en á móti hverfa sektartekjurnar. Óvissa um hvor áhrifin vega þyngra veldur því að rekstraraðilinn gæti viljað slaka á nákvæmniskröfum eða halda inni sektarákvæðum sem grafa undan upphaflegu markmiði kerfisins.

- **Tegund:**
  - [ ] Viðfangsefnaárekstur (*subject matter conflict*)
  - [ ] Gagnaárekstur (*data conflict*)
  - [x] Hagsmunaárekstur (*interest conflict*)
  - [ ] Gildisárekstur (*value conflict*)
  - [ ] Tengslaárekstur (*relationship conflict*)
  - [ ] Skipulagsárekstur (*structural conflict*)

- **Úrlausn:** Við leggjum til samningalausn þar sem leitað er að lausn sem uppfyllir undirliggjandi hagsmuni beggja aðila frekar en yfirlýstar afstöður þeirra. Rekstraraðilinn hefur í reynd ekki hagsmuni af sektum sem slíkum, heldur af stöðugum tekjum — og ökumenn hafa ekki hagsmuni af því að greiða ekki, heldur af því að vera ekki refsað fyrir mistök. Þessir hagsmunir rekast ekki á.

  Í framkvæmd þýðir þetta að áður en ákvörðun er tekin um að slaka á nákvæmniskröfum ætti að afla gagna: meta hversu stór hluti núverandi tekna kemur frá sektum og hversu stór hluti ökumanna greiðir í dag alls ekki. Ef sjálfvirk innheimta nær til þess hóps geta heildartekjur haldist eða aukist þótt sektir hverfi. Reynist tekjurnar samt lækka er réttara að leiðrétta það með gjaldskránni sjálfri en með því að veikja kerfið, því lægri nákvæmni bitnar á öllum notendum og grefur undan trausti á vörunni í heild.

  Við völdum þessa leið fram yfir málamiðlun þar sem báðir aðilar gefa eftir, því málamiðlun hér — t.d. að sætta sig við lægri nákvæmni gegn lægra verði — myndi skaða kjarnaverðmæti vörunnar. Ákvörðunin um gjaldskrá liggur hjá rekstraraðila og sveitarfélagi og er því rétti staðurinn til að leysa tekjuvandann, ekki kröfulýsing kerfisins.
