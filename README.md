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

