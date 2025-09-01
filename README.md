# Scrum-opas projektitiimille

## Versionhallinta ja tiimityöskentely Scrum-projekteissa  

Scrum-tiimissä kaikki jäsenet työskentelevät saman tuotteen parissa, joten versionhallinta on välttämätöntä. Repository toimii yhteisenä “totuuden lähteenä”, josta kaikki saavat uusimman koodin.  

### Hyvät käytännöt repositoryn käytössä
- **Synkronoi usein:** Vedä (`git pull`) uusin versio ennen kuin aloitat työskentelyn ja ennen kuin pusket (`git push`) omat muutokset. Näin vältät turhat konfliktit.  
- **Pienet commitit:** Tee committeja usein, esimerkiksi aina kun saat jonkin toiminnallisuuden valmiiksi. Tämä helpottaa muutosten seuraamista.  
- **Kuvailevat commit-viestit:** Kirjoita viesti, joka kertoo selkeästi mitä muutit ja miksi. Hyviä esimerkkejä:  
  - `Add login form validation`  
  - `Fix bug in payment calculation`  
  - `Update README with installation instructions`  
- **Ratkaise konfliktit huolellisesti:** Jos repositoryssa on ristiriitoja, tarkista koodin molemmat versiot ja varmista, ettei mitään tärkeää katoa. Kommunikoi tiimin kanssa, jos olet epävarma.  

### Branchien käyttö projektissa
- **Päähaara (`main`):** Sisältää aina toimivan ja testatun version projektista.  
- **Ominaisuushaarat (feature branches):** Tee uusi branch aina uutta ominaisuutta tai isompaa muutosta varten, esim. `feature/login-page`.  
- **Bugikorjaushaarat (bugfix branches):** Pienemmät korjaukset voidaan tehdä erillisessä haarassa, esim. `bugfix/navbar-link`.  
- **Mergeaminen:** Kun työ on valmis ja testattu, yhdistä se (`merge` tai `pull request`) päähaaraan.  

Branchien käyttö vähentää riskiä rikkoa projektin toimivaa versiota ja helpottaa tiimityötä, kun jokainen voi kehittää omaa osaansa rinnakkain.
