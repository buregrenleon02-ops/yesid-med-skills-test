# Yesid Måleri AB: designpaket (Tier 1)

## 1. Premiss
Ett ord från målarens värld: **underarbetet**. Det som syns sist görs först. Kunder är rädda för slarv och färg som släpper; Yesid säljer noggrannheten under färgen. Varje sektion bevisar det: steg för steg, före/efter, riktiga jobb, 27 år.

## 2. Palett (från videon och loggan)
```css
:root{
  --canvas:#F1ECE3;      /* kritvit vägg, tonad mot björkplywood i videon */
  --panel:#E7E0D3;
  --ink:#16223A;         /* loggans marinblå */
  --accent:#B4442C;      /* tegelröd: loggans pensel + videons vägg */
  --accent-hover:#963722;
  --accent-muted:rgba(180,68,44,.18);
  --sage:#7F907A;        /* fasadens gröna, sparsamt */
  --text-secondary:#4A5468;
  --text-primary:#16223A;
}
```

## 3. Typsnitt
Familjen Grotesk 600/700 (rubriker, svensk byrå), Hanken Grotesk 400/500/600 (brödtext), IBM Plex Mono 400/500 (etiketter).

## 4. Bandkarta (startvärden, hero 600vh; klippet i videon ligger vid 0.503, i glappet mellan band 2 och 3)

| Band | Range | Film | Copy | Entré |
|---|---|---|---|---|
| 1 | 0.00–0.27 | Rollern gör grön fasad vit | "Yesid Måleri AB · Göteborg" / "Målat som om det vore vårt eget hem." / "27 år med pensel och roller. För privatpersoner, fastighetsägare och företag." | ord reser sig (laddningsramp) |
| 2 | 0.30–0.47 | Rollern drar uppåt i ny vit yta | "Fasader. Fönster. Dörrar." / "Utvändigt arbete som tål väder och år." | ord stiger uppåt med rollern |
| 3 | 0.55–0.76 | Röd vägg, horisontella drag | "Väggar. Tak. Snickerier." / "Invändigt, från ett rum till ett helt hus." | tecken glider in i sidled (roller-svep) |
| 4 | 0.82–1.00 | Vila: stor röd yta vänster | "Vi kommer i tid. Vi lämnar rent." / "Kostnadsfri offert i Göteborg med omnejd." / CTA | ord reser sig, sub, CTA (stegvis) |

## 5. Statisk hero
Slutbilden (röd vägg) med band 4: rubrik, underrad, två knappar.

## 6. Sektioner nedanför
Underarbetet (4 steg) → Tjänster → Före/efter (interaktivt: dra-reglage, trapphus) → Projekt (riktiga bilder) → Om oss (27 år) → Frågor → Offert (formulär: demo, ärligt tack-läge) → Sidfot.

## 7. Vektorlager
Signatur: en handritad rollerstrimma i tegelrött som "målas" bakom nyckelord när de kommer i bild. Penselmärke i loggan som SVG. Ikoner för stegen. Bakgrund: långsam drift av kritkorn och mjuka toner (80 s).

## 8. Teknik
Blob-hämtning, dt-normaliserad lerp, gated seeks, delta-gated DOM, fem statiska grindar live, komplett utan video, reducerad rörelse åt båda håll.

## 9. Copy-grind
All copy ovan skeppas ordagrant. Noll tankstreck, noll stock-ord.
